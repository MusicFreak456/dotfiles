# Dotfiles

Use `chezmoi` to apply the configs.

Needed software: `niri` `waybar` `swaybg` `swaync` `fuzzel` `blueman` `pavucontrol`.
Optionally: `kitty` `xdg-desktop-portal-gnome`.

Needed fonts: `ttf-fira-code` `ttf-cantarell` `otf-font-awesome`.

Set theme to Adwaita Dark using `lxappearance`.

Set theme of xdg-desktop-portal-gnome with:
```
dconf write /org/gnome/desktop/interface/color-scheme '"prefer-dark"'
```

## Systemd setup

Execute the following:
```
systemctl --user add-wants niri.service waybar.service
systemctl --user add-wants niri.service swaybg.service
systemctl --user add-wants niri.service swaync.service 
```

