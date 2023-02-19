#knowledge
#linux
#archlinux
#arcolinux
#pacman

# How to solve the "invalid or corrupted package (PGP signature)" error when upgrading Arch Linux

First try upgrading archlinux-keyring.

```
>sudo pacman -Sy archlinux-keyring
```

If it doesn't work, try removing .part files in pacman's cache.

```
>find /var/cache/pacman/pkg/ -iname "*.part" -delete
```

If it doesn't work, try to delete and repopulate the key related to the error.

```
# Error
error: jansson: signature from "Eli Schwartz <eschwartz@archlinux.org>" is marginal trust
:: File /var/cache/pacman/pkg/jansson-2.10-3-x86_64.pkg.tar.xz is corrupted (invalid or corrupted package (PGP signature)).

# List the keys related to schwartz
>sudo pacman-key --list-sigs schwartz

# Output
gpg: Note: trustdb not writable
pub   rsa4096 2016-05-04 [SC] [expires: 2018-12-13]
      BD27B07A5EF45C2ADAF70E0484818A6819AF4A9B
uid           [marginal] Eli Schwartz <eschwartz@archlinux.org>
sig          B754AD1D789C8C83 2017-12-07  [User ID not found]
sig          BA1DFB64FFF979E7 2018-01-08  Allan McRae (Arch Linux Master Key) <allan@master-key.archlinux.org>
sig          9B729B06A680C281 2017-12-25  Bartłomiej Piotrowski (Arch Linux Master Key) <bpiotrowski@master-key.archlinux.org>
sig          A88E23E377514E00 2017-12-25  Florian Pritz (Arch Linux Master Key) <florian@master-key.archlinux.org>
sig 3        84818A6819AF4A9B 2017-07-19  Eli Schwartz <eschwartz@archlinux.org>
uid           [marginal] Eli Schwartz <eschwartz93@gmail.com>
sig          BA1DFB64FFF979E7 2018-01-08  Allan McRae (Arch Linux Master Key) <allan@master-key.archlinux.org>
sig          9B729B06A680C281 2017-12-25  Bartłomiej Piotrowski (Arch Linux Master Key) <bpiotrowski@master-key.archlinux.org>
sig          A88E23E377514E00 2017-12-25  Florian Pritz (Arch Linux Master Key) <florian@master-key.archlinux.org>
sig 3        84818A6819AF4A9B 2016-12-13  Eli Schwartz <eschwartz@archlinux.org>
sub   rsa4096 2016-05-04 [E] [expires: 2018-12-13]
sig          84818A6819AF4A9B 2016-12-13  Eli Schwartz <eschwartz@archlinux.org>
sub   rsa4096 2017-01-09 [S] [expires: 2019-01-09]
sig          84818A6819AF4A9B 2017-01-09  Eli Schwartz <eschwartz@archlinux.org>

# Delete and repopulate key

>sudo pacman-key --delete BD27B07A5EF45C2ADAF70E0484818A6819AF4A9B
>sudo pacman-key --populate archlinux
```
