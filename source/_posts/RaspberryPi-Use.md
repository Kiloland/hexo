---
title: RaspberryPi Use
date: 2019-07-23 23:21:45
tags:
---
#Raspberry 烧录要求
##SD卡要求

##烧录后处理

##开启SSH

##开启VNC

##查看树莓派安装的软件
dpkg -l |grep vim

or

which vim

whereis vim

or

aptitude is Raspberrypi package manage tool

##删除Vim-tiny
apt-get remove vim-tiny
apt-get remove vim-common
##安装vim-full
apt-get install vim
##Edit vimrc
vimrc


