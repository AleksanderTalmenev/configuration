
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
in vscode:
```
Vim: Use System Clipboard
Use system clipboard for unnamed register.
```

## For reading from file directly in clipboard:

```bach
sudo apt install xclip
```
```bach
xclip -sel c < input_file
```


[Vim in obsidian](
https://publish.obsidian.md/hub/04+-+Guides%2C+Workflows%2C+%26+Courses/for+Vim+users)

```bash
xclip -sel c < input_file
```
will copy the contents of `input_file` to clipboard. `xclip` requires installation. To install```
```bash
sudo apt install xclip
```
https://lamport.azurewebsites.net/tla/science.pdf

How to switch from code to explorer and return back:
```
Cntrl + Shift + E  
```
How switch by suggestions in vscode:
```
Cntrl + n
Cntrl + p
```

### How change hotkeys for switching between windows in vscode:

Press `Ctrl + Shift + P`

Type Preferences: `Open Keyboard Shortcuts (JSON) and open it.

Add these entries to remap (example):

```json

[
  {
    "key": "ctrl+shift+k",
    "command": "workbench.action.nextEditor"
  },
  {
    "key": "ctrl+shift+j",
    "command": "workbench.action.previousEditor"
  }
]
```

## Vim:

o - append (open) a new line below the current line.
O - append (open) a new line above the current line.

### Server mode:
Switch to server mode in Ubuntu:
```
Alt + F4 
```
Return to desktop mode:
```
Alt + F1
```
### Show suggesions in vscode:

```
Cntrl + Space
```
# Chrome
Another extension for suggesions ```
```
tridactyl
```
		

