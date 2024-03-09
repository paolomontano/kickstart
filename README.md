# Kickstart Playbook

This playbook installs and configures most of the software I use on my systems. Some things are slightly more difficult to automate; so it will be documented here.

## Installation

> If you're using MacOS, ensure that Apple's command line tools are installed.
>
> `xcode-select --install`


1. [Install Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html)
    - Add Python 3 to your $PATH: `export PATH="$HOME/Library/Python/3.9/bin:$PATH"`
    - Upgrade Pip: `sudo pip3 install --upgrade pip`
    - Install Ansible: `pip3 install ansible`
1. Clone this repo `git clone git@github.com:paolomontano/kickstart.git`
