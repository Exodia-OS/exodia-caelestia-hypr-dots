# ⌨️ Caelestia Hyprland Keybindings Reference

This document provides a comprehensive reference for all keyboard shortcuts available in the Caelestia Hyprland configuration.

## 📋 Table of Contents

- [Application Variables](#application-variables)
- [System Controls](#system-controls)
- [Workspace Navigation](#workspace-navigation)
- [Window Management](#window-management)
- [Application Launchers](#application-launchers)
- [Media Controls](#media-controls)
- [Utilities & Tools](#utilities--tools)
- [Special Workspaces](#special-workspaces)

## 🖥️ Application Variables

These are the default applications configured in the system:

| Application | Default Command | Variable |
|-------------|----------------|----------|
| Terminal | `foot` | `$terminal` |
| Browser | `brave` | `$browser` |
| Editor | `cursor` | `$editor` |
| File Explorer | `thunar` | `$fileExplorer` |

## 🎛️ System Controls

### Session Management
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Alt + Delete` | Session Menu | Open session management menu |
| `Super + L` | Lock Screen | Lock the current session |
| `Super + Alt + L` | Restore Lock | Restore shell and lock |
| `Super + Shift + L` | Suspend | Suspend system to hibernation |

### System Monitoring
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Shift + Escape` | System Monitor | Toggle system monitoring workspace |
| `Super + K` | Show Panels | Display all panels |

### Notifications
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Alt + C` | Clear Notifications | Clear all notifications |

## 🏠 Workspace Navigation

### Basic Workspace Switching
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + 1-9, 0` | Go to Workspace | Switch to workspace 1-10 |
| `Ctrl + Super + 1-9, 0` | Go to Workspace Group | Switch to workspace group 1-10 |
| `Super + Mouse Up/Down` | Next/Previous Workspace | Navigate workspaces with mouse |
| `Ctrl + Super + Left/Right` | Navigate Workspaces | Move between workspaces |
| `Super + Page Up/Down` | Navigate Workspaces | Alternative workspace navigation |

### Workspace Groups
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Super + Mouse Up/Down` | Navigate Groups | Move between workspace groups |

### Special Workspaces
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + S` | Toggle Special Workspace | Toggle special workspace on/off |

## 🪟 Window Management

### Window Movement & Resizing
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Arrow Keys` | Move Focus | Move focus between windows |
| `Super + Shift + Arrow Keys` | Move Window | Move active window |
| `Super + Z` | Move Window Mode | Enter window move mode |
| `Super + X` | Resize Window Mode | Enter window resize mode |
| `Super + Mouse Drag` | Move Window | Drag to move window |
| `Super + Right Mouse Drag` | Resize Window | Drag to resize window |

### Window Layout & Splitting
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Minus/Equal` | Adjust Split | Decrease/increase split ratio |
| `Ctrl + Super + Backslash` | Center Window | Center active window |
| `Ctrl + Super + Alt + Backslash` | Resize & Center | Resize to 55%x70% and center |

### Window States
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + F` | Fullscreen | Toggle fullscreen mode |
| `Super + Alt + F` | Bordered Fullscreen | Fullscreen with borders |
| `Super + Alt + Space` | Toggle Floating | Toggle window floating |
| `Super + P` | Pin Window | Pin window to stay on top |
| `Super + Q` | Close Window | Close active window |

### Picture-in-Picture
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Alt + Backslash` | Picture-in-Picture | Move window to PiP mode |

### Window Movement Between Workspaces
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Alt + 1-9, 0` | Move to Workspace | Move window to workspace 1-10 |
| `Ctrl + Super + Alt + 1-9, 0` | Move to Workspace Group | Move window to workspace group 1-10 |
| `Super + Alt + Page Up/Down` | Move to Previous/Next | Move window to adjacent workspace |
| `Super + Alt + Mouse Up/Down` | Move with Mouse | Move window with mouse scroll |
| `Ctrl + Super + Shift + Left/Right` | Move Adjacent | Move window to adjacent workspace |
| `Ctrl + Super + Shift + Up` | Move to Special | Move window to special workspace |
| `Ctrl + Super + Shift + Down` | Move from Special | Move window back to workspace 0 |
| `Super + Alt + S` | Move to Special | Move window to special workspace |

## 🎯 Window Groups

| Keybinding | Action | Description |
|------------|--------|-------------|
| `Alt + Tab` | Cycle Group Next | Cycle through window groups |
| `Shift + Alt + Tab` | Cycle Group Previous | Cycle through window groups backwards |
| `Ctrl + Alt + Tab` | Change Group Active | Change active window in group (forward) |
| `Ctrl + Shift + Alt + Tab` | Change Group Active | Change active window in group (backward) |
| `Super + Comma` | Toggle Group | Toggle window grouping |
| `Super + U` | Ungroup | Remove window from group |
| `Super + Shift + Comma` | Lock Group | Toggle lock on active group |

## 🚀 Application Launchers

### Primary Applications
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Super_L` | Launcher | Open main application launcher |
| `Super + T` | Terminal | Launch terminal (foot) |
| `Super + W` | Browser | Launch browser (brave) |
| `Super + C` | Editor | Launch code editor (cursor) |
| `Super + E` | File Explorer | Launch file manager (thunar) |

### Additional Applications
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + G` | GitHub Desktop | Launch GitHub Desktop |
| `Super + Alt + E` | Nemo File Manager | Launch Nemo file manager |
| `Ctrl + Alt + Escape` | Process Viewer | Launch system process viewer (qps) |
| `Ctrl + Alt + V` | Audio Control | Launch audio control (pavucontrol) |

## 🎵 Media Controls

### Playback Controls
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Super + Space` | Play/Pause | Toggle media play/pause |
| `XF86AudioPlay` | Play/Pause | Hardware play/pause button |
| `XF86AudioPause` | Play/Pause | Hardware pause button |
| `XF86AudioStop` | Stop | Stop media playback |

### Track Navigation
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Super + Equal` | Next Track | Skip to next track |
| `XF86AudioNext` | Next Track | Hardware next track button |
| `Ctrl + Super + Minus` | Previous Track | Go to previous track |
| `XF86AudioPrev` | Previous Track | Hardware previous track button |

### Volume Control
| Keybinding | Action | Description |
|------------|--------|-------------|
| `XF86AudioMute` | Mute/Unmute | Toggle audio mute |
| `Super + Shift + M` | Mute/Unmute | Alternative mute toggle |
| `XF86AudioRaiseVolume` | Volume Up | Increase volume (10% steps) |
| `XF86AudioLowerVolume` | Volume Down | Decrease volume (10% steps) |

### Brightness Control
| Keybinding | Action | Description |
|------------|--------|-------------|
| `XF86MonBrightnessUp` | Brightness Up | Increase screen brightness |
| `XF86MonBrightnessDown` | Brightness Down | Decrease screen brightness |

## 🛠️ Utilities & Tools

### Screenshot & Recording
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Print` | Screenshot | Full screen capture to clipboard |
| `Super + Shift + S` | Region Screenshot (Freeze) | Capture region with freeze frame |
| `Super + Shift + Alt + S` | Region Screenshot | Capture selected region |
| `Super + Alt + R` | Record Screen (Sound) | Record screen with audio |
| `Ctrl + Alt + R` | Record Screen | Record screen without audio |
| `Super + Shift + Alt + R` | Record Region | Record selected region |

### Clipboard & Emoji
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + V` | Clipboard History | Open clipboard history |
| `Super + Alt + V` | Clipboard History (Desktop) | Open clipboard history on desktop |
| `Super + Period` | Emoji Picker | Open emoji picker |
| `Ctrl + Shift + Alt + V` | Alternative Paste | Paste from clipboard history |

### Color Picker
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Shift + C` | Color Picker | Pick color from screen |

## 🎭 Special Workspaces

| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + M` | Music Workspace | Toggle music player workspace |
| `Super + D` | Communication Workspace | Toggle communication apps workspace |
| `Super + R` | Todo Workspace | Toggle todo manager workspace |

## 🔄 Shell & System

### Shell Management
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Ctrl + Super + Shift + R` | Kill Shell | Kill shell processes |
| `Ctrl + Super + Alt + R` | Restart Shell | Kill shell and restart |

### Testing & Debugging
| Keybinding | Action | Description |
|------------|--------|-------------|
| `Super + Alt + F12` | Test Notification | Send test notification |

## 📝 Notes

- **Super Key**: Refers to the Windows/Super key on your keyboard
- **Mouse Actions**: Some keybindings work with mouse interactions (scroll, drag, etc.)
- **Hardware Keys**: Function keys (F1-F12) and media keys are supported
- **Volume Steps**: Volume adjustments are made in 10% increments
- **Workspace Groups**: Groups allow for multiple sets of 10 workspaces
- **Special Workspaces**: Floating workspaces for specific application types

## 🔧 Customization

To modify keybindings, edit the following files:
- `/etc/skel/.config/hypr/hyprland/variables.conf` - Variable definitions
- `/etc/skel/.config/hypr/hyprland/keybinds.conf` - Keybinding mappings

After making changes, reload Hyprland with:
```bash
hyprctl reload
```

---

<div align="center">
  <strong>Made with ❤️ for the Exodia OS Caelestia community</strong>
</div>
