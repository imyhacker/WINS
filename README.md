# Wins - WinBox Installer
A helper script to install WinBox in GNU/Linux

## Tutorial Youtube / Artikel
1. `Youtube : https://www.youtube.com/channel/UCkov6NP1AjChi7XPJdiNCkA`
2. `Artikel : https://www.se-mangga.com`

## Fitur :
1. Dapat di install di berbagai maca distribusi linux seperti : Debian, Ubuntu, Elementary OS, Zorin OS, Linux Mint, Kali Linux, Fedora, RHEL, CentOS, IGOS Nusantara, Archlinux
2. Install wine
3. Upgrade wine (sesuai dengan repo dari OS Linux) ke versi terbaru (hanya untuk Fedora, RHEL, CentOS, IGN)
4. Terdaftar pada aplikasi menu
5. Winbox versi terbaru https://mikrotik.com/download

## Install :
Copy and paste perintah di bawah ke terminal :

1. `git clone https://github.com/imyhacker/wins.git`
2. `cd wins`
3. `sudo ./setup install` **OR** `sudo bash setup install`

## Firewall setting:
Pada Fedora/CentOS/Redhat, jika mendapatkan error, buka port pada terminal ketikan perintah :

`firewall-cmd --permanent --add-port=5678/udp`

`firewall-cmd --reload`

## Icon :
Jika menggunakan dekstop GTK, dan icon tidak terload dengan ukuran yang salah ketikan perintah :

`gtk-update-icon-cache -f -t /usr/share/icons/hicolor`

## Uninstall :
Jika ingin uninstall ketikan perintah :

`sudo ./setup uninstall` **OR** `sudo ./setup uninstall`
