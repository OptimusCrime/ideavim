# IdeaVim

Stuff I use for IdeaVim.

## Install

Clone this repo and symlink `.ideavimrc` to your `$HOME` directory.

### Windows installation

If you have to use Windows, you can symlink using the command example below. Run CMD as Administrator.

```
mklink C:\Users\your-username\.ideavimrc C:\Users\you-username\path\to\repo\ideavimrc
```

You may also want to install [AutoHotKey](https://www.autohotkey.com) and install the script below to make Caps Lock act as Esc. Save the file as `whatever.ahk`.

```
#NoEnv  ; Recommended for performance and compatibility with future AutoHotkey releases.
; #Warn  ; Enable warnings to assist with detecting common errors.
SendMode Input  ; Recommended for new scripts due to its superior speed and reliability.
SetWorkingDir %A_ScriptDir%  ; Ensures a consistent starting directory.
CapsLock::Esc
```

### macOS/Linux installation

```
ln -s /path/to/repo/ideavimrc ~/.ideavimrc
```

## Stuff to remember

### Default commands

- `gd`: Goto definition.

[See all](https://github.com/JetBrains/ideavim/blob/master/src/com/maddyhome/idea/vim/package-info.java)

### Commands I always forget

- `gUiw`: Uppercase inner word (lowercase `u` for lowercasing).
- `m[A-Z]`: Create mark (using IDEA marks).
- `'[A-Z]`: Goto mark.
- `'.`: Goto line start of last change in buffer.

### Source changes

Open up the vim terminal inside IDEA (by typing `:`), then execute:

```
source ~/.ideavimrc
```

## IDEA Plugins

- [IdeaVim](https://github.com/JetBrains/ideavim)
- [AceJump](https://github.com/acejump/AceJump)
- Nyan Progress Bar
- Rainbow Brackets
- Solarized Theme
- SonarLin

## Custom IDEA shortcuts

- Other -> Select In Project View: <kbd>Alt+Quote</kbd> | <kbd>⌘\</kbd>
- Editor Actions -> Down: <kbd>Ctrl+j</kbd> | <kbd>^j</kbd>
- Editor Actions -> Up: <kbd>Ctrl+k</kbd> | <kbd>^k</kbd>

### macOS specific

- Main Menu -> Window -> Editor Tabs -> Select Next Tab: <kbd>⌘j</kbd>
- Main Menu -> Window -> Editor Tabs -> Select Previous Tab: <kbd>⌘k</kbd>
- Main Menu -> View -> Recent Files: <kbd>^e</kbd>

## VIM Plugin Emulators

- [vim-surround](https://github.com/tpope/vim-surround)
- [vim-multiple-cursors](https://github.com/terryma/vim-multiple-cursors)

## Keys mapped to IDE defaults

- **c-e**
- **c-j**
- **c-k**

## Editor config

- Color Scheme: Solarized Dark
- Editor Tabs: Tab placement: None

## Editor styling

- **Font:** [Hack](https://github.com/source-foundry/Hack)
- **Size:** 12
- **Line spacing:** 1.2

## Webstorm

- Show auto-import tooltip: Yes
- Add ES6 imports on code completion: Yes
- Add TypeScript imports automatically: Yes
- Add TypeScript imports automatically, On code completion: Yes
- Add TypeScript imports automatically, With auto-import tooltip: No
- Add TypeScript imports automatically, Unambiguous imports on the fly: Yes

- Type-Matching Completion: Yes
- Sort suggestions alphabetically: No
- Show suggestions as you type: Yes
- Show suggestions as you type, Insert selected suggestion by typing space, [...]: No
- Insert parentheses automatically when applicable: Yes