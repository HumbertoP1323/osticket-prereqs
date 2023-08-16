<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />






<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

 
- Enable IIS (internet information services)
- Install PHP Manager
- Install MySQL
- Configure OsTicket and install permissions

<h2>Installation Steps</h2>



<p>
<img width="500" alt="image" src="https://github.com/HumbertoP1323/osticket-prereqs/assets/140670261/99e9096e-74b9-497d-82b5-70eb8c0915c1">

</p>
<p>
First is to enable Internet Information Services (IIS). This involves configuring IIS settings to make web hosting possible. Once enabled, you can serve and manage web content on the server.
<br />

<p>
<img width="496" alt="image" src="https://github.com/HumbertoP1323/osticket-prereqs/assets/140670261/a151e291-c008-4621-aa04-18a44bde37af">

</p>
<p>
Once IIS has been enabled, proceed by downloading and installing PHP Manager for IIS (PHPManagerforIIS_V1.5.0.msi) from the designated installation files directory. Following the installation of PHP Manager for IIS, download and install the Rewrite Module (rewrite_amd64_en-US.msi).
</p>
<br />

<p>
<img width="500" alt="image" src="https://github.com/HumbertoP1323/osticket-prereqs/assets/140670261/927c7ef5-1fa5-4fe9-bf24-ce452877fda6">


</p>
<p>
Next, move on to downloading and installing MySQL 5.5.62 (mysql-5.5.62-win32.msi) using the provided installation files. As you go through the MySQL setup wizard, simply agree to the terms by clicking "I agree." Then, choose the Typical installation option and follow through with the Install command. Once the installation is done, open the Configuration Wizard. Go for the Standard Configuration, and make sure to check the box for Install As Windows Service. Also, ensure that the MySQL Server will start automatically. For login details, use "root" as the username and set the password to "Password1." , while these credentials might be easy to guess in a practical situation, they'll work just fine for this lab.
</p>
<br />
<img width="497" alt="image" src="https://github.com/HumbertoP1323/osticket-prereqs/assets/140670261/b4628ac1-3689-4db8-89fb-0cf41789d5c1">

Begin by installing osTicket following the given instructions. Then, head to the PHP manager and turn on all the extensions needed for osTicket to work smoothly.
