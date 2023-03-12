Go away.


none of this is useful


no androids here


fresh out of apps


,,!,,(o_0),,!,,

I dont like the defalt screen size or one has root and one does not. In process of mixing the two and fixing screen

Under construction is the following:

Setting up kali on android with root and vnc.
Start:

https://f-droid.org/repo/com.termux_118.apk

https://store.nethunter.com/repo/com.termux.api_51.apk

Termux-setup-storage

pkg install wget openssl-tool proot -y && hash -r && wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/Installer/Kali/kali.sh && bash kali.sh

pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Kali/kali-xfce.sh -O kali-xfce.sh && chmod +x kali-xfce.sh && bash kali-xfce.sh 

wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/SSH/Apt/ssh-apt.sh --no-check-certificate && bash ssh-apt.sh

wget https://raw.githubusercontent.com/EXALAB/AnLinux-Resources/master/Scripts/DesktopEnvironment/Apt/Xfce4/de-apt-xfce4.sh --no-check-certificate && bash de-apt-xfce4.sh

