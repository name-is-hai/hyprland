# Complete Package Installation List for Hyprland Dots

**Project:** KooL's Hyprland Dots
**Total Packages:** 100+ from official repos + AUR

---

## 📦 Installation Scripts and Their Packages

### 1. **Base System** (`00-base.sh`)
- `base-devel`
- `archlinux-keyring`
- `findutils`

**Total:** 3 packages

---

### 2. **Hyprland Core** (`hyprland.sh`)
- `hyprland` (Window Manager)
- `hypridle` (Idle Management)
- `hyprlock` (Lock Screen)

**Total:** 3 packages

---

### 3. **Essential Hyprland Packages** (`01-hypr-pkgs.sh`)

#### Main Packages (Required - hypr_package):
- `bc` - Calculator utility
- `cliphist` - Clipboard history
- `curl` - Data transfer tool
- `grim` - Screenshot utility
- `gvfs` - Virtual filesystem
- `gvfs-mtp` - MTP support
- `hyprpolkitagent` - Authorization agent
- `imagemagick` - Image processing
- `inxi` - System information
- `jq` - JSON processor
- `kitty` - Terminal emulator
- `kvantum` - Qt theme engine
- `libspng` - PNG library
- `nano` - Text editor
- `network-manager-applet` - Network applet
- `pamixer` - Pulseaudio mixer
- `pavucontrol` - Volume control
- `playerctl` - Media player control
- `python-requests` - Python HTTP library
- `python-pyquery` - Python query library
- `qt5ct` - Qt5 settings
- `qt6ct` - Qt6 settings
- `qt6-svg` - Qt6 SVG support
- `rofi` - Application launcher
- `slurp` - Selection tool
- `swappy` - Screenshot annotation
- `swaync` - Notification daemon
- `swww` - Wallpaper utility
- `unzip` - Archive extraction
- `wallust` - Wallpaper color extraction
- `waybar` - Status bar
- `wget` - Download utility
- `wl-clipboard` - Wayland clipboard
- `wlogout` - Logout menu
- `xdg-user-dirs` - User directories
- `xdg-utils` - XDG utilities
- `yad` - Dialog utility

**Main Packages Total:** 37 packages

#### Optional Packages (hypr_package_2):
- `brightnessctl` - Screen brightness control
- `btop` - System monitor
- `cava` - Audio visualizer
- `loupe` - Image viewer
- `fastfetch` - System information
- `gnome-system-monitor` - System monitor
- `mousepad` - Text editor
- `mpv` - Media player
- `mpv-mpris` - MPRIS support for mpv
- `nvtop` - GPU monitor
- `nwg-look` - GTK settings
- `nwg-displays` - Display management
- `pacman-contrib` - Pacman utilities
- `qalculate-gtk` - Calculator
- `yt-dlp` - Download videos/audio

**Optional Packages Total:** 15 packages

#### Packages to Remove (Conflicts):
- `aylurs-gtk-shell`
- `dunst`
- `cachyos-hyprland-settings`
- `mako`
- `rofi`
- `wallust-git`
- `rofi-lbonn-wayland`
- `rofi-lbonn-wayland-git`

---

### 4. **Fonts** (`fonts.sh`)
- `adobe-source-code-pro-fonts`
- `noto-fonts-emoji`
- `otf-font-awesome`
- `ttf-droid`
- `ttf-fira-code`
- `ttf-fantasque-nerd`
- `ttf-jetbrains-mono`
- `ttf-jetbrains-mono-nerd`
- `ttf-victor-mono`
- `noto-fonts`

**Total:** 10 packages

---

### 5. **Audio System** (`pipewire.sh`)
- `pipewire` - Audio server
- `wireplumber` - Session manager
- `pipewire-audio` - Audio support
- `pipewire-alsa` - ALSA support
- `pipewire-pulse` - PulseAudio compatibility
- `sof-firmware` - SOF firmware

**Total:** 6 packages

---

### 6. **Shell & Terminal** (`zsh.sh`)
- `lsd` - Modern ls replacement
- `mercurial` - Version control
- `zsh` - Z shell
- `zsh-completions` - Completions for zsh
- `fzf` - Fuzzy finder

**Plus Git Clones:**
- `oh-my-zsh` (from GitHub)
- `zsh-autosuggestions` (from GitHub)
- `zsh-syntax-highlighting` (from GitHub)

**Total:** 5 packages + 3 git repositories

---

### 7. **Display Server & Portals** (`xdph.sh`)
- `xdg-desktop-portal-hyprland` - Hyprland portal
- `xdg-desktop-portal-gtk` - GTK portal
- `umockdev` - Mock devices

**Total:** 3 packages

---

### 8. **Bluetooth** (`bluetooth.sh`)
- `bluez` - Bluetooth daemon
- `bluez-utils` - Bluetooth utilities
- `blueman` - Bluetooth manager GUI

**Total:** 3 packages

---

### 9. **File Manager** (`thunar.sh`)
- `thunar` - File manager
- `thunar-volman` - Volume manager
- `tumbler` - Thumbnail service
- `ffmpegthumbnailer` - Video thumbnails
- `thunar-archive-plugin` - Archive support
- `xarchiver` - Archive manager

