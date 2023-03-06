<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- https://www.youtube.com/watch?v=K7T_JjvEamg

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create and Connect to virtual machine with remote desktop
- Install/Enable IIS in windows 
- Install Web Platform installer
- Install Osticket version 1.15.8 
- Download and install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src=https://i.imgur.com/Dwt0wkd.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Created a virtual machine in Microsoft Azure. Created a Azure Virtual Machine 10, with 2-4 Virtual CPUs. Connected to that Virtual Machine using  Remote Destop Connection on my Microsoft Laptop.
</p>
<br />

<p>
<img src=https://i.imgur.com/WiWTu1g.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Go to Contol Panle and under Programs, select uninstall a Program. on the next page, select Turn Windows features on/off, then enable the Internet Information Services known as the (IIS) from available services.
</p>
<br />

<p>
[<img src=https://i.imgur.com/CvR0gsb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
With (IIS) being enabled, we are now able to install Web Platform installers.
</p>
<br />
<img src=https://i.imgur.com/HmPphxb.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
Download OSticket from the installation files folder.
[<img src= https://i.imgur.com/rtNwGG1.png height="80%" width="80%" alt="Disk Sanitization Steps"/>
Once the WEBPI is installed, we can now download and install HeidiSQL. Create a new session, root/Password1, then create new seesion, and create database called OSticket.
