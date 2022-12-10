<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install / Enable IIS in Windows
- Downnload and Install Web Platform Installer
- Install osTicket v1.15.8
- Download and Install HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/mIIKyih.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
IIS was enable by going to "control panel" > "programs" > "programs and features", clicking on "turn windows features on and off", and selecting IIS. It can also be enable by using PowerShell and Server Manager. Internet Information Services (IIS) is a flexible, general-purpose web server from Microsoft that runs on Windows systems to serve requested HTML pages or files and can be used to host, deploy, and manage web applications using technologies such as ASP.NET and PHP.
<br />


<p>
<img src="https://i.imgur.com/x9HRiEo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
<p>
Web Platform Istaller was download and installed.
Microsoft web platform is a free tool that makes it simple to download, install and keep up-to-date with the latest components of the Microsoft Web Platform, including Internet Information Services (IIS), SQL Server Express, .NET Framework and Visual Studio. 

Deeper confirguration:
- Open after installation, "MySQL 5.5" and simple versions of x86 PHP (until 7.3) was added. 
- Credentials were created (name & password
- failures were fixed by downloading the necessary files belows: "Installed PHP Manager 1.5.0" for IIS 10 and "Microsoft Visual C++ 2009 Redistributable Package".
</p>
<br />


<p>
<img src="https://i.imgur.com/Hm340w0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
<p>
osTicket was downloaded and extracted. the “upload” folder was copied INTO "c:\inetpub\wwwroot" and Within "c:\inetpub\wwwroot", “upload” folder was renamed to “osTicket”. OsTicket was launched on a web broswer for set up by click on Broswer 80 (as shown above)

Osticket is an open source support ticket system and customer support platformn. The software features a built-in customer portal that allows users to submit tickets and track the status of their requests. The osticket uses a MysQL database to store information.

Deeper Configuration:
- Enabled Extensions in IIS: 
- Assign Permissions: ost-config.php
- Continue Setting up osTicket in the browser 
</p>
<br />


<p>
<img src="https://i.imgur.com/cQxnocY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
HeidiSQL was downloaded and installed. A new section was created along with a new Osticket datatbase. 

HeidiSQL is a free open source database management tool that runs under Windows. It provides features to manage on your desktop database actions that range from creating a database to exporting data as a dump file or csv files. It includes an integrated help for the SQL language, allows connecting to multiple local and or remote database servers and can be used with command line parameters.

Deeper Configuration:
- Osticket was fully step up on the broswer with all the necessary information and installed successfully.
</p>
<br />
