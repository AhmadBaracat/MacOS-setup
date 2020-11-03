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
### Install zplug
`brew install zplug`

Add these to `~/.zshrc`
```
export ZPLUG_HOME=$(brew --prefix)/opt/zplug
source $ZPLUG_HOME/init.zsh
```
