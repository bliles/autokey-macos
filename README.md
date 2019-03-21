# Autokey Scripts for macOS Keyboard Shortcuts

If you regular switch between macOS and Linux you know the pain of your
muscle memory for common keyboard shortcuts not working. This is a
collection of scripts for Autokey that emulate macOS style keyboard
shortcuts in the Gnome desktop environment.

## Things That Don't Work

Copy and paste in terminals is particularly troublesome. I've added
workarounds for Gnome Terminal, but other terminals like Tilix would
need exclusions added to work properly. Also if you use a tool with
a built-in terminal like VS Code, it is difficult to detect if you are
in the editor or in the terminal so copy/paste will currently work
only in the editor, not in the terminal.

## Installation

First install Autokey `sudo apt install autokey-gtk`. Then copy these
scripts into your personal configuration folder. You'll then need to
assign the correct shortcut to these actions, for example, `<super>+c`
for Copy.
