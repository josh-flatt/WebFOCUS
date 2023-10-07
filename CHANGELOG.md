# Change Log

All notable changes to the WebFOCUS extension are documented in this file.

## 0.1.0

Initial release (preview).

This has not yet been published in the VSCode Extensions Marketplace. If you would like to preview this extension, you need to download this repository, unzip it into your VSCode Extensions directory (~/.vscode/extensions), and make sure that you modify the leading "W" in the folder name to be lower case.

Depending on your platform, it's located in the following directory:

- **Windows:** %USERPROFILE%\\.vscode\extensions
- **macOS:** ~/.vscode/extensions
- **Linux:** ~/.vscode/extensions

## 0.2.0

Initial VSCode Extension Marketplace release.

## 0.2.1

Non-functional update.

- Added more details to Visual Studio Marketplace page.
  - Banner -> Darkened.
  - Icon -> New Icon.
  - Tags -> Added more:
    - fex
    - FOCUS
    - webfocus
- Updated Readme to be more concise/accurate.

## 0.2.2

Bug Fixes.

- Accounted for some join syntax.
  - TAG X AS X no longer has to be on one line.
- Updated to account for double quotes.
- Fixed issue regarding `ctrl + /` not commenting out lines.
- Changed criteria for variables.
- Added new parameters for WHERE clauses
  - Added `FROM + TO` highlighting.
  - Added `NOT-FROM` highlighting.
- Fixed bug where ghost column prefixes were being incorrectly detected.
