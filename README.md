# Aero-grub

This is WIP I haven't fully fixed it. Works on Fedora 43

## Fixes
### `/etc/default/grub`
```
GRUB_TERMINAL_OUTPUT="gfxterm"
GRUB_GFXMODE=auto
GRUB_THEME="/boot/grub2/themes/Aero/theme.txt"
```

Should work if you rebuild it with
```bash
sudo grub2-mkconfig -o /boot/grub2/grub.cfg
```
