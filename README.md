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
- [Visual Studio Code](https://github.com/microsoft/vscode): Universal code and text editor
- [LibreOffice](https://www.libreoffice.org/): Office suite containing tools for word processing, spreadsheets, presentations, ...
- [VirtualBox](https://www.virtualbox.org/): Virtualization software (for managing and running VM's)
	- VM's are really useful! Testing out operating systems, checking the safety of executables with no risk to your system, ...
- [GIMP](https://www.gimp.org/): Image editing and manipulation software
- [Inkscape](https://github.com/inkscape/inkscape): Create and edit vector graphics (SVG, PDF, ...)
- [Darktable](https://github.com/darktable-org/darktable): Photography workflow application and non-destructive raw developer 
- [Overleaf](https://github.com/overleaf/overleaf): Web-based real-time collaborative LaTeX editor
- [GParted](https://gparted.org/): Partition editor 
	- Especially useful as bootable USB drive!
- [Alacritty](https://github.com/alacritty/alacritty): GPU-accelerated terminal emulator
- [OBS Studio](https://github.com/obsproject/obs-studio): Live streaming and screen recording
- [Gitnuro](https://github.com/JetpackDuba/Gitnuro): Desktop GUI for `git`
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

# Linux
> The following software is only available for Linux-based operating systems.
- [NixOS](https://github.com/NixOS/nixpkgs): Linux-based immutable operating system
- [GNOME](https://www.gnome.org/): Desktop Environment
	- [GNOME Tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks): GNOME configuration, also supports setting GTK themes, cursors, icons, ...
	- [Dconf Editor](https://apps.gnome.org/app/ca.desrt.dconf-editor/): Advanced GNOME configuration (can change settings for a lot of apps and extensions, even some otherwise hidden settings)
- [AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher): Integrate AppImages into your system seamlessly
- [OneDrive Client for Linux](https://github.com/abraunegg/onedrive): CLI tool for accessing Microsoft OneDrive
	- [OneDriveGUI](https://github.com/bpozdena/OneDriveGUI): GUI for before-mentioned OneDrive CLI tool
- [Input Remapper](https://github.com/sezanzeb/input-remapper): Change behaviour of input devices
	- very useful for European folks who are used to `Ctrl+Alt` doing the same thing as `AltGr`, which is not the default on Linux, but can be configured to work like that with this program
	- [Autokey](https://github.com/autokey/autokey) is a good alternative (but only runs on Xorg)
- [Fish Shell](https://github.com/fish-shell/fish-shell): Modern shell

### GNOME Extensions
> I don't actively use GNOME anymore, but these were my extensions when I did.
> Links go to https://extensions.gnome.org/
- [Clipboard Indicator](https://extensions.gnome.org/extension/779/clipboard-indicator/): Access clipboard history
- [Color Picker](https://extensions.gnome.org/extension/3396/color-picker/): Simple color picker
- [Lock Keys](https://extensions.gnome.org/extension/36/lock-keys/): Hints and notifications when toggling capslock and numlock
- [Media Controls](https://extensions.gnome.org/extension/4470/media-controls/): Controls and information of the currently playing media in the panel
- [Sound Input & Output Device Chooser](https://extensions.gnome.org/extension/906/sound-output-device-chooser/): Lets you select input and output devices below the volume slider
- [Tray Icons: Reloaded](https://extensions.gnome.org/extension/2890/tray-icons-reloaded/): Shows tray icons in panel
- [Workspace indicator](https://extensions.gnome.org/extension/21/workspace-indicator/): Shows current workspace in panel and lets you switch between them
- [Date Menu Formatter](https://extensions.gnome.org/extension/4655/date-menu-formatter/): Customize the date and time display in the panel
- [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/): Displays dash (from the overview) permanently
- [ArcMenu](https://extensions.gnome.org/extension/307/dash-to-dock/): Application menu (like Windows start menu)

##### Just for fun (purely visual stuff)
- [Burn my Windows](https://extensions.gnome.org/extension/4679/burn-my-windows/): Animations when closing windows
- [Desktop Cube](https://extensions.gnome.org/extension/4648/desktop-cube/): Look at and switch between your workspaces as a 3D cube
- [Compiz windows effect](https://extensions.gnome.org/extension/3210/compiz-windows-effect/): Make windows wiggle and wobble when moving them
- [Blur my Shell](https://extensions.gnome.org/extension/3193/blur-my-shell/): Add transparency and blur in a lot of places
- [User Themes](https://extensions.gnome.org/extension/19/user-themes/): Set GNOME shell theme in GNOME Tweaks

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

### Custom Xorg Desktop
> This is software I exclusively use when I am not using a desktop environment but a standalone Xorg window manager.
>
> If you are interested in this section you might also want to take a look at my [dotfiles](https://github.com/julius-boettger/dotfiles) ;)
- [Awesome](https://github.com/awesomeWM/awesome): Highly customizable tiling window manager
	- [Awesome Copycats](https://github.com/lcpz/awesome-copycats): Set of themes for the Awesome window manager
- [picom (jonaburg-fork)](https://github.com/jonaburg/picom): compositing manager with support for transparency, blur, rounded corners, shadows, animations, transitions, ...it just looks good.
- [SDDM](https://github.com/sddm/sddm): Display manager / login screen
	- [`sddm-sugar-candy`](https://github.com/Kangie/sddm-sugar-candy): Theme for SDDM
- [Circadian](https://github.com/mrmekon/circadian): For suspending system on idle
- [PCManFM](https://github.com/lxde/pcmanfm): File manager
- [Font Manager](https://github.com/FontManager/font-manager): Font management
- [Pick Colour Picker](https://github.com/stuartlangridge/ColourPicker): Screen-wide colour picker with history of last picks
- [Ulauncher](https://github.com/Ulauncher/Ulauncher): Application Launcher
	- [Emoji Extension](https://github.com/Ulauncher/ulauncher-emoji): Select and type emojis from Ulauncher
- [Stacer](https://github.com/oguzhaninan/Stacer): System optimization and monitoring (processes, services, cache, ...)
- `lxpolkit` (shipped with [`lxsession`](https://github.com/lxde/lxsession)): Simple PolicyKit authentication agent
- [`lxqt-powermanagement`](https://github.com/lxqt/lxqt-powermanagement): For turning off monitors on idle
- [`lxappearance`](https://github.com/lxde/lxappearance) (not needed when using [NixOS](https://github.com/NixOS/nixpkgs)): Tool to set GTK themes, cursors, icons, ...
- [`unclutter-xfixes`](https://github.com/Airblader/unclutter-xfixes): Hide cursor on inactivity

# Proprietary (but Privacy-Respecting!) + Cross-Platform Software
> I thought hard about referencing any proprietary software, but [Obsidian](https://obsidian.md/), being among my favorite software in general, made me do it.
- [Obsidian](https://github.com/obsidianmd/obsidian-releases): Markdown-based extensible note-taking app (also supports freehand drawing, pens, creating diagrams of all sorts, ...)
