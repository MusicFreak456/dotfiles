# Dotfiles

Use `chezmoi` to apply the configs.

Needed software: `niri` `waybar` `swaybg` `swaync` `fuzzel` `blueman` `pavucontrol`.
Optionally: `kitty` `xdg-desktop-portal-gnome`.

Needed cursor: `phinger-cursors`.

Needed fonts: `ttf-fira-code` `ttf-cantarell` `otf-font-awesome`.

Set theme to Adwaita Dark using `lxappearance`.

Set theme of xdg-desktop-portal-gnome with:
```
dconf write /org/gnome/desktop/interface/color-scheme '"prefer-dark"'
```

## Screenshot

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d6489119-9f87-4b48-9d6f-2cd09ab626c3" />

## Systemd setup

Execute the following:
```
systemctl --user add-wants niri.service waybar.service
systemctl --user add-wants niri.service swaybg.service
systemctl --user add-wants niri.service swaync.service 
```

