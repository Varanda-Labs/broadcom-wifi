# Debian repackong for broadcom-sta-dkms
This is just a patch for broadcom-sta-dkms_6.30.223.271-17 to work with kernel 5.18<br>
Thanks for [this](https://github.com/archlinux/svntogit-community/blob/packages/broadcom-wl-dkms/trunk/013-linux518.patch) patch.<br>

## Directories
- `Installer_original` as the name suggests it is the original Debian package (Debian 11 - Bullseyes)
-  `mv_package` the pathed package
files \*.c are the ones modified.<br>
## To build package (if needed)
```
cd mv_package
./mk.sh
```
