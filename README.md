# Help-Desk-Dynamics
Abit of an overall for help desk and analysis of incounted problems




Help Desk Dynamics

Task 2 - IP Address
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

Task 3 - Networking Faults

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

OSI Layer – Application Layer 7
 

Task 4 & 5 - Customer Interactions
Role Play 1 – Windows 10 Back Up Process
1.	To start your back up process, navigate yourself to the settings page by right clicking on the bottom left windows icon and selecting the settings tab.
2.	After finding the settings tab, locate the updates & security section which should be the last one on the page.
3.	On the left bar, select the Backup tab, if you want to add a drive from there you can and go through a scheduled back up time, but if you want to do a windows 7 version, follow along…
4.	Select “Back up & Restore (windows 7)” as it is a simpler way to store back up on a hard drive
5.	Under Back-Up select the blue hyperlink on the right that says set up back-up
6.	Refresh the backup destination till you can see your device to save the back up on
7.	Select the recommended unless you want to configure you selection to your standard
8.	Save settings and run the back up
9.	Wait till it’s done  
Feedback – Overall happy with the steps listed looks easily enough to follow, maybe one point to improve would be to include screenshots to make it even easier to follow.
Task 6 - Advice about upgrade options
Client’s Needs (Scenario) – My client is a Graphics Designer and is involved with a Digital Animation company and his computer is in need of the latest upgrades to work at an efficient pace with no limitations to his work and projects. He says that his computer is always slowing down after working on a project through an editing program for a while, he also says that majority of the time the program crashes leading to loss of work and production time. 

Recommended Upgrades - 
My client needs a computer that works at a pace to get work done efficiently and could stop the potential issues he is currently dealing with.
	CURRENT	UPGRADES
CPU	I5 3570	AMD Ryzen 5 3400G APU with Vega 11 Graphics
RAM	8gb 1600mhz DDR3	Corsair Vengeance LPX CMK8GX4M2A2133C13 (2X4GB) DDR4
DISK	Toshiba 7200rpm 500GB	Corsair Force Series MP510 1920GB M.2 NVME SSD
GRAPHICS	Radeon HD 7570 OEM	MSI Radeon RX 570 Armor OC 4GB
MOTHERBOARD	M-ATX Dell OptiPlex 9010 OEM	ASRock B450M Steel Legend Motherboard
NOTES: What I have done for my client is built a computer that will be able to produce work for his projects. Although I upgraded all items, the main infrastructure changed was the DISK and GRAPHICS as my client will be needing the top of the line items for his business projects. Editing will take up a lot of space on the disk so to ensure loss of work is stopped, I made the disk space from a 500gb to 1920gb, another option is to add an external hard drive if more space is needed. All other specs will provide a good level of power towards work but if he did want more, he could upgrade it. This build is set at a decent price and will work very efficiently for my client.

Task 7 - OS Installation
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
Web server journal
1 – after installing Lubuntu and opening the command lines I was having trouble with the codes to load up the web server (“sudo apt-get install apache2”) 
2 – I was receiving a message about a “dpkg” which needed me to reset and turn it off and back on again
3- after doing that, I was able to put the line in and have my web server running
Occupational Health & Safety –
Tripping Hazards – 
With the wires that are needed for a computer, tripping hazards will be very clear and obvious. This is a very dangerous scenario that needs to be monitored at all times. A way to stop a tripping hazard would be wire management, keeping all cables tied up and separated from walking areas and possible zones where those who are near can walk into cables.

Slipping Hazards –
Slipping hazards are very serious in every working area. Someone could spill water in the area from their water bottle or even a coffee and this would lead to someone having an incident from minor to very large. A way to prevent this from happening is to keep a mop or cleaning equipment in the area for immediate clean and incident prevention.

Electrical Hazards -
When dealing with computers, electricity is a factor you will have to deal with. This means no water or liquid should be near the machines to prevent any combinations of the two. This also relates to the handling of cables and the machines with safety and precaution. Away to stop these incidents from occurring is having all liquids kept in the kitchen or other areas and also handling with care when it comes to plugging and unplugging different plugs.
Task 8 – Design a Network (Draw.io) 
 

