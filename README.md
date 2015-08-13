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

#### Cleaning up
echo "Cleaning Up" &&  
sudo apt-get -f install &&  
sudo apt-get autoremove &&  
sudo apt-get -y autoclean &&  
sudo apt-get -y clean  
