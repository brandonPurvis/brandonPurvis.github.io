---
layout: post
title: "Installing PyCharm on Debian"
categories: how-to
---

## Download Pycharm

Go to [jetbrains](http://www.jetbrains.com/pycharm/) and download the community version of pycharm for Linux.
This downloads a *.tar.gz file into your Downloads folder.

## Go To Download Location

Using the terminal, `cd` into your downloads folder.
It will contain 'pycharm-community-<year/version>.tar.gz'.

## Extract the Archive to Folder

Extract the archive by executinh `tar xvf <name of file>`.
'x' means extract;
'v' means verbose and so the program displays the files it's working on;
'f' means use an archive file.
You should now have folder named 'pycharm-community-<year/version>'.


## Move Folder to Install Location

Move the newly created folder to where you want it installed by executing
`mv pycharm-community-<year/version> <your-location>`.

## Run Install

`cd` into the folders 'bin' folder and execute `./pycharm.sh`

## Use PyCharm to Make Cool Things