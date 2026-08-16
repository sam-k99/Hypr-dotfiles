# Dotfiles


## Features

-  **Hyprland** — fluid animations with custom bezier curves, rounded corners, blur and transparency
-  **Catppuccin Mocha** — consistent color theme across everything
-  **Liquid Glass Waybar** — macOS Tahoe inspired floating pills with water-on-glass effect
-  **Rofi** — clean dark app launcher matching the theme
-  **swww** — smooth wallpaper transitions
-  **Battery optimized** — charge limit, VRR disabled for stability
-  **Dual GPU** — AMD iGPU for compositor, GTX 1650 available via `prime-run`
-  **Clipboard manager** — cliphist with rofi picker
-  **Dunst** — minimal notification daemon
-  **Dual boot** — Windows 11 + Arch via systemd-boot
-  **144hz** — properly configured for smooth experience


## Installation

### 1. Clone the repo
```bash
git clone https://github.com/sam-k99/hypr-dotfiles.git
cd dotfiles
```




## File Structure

```
dotfiles/
├── config/
│   ├── hypr/
│   │   └── hyprland.conf        # Main Hyprland config
│   ├── waybar/
│   │   ├── config.jsonc         # Waybar modules and layout
│   │   └── style.css            # Waybar liquid glass theme
│   ├── rofi/
│   │   └── config.rasi          # Rofi launcher theme
│   ├── kitty/
│   │   └── kitty.conf           # Terminal config
│   └── dunst/
│       └── dunstrc              # Notification config
└── README.md
```
