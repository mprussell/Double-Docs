# Double Docs

Double Docs is a simple, two-up, single-window, side-by-side Google Docs editor in Electron.

## To build (mac)

Requires npm and Electron.
Requires npm module `electron-packager`.

From project folder run: `npm run package-mac`.
The build will be in in the `release-builds` folder.

## First run

* Run the application in `release-builds` (or move it somewhere like /Applicartions first).
* Sign-in using either of the Google sign-in windows, after which both docs will be authenticated.
* Edit either/both new docs OR select the blue Google Docs icon top-left to browse for other docs. Click one to load and edit.

Note. Use the Docs, Sheets, Slides or Forms file browsers, not Google Drive's as the latter won't open a document in Double Docs.