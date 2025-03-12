# Mac Setup

## Do this First!


## Essentials

## Laptop Configs
* Add Russian Keyboard
  

### Google Chrome
1. Install Google Chrome

### iTerm2
1. iTerm2 - https://www.iterm2.com/
2. Term2 Theme - https://github.com/MartinSeeler/iterm2-material-design
3. iTerm2 Font -  Hasklig font (https://github.com/i-tu/Hasklig)

## Misc. Apps



## Development Tools

### Xcode
Command Line Developer Tools for Xcode
```Shell Session
$ xcode-select --install
```

### Visual Studio
https://code.visualstudio.com/

### Homebrew

```Shell Session
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew tap homebrew/versions
$ brew tap caskroom/cask
$ brew doctor
```

### Java JDK
```Shell Session
$ brew tap caskroom/versions
$ brew cask install java8
```

### Git
```Shell Session
$ brew install git
```

When done, to test that it installed fine you can run:
```Shell Session
$ which git
```
The output should be /usr/local/bin/git.

Always set your details before you create or clone repositories on a new system. This requires two commands in a terminal window:
```Shell Session
$ git config --global user.name "Name"                                                                                     
git config --global user.email "email@emailaddress.com"
```
To enable colors in the output, which can be very helpful, enter this command:
```Shell Session
git config --global color.ui auto
```

Generate SSH key for GitHub authorization
```
cd ~/
ssh-keygen -t rsa
pbcopy < ~/.ssh/id_rsa.pub
```
Upload your public SSH key to GitHub

### Install plugins

Z
```
fisher add jethrokuan/z
```
