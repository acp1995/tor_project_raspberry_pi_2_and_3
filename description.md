# tor_project_raspberry_pi_2_and_3
The tor.sh and pifi.sh are ready to be compiled and run on Raspberry Pi 2 and 3.
I've tested it with Raspberry Pi 2 Model B with Kali Sana 2.0 (ARM) and used a Canakit 150 mbps usb wifi dongle and the results were awesome .

Steps :
1>Compiled both the .sh files  (make 'filename' works)
2>Transfered the compiled files to the sd card pre loaded with Kali 2.0 ( I had to compile the files in my UBUNTU PC as the version of Kali I was using was not pre installed with the "make" command and i was too lazy to apt-get that :p )
#I added exceptions and mentioned the file names "pifi" and then "tor" to the .bashrc file (so that i wont need to connecta screen and manually run the files on every start up .
3>Connent an ethernet cable , wifi usb dongle,sd card and turn ON the pi .
4>Enjoy tor :)
