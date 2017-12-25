#### MacOS ML Setup

### Cloud Accounts

AWS Account

google cloud account

------

#### IDE

IDE with python, markdown modules
 > intellij CE
https://www.jetbrains.com/idea/download/#section=mac

modules needed:

markdown

python community edition

how to get modules for IDEA CE:  menu > preferences > plug ins > browse repositories

------

#### XCODE

 install XCode

    https://developer.apple.com/xcode/


 Install Apple command line tools

  part of XCode, check for install: xcode-select -p

------

#### brew and cask

install command:

/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

brew formula list
https://github.com/Homebrew/homebrew-core/tree/master/Formula



 > brew doctor
   >> fix the issues with brew, there will be a few
 > brew search python
 > brew install python (whatever version you need)
 > brew missing (install any missing modules)
 > brew update

cask

install commands (2x)

brew tap phinze/homebrew-cask

brew install brew-cask

 > cask doctor
 >> fix the issues with cask, there will be a few

#### helpful things to install with brew:

 command:

 brew install XXXX

 python

 git

 aws-cli and aws-shell

 git and git-flow

 tree (lists all teh folders)

 tmux (terminal emulationl)

 wget (http downloads)

 jq (for json work)

 htop (replacement for top, system vitals)

 ------

 #### Python PIP

 after installing python, install PIP

 $ curl -O http://python-distribute.org/distribute_setup.py
 $ python distribute_setup.py
 $ curl -O https://raw.github.com/pypa/pip/master/contrib/get-pip.py
 $ python get-pip.py

 ------

 #### Python Virtualenv

 pip install virtualenv

 ------

 #### GIT

 brew install git


 ------

 #### XCODE

 install XCode

 Install Apple command line tools

