osxc
=======

Ansible scripts to setup a Mac

## Get started

1. Be sure to have the XCode Command-Line tools installed: `xcode-select --install`
1. Install homebrew
1. Install ansible
1. [Install MacVim app](https://github.com/macvim-dev/macvim/releases) and then `ln -s /Applications/MacVim.app/Contents/bin/mvim /usr/local/bin/mvim && ln -s /usr/local/bin/mvim /usr/local/bin/vim`
1. `git clone git@github.com:baopham/ansible-mac ~/osxc`
1. Take a quick look at `requirements.yml`, `installation.yml`, `configuration.yml` and customizing to your liking.
1. Start osxc with `ansible-playbook desktop.yml` (run: `ansible-galaxy install -r requirements.yml` first if you need to install any roles)

