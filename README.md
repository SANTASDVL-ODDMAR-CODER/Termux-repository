# Termux-repository

# 🥵🔥TERMUX-TUTORIAL☠️

* Here the is the all code, for setup the termux 🔥
* First download the termux in a genuine process, like F-droid or termux-offical website
* Here I gave you links ==> 
* F-droid link **https://f-droid.org/packages/com.termux/**
* Termux-offical website **https://github.com/termux/termux-app/releases** ==> v0.119.0-beta.1 pre-release

# 📚 Commend-for-termux

# 🌸 After open the termux past or write this commend to setup the termux
* **termux-setup-storage** // This commend help to link the phone storage with termux
* **termux-change-repo** // This commend help to change the mirror on termux

# 🏁 Basic packages to download first 
* you can all so run the commend with --> **apt**
* like # apt update -y
* like # apt upgrade -y 
```
pkg update
pkg upgrade
pkg install x11-repo
pkg install termux-x11-nightly
pkg install tur-repo
pkg install pulseaudio
pkg install proot-distro
pkg install wget
pkg install git
```
* Downlaod the basic packages with --> **pkg**

# 🐍 Intsalling the python language
🌸 Inctalling the python language for hight frame rate mobels

```
pkg update -y
pkg upgrade -y 
pkg install python-pip
pkg install python-pygame
python --version
```
👀 --> pkg install python-pygame <-- For installing the pygame in python 

# 🔥 Installing the **Nodejs** in termux 
* After the install the **python** you can all so install the **nodejs**
* This give you freedom to programe in javascript 
```
apt-get update -y
apt-get upgrade -y
apt-get install nodejs
node --version 
```
👀 --> nodejs --version <-- For the seeing the version of nodejs

# 📚 Download the Termux-x11 for gui version of termux
 
## 🥵 termux-Native Desktop
* **Termux-Native desktop** refers the visual linux envirement, that used in mobile
* **proot-distro** refers or help to download the linux envirement like 👉👉👉👉👉👉👉👉

  * 📚 Alpine Linux < alpine >
  * 🔥 Arch Linux < archlinux >
  * 🥵 Artix Linux < artix >
  * 💯 Chimera Linux < chimera >
  * 🤝 Debian (bookworm) < debian >
  * 🍫 Debian (bullseye) < debian-oldstable >
  * 💀 deepin < deepin >
  * ☠️ Fedora < fedora >
  * 😘 Manjaro < manjaro >
  * 🤤 OpenKylin < openkylin >
  * 😋 OpenSUSE < opensuse >
  * 🥴 Pardus < pardus >
  * 🐍 Ubuntu (24.04) < ubuntu >
  * 🌝 Ubuntu (22.04) < ubuntu-oldlts >
  * 🤖 Void Linux < void >

# 🤖 Proot-distro download in termux
## 🌸 First download the **proot-distro**

* 📚 First download the **proot-distro** and select the distro that what you need to download
* 👀 After the downloading the **distro**, Open **distro**, use this commend 👉👉👉👉👉 **proot-distro login <distro_name>**
```
pkg install proot-distro
proot-distro install <distro>
proot-distro login <distro>
```
# 🧏 Termux backup plane
## 🗣️ termux backup plane commend work by creating a **termux.backup.tar.gz** file for backup 

* 👉 First download the tar package with **pkg install tar** commend........ 👈
* 👉 Then use the chocolate 🍫 commend for creating the backup file............. 👈
* 👉 If you need to extract the **backfile** use the third mean the 👀 commend............ 👈

⚠️ Creating a backup file it take some time by according your termux file size. As same by extracting the **backupfile** it take some time according your **backupfile** size 🔥

* 👉 pkg install tar 
* 🍫 cd $PREFIX/../../;tar -pczvf /sdcard/termux.backup.tar.gz files/;cd;
* 👀 cd $PREFIX/../../;tar -xzvf /sdcard/termux.backup.tar.gz;cd;

