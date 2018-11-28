# Lovemouth
I &lt;3 OS' sexy Plymouth theme.<br>
(No mouth was loved in the process of making this theme)

## How to use it <br>
(Everything as root btw)
1. Clone it into /usr/share/plymouth/themes/ilos-write/ <br>
```
# git clone https://github.com/I-love-os/Lovemouth.git /usr/share/plymouth/themes/ilos-write/
```

2. Select it and rebuild the initrd (you have to have plymouth (duh) and dracut installed)
```
# plymouth-set-default-theme ilos-write -R
```

3. Reboot <br>
You should see the cool I <3 OS splash screen on boot woo.
