
# Setting Up My Mac (as of 2018, Jun 11)
Below is the basic setup requirements for my MAC to get it ready for development.

## Mac Configuration
* **Set up Accessibility Options**
  * 3-finger **Drag**
  * 4-finger **Switch Screen**
* **Link Email Accounts**
  * <username>@elephantventures.com
  * <username>@personal-emails.com
* **Generate SSH Key**
  * `sudo ssh-keygen -t rsa -b 4096 -C “<username>@elephantventures.com”`
  * `ssh-add -K ~/.ssh/id_rsa`
  * Set up Git SSH

## Main Installs

* Install **Browsers**
  * Google Chrome
  * Mozilla Firefox

* Install **Xcode (takes 1hr to 2hrs)**
  * For you to be able to install most command-line tools, you’ll need Xcode installed first
  * Once installed, open XCode once to agree to terms & conditions.

* Install **iTerm**
  * Install [oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh)
  * Set theme to “amuse”
    * Run `vi ~/.zshrc`
    * Change `ZSH_THEME="robbyrussell"` to `ZSH_THEME="amuse"`

* Install **Homebrew**
  * `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)”`

* Install the following with **brew**:
  * `brew install wget`
  * `brew install git`
  * `brew install htop`
  * `brew install npm -g`
  * `brew install python`
  * **Command:** `brew install wget && brew install git && brew install htop  && brew install python3`

* Install **Docker for Mac (350 Mb+)**
  * https://docs.docker.com/docker-for-mac/install/
  * Download, mount and open app
  * Enter password
  * Configure Preferences:
  * Set Disk Space to only 32Gb

* Install **DiffMerge**
  * https://sourcegear.com/diffmerge/downloads.php

* Install **Communication Tools**
  * Install **Slack**

* Install **Visual Studio Code (68.6mb)**
  * Install Plugins: `tslint`, `vscode-docker` and `vscode-icons`

* Install **Postman App (66.1mb)**
  * https://www.getpostman.com/apps

* Install **Skitch**

* Install **SQL Editor 3 (56.3mb)**
  * License Password in Zoho

* Install **PSequel**
  * PostgreSQL GUI Lightweight Tool

* Install **DBeaver (45mb)**
  * Database GUI Tool

## Optional Installs

* Install **FileZilla**
  * (optional) Transfer FTP Credentials from other devices
  * You may have to manually set up folders if you encounter some permission errors
    * `/Users/<username>/.config/filezilla`
    * `sudo chown -R <username> .config`
    * then `sudo choen -R <username> /Users/<username>/.config/filezilla`
  * Re-run FileZilla and check if errors still occur

* Install **Dropbox**
  * https://www.dropbox.com/en_GB/install

* Install **Skype**
* Install **VLC Player (45.7mb)**
  * https://www.videolan.org/vlc/download-macosx.html
* Install **Spotify**
* Install **MAMP**
  * Download PHP 5.5.38 and copy to /bin
* Install **Adobe Creative Cloud**
  * I have Photoshop Subscription that needs to be installed
* Install **Pomodoro Time (paid)**
