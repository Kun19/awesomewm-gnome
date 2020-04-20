# awesomewm-gnome

Run a GNOME 3.x session but use awesome for window management

## Dependencies

The scripts in this repository create a new session in GDM called "awesome GNOME". The requirements are gnome-flashback and awesome 4.3. Earlier versions of awesome don't integrate well with GTK and are sort of buggy.

Because gnome-flashback isn't always packaged you might need grab a copy of it from somewhere. Below you can find packages and repositories that worked for me.

### Ubuntu 18.04

```sh
sudo apt-get install gnome gnome-flashback gnome-icon-theme gnome-themes-extra make
```

## Setup

Run the following with if you have sudo installed

```sh
sudo make install
```

## How to uninstall

```sh
sudo make uninstall
```
