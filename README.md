# hyprland-dotfiles

Personal Hyprland desktop configuration for an ASUS ROG G15 Strix (2021) laptop.

## Contents

| Directory  | App                              |
|------------|-----------------------------------|
| `hypr/`    | Hyprland compositor, hyprpaper, xdg-desktop-portal helper script |
| `waybar/`  | Status bar (incl. custom weather script) |
| `wofi/`    | App launcher |
| `swaylock/`| Screen locker |
| `kitty/`   | Terminal emulator |

Theme is Catppuccin Mocha across most apps.

## Install

Symlink (or copy) each directory into `~/.config/`, e.g.:

```sh
ln -s "$(pwd)"/hypr      ~/.config/hypr
ln -s "$(pwd)"/waybar    ~/.config/waybar
ln -s "$(pwd)"/wofi      ~/.config/wofi
ln -s "$(pwd)"/swaylock  ~/.config/swaylock
ln -s "$(pwd)"/kitty     ~/.config/kitty
```

## Dependencies

hyprland, waybar, wofi, wlogout, swaylock-effects, swaybg/hyprpaper, kitty, grim, slurp, swappy, pamixer, brightnessctl, asusctl (ROG-specific), thunar.

## Notes

- Wallpaper image files are not tracked here (kept local, referenced by absolute path in `hypr/hyprland.conf` / `hypr/hyprpaper.conf`).
- ROG-specific keybinds (fan profile, ASUS RGB, Armory Crate) live in `hypr/hyprland.conf` and are hardware-specific to the G15 Strix.
