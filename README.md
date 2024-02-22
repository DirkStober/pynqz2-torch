# Pytorch compiled for the pynq-z2 board (pynq os: 3.0.1)
## System:
- kernel: 5.15.0-91-generic
- PynqLinux, based on Ubuntu 22.04 
- Release 3.0

## Pytorch
- python: 3.10.4
- pytorch: 3.13.1
- torchvision: 0.14.1

## How to compile:
I followed this guide:
https://github.com/sterngerlach/pytorch-pynq-builds/blob/master/how-to-build-wheels.md
although you can just get the rootfs directly from the pynq website:
http://www.pynq.io/board.html

You need to change some print statements for the code to compile (or disable compiler warnings as errors):
https://github.com/jinyangustc/pytorch-rpi/blob/183dfa0483034ebd154ab0fb2c2cf9ce3ce5a7d9/v1.13.1_armhf.patch
