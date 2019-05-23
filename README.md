# OSX Provision

## Installation

  1. Install Command Line Tools:

  `xcode-select --install`

  2. Install Homebrew:

  `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

  3. Install ansible:

  `brew install ansible`

  4. Clone this repository:

  `git clone git@github.com:italodr/osx-provision.git`

  5. Run:

  `ansible-playbook playbook.yml -i "localhost," -K`

  6. Install VirtualBox:

    1. Mojave
    You need to boot your machine in Recovery mode and [follow this link](http://osxdaily.com/2018/12/31/install-run-virtualbox-macos-install-kernel-fails/)

    2. Older versions
    `brew cask install virtualbox`
