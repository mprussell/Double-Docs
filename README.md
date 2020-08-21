# Double Docs

Double Docs is a simple, two-up, single-window, side-by-side Google Docs editor built in Electron.

![Double Docs screenshot](https://mrussell.co.uk/projects/double-docs-screenshot.png)

## To build

Requires,
* npm
* Electron
* npm module `electron-packager`

From project folder run: `npm run package-mac`. The build will be in the `release-builds` folder.

Alternative builds, `npm run package-linux` and `npm run package-win` not tested.

## First run

* Run the application in `release-builds` (or move it somewhere like /Applications first).
* Sign-in using either of the Google sign-in windows, after which both docs will be authenticated.
* Edit either/both new docs OR select the blue Google Docs icon top-left to browse for other docs. Click one to load and edit.

Note. Use the Docs, Sheets, Slides or Forms file browsers, not Google Drive's as the latter can't open a document in Double Docs.