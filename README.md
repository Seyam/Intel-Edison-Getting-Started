# Intel-Edison-Getting-Started
# https://www.sitepoint.com/getting-started-with-programming-the-intel-edison/
# http://alextgalileo.altervista.org/edison-package-repo-configuration-instructions.html

configure_edison --setup
configure_edison --wifi
wpa_cli status
systemctl poweroff
shutdown -P now

ssh -X root@192.168.5.44

//to log data


echo 20.2
echo 20.2 > file_name.txt

//to view

vi file_name.txt
nano filename.ext


To find your board’s IP address, establish a serial communication session with your board and enter the command:

ifconfig


//Set Edison in AP Mode

On the board, hold the PWR button down for about 4 seconds. The LED at JS2 near the center of the board blinks to signal that your board is in AP Mode.



//Command after SSHing into the Edison IP address

ls
ls /sketch
mkdir
cd /
cd..
rm filename.ext
clear
curl  //to print current channel(URL)
