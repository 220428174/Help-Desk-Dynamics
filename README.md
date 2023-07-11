# Help-Desk-Dynamics
Abit of an overall for help desk and analysis of incounted problems

##IN PRODUCTION##


Help Desk Dynamics

IP Address
3 Different types of IP addresses are HOST / NETWORK / BROADCAST
HOST = In-between the host min and host max 
NETWORK = Lower the host min
BROADCAST = Higher than the host max
Address(Answer)	Type(Answer)	Network ID	Host Min	Host Max	Broadcast
192.168.1.0	Network	192.168.1.0/24	192.168.1.1	192.168.1.254	192.168.1.255
192.168.3.2	Host	192.168.3.2/24	192.168.3.1	192.168.3.254	192.168.3.255
192.168.5.255	Broadcast	192.168.5.255/24	192.168.5.1	192.168.5.254	192.168.5.255
192.168.7.0	Network	192.168.7.0/24	192.168.7.1	192.168.7.254	192.168.7.255
192.168.9.3	Host	192.168.9.3/24	192.168.9.1	192.168.9.254	192.168.9.255

Networking.

OSI – Open Systems Interconnection

7 layers = Red – Media Layers / Blue – Host Layers

7- Application Layer
6- Presentation Layer
5- Session Layer
4- Transport Layer 
3- Network Layer (IP Address) 
2- Data Link Layer (MAC Addressing) 
1- Physical Layer (Cable) 

Fault 1 – Can’t connect to the network 
User Complaint – The user can’t connect to the internet but other computers in the office are connecting to the internet as usual.

Troubleshooting Process - The first step I did was check the computer for its LAN cable for any physical damages, make sure all cables are plugged in all the way and aren’t slightly moved. I then switched the cable for a working and un-damaged one so that no other physical issues would occur.

Proposed Solution – I would propose that you switch the cable to a new and un-damaged one.

Solution Verification - I would ask the user if they were being connected to the internet. I would ask them to refresh their browser to see if a website can be searched or I would ask them to refresh their settings to see if they can connect to their local Wi-Fi.               
                                                                                                                                                                                                                                                     OSI Layer – Physical Layer 
 
Fault 2 – Can’t connect to the Printer 
User Complaint – The user is trying to print to a printer that is on the same network but isn’t connected physically. They can’t find the printer of choice to print to and don’t know how to connect to it.

Troubleshooting Process – The first thing I did was to make sure that the printer has been added on the computers network and clear out all printers that aren’t being used with that device. Then I made sure the computer or device has access to the printer. The last thing I did before touching anything else was made sure that both the device and the printer were updated and compatible with each other.

Proposed Solution – My proposed solution would be to reset both devices and try searching for each other again after a reboot.

Solution Verification – I would ask the user if they can see the printer device on their device list after refreshing it. I would then ask them to test out if they could print something from their computer too see if it all goes through the printer.

OSI Layer – Network Layer 
 
Fault 3 – Slow computer performance
User Complaint – File access is slow when searching through the computer and trying to open up different files around the computer.

Troubleshooting Process – The first thing I would do is restart the computer, this is to check that everything is running smoothly in the start-up process. Once the computer is running I would try to run minimal programs at once to reduce the risk of slow computer performance. I would then go through and delete any files or programs that aren’t being used or are just not needed in the computer for it to run. I would then do an update check for the computer to see it’s at the latest edition and isn’t out dated. To finish of the check I would run other programs such as disk defrag and disk clean to help search for any viruses or issues that can be the reason for slow computer performance.
Proposed Solution – My proposed solution would be to run through the system for any programs that are useless and can be wiped or deleted to create less problems for the computer.

Solution Verification – I would then ask the user to describe if there computer was running differently after this troubleshooting process. I would recommend to them to document how it runs for the next couple of days and to contact back if more issues occur.

 

OS Installation
Apache2 on Lubuntu
How-to-steps: 
Step 1 – Load up your Lubuntu device and press (CTRL – ALT – T) 
this will load up the command line
Step 2 – Type “sudo apt-get install apache2”
and this will run the webserver installation
Enter “Yes” in the next option
Step 3 – Your installation should be complete
test it out by loading a web browser and typing in “localhost”
if your browser looks like this, it’s done.
 
After completing your installation, you can now edit your webserver to your likings,
do this by:
Step 1 – Load up your command line
(CTRL – ALT – T)
Step 2 – type in “sudo LeafPad /var/www/html/index.html”
this should load up a file
 
Step 3 – Edit this file however you like and don’t forget to save it
Step 4 – load up the website by placing your IP in the web browser and testing if it works

 

