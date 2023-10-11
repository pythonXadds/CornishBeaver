
# Virtualbox 


If one gets the kernal messagetype into the terminal

> sudo modprobe vboxdrv


Download the Virtualbox guest editions manually from their website, copy guest iso to home folder, then chmod +x to make the script executable. then simply
type into the terminal: 

> ./virtualbox.sh 

grant vbox user priveledges

> sudo usermod -a -G vboxusers $USER

if you get problems updating the guest editions automatically, update the linux headers and then retry. type into a terminal:

> sudo apt install linux-headers-amd64

Then try to reinstall the Guest additions. 
