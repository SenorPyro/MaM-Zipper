# MaM Zipper v1.1b

## Description
This is a script for Violentmonkey and Tampermonkey that
adds a "Download as Zip" button to search pages of the MaM tracker.

It also adds a button that excludes previously/currently seeding/leeching, \
and an option to set an upper limit to the torrent size.


It uses JSzip 3.1.5, found here:
https://github.com/Stuk/jszip

## Install instructions

1. Visit: https://addons.mozilla.org/en-US/firefox/addon/violentmonkey/ for Firefox\ or https://tampermonkey.net/ for other browsers
2. Install Tampermonkey for your desired browser
3. Open this link: https://github.com/SenorPyro/MaM-Zipper/raw/master/MaMzip.user.js
4. Click Install/Update
5. You're done

## Compatibility
Currently only tested on: 

* Violentmonkey for Firefox Quantum on Windows 10
* Tampermonkey for Chrome on Windows 10

Known to not work on:

* Greasemonkey for Firefox Quantum on Windows 10

I do however not see a reason why it shouldn't work on Tampermonkey/Violentmonkey
for any other browser on any other operating system, 
except for Internet Explorer, but should work on Edge.

## Known issues
* Strips the encoding of the torrent files which may cause problems for poorly implemented torrent scripts

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
