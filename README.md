# My favorite _**Free and Open Source**_ Software
- Links go to...
	- GitHub repositories (whenever possible)
	- Project websites
- I strongly recommend the following websites for finding and comparing the right software for anyone and their use case:
	- [AlternativeTo](https://alternativeto.net/): Find alternatives for specific products
	- [Slant](https://slant.co): Compare products of a broader category (like "Linux distributions")
- If you are familiar with [NixOS](https://nixos.org/) you can find my `configuration.nix` in my [dotfiles](https://github.com/julius-boettger/dotfiles), which contains all the software I currently use

# Cross-Platform
> All of this is available at least on Linux and Windows, probably even more!
- [Firefox Browser Developer Edition](https://www.mozilla.org/en-US/firefox/developer/): Internet browser
	- [Bonjourr](https://github.com/victrme/Bonjourr): Add-on for a better startpage
- [Qwant](https://about.qwant.com/en/): Search engine
- [VSCodium](https://github.com/VSCodium/vscodium): Open source builds of [VSCode](https://github.com/microsoft/vscode), a universal code and text editor
- [Proton Mail](https://github.com/ProtonMail) + [Proton Calendar](https://proton.me/calendar): End-to-end encrypted email and calendar
- [LibreOffice](https://www.libreoffice.org/): Office suite containing tools for word processing, spreadsheets, presentations, ...
- [VirtualBox](https://www.virtualbox.org/): Virtualization software (for managing and running VM's)
	- VM's are really useful! Testing out operating systems, checking the safety of executables with no risk to your system, ...
- [GIMP](https://www.gimp.org/): Image editing and manipulation software
- [Inkscape](https://github.com/inkscape/inkscape): Create and edit vector graphics (SVG, PDF, ...)
- [Darktable](https://github.com/darktable-org/darktable): Photography workflow application and non-destructive raw developer 
- [OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB): RGB lighting control for various hardware
- [Insomnia](https://github.com/Kong/insomnia): HTTP API client, useful for testing e.g. REST API's
- [Ventoy](https://github.com/ventoy/Ventoy): For creating a reusable bootable USB drive that can hold multiple ISO's at once (no more reformatting for every ISO!)
- [Digital](https://github.com/hneemann/Digital) + [GHDL](https://github.com/ghdl/ghdl): Digital circuit and VHDL simulation
- [`liquidctl`](https://github.com/liquidctl/liquidctl): CLI-tool and drivers for liquid coolers (also see [`liquidtux`](https://github.com/liquidctl/liquidtux) when on [Linux](#linux))
- [Overleaf](https://github.com/overleaf/overleaf): Web-based real-time collaborative LaTeX editor
- [GParted](https://gparted.org/): Partition editor 
	- Especially useful as bootable USB drive!
- [Alacritty](https://github.com/alacritty/alacritty): GPU-accelerated terminal emulator
- [OBS Studio](https://github.com/obsproject/obs-studio): Live streaming and screen recording
- [Gitnuro](https://github.com/JetpackDuba/Gitnuro): Desktop GUI for `git`
	- If you run into issues with credentials see [this issue](https://github.com/JetpackDuba/Gitnuro/issues/16)
- [rEFInd](http://www.rodsbooks.com/refind/): (U)EFI boot manager
	- [refind-dark](https://github.com/2KAbhishek/refind-dark): Theme for rEFInd
	- I strongly recommend this for dual boot systems, as you will need some kind of boot manager either way. This is probably the best-looking one + it supports using your mouse!
- [Barrier](https://github.com/debauchee/barrier): Switch between using your mouse and keyboard on different systems over the network (instead of physically replugging them all the time)
- [Flameshot](https://github.com/flameshot-org/flameshot): Quickly take, edit, share and save screenshots
- [Sioyek](https://github.com/ahrm/sioyek): Minimal keyboard-focused PDF viewer
- [Starship](https://github.com/starship/starship): Highly customizable shell prompt (for any shell)
- [VeraCrypt](https://github.com/veracrypt/VeraCrypt): Encrypt (password-protect) disks/drives and partitions
	- I use this to password-protect my external backup-SSD
- [FreeFileSync](https://freefilesync.org/): Folder comparison and synchronization software that creates and manages backups
	- I use this to make occasional differential backups of my data on an external SSD

# Mobile (Android / iOS)
- [ente Authenticator](https://github.com/ente-io/auth): 2FA with end-to-end encrypted cloud backups and web access

# Linux
> The following software is only available for Linux-based operating systems.
- [NixOS](https://github.com/NixOS/nixpkgs): Linux-based immutable operating system
- [keyd](https://github.com/rvaiya/keyd): Key remapping daemon
	- very useful for European folks who are used to `Ctrl+Alt` doing the same thing as `AltGr`, which is not the default on Linux, but can be configured to work like that with this program
- [SDDM](https://github.com/sddm/sddm): Display manager / login screen
	- [`sddm-sugar-candy`](https://github.com/Kangie/sddm-sugar-candy): Theme for SDDM
- [OneDrive Client for Linux](https://github.com/abraunegg/onedrive): CLI tool for accessing Microsoft OneDrive
	- [OneDriveGUI](https://github.com/bpozdena/OneDriveGUI): GUI for before-mentioned OneDrive CLI tool
- [Proton GE Custom](https://github.com/GloriousEggroll/proton-ge-custom): [Proton](https://github.com/ValveSoftware/Proton) fork with various changes for a better gaming experience (primarily with Steam games for Windows)
	- [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt): GUI for easy management of Proton and Wine installations
- [`liquidtux`](https://github.com/liquidctl/liquidtux): Kernel drivers for liquid coolers (e.g. makes [lm-sensors](https://github.com/lm-sensors/lm-sensors) recognize coolant temperature sensor, also see [`liquidctl`](https://github.com/liquidctl/liquidctl) under [Cross-Platform](#cross-platform))
- [Fish Shell](https://github.com/fish-shell/fish-shell): Modern shell
- [Font Manager](https://github.com/FontManager/font-manager): Font management
- [Stacer](https://github.com/oguzhaninan/Stacer): System optimization and monitoring (processes, services, cache, ...)
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher): Integrate AppImages into your system seamlessly
- [Flatseal](https://github.com/tchx84/Flatseal): Manage Flatpak permissions per app
- [Psensor](https://github.com/chinf/psensor) (GUI) + [lm-sensors](https://github.com/lm-sensors/lm-sensors) (CLI): Sensor monitoring (e.g. cpu temperature)
- [Piper](https://github.com/libratbag/piper): Configure gaming mice
- [Playerctl](https://github.com/altdesktop/playerctl): CLI-tool for controlling media players (e.g. play/pause current media player)
- [nvidia-system-monitor](https://github.com/congard/nvidia-system-monitor-qt): System monitor for NVIDIA GPU's
- [NoiseTorch](https://github.com/noisetorch/NoiseTorch): Real-time microphone background noise suppression

### Theming
> Theming of this kind is possible on almost any graphical Linux-system, although the methods to apply these themes vary.
- GTK Themes (change the look and feel of apps built with GTK)
	- [Orchis theme](https://github.com/vinceliuice/Orchis-theme): Rounded corners
	- [Fluent gtk theme](https://github.com/vinceliuice/Fluent-gtk-theme): Sharp corners (often better with window managers)
- Cursors (sets of custom cursors)
	- [Capitaine cursors](https://github.com/keeferrourke/capitaine-cursors): Unobtrusive and modern cursor with rainbow loading animation
	- [Colloid cursors](https://github.com/vinceliuice/Colloid-icon-theme/tree/main/cursors): Based on [Capitaine cursors](https://github.com/keeferrourke/capitaine-cursors), but has a slightly more uncommon shape
- Icons (sets of custom icons for common applications, folders, ...)
	- [Papirus icon theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme): Flat, modern and minimalistic icons
	- [Fluent icon theme](https://github.com/vinceliuice/Fluent-icon-theme): Uses transparency and blur wherever possible

### Custom Desktop Environment
> This is software I exclusively use when I am not using a desktop environment but a standalone Xorg window manager or Wayland compositor.
>
> If you are interested in this section you might also want to take a look at my [dotfiles](https://github.com/julius-boettger/dotfiles) ;)
- [Rofi](https://github.com/lbonn/rofi) (fork with Wayland support): Application Launcher
- [CopyQ](https://github.com/hluk/CopyQ): Clipboard manager with history
- `lxpolkit` (shipped with [`lxsession`](https://github.com/lxde/lxsession)): Simple PolicyKit authentication agent
- [`lxappearance`](https://github.com/lxde/lxappearance) (not needed when using [NixOS](https://github.com/NixOS/nixpkgs)): Tool to set GTK themes, cursors, icons, ...

#### [`wlroots`](https://gitlab.freedesktop.org/wlroots/wlroots)-based Wayland compositor only

- [Hyprland](https://github.com/hyprwm/Hyprland): Highly customizable tiling compositor
	- [Hyprsome](https://github.com/sopa0/hyprsome): [Awesome](https://github.com/awesomeWM/awesome)-like workspace management for Hyprland
	- Grimblast (part of [Hypr Dev Contrib](https://github.com/hyprwm/contrib)): Screenshot utility for Hyprland based on Sway's Grimshot
- [Hyprpicker](https://github.com/hyprwm/hyprpicker): Simple color picker
- [SwayNotificationCenter](https://github.com/ErikReider/SwayNotificationCenter): Customizable Notification daemon and control center
- [SwayOSD](https://github.com/ErikReider/SwayOSD): On-screen display for changing volume, brightness, toggling capslock, ...
- [swaylock-effects](https://github.com/jirutka/swaylock-effects): Modern-looking lockscreen
- [`swww`](https://github.com/Horus645/swww): Wallpaper setter with change animations and support for animated wallpapers
	
#### Xorg window manager only

- [Awesome](https://github.com/awesomeWM/awesome): Highly customizable tiling window manager
	- [Awesome Copycats](https://github.com/lcpz/awesome-copycats): Set of themes for the Awesome window manager
- [picom](https://github.com/jonaburg/picom) (jonaburg fork): compositing manager with support for transparency, blur, rounded corners, shadows, animations, transitions, ...it just looks good.
- [Pick Colour Picker](https://github.com/stuartlangridge/ColourPicker): Screen-wide color picker with history of last picks
- [Circadian](https://github.com/mrmekon/circadian): For suspending system on idle
- [`lxqt-powermanagement`](https://github.com/lxqt/lxqt-powermanagement): For turning off monitors on idle
- [`unclutter-xfixes`](https://github.com/Airblader/unclutter-xfixes): Hide cursor on inactivity

# [Obsidian](https://github.com/obsidianmd/obsidian-releases)
- **Proprietary!** But source code can be inspected and seems to respect privacy (see [this](https://forum.obsidian.md/t/is-it-true-that-obsidian-is-already-open-source/46413))
- Markdown-based extensible note-taking app (also supports freehand drawing, pens, creating diagrams of all sorts, ...)
- Cross-Platform
> I thought hard about referencing any proprietary software, but Obsidian is among my favorite and most used software in general, so I felt it was justified.