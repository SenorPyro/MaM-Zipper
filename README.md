# MaM-Zipper v1.0.1b

## Description
This is a script for Violentmonkey and Tampermonkey that
adds a "Download as Zip" button to search pages of the MaM tracker.

It uses JSzip 3.1.5, found here:
https://github.com/Stuk/jszip

## Compatebility
Currently only tested on: 

* Violentmonkey for Firefox Quantum on Windows 10
* Tampermonkey for Chrome on Windows 10

Known to not work on:

* Greasemonkey for Firefox Quantum on Windows 10

I do however not see a reason why it shouldn't work on Tampermonkey for Safari on OSX and
Violentmonkey/Tampermonkey on Linux and OSX

## Known issues
* Strips the encoding of the torrent files which may cause problems for poorly implemented torrent scripts

## Future plans
* Add an option to exclude currently/previously leeched/seeded
* Add an option to limit torrent data size

## Changelog
Description | Version | State
--- | --- | ---
Initial commit | v1.0 | Beta
Addeed "id" to the torrents to not get filename conflicts | v1.0.1 | Beta
