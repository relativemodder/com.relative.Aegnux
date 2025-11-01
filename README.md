<img src="https://github.com/relativemodder/aegnux/raw/main/icons/aegnux.png" width="128" />

# Aegnux Flatpak source

Builds Aegnux Flatpak from [this source](https://github.com/relativemodder/aegnux).

[<img src="https://github.com/relativemodder/aegnux/raw/main/assets/download_flatpak.png">](https://github.com/relativemodder/com.relative.Aegnux/releases/latest)


## F.A.Q.

### Why does this flatpak require so many permissions?
I can't get it working with less permissions (e.g. Wine IPC is screwed, Wine's file picker can't work with XDG Desktop Portal, and many other problems)

### Why it's so heavy?
I bundle:

- VCR
- Wine
- Kitty terminal
- Cabextract
- Winetricks
- Aegnux itself

I'm very sorry, that's just how I made the software.


### Will this ever be published on Flathub?
Hell no.

### How do I install this?

You can download the release [here](https://github.com/relativemodder/com.relative.Aegnux/releases/latest).

Most distros have a software center built-in (e.g. GNOME software or KDE Discover) and Flatpak installed. You can learn more about this [here](https://flatpak.org/setup/).
If you have a **GUI frontend** for Flatpak, you can, in theory, simply open the `.flatpak` file from your **file manager.**

However, if it's **not an option**, here's the command for you:
```bash
flatpak install aegnux.flatpak
```