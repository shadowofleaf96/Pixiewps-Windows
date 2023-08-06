# Pixiewps-Windows


This is a modified pixiewps that can be compiled for windows on linux using MinGW
to Compile on ubuntu
you need :

1 - install MinGW

sudo apt-get update
sudo apt-get -y install mingw-w64

2 - git clone this repo

git clone https://github.com/shadowofleaf96/Pixiewps-Windows

3 - change to repo current directory

cd Pixiewps-Windows

4 - build exe from pixiewps.c

32bit : make
64bit : make -f '/home/unk/Bureau/pixiewps-1.4.2/Makefile64' 

5 - voila you will find a file called pixiewps.exe
