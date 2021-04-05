### make sure you replace /home/ari/ with /home/your-username-here/ or ~/
##### if anything breaks please make sure to have logs, for example what you ran and what was the output

### CONTENTS
```text
config.fish - systemwide fish config [/etc/fish/config.fish]
nanorc - nano rc file [/etc/nanorc]
Xenlism-Arch - grub theme i use (SEE CREDITS)
.config/ (_.themes.zip) - some app configs [~/.config/]
.icons/ (_.icons.zip) - icons and cursors [~/.icons] (SEE CREDITS)
.themes/ - gnome themes [~/.themes/] (SEE CREDITS)
patch_fish/ - modifies your fish to look better
clean_gnome.arch.sh - removes unnecessary packages that come with gnome
bye_gdm.arch.sh - removes GDM and replaces it with lightdm
gnome_repair.arch/ - fixes common problems i had with my scripts (run them one by one and see if they fix your issue, if one worked - don't run the other, reboot after every attempt) 
svcs.arch.sh - enables services to make your computer and packages run smoother
```

### packages (arch linux)
```shell
sudo pacman -S fish nano gnome gnome-tweaks
```

### CREDITS
[Xenlism Grub Theme](https://www.gnome-look.org/p/1440862/)<br/>
[Bibata Cursors](https://www.gnome-look.org/p/1197198/)
