# FiveM-Server-Ubuntu
This is a FiveM server For Ubuntu Were this shows how to create a Ubuntu Server for a FiveM server.

# What you would need
1. FlashDrive
2. Computer/Server

# How to Create a Ubuntu Server
1. Go to https://ubuntu.com/download/server
2. Then download it
3. then go to https://rufus.ie/en/
4. Download Rufus
5. set Rufus up
6. Add the Ubuntu ISO to Rufus and press Start
7. After it added the ISO to The flash Drive Turn off the Server/Computer
8. add the Flash Drive into the computer then reboot, and Press the key to get into boot menu and then Change the boot drive to the Flash Drive
9. Then Setup the Ubuntu Server.
10. type this command sudo apt update && sudo apt upgrade -y

# Add the FiveM server to the Ubuntu Server
1. Go into the Folder you want to add the fivem server to
2. Type this command sudo apt clone https://github.com/Cabler-Development/FiveM-Server-Ubuntu.git
3. then go into the folder "server", and start the FxServer.exe
