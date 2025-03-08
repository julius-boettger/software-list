# My favorite _**Free and Open Source**_ Software
- Links go to...
	- Source code repositories (e.g. GitHub, GitLab, Codeberg)
	- Project websites (only when they contain more information than the repo OR the repo isn't public)
- I strongly recommend the following websites for finding and comparing the right software for anyone and their use case:
	- [AlternativeTo](https://alternativeto.net/): Find alternatives for specific products
	- [Slant](https://slant.co): Compare products of a broader category (like "Linux distributions")
- I keep my [GitHub Stars](https://github.com/julius-boettger?tab=stars) up-to-date with this list, so you can also scroll through there (at least for software that primarily uses GitHub)
- If you are familiar with [NixOS](https://nixos.org/) you can find my configuration in my [dotfiles](https://github.com/julius-boettger/dotfiles), which contains all the software I currently use

# Cross-Platform
> All of this is available at least on Linux and Windows, probably even more!
- [Zen Browser](https://github.com/zen-browser/desktop): Minimalistic internet browser
	- If you are looking for a more conventional browser, I recommend [Brave](https://github.com/brave/brave-browser)
	- [uBlock Origin](https://github.com/gorhill/uBlock): Content blocker (ads, trackers, pop-up, ...) add-on
- [VSCodium](https://github.com/VSCodium/vscodium): Open source builds of [VSCode](https://github.com/microsoft/vscode), a universal code and text editor
- [Proton Mail](https://github.com/ProtonMail) + [Proton Calendar](https://proton.me/calendar): End-to-end encrypted email and calendar
- [Signal](https://github.com/signalapp): Private messenger (also on [mobile](#mobile-android--ios)!)
- [Notesnook](https://github.com/streetwriters/notesnook): Simple note taking (also on [mobile](#mobile-android--ios)!)
- [OnlyOffice](https://github.com/ONLYOFFICE/DesktopEditors): Office suite containing tools for word processing, spreadsheets, presentations, ...
- [VirtualBox](https://www.virtualbox.org/): Virtualization software (for managing and running VM's)
	- VM's are really useful! Testing out operating systems, checking the safety of executables with no risk to your system, ...
- [GIMP](https://www.gimp.org/): Image editing and manipulation software
- [Inkscape](https://github.com/inkscape/inkscape): Create and edit vector graphics (SVG, PDF, ...)
- [Darktable](https://github.com/darktable-org/darktable): Photography workflow application and non-destructive raw developer 
- [Tenacity](https://codeberg.org/tenacityteam/tenacity): Multi-track audio editor (a.k.a. [Audacity](https://www.audacityteam.org/), but better)
- [Vesktop](https://github.com/Vencord/Vesktop): Open source 3rd party [Discord](https://discord.com/) client with better Wayland support on Linux
- [OpenRGB](https://gitlab.com/CalcProgrammer1/OpenRGB): RGB lighting control for various hardware
- [USBImager](https://gitlab.com/bztsrc/usbimager): Minimal GUI to create bootable USB sticks
- [`liquidctl`](https://github.com/liquidctl/liquidctl): CLI-tool and drivers for liquid coolers (also see [`liquidtux`](https://github.com/liquidctl/liquidtux) when on [Linux](#linux))
- [Overleaf](https://github.com/overleaf/overleaf): Web-based real-time collaborative LaTeX editor
- [GParted](https://gparted.org/): Partition editor 
	- Especially useful as bootable USB drive!
- [OBS Studio](https://github.com/obsproject/obs-studio): Live streaming and screen recording
- [Gitnuro](https://github.com/JetpackDuba/Gitnuro): Desktop GUI for `git`
	- If you run into issues with credentials see [this issue](https://github.com/JetpackDuba/Gitnuro/issues/16)
- [JetBrains Mono](https://github.com/JetBrains/JetBrainsMono): Monospaced font for programming. I especially like the "No Ligatures" (NL) version :)
- [rEFInd](http://www.rodsbooks.com/refind/): (U)EFI boot manager
	- [refind-dark](https://github.com/2KAbhishek/refind-dark): Theme for rEFInd
	- I strongly recommend this for dual boot systems, as you will need some kind of boot manager either way. This is probably the best-looking one + it supports using your mouse!
- [Barrier](https://github.com/debauchee/barrier): Switch between using your mouse and keyboard on different systems over the network instead of physically replugging them all the time
	- If you plan on using this with Linux: it only works on Xorg, not on Wayland!
- [Flameshot](https://github.com/flameshot-org/flameshot): Quickly take, edit, share and save screenshots
- [VeraCrypt](https://github.com/veracrypt/VeraCrypt): Encrypt (password-protect) disks/drives and partitions
	- I use this to password-protect my external backup-SSD
- [FreeFileSync](https://freefilesync.org/): Folder comparison and synchronization software that creates and manages backups
	- I use this to make occasional differential backups of my data on an external SSD
- [RethinkDNS](https://rethinkdns.com/): Transparent DNS provider with options to block e.g. trackers, ads, ...
- [Obsidian LiveSync](https://github.com/vrtmrz/obsidian-livesync): Self-hosted server to (live-)sync [Obsidian](https://obsidian.md/) notes between devices

# Mobile (Android / iOS)
- [Brave](https://github.com/brave/brave-browser): Internet browser
- [ente Authenticator](https://github.com/ente-io/auth): 2FA with end-to-end encrypted cloud backups and web access
- [Bura](https://github.com/davidtakac/bura): Weather app (Android only)

# Linux
> The following software is available for Linux-based (and possibly other [Unix-like](https://en.wikipedia.org/wiki/Unix-like)) operating systems
- [NixOS](https://github.com/NixOS/nixpkgs): Linux-based immutable and declaratively configured operating system
	- [nh](https://github.com/viperML/nh): **N**ix **H**elper for prettier/better `nix` commands
	- [nix-output-monitor](https://github.com/maralorn/nix-output-monitor): Prettier output for `nix` commands
- [keyd](https://github.com/rvaiya/keyd): Key remapping daemon
	- very useful for European folks who are used to `Ctrl+Alt` doing the same thing as `AltGr`, which is not the default on Linux, but can be configured to work like that with this program
- [SDDM](https://github.com/sddm/sddm): Display manager / login screen
	- [`sddm-sugar-candy`](https://github.com/Kangie/sddm-sugar-candy): Theme for SDDM
- [OneDrive Client for Linux](https://github.com/abraunegg/onedrive): CLI tool for accessing Microsoft OneDrive
	- [OneDriveGUI](https://github.com/bpozdena/OneDriveGUI): GUI for before-mentioned OneDrive CLI tool
- [Proton GE Custom](https://github.com/GloriousEggroll/proton-ge-custom): [Proton](https://github.com/ValveSoftware/Proton) fork with various changes for a better gaming experience (primarily with Steam games for Windows)
	- [ProtonUp-Qt](https://github.com/DavidoTek/ProtonUp-Qt): GUI for easy management of Proton and Wine installations
- [Pitivi](https://www.pitivi.org/): Video editor
- [Bottles](https://github.com/bottlesdevs/Bottles): [Wine](https://www.winehq.org/) wrapper to easily run Windows software (including games) on Linux
- [`liquidtux`](https://github.com/liquidctl/liquidtux): Kernel drivers for liquid coolers (e.g. makes [lm-sensors](https://github.com/lm-sensors/lm-sensors) recognize coolant temperature sensor, also see [`liquidctl`](https://github.com/liquidctl/liquidctl) under [Cross-Platform](#cross-platform))
- [Font Manager](https://github.com/FontManager/font-manager): Font management
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher): Integrate AppImages into your system seamlessly
- [Flatseal](https://github.com/tchx84/Flatseal): Manage Flatpak permissions per app
- [Psensor](https://github.com/chinf/psensor) (GUI) + [lm-sensors](https://github.com/lm-sensors/lm-sensors) (CLI): Sensor monitoring (e.g. cpu temperature)
- [Piper](https://github.com/libratbag/piper): Configure gaming mice
- [Playerctl](https://github.com/altdesktop/playerctl): CLI-tool for controlling media players (e.g. play/pause current media player)
- [Plymouth](https://www.freedesktop.org/wiki/Software/Plymouth/): Beautiful loading animations during boot
- [NoiseTorch](https://github.com/noisetorch/NoiseTorch): Real-time microphone background noise suppression
- System monitors
	- [Resources](https://github.com/nokyan/resources): Great system monitor overall
	- [Monitor](https://github.com/stsdc/monitor): System monitor with a great process view
	- [nvidia-system-monitor](https://github.com/congard/nvidia-system-monitor-qt): System monitor for NVIDIA GPU's

### Command line
> Tools to improve your command line experience
- [Alacritty](https://github.com/alacritty/alacritty): GPU-accelerated terminal emulator
- [Fish Shell](https://github.com/fish-shell/fish-shell): Modern shell with command suggestions and completions
- [Starship](https://github.com/starship/starship): Highly customizable shell prompt (for any shell)
- [zoxide](https://github.com/ajeetdsouza/zoxide): Provides the `z` command as a better `cd`, e.g. remembering your most frequent directories so you don't have to type them out fully
- [Numbat](https://github.com/sharkdp/numbat): Scientific calculator (and also a programming language!)
- [nomino](https://github.com/yaa110/nomino): Batch rename utility
- [LibreSpeed CLI](https://github.com/librespeed/speedtest-cli): Internet speed test
- [`bat`](https://github.com/sharkdp/bat): Better `cat` with syntax highlighting and paging
- [`lsd`](https://github.com/lsd-rs/lsd): Better `ls` with icons, colors and tree-views
- [`fzf`](https://github.com/junegunn/fzf): Fast fuzzy finder (useful to e.g. search for a file in a directory with thousands of files)
- [`tldr`](https://github.com/tldr-pages/tldr): Like `man`, but way shorter, more comprehensive and colored
- [`wsl-vpnkit`](https://github.com/sakai135/wsl-vpnkit): Fix company VPN issues on WSL
- Just for fun
	- [`cbonsai`](https://gitlab.com/jallbrit/cbonsai): ASCII art bonsai
	- [`asciiquarium`](https://github.com/nothub/asciiquarium): ASCII art aquarium/sea
	- [`fastfetch`](https://github.com/fastfetch-cli/fastfetch): Fast overview of system information

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
- [Eww](https://github.com/elkowar/eww) ("Elkowars Wacky Widgets"): Widget system to implement your own window manager agnostic widgets

#### [`wlroots`](https://gitlab.freedesktop.org/wlroots/wlroots)-based Wayland compositor only

- [Hyprland](https://github.com/hyprwm/Hyprland): Highly customizable tiling compositor
	- [Hyprsplit](https://github.com/shezdy/hyprsplit): Hyprland plugin for separate workspaces for each monitor ([Awesome](https://github.com/awesomeWM/awesome)-like)
	- [grimblast](https://github.com/hyprwm/contrib/tree/main/grimblast): Screenshot utility for Hyprland based on Sway's Grimshot
	- [`hyprland-workspaces`](https://github.com/FieldofClay/hyprland-workspaces): Useful for building Hyprland workspace widgets e.g. with [Eww](https://github.com/elkowar/eww)
- [Hyprpicker](https://github.com/hyprwm/hyprpicker): Simple color picker
- [SwayNotificationCenter](https://github.com/ErikReider/SwayNotificationCenter): Customizable Notification daemon and control center
- [SwayOSD](https://github.com/ErikReider/SwayOSD): On-screen display for changing volume, brightness, toggling capslock, ...
- [swaylock-effects](https://github.com/jirutka/swaylock-effects): Modern-looking lockscreen
- [swappy](https://github.com/jtheoof/swappy): Screenshot editing
- [`swww`](https://github.com/Horus645/swww): Wallpaper setter with change animations and support for animated wallpapers
- [`nwg-look`](https://github.com/nwg-piotr/nwg-look): Tool to set GTK themes, cursors, icons, ... (better on Wayland)
	
#### Xorg window manager only

- [Awesome](https://github.com/awesomeWM/awesome): Highly customizable tiling window manager
	- [Awesome Copycats](https://github.com/lcpz/awesome-copycats): Set of themes for the Awesome window manager
- [picom](https://github.com/jonaburg/picom) (jonaburg fork): compositing manager with support for transparency, blur, rounded corners, shadows, animations, transitions, ...it just looks good.
- [Pick Colour Picker](https://github.com/stuartlangridge/ColourPicker): Screen-wide color picker with history of last picks
- [`unclutter-xfixes`](https://github.com/Airblader/unclutter-xfixes): Hide cursor on inactivity
- [`lxappearance`](https://github.com/lxde/lxappearance): Tool to set GTK themes, cursors, icons, ... (better on Xorg)

-----
-----
-----

# Proprietary Software
> I thought hard about referencing any proprietary software at all, as I try my best to avoid it. But there is some proprietary software that still seems to respect privacy somewhat and that I couldn't replace with an open source alternative just yet, because I simply couldn't find one that fits my needs in the same way.
- [Obsidian](https://obsidian.md/): Markdown-based extensible note-taking app (also supports freehand drawing, pens, creating diagrams of all sorts, ...)
	- Cross-Platform
	- Source code can be inspected and seems to respect privacy (see [this](https://forum.obsidian.md/t/is-it-true-that-obsidian-is-already-open-source/46413))
- [Qwant](https://about.qwant.com/en/): Privacy-respecting and unbiased search engine (using [Bing](https://www.bing.com/)s index)
	- Mainly used as a [website](https://www.qwant.com/), but is also available through browser extensions and Android/iOS apps
	- Privacy is not top-notch, but still better than most reasonable alternatives