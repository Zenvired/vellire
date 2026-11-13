# Vellire

Vellire is a desktop typography studio. Preview Unicode styles and use them in compatible Linux apps through IBus.

[Download the latest release](https://github.com/Zenvired/vellire-releases/releases/latest)

## Install on Linux

Download the x86-64 Flatpak bundle and open a terminal in your Downloads folder:

```sh
flatpak install --user ./Vellire_0.1.5_x86_64.flatpak
flatpak run io.vellire.desktop
```

The Flatpak needs a running IBus session for system-wide typing. For Debian, Ubuntu or Zorin, download the Debian package and run:

```sh
sudo apt install ./vellire_0.1.5_amd64.deb
```

The Debian package can register Alt+S and Alt+T in GNOME. The Flatpak handles those shortcuts inside the app.
