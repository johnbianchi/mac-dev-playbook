# Mac Development Ansible Playbook

This repository is a fork of Phillip Schreiber's excellent repository: 
https://github.com/PhilippSchreiber/mac-dev-playbook.  It is a stripped version suited to my needs.

For installation:

    $ xcode-select --install
    $ sudo easy_install pip
    $ sudo pip install ansible
    $ mkdir dev && cd dev
    $ git clone git@github.com:johnbianchi/mac-dev-playbook.git
    $ cd mac-dev-playbook
    $ ansible-galaxy install -r requirements.yml

    $ ansible-playbook -i inventory --ask-become-pass main.yml

    $ cd ~/dotfiles
    $ bin/install
    $ bin/setup_osx
