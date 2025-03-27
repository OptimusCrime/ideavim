# IdeaVim

My [IdeaVim](https://github.com/JetBrains/ideavim) config.

## Install

Clone this repo and symlink `ideavimrc` to your `$HOME` directory.

### Windows installation

If you have to use Windows, you can symlink using the command example below. Run CMD as Administrator.

```
mklink C:\Users\your-username\.ideavimrc C:\Users\you-username\path\to\repo\ideavimrc
```

### macOS/Linux installation

```
ln -s /path/to/repo/ideavimrc ~/.ideavimrc
```

## Stuff to remember

### Default commands

- `gd`: Goto definition.

[See all](https://github.com/JetBrains/ideavim/tree/master/vim-engine/src/main/resources/ksp-generated)

### Commands I always forget

- `'.`: Goto line start of last change in buffer.
- `nG`: Goto line n.
- `%`: Goto matching pair.
- `gv`: Reselect last selection.
- `gr{motion}`: Replace with registry
- `]}`: Goto unmatched }
- `gc{motion}`: Comment or uncomment
- `af` and `if`: Outer and inner function text objects
- `ys{motion}{char}`: Surround motion with char

### Text objects

- `if` / `af`: Inner/Outer function body
- `iq` / `aq`: Inside/Outside any quotes
- `ab` / `ib`: Inside/Outside parentheses, curly braces, and square brackets

### Source changes

Open up the vim terminal inside IDEA (by typing `:`), then execute:

```
source ~/.ideavimrc
```

Or, via the mapping <kbd>space</kbd> <kbd>9</kbd>

### Own functions

#### Toggle WhichKey

Enable/Disable the plugin with the mapping <kbd>space</kbd> <kbd>8</kbd>

#### Toggle relative line numbers

Enable/Disable relative line numbers in the gutter with the mapping <kbd>space</kbd> <kbd>tab</kbd>

## Plugins

- [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
- [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)

### IdeaVim Plugins

- [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
- [IdeaVim-Sneak](https://plugins.jetbrains.com/plugin/15348-ideavim-sneak) 
- [Vim Switch](https://plugins.jetbrains.com/plugin/25899-vim-switch)
- [Vim FunctionTextObj](https://plugins.jetbrains.com/plugin/25897-vim-functiontextobj)
- [Vim Peekaboo](https://plugins.jetbrains.com/plugin/25776-vim-peekaboo)
- [HarpoonIJ](https://plugins.jetbrains.com/plugin/20782-harpoonij)
- Optional: [Which-Key](https://plugins.jetbrains.com/plugin/15976-which-key)

### Random plugins

- [Nyan Progress Bar](https://plugins.jetbrains.com/plugin/8575-nyan-progress-bar)
- [Rainbow Brackets](https://plugins.jetbrains.com/plugin/10080-rainbow-brackets)

## Custom IDEA shortcuts

- Editor Actions -> Down: <kbd>Ctrl+j</kbd> or <kbd>^j</kbd>
- Editor Actions -> Up: <kbd>Ctrl+k</kbd> or <kbd>^k</kbd>

## Editor config

- Color Scheme: Dark
- Editor Tabs: Tab placement: None

## Editor styling

- **Font:** [Hack](https://github.com/source-foundry/Hack)
- **Size:** 12
- **Line spacing:** 1.2
