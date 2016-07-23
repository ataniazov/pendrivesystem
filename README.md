#### To clone git over https:
git clone https://github.com/ataniazov/pendrivesystem.git
#### Or over SSH:
git clone git@github.com:ataniazov/pendrivesystem.git

#### Do not forget to edit /etc/fstab:
sudo vi /etc/fstab  
UUID=3769d8de-a2f2-4155-b35a-7df214638750 /               ext4    noatime,errors=remount-ro 0       1
##### On some systems add your hostname to /etc/hosts

#### Apps needed:
sudo apt-get install ratpoison stalonetray  
#### CLI tools
sudo apt-get install vim-nox ranger cmus openvpn
#### Fonts
sudo apt-get install ttf-mscorefonts-installer ttf-dejavu ttf-xfree86-nonfree
#### Archives
sudo apt-get install p7zip p7zip-full p7zip-rar unrar rar unzip zip
#### Firmware
sudo apt-get install linux-firmware linux-firmware-nonfree intel-microcode 
#### Boardcom BCM43142 802.11b/g/n (rev 01)
sudo apt-get install bcmwl-kernel-source
#### Codecs
chromium-codecs-ffmpeg-extra gstreamer0.10-fluendo-mp3 gstreamer0.10-plugins-bad gstreamer0.10-plugins-bad-multiverse gstreamer0.10-plugins-ugly gstreamer1.0-fluendo-mp3 gstreamer1.0-plugins-bad gstreamer1.0-plugins-bad-faad gstreamer1.0-plugins-bad-videoparsers gstreamer1.0-plugins-ugly libavcodec-extra libavcodec-extra-54 libcdaudio1 libfaac0 libfftw3-double3 libflite1 libfluidsynth1 libgme0 libgstreamer-plugins-bad0.10-0 libgstreamer-plugins-bad1.0-0 libgtkglext1 libmimic0 libmjpegutils-2.1-0 libmms0 libmpeg2encpp-2.1-0 libmpg123-0 libmplex2-2.1-0 libofa0 liboil0.3 libopenal-data libopenal1 libopencore-amrnb0 libopencore-amrwb0 libopencv-calib3d2.4 libopencv-contrib2.4 libopencv-core2.4 libopencv-features2d2.4 libopencv-flann2.4 libopencv-highgui2.4 libopencv-imgproc2.4 libopencv-legacy2.4 libopencv-ml2.4 libopencv-objdetect2.4 libopencv-video2.4 libsbc1 libsidplay1 libslv2-9 libsoundtouch0 libspandsp2 libsrtp0 libtbb2 libvo-aacenc0 libvo-amrwbenc0 libwildmidi-config libwildmidi1 libzbar0 oxideqt-codecs-extra ubuntu-restricted-addons ubuntu-restricted-extras unrar
#### Soundcloud plays without flash
sudo apt-get install gstreamer1.0-plugins-ugly gstreamer1.0-plugins-good gstreamer1.0-fluendo-mp3 gstreamer1.0-libav  

#### Packages needed to be deleted
sudo apt-get purge thunderbird pidgin gimp gmusicbrowser abiword gnumeric gnome-mines gnome-sudoku onboard system-config-printer-gnome system-config-printer-common simple-scan

