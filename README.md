# Arch cybers4ge
> Based on [Cyber-Arch](https://github.com/V1xEr3bus/Cyber-Arch) by V1xEr3bus — "Into the dark... with precision."

![screenshot](./.assets/screenshot.png)

## Changes from Cyber-Arch
- **Zsh** instead of Fish shell (custom `.zshrc` with aliases & prompt)
- Custom **Hyprland** config (keybinds, animations, rules)
- Custom **Kitty** config

## Stack
- **WM:** Hyprland
- **Terminal:** Kitty + Starship
- **Shell:** Zsh
- **Bar:** Waybar
- **Notifications:** SwayNC
- **Launcher:** Rofi (Wayland)
- **Wallpaper:** Waypaper + swww
- **Editor:** NvChad (Neovim)
- **File Manager:** Ranger
- **Clipboard:** Clipse
- **Fetch:** Fastfetch

## Dependencies
```bash
paru -S zoxide bat fastfetch cava cmatrix blueman swww \
  wl-clipboard python-pywal playerctl jq fzf rofi-wayland kitty \
  neovim clipse ranger starship zsh
```

Optional:
- `grim` + `slurp` → Screenshots
- `pamixer` → Volume management

## Included Configs
```
.config/
├── hypr/         → Hyprland config & scripts
├── kitty/        → Terminal config
├── waybar/       → Top bar
├── swaync/       → Notification center
├── rofi/         → Wi-Fi, Bluetooth, emoji menus
├── cava/         → Audio visualizer
├── clipse/       → Clipboard manager
├── fastfetch/    → Fetch theme
├── ranger/       → File manager
├── nvim/         → NvChad setup
.zshrc            → Zsh config
.local/share/rofi/ → cyberpunk.rasi theme
```

## Installation
> ⚠️ Back up your existing configs first.
```bash
git clone https://github.com/Gl1tchS4ge/my-arch-env
cd my-arch-env

cp -r .config/* ~/.config/
cp -r .local/share/rofi ~/.local/share/rofi
cp .zshrc ~/
```

Then log into Hyprland. Make sure you have **Nord font** installed or you may run into visual issues.

## Scripts
- `wallpaper.sh` — Toggle wallpaper directories
- `wifi.sh` — Rofi wireless menu
- `bluetooth.sh` — Rofi Bluetooth controller

## Credits
- Original rice: [V1xEr3bus/Cyber-Arch](https://github.com/V1xEr3bus/Cyber-Arch)

## License
MIT — Free to use, modify, and share.
