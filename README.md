<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Installation</h1>
This demostration outlines the installation of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/5yQN5Wc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After Installing PHP Manager for ISS, downloading and setting up MySQL 5.5.62, I will open ISS as an administrator and register PHP Manager with correct files. I will proceed to download osTicket, extract and copy “upload” folder to c:\inetpub\wwwroot. Within c:\inetpub\wwwroot, I will rename “upload” to “osTicket." Back on ISS, I will select Sites/Default Web Site/osTicket and click on Browse *:80 http. 

</p>
<br />

<p>
<img src="https://i.imgur.com/4FLYD9I.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
After opening osTicket on the browser there will be features not yet enabled. With a quick fix, I will access ISS, select PHP Manager, and enable missing extensions: php_imap.dll, hp_intl.dll, php_opcache.dll. Refresh osTicket browser to see changes.  
In file explorer, C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php rename "ostsampleconfig.php" to "ost-config.php." Remove all heritance from ost-config.php. 


</p>
<br />

<p>
<img src="https://i.imgur.com/v3q9LEX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Continue on osTicket browser and osTicket Basic Installion should be ready to setup and personalize. Open HeidiSQL to create a new session.
</p>
<br />


</p>
<br />

<p>
<img src="https://i.imgur.com/Ts1mxiR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Complete basic installion database settings.
  
  
  </p>
<br />

<p>
<img src="https://i.imgur.com/K9J2Ktd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
