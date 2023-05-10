---
title: How to format an usb memory using the command line?
date: 2023-05-07
tags: [  ]
---

# How to format an usb memory using the command line?

- Check if the usb memory is mounted.
```
$ df
```

- If it's mounted, unmount it.
```
$ sudo unmount /dev/usb-name
```

- Format the usb memory using your preferred format.
    * FAT32:
        ```
        $ sudo mkfs.vfat /dev/usb-name
        ```

    * NTFS:
        ```
        $ sudo mkfs.ntfs /dev/usb-name
        ```

    * exFAT:
        ```
        $ sudo mkfs.exfat /dev/usb-name
        ```

- Verify.
```
$ sudo fsck /dev/usb-name
```
