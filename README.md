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

### Plugin settings

| Shortcut | Handler |
|----------|---------|
| ^J       | IDE     |
| ^K       | IDE     |

### Default commands

- `gd`: Goto definition.

[See all](https://github.com/JetBrains/ideavim/blob/master/src/main/java/com/maddyhome/idea/vim/package-info.java)

### Commands I always forget

- `'.`: Goto line start of last change in buffer.
- `%`: Goto end of bracket etc.
- `gv`: Reselect last selection.
- `gr{motion}`: Replace with registry

### Source changes

Open up the vim terminal inside IDEA (by typing `:`), then execute:

```
source ~/.ideavimrc
```

## Plugins

- [IdeaVim](https://plugins.jetbrains.com/plugin/164-ideavim)
- [AceJump](https://plugins.jetbrains.com/plugin/7086-acejump)

### IdeaVim Plugins

- [IdeaVim-Quickscope](https://plugins.jetbrains.com/plugin/19417-ideavim-quickscope)
- [IdeaVim-Sneak](https://plugins.jetbrains.com/plugin/15348-ideavim-sneak) 
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
