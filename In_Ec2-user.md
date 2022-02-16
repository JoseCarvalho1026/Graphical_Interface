# Graphical Interface in Ec2-user

### Update.

◻️ `sudo yum update -y` .

### Install Additional Software.

◻️ `sudo amazon-linux-extras install epel -y` .

### Install the Graphical Interface and Browser.

◻️ `yum groupinstall "MATE Desktop"` ;

◻️ `sudo yum install xrdp chromium` ;

◻️ `systemctl enable --now xrdp` .

### So that every users have Graphical Interface.

◻️ `sudo bash -c 'echo PREFERRED=/usr/bin/mate-session > /etc/sysconfig/desktop'` .

### So that only one user has Graphical Interface.
Exit the root:

◻️ `adduser user` ;

◻️ `passwd user` ;

◻️ `login user` ;

◻️ `echo "/usr/bin/mate-session" > ~/.Xclients && chmod +x ~/.Xclients` .
