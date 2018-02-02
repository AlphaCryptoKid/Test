# Nobis

Based On Bytecoin v.2.1.2 Release (October 10, 2017)

Quick Start Guide on (Ubuntu 16.04)

## GIT
```
sudo apt-get update

sudo apt-get upgrade -y
sudo apt-get install -f

sudo apt-get install git
```
## MAKE
```
sudo apt-get install build-essential
```
## CMAKE v3.5.1
```
sudo apt-get install cmake -y
sudo apt-get upgrade
```
## Check Version CMAKE v3.5.1
```
cmake --version
```
## BOOST v1.58.0
```
sudo apt-get install libboost-all-dev
```
## Check Version BOOST v1.58.0
```
dpkg -s libboost-dev | grep 'Version'
```
## GCC v5.4.1
```
sudo apt-get update

sudo apt-get install build-essential software-properties-common -y
sudo add-apt-repository ppa:ubuntu-toolchain-r/test -y
sudo apt-get update

sudo apt-get install gcc-snapshot -y
sudo apt-get update

sudo apt-get install gcc-5 g++-5 -y
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-5 60 --slave /usr/bin/g++ g++ /usr/bin/g++-5
```
## Check Version GCCv5.4.1 
```
gcc -v
```
## PACKAGES
```
sudo apt install libqt4-dev qt5-qmake qttools5-dev libqt5webkit5-dev qttools5-dev-tools qt5-default python-sphinx texlive-latex-base inotify-tools openssl libssl-dev libdb++-dev libminiupnpc-dev git sqlite3 libsqlite3-dev g++ libpng-dev gedit python make libbz2-dev libdb-dev libssl-dev libreadline-dev autoconf libtool libleveldb-dev libblkid-dev e2fslibs-dev libaudit-dev nano qtbase5-dev qt4-dev-tools libqtcore4 libqtgui4 automake -y
```
