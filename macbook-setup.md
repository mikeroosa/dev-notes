# MacBook Setup

Use this guide to set up a development environment for a fresh Mac install.

## Homebrew

Install the Homebrew package manager and run the update.

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
```

## Install Apps

```
brew install git
```

```
brew cask install \
  visual-studio-code \
  google-chrome \
  firefox \
  rectangle \
  iterm2 \
  docker \
  vlc \
  slack \
  keybase \
  spotify \
  postgres \
  postico \
  insomnia
```

## Shell

Install Oh My Zsh to fancy up the terminal.

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## Node

Use the Node Version Manager to install node. This will allow you to easily switch node versions.

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.2/install.sh | bash
nvm install node
nvm use node
node -v
npm -v
```

### Update nvm

```
nvm install node --reinstall-packages-from=node
```

### Use nvm to change versions

```
nvm install xx.xx
nvm use xx.xx
```

### Set nvm defaults

```
nvm alias default xx.xx
```

