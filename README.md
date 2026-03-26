# FembArcher
FembArcher is a Shell script to install FembArch Linux customizations on many Linux Distributions

## Warning for non-arch users.
This tool uses mainly the pacman package manager, you might need to change the part where it installs things like lollypop, shortwave, chrome and etc. (yay also doesnt exist in non-arch distro's so uh non-arch users are kinda cooked)

# Install pre-requirements
For FembArcher to work properly you need:
    flatpak
    gnome version 47 or above
    uwufetch
    wget

## Arch-based distro's
```bash
sudo pacman -S gnome-shell gnome-menus wget uwufetch flatpak
```
## Fedora-based distro's

```bash
sudo dnf install gnome-shell gnome-menus wget flatpak
```
## Ubuntu-based distro's
```bash
sudo apt install gnome-shell gnome-menus wget flatpak
```

## WARNING
In the official ubuntu and fedora repo's uwufetch does not exist.
Yet via git clone. Do in the terminal

```bash
git clone https://github.com/ThatOneCalculator/uwufetch.git
cd uwufetch
sudo make install
```
# Running the script
If you wanna learn what the code does you can read fembarch.sh's source code.
To run the script you first need to download fembarcher from this Git repo.
Do in your terminal
```bash
git clone https:/FembArchyyLinux/FembArcher.git
cd FembArcher
chmod +x fembarcher.sh
./fembarcher.sh
```
