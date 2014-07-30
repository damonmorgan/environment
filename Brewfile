# Install command-line tools using Homebrew
# Usage: `brew bundle Brewfile`

# Make sure we’re using the latest Homebrew
update

# Upgrade any already-installed formulae
upgrade

# brew cask for apps
install caskroom/cask/brew-cask
tap caskroom/versions

# shell
install zsh

# terminal
cask install iterm2

# git
install git
install git-extras
install legit
cask install gitx-l

# ruby version manager
install rbenv
install ruby-build

# other development languages
install node
install python
cask install java
install go
install scala

# databases
install postgresql --no-python
install redis
install rabbitmq
install memcached

# replace default openssl
install openssl
link openssl --force
#install curl-ca-bundle
#tap raggi/ale
#install openssl-osx-ca

# utils
install ack
install fasd
install wget
install curl
link curl --force
install ngrok

# editor
install vim --override-system-vi
install macvim

# development font
tap caskroom/fonts
cask install font-inconsolata
cask install font-inconsolata-for-powerline

# browsers
cask install google-chrome-dev
cask install opera
cask install firefox
cask install lastpass-universal

# apps
cask install virtualbox
cask install vmware-fusion
cask install vlc
cask install adium
cask install atom
cask install calibre
cask install crashplan
cask install flux
cask install prey
cask install skitch
cask install skype
cask install spotify
cask install tinyumbrella
cask install transmission-remote-gui
cask install truecrypt71a
cask install cyberduck

# drives
cask install dropbox
cask install google-drive
cask install skydrive #onedrive

# Remove outdated versions from the cellar
cleanup
