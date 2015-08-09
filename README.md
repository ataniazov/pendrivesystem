### To clone git over https:
git clone https://github.com/ataniazov/pendrivesystem.git
### Or over SSH:
git clone git@github.com:ataniazov/pendrivesystem.git

### Do not forget to edit /etc/fstab:
sudo vi /etc/fstab  
UUID=3769d8de-a2f2-4155-b35a-7df214638750 /               ext4    noatime,errors=remount-ro 0       1
#### On some systems add your hostname to /etc/hosts

### Apps needed:
sudo apt-get install ratpoison stalonetray ttf-mscorefonts-installer vim-nox ranger cmus  
