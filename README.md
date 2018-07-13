# MaM Zipper v1.0.1b

## Description
This is a script for Violentmonkey and Tampermonkey that
adds a "Download as Zip" button to search pages of the MaM tracker.

It uses JSzip 3.1.5, found here:
https://github.com/Stuk/jszip

## Install instructions

1. Visit: https://tampermonkey.net/
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
* Add an option to exclude currently/previously leeched/seeded
* Add an option to limit torrent data size

## Changelog
Description | Version | State
--- | --- | ---
Initial commit | v1.0 | beta
Added "id" to the torrents to not get filename conflicts | v1.0.1 | beta
