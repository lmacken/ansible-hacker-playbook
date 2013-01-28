ansible-hacker-playbook
=======================

An ansible playbook that sets up a tricked-out zsh & vim environment.

Features
--------

- Installs (oh-my-zsh)[https://github.com/robbyrussel/oh-my-zsh], A community-driven framework for managing your zsh configuration.
- Installs (spf13-vim)[https://vim.spf13.com], "The Ultimate Vim Distribution"

Running
-------

- `yum -y install ansible`
- `systemctl start sshd`
- `ansible-playbook --inventory 'localhost,' --ask-pass --ask-sudo-pass playbook.yml`

Authors
-------
- [Luke Macken](http://lewk.org) ([@lmacken](http://twitter.com/lmacken))
