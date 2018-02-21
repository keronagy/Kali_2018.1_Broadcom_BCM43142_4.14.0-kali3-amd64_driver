# broadcom_BCM43142_4.14.0-kali3-amd64_driver
how to make the wifi (BCM43142) works in kali 4.14.0 
you can download the driver from the repository or from here

https://packages.debian.org/sid/all/broadcom-sta-dkms/download

# then execute this commands: 

apt update && apt dist-upgrade
<br />
apt install gdebi linux-headers-4.14.0-kali3-amd64

# after downloading .deb file cd to the downloded file then execute

gdebi downloaded_file.deb
<br />
modprobe wl

# useful commands: 

wifi card
<br />
lspci | grep BCM
<br />
kernel version
<br />
uname -r



