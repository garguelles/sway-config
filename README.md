# Sway Configuration

Wayland compositor config with vim-style navigation, waybar status bar, and laptop clamshell mode support.

## Features

- **Mod key**: Alt (Mod1)
- **Navigation**: vim hjkl keys
- **Terminal**: foot
- **Launcher**: fuzzel
- **Status bar**: waybar
- **Idle**: Lock at 30min, displays off at 60min
- **Clamshell**: Auto-disable laptop display on lid close
- **Caps Lock**: Remapped to Ctrl

## Key Bindings

| Binding | Action |
|---------|--------|
| `Alt+Return` | Terminal |
| `Alt+d` | App launcher |
| `Alt+Shift+q` | Kill window |
| `Alt+hjkl` | Focus direction |
| `Alt+Shift+hjkl` | Move window |
| `Alt+1-0` | Switch workspace |
| `Alt+Shift+1-0` | Move to workspace |
| `Alt+f` | Fullscreen |
| `Alt+Shift+Space` | Toggle floating |
| `Alt+r` | Resize mode |
| `Alt+b/v` | Split horizontal/vertical |
| `Alt+s/w/e` | Stacking/tabbed/split layout |
| `Alt+Ctrl+l` | Lock screen |
| `Alt+Ctrl+p` | Screenshot all |
| `Alt+Ctrl+Shift+p` | Screenshot region |
| `Alt+Shift+c` | Reload config |
| `Alt+Shift+e` | Exit sway |

## Installation

### Fedora

```bash
sudo dnf install sway foot fuzzel swaylock swayidle waybar pipewire-utils brightnessctl grim slurp wl-clipboard jq
```

### Arch

```bash
sudo pacman -S sway foot fuzzel swaylock swayidle waybar pipewire brightnessctl grim slurp wl-clipboard jq
```

### Ubuntu/Debian

```bash
sudo apt install sway foot fuzzel swaylock swayidle waybar pipewire brightnessctl grim slurp wl-clipboard jq
```

## Files

- `config` - Main sway configuration
- `lid-state.sh` - Laptop lid state detection script