##### Xubuntu 16.04.1
apport apport-gtk apport-symptoms aspell aspell-en avahi-autoipd avahi-daemon avahi-utils
blueman bluez bluez-cups bluez-obexd brltty brltty-x11
catfish cheese-common cups cups-browsed cups-bsd cups-client cups-common cups-core-drivers cups-daemon cups-filters cups-filters-core-drivers cups-ppdc cups-server-common
debconf-i18n
enchant espeak espeak-data:amd64 evolution-data-server-common
firefox firefox-locale-en fonts-guru fonts-guru-extra fonts-kacst fonts-kacst-one fonts-khmeros-core fonts-lao fonts-lklug-sinhala fonts-lohit-guru fonts-nanum fonts-sil-abyssinica fonts-sil-padauk fonts-takao-pgothic fonts-thai-tlwg fonts-tibetan-machine fonts-tlwg-garuda fonts-tlwg-garuda-ttf fonts-tlwg-kinnari fonts-tlwg-kinnari-ttf fonts-tlwg-laksaman fonts-tlwg-laksaman-ttf fonts-tlwg-loma fonts-tlwg-loma-ttf fonts-tlwg-mono fonts-tlwg-mono-ttf fonts-tlwg-norasi fonts-tlwg-norasi-ttf fonts-tlwg-purisa fonts-tlwg-purisa-ttf fonts-tlwg-sawasdee fonts-tlwg-sawasdee-ttf fonts-tlwg-typewriter fonts-tlwg-typewriter-ttf fonts-tlwg-typist fonts-tlwg-typist-ttf fonts-tlwg-typo fonts-tlwg-typo-ttf fonts-tlwg-umpush fonts-tlwg-umpush-ttf fonts-tlwg-waree fonts-tlwg-waree-ttf
genisoimage gigolo gnome-accessibility-themes gnome-keyring gnome-mines gnome-software gnome-software-common gnome-sudoku gnome-user-guide
hplip hplip-data hunspell-en-us hyphen-en-us
imagemagick imagemagick-6.q16 imagemagick-common ippusbxd
libabw-0.1-1v5:amd64 libavahi-core7:amd64 libavahi-glib1:amd64 libbdplus0:amd64 libbluray1:amd64 libbrlapi0.6:amd64 libburn4:amd64 libcamel-1.2-54:amd64 libcdio-cdda1:amd64 libcdio-paranoia1:amd64 libcdio-paranoia1:amd64 libcdio13:amd64 libcdparanoia0:amd64 libcheese8:amd64 libcupscgi1:amd64 libcupsmime1:amd64 libcupsppdc1:amd64 libebackend-1.2-10:amd64 libebook-1.2-16:amd64 libebook-contacts-1.2-2:amd64 libedata-book-1.2-25:amd64 libedataserver-1.2-21:amd64 libespeak1:amd64 libgnome-keyring-common libgnome-keyring0:amd64 libgoa-1.0-0b:amd64 libgoa-1.0-common libgphoto2-6:amd64 libgphoto2-l10n libgphoto2-port12:amd64 libgsm1:amd64 libgtkspell0 libgtkspell3-3-0:amd64 libgutenprint2 libhpmud0:amd64 liblouis-data liblouis9:amd64 liblouisutdml-bin liblouisutdml-data liblouisutdml6:amd64 libp11-kit-gnome-keyring:amd64 libreoffice-base-core libreoffice-calc libreoffice-common libreoffice-core libreoffice-gtk libreoffice-help-en-us libreoffice-math libreoffice-style-elementary libreoffice-style-galaxy libreoffice-writer libsane-hpaio:amd64 libwacom-bin libwacom-common libwacom2:amd64 libwbclient0:amd64
memtest86+
onboard onboard-data openoffice.org-hyphenation os-prober
parole pidgin pidgin-data pidgin-libnotify pidgin-otr popularity-contest printer-driver-brlaser printer-driver-c2esp printer-driver-foo2zjs printer-driver-foo2zjs-common printer-driver-gutenprint printer-driver-hpcups printer-driver-min12xxw printer-driver-pnm2ppa printer-driver-postscript-hp printer-driver-ptouch printer-driver-pxljr printer-driver-sag-gdi printer-driver-splix 
samba-libs:amd64 sane-utils simple-scan snapd system-config-printer-common system-config-printer-gnome system-config-printer-udev
thunderbird thunderbird-locale-en thunderbird-locale-en-us toshset
uno-libs3 update-notifier update-notifier-common ure
wamerican wbritish whoopsie
xbrlapi xfburn xfce4-cpugraph-plugin xfce4-dict xfce4-mailwatch-plugin xfce4-netload-plugin xfce4-notes xfce4-notes-plugin xfce4-quicklauncher-plugin xfce4-systemload-plugin xfce4-taskmanager xfce4-verve-plugin xfce4-weather-plugin xubuntu-docs xul-ext-ubufox
yelp yelp-xsl



#### Cleaning up
echo "Cleaning Up" &&  
sudo apt-get -f install &&  
sudo apt-get autoremove &&  
sudo apt-get -y autoclean &&  
sudo apt-get -y clean  
