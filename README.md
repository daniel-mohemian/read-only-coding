# Share code snippets from Xcode via GitHub

Automator service to make sharing code snippets from Xcode easier. Written mostly in AppleScript, the [read-only language](https://en.wikipedia.org/wiki/Read-only_language). Pretty much all of the work is shamelessly cloned from [@1ec5’s read-only-coding](https://github.com/1ec5/read-only-coding).

## Usage

If a Git-managed source code file is open in Xcode and some lines are marked, this service copies the direct URL to the marked lines on GitHub to your clipboard.

## Installation

To install this service:

1. [Download a ZIP of this repository](https://github.com/1ec5/read-only-coding/archive/master.zip).
2. Double-click the .workflow bundle and click Install. (Or drop each .workflow bundle into ~/Library/Services/.)

To assign keyboard shortcuts to this service:

1. Open System Preferences and go to the Keyboard preference pane.
2. Switch to the Keyboard Shortcuts tab and select Services from the pane on the left.
3. Select a service and click “add shortcut”.

Or run the service via _Xcode -> Services -> Copy link of lines on GitHub_.
