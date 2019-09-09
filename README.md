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

  ⚠️**IMPORTANT befor you run the next command**
  You need to have:
  - been logged in into iCloud
  - created an ssh-key for github connection

  `ansible-playbook playbook.yml -i "localhost," -K`

  ----

  ## Install VirtualBox:

  1. OS Mojave +10.14.5
    You need to boot your machine in Recovery mode and [follow this link](http://osxdaily.com/2018/12/31/install-run-virtualbox-macos-install-kernel-fails/)

    Basically you need to:
    - Download VirtualBox
    - Restart your Mac into Recovery Mode (Cmd + R)
    - Open Utilities > Terminal
    - Type `spctl kext-consent add VB5E2TV963` and hit Return
    - Restart your Mac normally

  2. Older versions
    `brew cask install virtualbox`
