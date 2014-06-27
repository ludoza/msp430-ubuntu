# msp430-ubuntu

## Introduction

I'm playing around with the [msp430 value line launchpad](http://www.ti.com/tool/msp-exp430g2) and started to write scripts for myself as I progressed, this git repo is where the scripts live. I will try to give a url when I execute a bunch of commands without giving a explanation.

## Usage

Execute `./install` then it will ask you for your sudo password and confirmation that you want to install the msp430 packages. After instellation make sure your msp430 development tool is plugged in via usb and execute `./c-to-msp example/blink.c` then in a perfect world it should upload the c program to the MCU and execute it.
