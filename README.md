# IdeaVim

Stuff I use for IdeaVim.

## Install

Clone this repo and symlink `.ideavimrc` to your `$HOME` directory.

### Windows installation

If you have to use Windows, you can symlink using the command example below. Run CMD as Administrator.

```
mklink C:\Users\you-username\path\to\repo\.ideavimrc C:\Users\your-username\.ideavimrc
```

You may also want to install [AutoHotKey](https://www.autohotkey.com) and install the script below to make Caps Lock act as Esc. Save the file as `whatever.ahk`.

```
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
CapsLock::Esc
```

## Remember stuff

_Some things I need to remember here._

### Source changes

Open up the vim terminal inside IDEA (by typing `:`), then execute:

```
source ~/.ideavimrc
```

## IDEA Plugins

- [IdeaVim](https://github.com/JetBrains/ideavim)
- [AceJump](https://github.com/acejump/AceJump)

## Custom IDEA shortcuts

- Other -> Select In Project View: <kbd>Alt+Quote</kbd>
- Editor Actions -> Down: <kbd>Ctrl+j</kbd>
- Editor Actions -> Up: <kbd>Ctrl+k</kbd>

## VIM Plugin Emulators

- [vim-surround](https://github.com/tpope/vim-surround)
- [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors)

## Keys mapped to IDE defaults

- **c-e**
- **c-j**
- **c-k**

## Other Things

- **Font:** [Hack](https://github.com/source-foundry/Hack)
- **Size:** 12
- **Line spacing:** 1.2
