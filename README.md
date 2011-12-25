          _       _    __ _ _
         | |     | |  / _(_) |
       __| | ___ | |_| |_ _| | ___  ___
      / _` |/ _ \| __|  _| | |/ _ \/ __|
     | (_| | (_) | |_| | | | |  __/\__ \
    (_)__,_|\___/ \__|_| |_|_|\___||___/

# My ideal Unix environment

Inspired and borrowed form Ryan Bates, Ryan Tomayko, Carlhuda, Robert Evans, and Mislav Marohnić dotfile repos. covering:

- ack
- bash (bash-it framework: https://github.com/revans/bash-it)
- capistrano
- cvs
- rubygems
- ruby
- git
- nano
- rails
- custom global rake tasks
- screen
- tmux
- vim (janus from carlhuda: https://github.com/carlhuda/janus)
- ssh

With some little tools and templates that could be helpful here and there.

## Setup
`./install.sh`

## Requirements
- install rvm then rubies
- on OSX: `brew install git ack tree tmux screen vim grc unrar p7zip`
- on Linux: 'sudo apt-get install ctags git-core ack tmux(>1.3) screen grc p7zip'
- `gem  install tmuxinator rails capistrano capistrano_colors looksee wirble hirb awesome_print yui-compressor bundle-outdated`
