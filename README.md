
<p align="center">My Channel</br><b>
| <a href="https://discord.gg/GCehyym">Discord</a> | <a href="https://youtube.com/channel/UC3sLb7eZCu72iv3G1yUhUHQ">YouTube</a> |</b></p>

---
## Kali-Linux on Termux Android

---
Warning :</br>
Especially for Android 12 there are several bugs, and for more details, please read in Official [Termux](https://github.com/termux/termux-app).

---
### Materials</br>
1. [Termux](https://github.com/termux/termux-app/releases)
2. [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)
3. [Link Download](http://kali.download/nethunter-images/current/rootfs/?C=S&O=D) (install from sdcard)

Note :</br>
Before downloading, run this command to termux :

> uname -m

* kalifs-armhf-nano (armeabi-v7a/v6a)
* kalifs-arm64-nano (Arm64-v8a/AArch64)

---
Install Kali-linux via Rootless [Click here](https://github.com/wahasa/nethunter)

---
### Installation (Kali-Only)
Copy and paste this command to Termux :

> pkg update && pkg upgrade

> pkg install root-repo x11-repo

---
1. Install kali-Nethunter from termux</br>
on Termux, run this command :

```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/nethunter/main/install-nethunter.sh && chmod +x install-nethunter.sh && ./install-nethunter.sh
```

</br>
Note :</br>
The file size is 1.7 Gb, the extract time is 10-15 minutes and when it is finished it will be taken to the Kali-Nethunter menu.

---
2. [Install kali-Nethunter from Sdcard](https://youtu.be/ko5m-ghehKw)</br>
on Termux, run this command :

> termux-setup-storage

> cd /sdcard/Download

> cp (Nama file) ~/

> cd 
```
pkg install wget -y && wget https://raw.githubusercontent.com/wahasa/nethunter/main/install-nethunter.sh && chmod +x install-nethunter.sh && ./install-nethunter.sh
```

</br>
Note :</br>
If there are options (Y/N), select (N) all. the extract time is 10-15 minutes and when it is finished it will be taken to the Kali-Nethunter menu.

---
3. Start Kali-Nethunter</br>

> nethunter

---
4. Stop Kali-Nethunter

> exit

</br>

Note :</br>
[sudo] password for kali:kali
</br>
