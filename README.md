# Double Docs

Double Docs is a simple two-up, single-window Google Docs editor for writers built in Electron.

![Double Docs screenshot](https://mrussell.co.uk/projects/double-docs-screenshot.png)

## Download Double Docs

[Download the latest release for your OS](https://github.com/mrkrsl/Double-Docs/releases)

## First run

* Open the disk image (Mac), run the installer (Windows) or run or the AppImage (Linux).
* Sign-in using either of the Google sign-in windows, after which both Docs panels will be authenticated.

Note. On Linux you may need to grant executable permission to the AppImage before it will run. (Right click > Properties > Permissions + Check 'Allow executing file as program', OR `chmod o+x file.appimage`.)

## Usage

* Edit either/both new Docs OR select the blue Google Docs icon top-left to browse for other Docs. Click one to load and edit.
* Drag the slider between the Docs to resize. 
* Double-click to reset the 50/50 split.

Note. Use the Docs, Sheets, Slides or Forms file browsers, not Google Drive's as the latter can't open a document in Double Docs.

## To build

Requires,
* npm
* Electron
* npm module `electron-builder`

From project folder run: `electron-builder -mwl`. Builds for Mac, Windows and Linux will be in the `dist` folder.

Alternatively, to target only one platform it's `electron-builder --mac`, `electron-builder --win` or `electron-builder --linux`.

Note. Windows and Linux builds minimally tested.

## Licence

[Released under the MIT Licence](LICENSE.md)