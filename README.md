# MaM Zipper v2.3

## Description
This is a script for Violentmonkey and Tampermonkey that  
adds a "Download as Zip" button to search pages of the MaM tracker.

It also adds a button that excludes previously/currently seeding/leeching,  
and an option to set an upper limit to the torrent size.

Currently only supports Chrome, Chromium and Firefox

It uses JSzip 3.2.1, found here:
https://github.com/Stuk/jszip

## Install instructions

1. Visit: https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/ for Firefox  
    or https://tampermonkey.net/ for Chrome and Chromium
2. Install Tampermonkey or Violentmonkey for your browser
3. Open this link: https://github.com/SenorPyro/MaM-Zipper/raw/master/MaMzip.user.js
4. Click Install/Update
5. Enjoy

## Compatibility

Operating System | Browser | Plugin | State
--- | --- | --- | ---
Windows 10 | Firefox Quantum | Violentmonkey | :heavy_check_mark:
Windows 10 | Chrome | Tampermonkey | :heavy_check_mark:
macOS 10.12 | Firefox ESR | Violentmonkey | :heavy_check_mark:
macOS 10.12 | Chrome | Tampermonkey| :heavy_check_mark:
Debian 9 | Firefox Quantum | Violentmonkey | :heavy_check_mark:
Debian 9 | Firefox ESR | Violentmonkey | :heavy_check_mark:
Debian 9 | Chrome | Tampermonkey | :heavy_check_mark:
Debian 9 | Chromium | Tampermonkey | :heavy_check_mark:
Windows 10 | Firefox Quantum | Tampermonkey | :grey_question:
Windows 10 | Chrome | Violentmonkey| :grey_question:
macOS 10.12 | Safari | Tampermonkey | :grey_question:
macOS 10.12 | Firefox Quantum | Tampermonkey | :grey_question:
macOS 10.12 | Chrome | Violentmonkey| :grey_question:
Debian 9 | Firefox Quantum | Tampermonkey | :grey_question:
Debian 9 | Firefox ESR | Tampermonkey | :grey_question:
Debian 9 | Chrome | Violentmonkey | :grey_question:
Debian 9 | Chromium | Violentmonkey | :grey_question:


I do however not see a reason why it shouldn't work on Tampermonkey/Violentmonkey
for any other browser on any other operating system, 
except for Internet Explorer, but should work on Edge.

## Known issues
* The conversion to blob strips the file encoding property of the file,  
   which can interfere with some poorly written scripts  
   This is a bug with JSzip

## Future plans
* Test the whole compatability list

## Changelog
Description | Version | State
--- | --- | ---
Fixed actively seeding filter and filename bug | 2.3 | release
Fixed indentation | 2.2.2 | release
Reverted broken JSZip uglified line | 2.2.1 | release
Fixed bug where size selector would get searched for because of the inherited name field | 2.2 | release
Fixed bug where you can't download your own torrents and made detection of previous activity work on previously seeded torrents | v2.1 | release
Rewrote most of the code and updated from JSzip 3.1.5 to 3.2.1 | v2.0 | beta
Added exclude previously/currently seeding/leeching and size limiter | v1.1 | beta
Added ordering to the downloads to make them match their filenames | v1.0.2 | beta
Added "id" to the torrents to not get filename conflicts | v1.0.1 | beta
Initial commit | v1.0 | beta
