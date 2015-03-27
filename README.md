# razer-blackwidow-ultimate
Enables M1-M5 and FN keys in Linux for the Razer BlackWidow Ultimate keyboard.

##TODO
This package has the ProductID of the kb baked in.
I updated it with my own, but it should try them all.
Known possible IDs are 010d, 010e, 010f, 011a.
To find out yours run in the terminal:
```
lsusb -d 1532:
```
You should get something like:
```
Bus 004 Device 005: ID 1532:010d Razer USA, Ltd
```
The original Haskell program at https://github.com/tuxmark5/EnableRazer on which this is based does the right thing.

## AUR

#### If you have Arch Linux or Arch based distribution compatible with AUR (Manjaro, Antergos, ArchBang, Bridge Linux) then you can simply install razer-blackwidow-ultimate from the AUR:

##### $ yaourt -S razer-blackwidow-ultimate

https://aur.archlinux.org/packages/razer-blackwidow-ultimate
