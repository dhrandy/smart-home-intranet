# Smart Home Intranet

## The What? ##

What's this exciting new project you're working on you ask?  Glad you did, this is a smart home intranet site.  For anyone that doesn't know intranet is where the site is on an internal network.  I am accessing this site from my house and no-one has access to the site outside my house.

The site itself is just a simple site that gives details about my smart home.  

## The Why? ##

Sometimes you may have company or friends over at your house and they are interested in your smart home.  Or (the more real scenario) you want to show someone your smart home setup. Sometimes you can't remember all the commands and features.  That's where this site comes in handy.  You whip out your smartphone or computer and you have access to all the information.  To get to the site you just punch in the url and there it is!

## The Challenge ##

This was also kind of a challenge for myself.  I wanted to completely write the code on a small Linux computer that I have that's running Zorin OS.  The computer only has 32 gigs of ram and 4 gigs of memory.  It actually runs everything just fine.  Linux is awesome!

## Setup ##

You'll need a server or computer to set this up to be available all the time. I used my Minecraft server, which is just a computer running Windows 10.  You'll need to install something to host the site with, used XAMPP.  Within XAMPP you'll have to enable Apache.  You'll also need to copy the files to the folder located at C:\xampp\htdocs\dashboard.  You'll then want to change the computer name to something easy to type into the browser.  You should open the port for your webpage to get through the firewall of the computer.  Default port is 80.  You can use Google if you don't know how to do that, it's pretty simple.  When all that's done you'll want to start the Apache server, to do this simply open the XAMPP software and click start beside Apache.  Now navigate to the IP or URL.  For example, if you named your computer server, then you'd navigate to server:80 in  your browser.

## Pages ##
- index.html - Gives an overall view of the additional pages and a small amount of info.  It also contains links to the additional pages.
- alexa.html - Information about Alexa and the Echo devices.
- alexa-lights.html - Additional commands for the light colors.
- entertainment.html - Firestick Alexa commands information.
- smartthings.html - Information about the smart home hub.
- security.html - Camera Security information.
- other.html - Additional smart home information that doesn't fit into the other groups.

## Technologies Used

- HTML 5
- CSS
- Bootstrap CSS
- Xampp
- Apache

## Software Used
- VS Code
- Gimp