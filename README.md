# Linux-ck-uksm-cjktty

![GitHub](https://img.shields.io/github/license/RiverOnVenus/linux-ck-uksm-cjktty) [![PKGBUILD CI](https://github.com/RiverOnVenus/linux-ck-uksm-cjktty/actions/workflows/main.yml/badge.svg)](https://github.com/RiverOnVenus/linux-ck-uksm-cjktty/actions/workflows/main.yml) ![GitHub all releases](https://img.shields.io/github/downloads/RiverOnVenus/linux-ck-uksm-cjktty/total)

The Linux-ck-uksm-cjktty kernel and modules with the ck1 patchset and uksm patch and cjktty patch featuring MuQSS CPU scheduler and default bbr.

- Con Kolivas' ck patchset including a CPU scheduler named MuQSS (*Multiple Queue Skiplist Scheduler*, pronounced *mux*) which replaces Brain Fuck Scheduler (BFS), his previous work. Many Arch Linux users choose this kernel for its excellent desktop interactivity and responsiveness under any load situation. It is designed for desktop/laptop use but not for servers. It provides low latency environment and works well for 16 CPUs or fewer.
- UKSM patch is an improvement upon KSM. Some basic data structures and routines are borrowed from ksm.c .
- CJKTTY patch support in Linux tty display Chinese.
- BBR is a congestion control algorithm proposed by Google.

## Build and install

- [AUR](https://aur.archlinux.org/packages/?K=linux-ck-uksm-cjktty)
- [Release page](https://github.com/RiverOnVenus/linux-ck-uksm-cjktty/releases)

## About CK

- [Linux-ck](https://wiki.archlinux.org/title/Linux-ck)
- [LKML announcement](https://lkml.org/lkml/2016/10/29/4)
- [Kernel patch repository of Con Kolivas](http://ck.kolivas.org/patches/)
- [Con Kolivas' Blog](https://ck-hack.blogspot.it/)

## About UKSM

- [dolohow/uksm](https://github.com/dolohow/uksm)

## About CJKTTY

- [zhmars/cjktty-patches](https://github.com/zhmars/cjktty-patches)

## About BBR

- [google/bbr](https://github.com/google/bbr)
