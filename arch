clear
echo "Schritt 1/54"
echo "Lets fets, los gehts Dienste werden Installiert"
pacman -S --noconfirm acpid avahi cups cronie
clear
echo "Schritt 2/54"
echo "Dienste werden gestartet"
systemctl enable acpid avahi-daemon org.cups.cupsd.service cronie
clear
echo "Schritt 3/54"
echo "Zusatzbibliotheken für cups werden Installiert"
pacman -S --noconfirm lib32-glibc lib32-gcc-libs
clear
echo "Schritt 4/54"
echo "Automatische Zeiteinstellung wird gestartet"
systemctl enable systemd-timesyncd.service
clear
echo "Schritt 5/54"
echo "X-Server wird Installiert"
pacman -S --noconfirm xorg-server xorg-xinit xorg-xrandr
clear
echo "Schritt 6/54"
echo "Garfiktreiber wird Installiert"
pacman -S --noconfirm xf86-video-amdgpu
clear
echo "Schritt 7/54"
echo "Mesa wird Installiert"
pacman -S --noconfirm mesa lib32-mesa
clear
echo "Schritt 8/54"
echo "Vulkan wird Installiert"
pacman -S --noconfirm vulkan-radeon lib32-vulkan-radeon
clear
echo "Schritt 9/54"
echo "Video Beschleunigung wird Installiert"
pacman -S --noconfirm libva-mesa-driver lib32-libva-mesa-driver
clear
## echo "Video Beschleunigung wird Installiert Teil 2"
## pacman -S --noconfirm libva-vdpau-driver lib32-libva-vdpau-driver
## clear
echo "Schritt 10/54"
echo "Video Beschleunigung wird Installiert Teil 2"
pacman -S --noconfirm mesa-vdpau lib32-mesa-vdpau
clear
echo "Schritt 11/54"
echo "XFCE wird Installiert"
pacman -S --noconfirm xfce4 xfce4-goodies lightdm lightdm-gtk-greeter lightdm-gtk-greeter-settings networkmanager network-manager-applet nm-connection-editor alsa-tools alsa-utils pulseaudio-alsa pavucontrol
clear
echo "Schritt 12/54"
echo "login und Netzwerkmanager werden gestartet"
systemctl enable lightdm.service NetworkManager
clear
echo "Schritt 13/54"
echo "Browser und E-Mail Programm wreden Installiert"
pacman -S --noconfirm chromium thunderbird thunderbird-i18n-de
clear
echo "Schritt 14/54"
echo "Libreoffice wird Installiert"
pacman -S --noconfirm libreoffice-fresh libreoffice-fresh-de hunspell-de
clear
echo "Schritt 15/54"
echo "Fonts werden Installiert"
pacman -S --noconfirm ttf-ubuntu-font-family ttf-liberation ttf-droid gnu-free-fonts noto-fonts ttf-anonymous-pro
clear
echo "Schritt 16/54"
echo "Icon Temes werden Installiert"
pacman -S --noconfirm human-icon-theme elementary-icon-theme arc-icon-theme faenza-icon-theme hicolor-icon-theme
clear
echo "Schritt 17/54"
echo "GTK Themes werden Installiert"
pacman -S --noconfirm deepin-gtk-theme arc-gtk-theme
clear
echo "Schritt 18/54"
echo "gtk-engine-murrine wird Installiert"
pacman -S --noconfirm gtk-engine-murrine
clear
echo "Schritt 19/54"
echo "AUR Tools werden Installiert"
pacman -S --noconfirm git svn rsync wget linux-headers
clear
echo "Schritt 20/54"
echo "Archiv unterstützung für Thunar wird Installiert"
pacman -S --noconfirm file-roller unrar p7zip
clear
echo "Schritt 21/54"
echo "Dateisystem Helper werden Installiert"
pacman -S --noconfirm gvfs
clear
echo "Schritt 22/54"
echo "numlockx wird Installiert"
pacman -S --noconfirm numlockx
clear
echo "Schritt 23/54"
echo "Dateisystem Helper (Teil 2) werden Installiert"
pacman -S --noconfirm ntfs-3g exfat-utils
clear
echo "Schritt 24/54"
echo "Blutooth Tools werden Installiert und gestartet"
pacman -S --noconfirm bluez bluez-tools blueman
systemctl enable bluetooth.service
clear
echo "Schritt 25/54"
echo "Samba Unterstützung wird Installiert"
pacman -S --noconfirm gvfs-smb
clear
echo "Schritt 26/54"
echo "Netzwerk Manager wird Konfiguriert"
systemctl enable NetworkManager-wait-online
clear
echo "Schritt 27/54"
echo "Firewall wird Installiert und gestartet"
pacman -S --noconfirm gufw
systemctl enable ufw.service
clear
echo "Schritt 28/54"
echo "PDF Drucker wird Installiert"
pacman -S --noconfirm system-config-printer cups-pdf
clear
echo "Schritt 29/54"
echo "nmap wird Installiert"
pacman -S --noconfirm nmap
clear
echo "Schritt 30/54"
echo "Evince wird Installiert"
pacman -S --noconfirm evince
clear
echo "Schritt 31/54"
echo "Audacious wird Installiert"
pacman -S --noconfirm audacious
clear
echo "Schritt 32/54"
echo "Double Commander wird Installiert"
pacman -S --noconfirm doublecmd-gtk2 zip unzip libunrar
clear
echo "Schritt 33/54"
echo "Midnight Commander wird Installiert"
pacman -S --noconfirm mc
clear
echo "Schritt 34/54"
echo "Simple-Scan wird Installiert"
pacman -S --noconfirm simple-scan
clear
echo "Schritt 35/54"
echo "Wake on LAN wird Installiert"
pacman -S --noconfirm wol
clear
echo "Schritt 36/54"
echo "Taschenrechner wird Installiert"
pacman -S --noconfirm mate-calc
clear
echo "Schritt 37/54"
echo "Icon Preview wird Installiert"
pacman -S --noconfirm libgsf tumbler poppler-glib ffmpegthumbnailer
clear
echo "Schritt 38/54"
echo "Libmediainfo wird Installiert"
pacman -S --noconfirm libmediainfo
clear
echo "Schritt 39/54"
echo "openssh wird Installiert"
pacman -S --noconfirm openssh
clear
echo "Schritt 40/54"
echo "Cairo Dock wird Installiert"
pacman -S --noconfirm cairo-dock cairo-dock-plug-ins
clear
echo "Schritt 41/54"
echo "Grafikprogramme werden Installiert"
pacman -S --noconfirm pinta krita gimp gimp-help-de
clear
echo "Schritt 42/54"
echo "Gnome Disk Utility wird Installiert"
pacman -S --noconfirm gnome-disk-utility
clear
echo "Schritt 43/54"
echo "Deutsche Hilfe (Man-Pages) wird Installiert"
pacman -S --noconfirm man-pages-de
clear
echo "Schritt 44/54"
echo "Audio und Video Tools werden Installiert"
pacman -S --noconfirm lmms kdenlive cdrtools dvdauthor xine-ui vlc
pacman -S --noconfirm handbrake asunder lame vorbis-tools
clear
echo "Schritt 45/54"
echo "Windows Runtimes werden Installiert"
pacman -S --noconfirm wine wine-mono wine_gecko
clear
echo "Schritt 46/54"
echo "Conky wird Installiert"
pacman -S --noconfirm conky
clear
echo "Schritt 47/54"
echo "Steam wird Installiert"
pacman -S --noconfirm steam steam-native-runtime
clear
## echo "Code wird Installiert"
## pacman -S --noconfirm code
## clear
echo "Schritt 48/54"
echo "Samba wird Installiert und Konfiguriert"
pacman -S --noconfirm samba
cp /home/vespi/WD-1TB/Backup/smb.conf /etc/samba/
systemctl enable smb.service nmb.service
clear
echo "Schritt 49/54"
echo "Remmina wird Installiert"
pacman -S --noconfirm remmina
clear
echo "Schritt 50/54"
echo "Java wird Installiert"
pacman -S --noconfirm jre-openjdk jre-openjdk-headless
clear
echo "Schritt 51/54"
echo "Youtube unterstützung für MPV-Git wird Installiert"
pacman -S --noconfirm youtube-dl rtmpdump
clear
echo "Schritt 52/54"
echo "Smartmon Tools und HDParm werden Installiert"
pacman -S --noconfirm smartmontools hdparm
clear
echo "Schritt 53/54"
echo "Spiele werden Installiert"
pacman -S --noconfirm pingus kpatience
clear
echo "Schritt 54/54"
echo "Screenfetch wird Installiert"
pacman -S --noconfirm screenfetch
clear
echo "Installation beendet."
## mkdir /home/vespi/.dl-aur
## cd /home/vespi/.dl-aur/

## git clone https://aur.archlinux.org/brother-mfc-l2700dn.git

## git clone https://aur.archlinux.org/brscan4.git

## git clone https://aur.archlinux.org/xerox-c525a.git

## git clone https://aur.archlinux.org/xnviewmp.git

## git clone https://aur.archlinux.org/yay.git

## git clone https://aur.archlinux.org/sound-theme-smooth.git

## git clone https://aur.archlinux.org/mpv-git.git

## git clone https://aur.archlinux.org/brave-bin.git

## cd mpv-git/
## makepkg -rsi
## cd ../brother-mfc-l2700dn/
## makepkg -rsi
## cd ../brscan4/
## makepkg -rsi
## cd ../xnviewmp/
## makepkg -rsi
## brsaneconfig4 -a name="Brother" model="MFC-L2700DN" ip=192.168.1.50

cp /home/vespi/WD-1TB/Backup/xorg.conf.d/* /etc/X11/xorg.conf.d/
cp /home/vespi/WD-1TB/Backup/loader/loader.conf /boot/loader/
cp /home/vespi/WD-1TB/Backup/loader/entries/* /boot/loader/entries/
## bootctl install

