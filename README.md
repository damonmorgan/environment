Damon Morgan Environment
========================

Environment is a script to get Max OS X set up as a development machine with all my preferences.

Prerequisites
-------------

1) XCode (required to build MacVim)

Installation
------------

  bash <(curl -s https://raw.githubusercontent.com/damonmorgan/environment/master/mac)

What is installed
-----------------

* Generate SSH public key (for authenticating with services like Github and Heroku)
* [Homebrew](http://brew.sh/) and [Cask](http://caskroom.io/)
* zsh with [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (preferred shell)
* [iterm2](http://www.iterm2.com/) (preferred terminal)
* git
  * [git-extras](https://github.com/visionmedia/git-extras)
  * [legit](http://www.git-legit.org/)
  * [gitx](http://gitx.laullon.com/)
* development environment version managers
  * [rbenv](https://github.com/sstephenson/rbenv), ruby-build
  * [nvm](https://github.com/creationix/nvm) (not using yet)
* development languages
  * ruby, node, python, java, go, scala
* 'databases'
  * postgresql, redis, rabbitmq, memcached
* utilities (openssl, ack, silver searcher, [fasd](https://github.com/clvv/fasd), wget, curl, [ngrok](https://ngrok.com/))
* vim/MacVim with [Vundle](http://github.com/gmarik/vundle) (preferred editor)
* development fonts
  * [Inconsolata](http://www.levien.com/type/myfonts/inconsolata.html)
  * Inconsolata for [powerline](https://github.com/Lokaltog/powerline)
* development colourscheme
  * [Solarized](http://ethanschoonover.com/solarized)
* browsers
  * chrome dev channel, opera, firefox
* apps
  * virtualbox, atom, dropbox, etc.
* [dotfiles](https://github.com/damonmorgan/dotfiles) (preferred configuration)
* [Heroku Toolbelt](https://toolbelt.heroku.com/)
  * [config plugin](https://github.com/ddollar/heroku-config) for local `ENV` variables
  * [accounts plugin](https://github.com/ddollar/heroku-accounts) heroku accounts:set work
  * [pg-extras plugin](https://github.com/heroku/heroku-pg-extras) heroku pg:index-size
  * [redis:cli plugin](https://github.com/ddollar/heroku-redis-cli) heroku redis:cli
* [sshuttle](https://github.com/apenwarr/sshuttle)
* [aws cli](http://aws.amazon.com/cli/)
* [docker](http://boot2docker.io/)


Post Install
------------

Configure iTerm to use the new Inconsolata Font and Solarized colourscheme
(change profile preferences to Inconsolata for Powerline 14pt and Solarized Dark)

Turn on FileVault


Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)
