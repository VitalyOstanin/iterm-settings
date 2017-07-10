# Native mac os hotkeys for Iterm2

# Backup your profile

1. Open iterm settings, `Profiles`, select your profile (Default)
2. Choose `Other Actions...` at bottom, `Duplicate profile`

# Install

1. Download `Hotkeys.json` to `~/Library/Application Support/iTerm2/DynamicProfiles/Hotkeys.json`
2. Open iterm settings, `Profiles`, select `Hotkeys (Dynamic)`
3. Choose `Other Actions...` at bottom, `Bulk Copy from Selected Profile...`
4. Enable `Keys` checkbox and choose your profile (Default), press `Copy` button

# Hotkeys list

Move:
* `⌘←` move to begin of line
* `⌘→` move to end of line
* `⌥←` move left by word
* `⌥→` move right by word

Delete:
* `⌘⌫` delete from cursor to begin of line
* `⌘⌦`, `fn⌘⌫` delete from cursor to end of line
* `⌥⌫` delete word left
* `⌥⌦`, `fn⌥⌫` delete word right

Selection:
* `⌥⇧Arrow` - move start of selection by char or line
* `⌘⇧Arrow` - move end of selection by char or line

Navigation:
* `⌥⌘←` cycle tabs left
* `⌥⌘→` cycle tabs right
* `⌘^←` move tab left
* `⌘^→` move tab right

# Note for zsh users

`⌘⌫` mapped to Ctrl-u, which is bound to `kill-whole-line` by default. Try
```sh
bindkey \^U backward-kill-line
```