# 🥶 proot-distro debian installation

* 🗣️ I show you the full prosess of how to install **Proot-distro debian** package on termux
* 👌 That give you the full **freedom** to use a linux envirment in your mobile
* 👉👈 And all so you can use the 👉 **firefox** and **chromium** 👉 **VLC Media** 👉 and all so **Discord Server**
* 🤤 Here is the prosess 🤳

1. Download the first packages
```
proot-distro install debian
proot-distro login debian
apt update -y
apt upgrade -y
apt install sudo -y
apt install nano -y
apt install git -y
apt install wget -y
apt install xfce4 -y
apt update -y
apt upgrade -y
```
2. Add the user

```
adduser droidmaster 
```
* ☝️ First commend **proot-distro install debian** install the proot-debian
* ✌️ By using this commend **proot-distro login debian** you can login the debian
* 🥉Now running the debian in a virtualy, We use the **Termux-x11 app** for this 👉 👉 👉 👉 The download link [here] (**https://github.com/termux/termux-x11/releases/tag/nightly**)
* 📚 Here a commend name **adduser**, It added the user in debian <I use the **droidmster** name for this time>
* ✨ After use the **adduser** commend it show to give a **password** 👉 It your choise to give a password but I suggest to give number's like **12345678** for better remembering

# 🔥 Setuping the sudo user on debian

* 🗣️ After install all those thinks, now we setup **sudo user** or the **root user**
* 🗣️ Here all commend 🤝

3. Give the user sudo privileges
```
nano /etc/sudoers

# Add the user in /etc/sudoers file 
droidmaster ALL=(ALL:ALL) ALL
```
👉 Here is the photo, to how to add 👈 | 
🍫 Image link --> https://photos.app.goo.gl/8hhwSbD73DqqRoV38

4. Check you can execute sudo commands (it should return `root`)
```
su - droidmaster
sudo whoami
```

* 📚 By using the **su - droidmaster** it transfer as droidmaster user
* 🌟 And using the **sudo whoami** commend  enable the root user

5. Running script for Termux-x11
```
wget https://raw.githubusercontent.com/LinuxDroidMaster/Termux-Desktops/main/scripts/proot_debian/startxfce4_debian.sh
chmod +x startxfce4_debian.sh
./startxfce4_debian.sh 
```

* 😲 Pasting this commend it automaticly open the Termux-x11 with virtual distro 
* 🤗 Here is the finished, I hope you like it

# 😎 Pre-build termux Setup 
* 🤜 In this pre-build setup tutorial I show you, how to setup as quickly as possible and all so a deautiful customizetion
* 🗣️ Here is the commend 👉 👉 👉 👉 👉 👉
```
apt update && apt upgrade -y
apt install xfce4 -y
cd ~

# This commend setup the virtual enverment
wget https://raw.githubusercontent.com/LinuxDroidMaster/Termux-Desktops/main/scripts/termux_native/startxfce4_termux.sh

chmod +x startxfce4_termux.sh

./startxfce4_termux.sh
```
* **wget https://raw.githubusercontent.com/LinuxDroidMaster/Termux-Desktops/refs/heads/main/scripts/termux_native/startxfce4_termux(old-android).sh** this commend open the linxu virtual enverment in **termux-x11** app
* After open the linux virsual enverment, if you see all is good than fully close it **termux** and **termux-x11** and past another commend to enjoying full setup experiment

```
curl -sLf https://raw.githubusercontent.com/Yisus7u7/termux-desktop-xfce/main/boostrap.sh | bash
```

* After pasting the commend press enter and wait till the download end, after fully downloading update and upgrade the pachages and open the linux virtual envirment with this commend **./startxfce4_termux.sh**
* Then you this 👉 👉 👉 👉
* ![1315629](https://github.com/user-attachments/assets/6b4e4d1b-fade-443c-90a3-7ea6c1f52a7a)
* 🗣️ I hope this tutorial you like it 🥰





