# Double Docs Changelog

Double Docs is a simple two-up, single-window Google Docs editor for writers built in Electron.

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).


## [1.0.0] - 2020-09-24

Tidy for 1.0.0 release.

### Added

### Changed
* Now battle tested wiht daily use (Mac version) this is a minor codebase tidy up ready for bump to 1.0.0 release.

### Removed

## [0.2.2] - 2020-09-14

Now built for Mac, Windows and Linux with electron-builder.

### Added
* Files and folders to supprt electron-builder (.dmg for Mac, NSIS installer for Windows and AppImage for Linux.)

### Changed
* Replaced electron-packager package.json config for electron-builder

### Removed
* release-builds/

## [0.2.1] - 2020-09-10

Double-click to reset the 50/50 panel split.

### Added
* Feature: Double click the Doc resizing bar to reset the split to 50/50

### Changed
* Moved the CSS into its own file

### Removed

## [0.2.0] - 2020-09-09

Addition of resizable Doc panels.

### Added
* Javascript and additional HTML markup to enable Doc panel resizing by dragging a central bar
* Windows .ico and a PNG for Linux, should anybody build those

### Changed
* Improved the equal split between left and right Doc panels
* Created a new application icon and updated the .icns file for Mac

### Removed

## [0.1.8] - 2020-08-20

Initial build for relase.

### Added
* Base Electron project
* Dual panel Google Docs webviews, launching with the Docs file browser
* MIT license
* Visual assets for Github
* Icon for release build

### Changed

### Removed
