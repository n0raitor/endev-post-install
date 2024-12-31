# endev-post-install

```bash
# Install Packages with Pacman and yay

Chaotic Repo: https://aur.chaotic.cx/docs
Pamac: sudo pacman -S pamac

sudo pacman -S xreader flatpak code obsidian nvidia-inst qbittorrent neofetch ipython bleachbit tree ghex most python python-virtualenv python-pip filelight baobab 

yay -S brave-bin
yay -S proton-pass-bin
yay -S proton-mail
yay -S jdownloader2
yay -S install guitar-pro 


sudo pacman -S obs-studio signal-desktop handbrake brasero gimp gimp-help-de darktable calibre lutris steam virtualbox virtualbox-ext-oracle burpsuite nmap zenmap wireshark-qt hashcat john 
sudo pacman -S pycharm-community-edition tor-browser kdenlive openshot balena-etcher audacity krita github-desktop ghc cabal-install haskell-language-server gparted libreoffice-still libreoffice-still-de aspell aspell-de aspell-en hunspell hunspell-en_us hunspell-de mythes  mythes mythes-en mythes-de languagetool enchant libmythes speech-dispatcher


# Hacking and Forensic tools
curl -O https://blackarch.org/strap.sh
chmod +x strap.sh 
sudo ./strap.sh 
sudo pacman -Syyyu
sudo pacman -S edb edb-debug ida-free maltego

# Post Config
flatpak remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
nvidia-inst
pip3 install pylint

sudo pacman -S zsh zsh-syntax-highlighting zsh-autosuggestions zsh-theme-powerlevel10k

ssh-keygen -t rsa -b 4096 -o -a 100
sudo systemctl start fstrim.timer

Flatpak:
flatpak install flathub com.usebottles.bottles
flatpak install flathub com.github.tchx84.Flatseal
flatpak install marktext

Fonts:
sudo pacman -S ttf-anonymous-pro ttf-droid ttf-ubuntu-font-family ttf-roboto ttf-roboto-mono ttf-font-awesome ttf-bitstream-vera ttf-dejavu ttf-liberation adobe-source-sans-pro-fonts ttf-fira-code

yay -S ttf-hackgen ttf-gentium-basic ttf-ms-fonts
yay -S ttf-nerd-fonts-hack-complete-git 
yay -S ttf-mac-fonts

yay -S archlinux-artwork

Oh My Zsh:
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
