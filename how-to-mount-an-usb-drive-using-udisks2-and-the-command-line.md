---
title: How to mount an usb drive using udisks2 and the command line?
date: 2023-05-14
tags: [ knowledge, linux, command-line, usb, udisks2 ]
---

# How to mount an usb drive using udisks2 and the command line?

- Find the unmounted usb drive.
```
$ sudo fdisk -l
```

- Mount the usb drive.
```
$ udisksctl mount -b /dev/usb_name
```
