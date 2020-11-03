# MacOS-setup
## Adjust Keyboard language
Go to `System Preferences` --> `Keyboard` --> `Input Sources` and choose `U.S.`

## Download Alfred
https://www.alfredapp.com/
* Go to `System Preferences` --> `Keyboard` --> `Shortcuts` --> `Spotlight` and change the key to `Alt/Option + Space`
* Make Alfred shortcut `CMD + Space`

## Install Homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
Note that this will install Command Line Tools for Xcode

## iTerm Related
### Install ohmyzsh
`sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

### Install Dracula Theme
Follow `Install manually` & `Activating theme` instructions on https://draculatheme.com/zsh

### Show full path with ~/
* `vim ~/.oh-my-zsh/themes/dracula.zsh-theme`
* Find `%c` (type `/%c` and then enter 😄)
* Press `i` to enter edit mode 😄
* Replace `%c` with `%~`


## View hidden files
Go to the root directory in `Finder` and press `Command+Shift+Dot`
