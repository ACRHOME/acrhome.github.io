
Setting up the VNC server to connect Raspberry Pi to laptop display

If you have an HDMI display: Using the connected HDMI display on your pi, you should install VNC server in raspberry pi. Open the LX-Terminal and type the following commands to install VNC:

$ sudo apt-get update

$ sudo apt-get install tightvncserver

If you don’t have an HDMI display: If you do not have a display even for one time setup, then no need to worry. Install Putty as per your windows configuration and via SSH you can connect with your raspberry pi. And, as you get access of your pi terminal, run the same commands as above to install VNC.
Starting VNC Server on Pi :
For starting VNC, enter the following command in SSH terminal:

$ vncserver :1

You will be prompted to enter and confirm a password. This will be asked only once, during first time setup. Enter an 8 digit password. Note that this is the password you will need to use, to connect to the Raspberry Pi remotely. You will also be asked if you want to create a separate “read-only” password – say no (n).
Yippeee :)….The VNC server is now running on your Pi and so we can attempt to connect to it. 
