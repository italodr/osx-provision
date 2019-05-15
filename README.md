# OSX Provision

## Installation

  1. Install Command Line Tools:
  
  `xcode-select --install`
  
  2. Install Homebrew:
  
  `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
  
  3. Install ansible:
  
  `brew install ansible`
  
  4. Clone this repository:
  
  `git clone git@github.com:asenor/osx-provision.git`
  
  5. Run:
  
  `ansible-playbook playbook.yml -i "localhost," -K`
