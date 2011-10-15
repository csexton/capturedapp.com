---
layout: captured_narrow
title: Captured - How to take a Screen Capture on Mac OS X
---

# How to change the default location for OS X's screencapture

By default when you press ⌘⇧4 on a mac it will save a file to your desktop. This can clutter up the desktop if you are taking a lot of screen shots. If you want to save your files somewhere else, say `Pictures/Screen Shots`, you can do the following:

    defaults write com.apple.screencapture location $HOME/Pictures/Screen\ Shots
    killall SystemUIServer

If you want to have captured upload those files make sure that you:

* Quit and restart Captured after you run the above the commands
* Ensure that "Ignore ⌘⇧4" is not checked in Preferences->Keyboard