**Total:** 6 packages

---

### 10. **Login Manager** (`sddm.sh`)
- `qt6-declarative` - Qt6 QML support
- `qt6-svg` - Qt6 SVG support
- `qt6-virtualkeyboard` - Virtual keyboard
- `qt6-multimedia-ffmpeg` - FFmpeg support
- `qt5-quickcontrols2` - Qt5 controls
- `sddm` - Login manager

**Total:** 6 packages

---

### 11. **GTK Themes** (`gtk_themes.sh`)
- `unzip` - Archive tool
- `gtk-engine-murrine` - GTK theme engine

**Plus Git Clone:**
- `GTK-themes-icons` (from GitHub)

**Total:** 2 packages + 1 git repository

---

### 12. **Aylur's GTK Shell** (`ags.sh`) - OPTIONAL
- `typescript` - TypeScript
- `npm` - Node package manager
- `meson` - Build system
- `glib2-devel` - GLib development
- `gjs` - GObject introspection
- `gtk3` - GTK3 library
- `gtk-layer-shell` - GTK layer shell
- `upower` - Power management
- `networkmanager` - Network manager
- `gobject-introspection` - GObject introspection
- `libdbusmenu-gtk3` - DBus menu for GTK3
- `libsoup3` - HTTP client library

**Total:** 12 packages (Optional - for AGS panel)

---

### 13. **QuickShell** (`quickshell.sh`) - OPTIONAL (Alternative to AGS)
- `qt6-5compat` - Qt6 backward compatibility
- `quickshell` - Shell replacement

**Total:** 2 packages (Optional - alternative to AGS)

---

### 14. **Nvidia Support** (`nvidia.sh`) - OPTIONAL (GPU Support)
- `nvidia-dkms` - Nvidia driver
- `nvidia-settings` - Nvidia control panel
- `nvidia-utils` - Nvidia utilities
- `libva` - Video acceleration
- `libva-nvidia-driver` - Nvidia VA driver
- `linux-headers` (dynamically selected based on kernel)

**Total:** 6 packages (Optional - for Nvidia GPUs)

---

### 15. **System Monitoring**

#### Battery Monitor (`battery-monitor.sh`)
- `acpi` - Power management info
- `libnotify` - Notifications

**Total:** 2 packages

#### Disk Monitor (`disk-monitor.sh`)
- *Specified in script* (Check if has custom packages)

#### Temperature Monitor (`temp-monitor.sh`)
- *Specified in script* (Check if has custom packages)

---

### 16. **AUR Helpers** (Choose One)

#### Option A: Paru (`paru.sh`)
- `paru-bin` - AUR helper

#### Option B: Yay (`yay.sh`)
- `yay-bin` - AUR helper

**Note:** Only one AUR helper is installed, depending on which is already available.

---

### 17. **Dotfiles** (`dotfiles-main.sh`)
- Clones and installs KooL's Hyprland configuration files

---

## 📊 Package Summary

| Category | Count | Status |
|----------|-------|--------|
| Base System | 3 | Required |
| Hyprland Core | 3 | Required |
| Essential Packages | 52 | Required (37) + Optional (15) |
| Fonts | 10 | Required |
| Audio (Pipewire) | 6 | Required |
| Shell & Terminal | 5 + 3 repos | Required |
| Display Portals | 3 | Required |
| Bluetooth | 3 | Required |
| File Manager | 6 | Required |
| Login Manager | 6 | Required |
| GTK Themes | 2 + 1 repo | Required |
| AGS (Optional) | 12 | Optional |
| QuickShell (Optional) | 2 | Optional |
| Nvidia (Optional) | 6 | Optional |
| System Monitors | 2+ | Optional |
| AUR Helper | 1 | Required (one of the two) |
| **TOTAL** | **~120+** | **Mix of required and optional** |

---

## 🔧 Installation Order (Default Sequence)

1. `00-base.sh` - Base development environment
2. `01-hypr-pkgs.sh` - Essential packages (installs or removes)
3. `hyprland.sh` - Hyprland window manager
4. `fonts.sh` - Required fonts
5. `gtk_themes.sh` - GTK themes
6. `pipewire.sh` - Audio system
7. `zsh.sh` - Shell configuration
8. `bluetooth.sh` - Bluetooth support
9. `thunar.sh` - File manager
10. `sddm.sh` - Display manager
11. `xdph.sh` - Desktop portals
12. `ags.sh` OR `quickshell.sh` - Desktop shell (optional)
13. `nvidia.sh` - Nvidia drivers (optional)
14. `battery-monitor.sh` - Battery monitoring (optional)
15. `dotfiles-main.sh` - Configuration files

---

## ⚠️ Important Notes

- **AUR Packages:** Some packages like `ags`, `quickshell`, and fonts may come from AUR
- **GPU Support:** Nvidia installation is optional and only needed for Nvidia GPUs
- **Desktop Shell:** Choose either AGS or QuickShell, not both
- **Conflicts:** Certain packages are automatically removed to avoid conflicts
- **Dependencies:** This is a complete, pre-configured Hyprland environment
- **Requirements:** Arch Linux based system with internet connection

---

Generated on: **February 8, 2026**
Source: Hyprland installation scripts analysis
