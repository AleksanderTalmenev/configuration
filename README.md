
sudo apt install gnome-tweaks

sudo apt install gnome-???

---

In case when my bluetooth does not found on ASUS (Ubuntu):

```
Check whether inxi --full --verbosity=7 --filter --no-host gives you <No Bluetooth data found>. If so, try to turn off fastboot in BIOS, soft reboot the system and check it again. The problem is that, when fastboot is ON in BIOS, a system skips initialization of some devices to speed up boot, so Ubuntu can't see Bluetooth device.
```
---
## Adding in vim connection with system clipboard:
 
check in vim 
```vim
:version 
```
if -clipboard -> `sudo apt install vim-gtk3`

## For reading from file directly in clipboard:

```bach
sudo apt install xclip
```
```bach
xclip -sel c < input_file
```

