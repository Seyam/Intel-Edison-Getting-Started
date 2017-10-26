# Intel-Edison-Getting-Started

configure_edison --setup
configure_edison --wifi
wpa_cli status

ssh -X root@192.168.5.44

//to log data


echo 20.2
echo 20.2 > file_name.txt

//to view

vi file_name.txt



To find your board’s IP address, establish a serial communication session with your board and enter the command:

ifconfig


//Set Edison in AP Mode

On the board, hold the PWR button down for about 4 seconds. The LED at JS2 near the center of the board blinks to signal that your board is in AP Mode.



//Command after SSHing into the Edison IP address

ls
ls /sketch
clear
curl  //to print current channel(URL)
