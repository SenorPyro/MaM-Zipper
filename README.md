# MaM Zipper v1.1b

## Description
This is a script for Violentmonkey and Tampermonkey that  
adds a "Download as Zip" button to search pages of the MaM tracker.

It also adds a button that excludes previously/currently seeding/leeching,  
and an option to set an upper limit to the torrent size.

Currently only supports Chrome, Chromium and Firefox

It uses JSzip 3.1.5, found here:
https://github.com/Stuk/jszip

## Install instructions

1. Visit: https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/ for Firefox  
    or https://tampermonkey.net/ for Chrome and Chromium
2. Install Tampermonkey or Violentmonkey for your browser
3. Open this link: https://github.com/SenorPyro/MaM-Zipper/raw/master/MaMzip.user.js
4. Click Install/Update
5. You're done

## Compatibility

Operating System | Browser | Plugin | State
--- | --- | --- | ---
Windows 10 | Firefox Quantum | Violentmonkey | :heavy_check_mark:
Windows 10 | Chrome | Tampermonkey | :heavy_check_mark:
macOS 10.12 | Firefox ESR | Violentmonkey | :heavy_check_mark:
macOS 10.12 | Chrome | Tampermonkey| :heavy_check_mark:
Debian 9.4 | Firefox Quantum | Violentmonkey | :heavy_check_mark:
Debian 9.4 | Firefox ESR | Violentmonkey | :heavy_check_mark:
Debian 9.4 | Chrome | Tampermonkey | :heavy_check_mark:
Debian 9.4 | Chromium | Tampermonkey | :heavy_check_mark:
Windows 10 | Firefox Quantum | Tampermonkey | :x:
Windows 10 | Chrome | Violentmonkey| :x:
macOS 10.12 | Safari | Tampermonkey | :x:
macOS 10.12 | Firefox Quantum | Tampermonkey | :x:
macOS 10.12 | Chrome | Violentmonkey| :x:
Debian 9.4 | Firefox Quantum | Tampermonkey | :x:
Debian 9.4 | Firefox ESR | Tampermonkey | :x:
Debian 9.4 | Chrome | Violentmonkey | :x:
Debian 9.4 | Chromium | Violentmonkey | :x:


I do however not see a reason why it shouldn't work on Tampermonkey/Violentmonkey
for any other browser on any other operating system, 
except for Internet Explorer, but should work on Edge.

## Known issues
* Crashes if the torrent page contains your own upload(s)
* The conversion to blob strips the file encoding property of the file,  
   which can interfere with some poorly written scripts  
   I can't seem to find a good way to solve this

## Future plans
* Wait for users to ask for features
* Bug hunting and fixing

## Changelog
Description | Version | State
--- | --- | ---
Added exclude previously/currently seeding/leeching and size limiter | v1.1 | beta
Added ordering to the downloads to make them match their filenames | v1.0.2 | beta
Added "id" to the torrents to not get filename conflicts | v1.0.1 | beta
Initial commit | v1.0 | beta
