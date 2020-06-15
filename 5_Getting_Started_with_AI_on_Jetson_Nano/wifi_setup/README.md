# Setup Edimax 2-in-1 WiFi and Bluetooth 4.0 Adapter
* https://learn.sparkfun.com/tutorials/adding-wifi-to-the-nvidia-jetson/all
* sudo apt-get update
* sudo reboot now
* sudo apt install dkms
* git clone https://github.com/lwfinger/rtl8723bu.git
* cd rtl8723bu
* source dkms.conf
* sudo mkdir /usr/src/$PACKAGE_NAME-$PACKAGE_VERSION
* sudo cp -r core hal include os_dep platform dkms.conf Makefile rtl8723b_fw.bin /usr/src/$PACKAGE_NAME-$PACKAGE_VERSION
* sudo dkms add $PACKAGE_NAME/$PACKAGE_VERSION
* sudo dkms autoinstall $PACKAGE_NAME/$PACKAGE_VERSION
* sudo reboot now
