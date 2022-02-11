# Graphical environment in Ubuntu

### Update and Upgrade

◻️ `sudo apt update -y && sudo apt upgrade -y`

### Install Additional Software

◻️ `sudo apt install -y xfce4 xfce4-goodies`

### Install the Graphical Environment and Browser

◻️ `sudo apt install -y xrdp chromium-browser`

### Add Users (Optional, because there is already a user. The password can be changed.)

◻️ `sudo adduser xrdp ssl-cert`

◻️ `sudo adduser user`

◻️ `login user`

◻️ `echo xfce4-session > ~/.xsession` (In case you are in "super user", you should type `exit`)

### Change the password that already exists.

◻️ `sudo passwd ubuntu`
