Damon Morgan Environment
========================

Environment is a script to get Max OS X set up as a development machine with all my preferences.

Prerequisites
-------------

1) XCode or [Command Line Tools for XCode](https://developer.apple.com/downloads/)

2) Set zsh as your login shell.

  chsh -s /bin/zsh

Installation
------------

  zsh < <(curl -s https://raw.github.com/damonmorgan/environment/master/mac)

What is installed
-----------------

* SSH public key (for authenticating with services like Github and Heroku)
* Homebrew (for managing operating system libraries)
* postgresql, redis (for database development)
* ack (for finding things in files)
* fasd (for fast directory switching)
* bash completion (for reducing rsi)
* MacVim with Vundle (for a development IDE with plugins)
* wget (for this installer and better file downloading)
* git (for version control)
* git-extras, legit (for git enhancements)
* zsh (for latest version to use as default shell)
* dotfiles (https://github.com/damonmorgan/dotfiles - my preferred configuration)
* oh-my-zsh (for zsh enhancements)
* the Inconsolata font (a nice development font - http://www.levien.com/type/myfonts/inconsolata.html)
* the Solarized colour scheme (a nice development scheme - http://ethanschoonover.com/solarized)
* rbenv, ruby-build (for Ruby version management - https://github.com/sstephenson/rbenv)
* latest stable ruby (currently 1.9.3-p327)
* node (for Node.js development)
* python (for running some useful tools)
* Heroku Toolbelt for interacting with the Heroku API
* Heroku Config plugin for local `ENV` variables
* pow (for development hosting of rack apps)

Post Install
------------

* gitx (http://gitx.laullon.com/)
* iterm2 (http://www.iterm2.com/ - change profile preferences to Inconsolata 14pt and Solarized Dark)
* Sequel Pro (http://www.sequelpro.com/)
* pgAdmin3 (http://www.pgadmin.org/)
* Induction (http://inductionapp.com/)
* Anvil for Pow (http://anvilformac.com/)

Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)
