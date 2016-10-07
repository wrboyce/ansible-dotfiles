wrboyce.dotfiles
================

[![Build Status](https://travis-ci.org/wrboyce/ansible-dotfiles.svg)](https://travis-ci.org/wrboyce/ansible-dotfiles)

Meta-role which depends on my app-specific dotfiles roles.

Dependencies
------------

* wrboyce.dotfiles-assh
* wrboyce.dotfiles-git
* wrboyce.dotfiles-vim
* wrboyce.dotfiles-zsh

Example Playbook
----------------

    - hosts: workstations
      roles:
         - wrboyce.dotfiles

License
-------

Apache 2.0
