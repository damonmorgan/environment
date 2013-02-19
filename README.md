Damon Morgan Environment
========================

Environment is a script to get Max OS X set up as a development machine with all my preferences.

Prerequisites
-------------

1) XCode and [Command Line Tools for XCode](https://developer.apple.com/downloads/)
Note: Both are required to build MacVim
Agree to the Xcode license by running Xcode.app or xcodebuild -license

2) Set zsh as your login shell.

  chsh -s /bin/zsh

Installation
------------

  zsh < <(curl -s https://raw.github.com/damonmorgan/environment/master/mac_part1)
  zsh < <(curl -s https://raw.github.com/damonmorgan/environment/master/mac_part2)
  rake install

restart terminal

  zsh < <(curl -s https://raw.github.com/damonmorgan/environment/master/mac_part3)



What is installed
-----------------

* SSH public key (for authenticating with services like Github and Heroku)
* [Homebrew](http://mxcl.github.com/homebrew/) (for managing operating system libraries)
* postgresql, redis (for database development)
* ack (for finding things in files)
* [fasd](https://github.com/clvv/fasd) (for fast directory switching)
* MacVim with Vundle (for a development IDE with plugins)
* wget (for this installer and better file downloading)
* git (for version control)
* [git-extras](https://github.com/visionmedia/git-extras), [legit](http://www.git-legit.org/) (for git enhancements)
* zsh (for latest version to use as default shell)
* [dotfiles](https://github.com/damonmorgan/dotfiles) (my preferred configuration)
* [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh) (for zsh enhancements)
* the [Inconsolata font](http://www.levien.com/type/myfonts/inconsolata.html) (a nice development font)
* the [Solarized colour scheme](http://ethanschoonover.com/solarized) (a nice development scheme)
* [rbenv](https://github.com/sstephenson/rbenv), ruby-build (for Ruby version management)
* latest stable ruby (currently 1.9.3-p327)
* node (for Node.js development)
* python (for running some useful tools)
* [Heroku Toolbelt](https://toolbelt.heroku.com/) for interacting with the Heroku API
* [Heroku Config plugin](https://github.com/ddollar/heroku-config) for local `ENV` variables
* [Heroku Accounts plugin](https://github.com/ddollar/heroku-accounts) for using work and personal heroku accounts
* [Heroku PG Extras plugin](https://github.com/heroku/heroku-pg-extras/) for awesome pg:* commands
* [pow](http://pow.cx/) (for development hosting of rack apps)
* [sshuttle](https://github.com/apenwarr/sshuttle)

Post Install
------------

* [gitx](http://gitx.laullon.com/)
* [iterm2](http://www.iterm2.com/ - change profile preferences to Inconsolata 14pt and Solarized Dark)
* [Sequel Pro](http://www.sequelpro.com/)
* [pgAdmin3](http://www.pgadmin.org/)
* [Induction](http://inductionapp.com/)
* [Anvil](http://anvilformac.com/) for Pow

Credits
-------

![thoughtbot](http://thoughtbot.com/images/tm/logo.png)
