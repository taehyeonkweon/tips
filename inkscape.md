### Install Inkscape (Ubuntu 20.04)
```bash
# Add official Inkscape PPA and install
sudo add-apt-repository ppa:inkscape.dev/stable -y
sudo apt update
sudo apt install inkscape -y
```
To remove:
```bash
sudo apt remove --purge inkscape -y
sudo add-apt-repository --remove ppa:inkscape.dev/stable -y
sudo apt autoremove -y
```