# Setting up your development environment

*This tutorial officially supports all operating systems as well as replit*

*Sections 1-2 are only required if not using an online IDE*




### Section 1: Installing required software

MacOS required software
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
This is homebrew, often called the missing package manager for MacOS, this will allow us to install software via the command line interface (cli), wait for it to install (it will take a while) then procede to the next steps.
```
brew install git python3 vim
```
This will install a few things, git what's called source control, it's used to control git repositories, python3 is the programming language we will be using, and vim is a cli text editor


Ubuntu required software

```
sudo apt update
sudo apt install python3 vim git
```
Similarly to the MacOS commands, these install a few things, git what's called source control, it's used to control git repositories, python3 is the programming language we will be using, and vim is a cli text editor

Windows required software

Download python3 from the Windows Store, git from [gits webpage](https://github.com/git-for-windows/git/releases/download/v2.36.0.windows.1/Git-2.36.0-64-bit.exe), git should automatically install vim as well
