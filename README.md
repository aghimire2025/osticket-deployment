<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Deployment on Azure Windows VM</h1>
This Project outlines the deployment of Windows 11 Pro Virtual Machine in Azure and installing osTicket helpdesk system with all necessary configurations and dependencies.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- PHP 7.3.8, MySQL 5.5.62
- osTicket v1.15.8
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (21H2)

<h2>List of Prerequisites</h2>

- Enabled Internet Information Services (IIS)
- Installed Web Platform Installer
- Installed my SQL and set up username and password
- Installed C++ Redistributable
- Configured permissions and installed osTicket

<h2>Key Tasks Performed:</h2>

<p>
  <img width="627" height="543" alt="image" src="https://github.com/user-attachments/assets/27cdaaf0-e360-443b-ab39-2ec6dca4f76d" />

</p>
<p>
• Created and deployed a Windows 11 Pro VM named osTicket-vm in Microsoft Azure and accessed it via RDP.
</p>
<br />

<p>
<img width="465" height="550" alt="image" src="https://github.com/user-attachments/assets/ff177ae2-ff05-4386-9d27-7c37ed35a207" />

</p>
<p>
•	Installed and enabled IIS with CGI support
</p>
<br />

<p>
<img width="523" height="296" alt="image" src="https://github.com/user-attachments/assets/0422cd0e-969f-44a9-a420-72d1c96ba3f9" />

</p>
<p>
•	Installed PHP Manager and IIS Rewrite Module
</p>
<br />

<p>
<img width="623" height="332" alt="image" src="https://github.com/user-attachments/assets/d90a8294-9718-4b81-9ae8-bd0e0ae0cb19" />

</p>
<p>
•	Registered PHP in IIS via PHP Manager and enabled required PHP extensions: php_imap.dll, php_intl.dll, php_opcache.dll in IIS in PHP Manager
</p>
<br />

<p>
<img width="466" height="785" alt="image" src="https://github.com/user-attachments/assets/e37a8705-11b8-428b-8882-5f2360125456" />

</p>
<p>
•	Renamed file name from ost-sampleconfig.php to ost-config.php and configured permissions, disabling inheritance permission and giving full control to everyone.
</p>
<br />

<p>
<img width="445" height="273" alt="image" src="https://github.com/user-attachments/assets/8cf68bcb-a35e-47ea-a9d5-af055a0dfbde" />

</p>
<p>
•	Installed HeidiSQL, connected with root credentials, and created the osTicket database. Finalized installation using MySQL DB details in the browser. Configured the osTicket web installer with the helpdesk name and admin email
</p>
<br />

<p>
<img width="560" height="268" alt="image" src="https://github.com/user-attachments/assets/47702657-b1a7-407a-983b-1fd2379abe70" />

</p>
<p>
• Verified successful deployment:  </br>
o	Admin Login: http://localhost/osTicket/scp/login.php </br>
o	End User Portal: http://localhost/osTicket/

</p>
<br />
<h2>Skills Demonstrated</h2>
•	Azure VM provisioning and RDP configuration </br>
•	Windows IIS setup with PHP and MySQL integration </br>
•	Application deployment and troubleshooting </br>
•	File system permissions and web server management </br>
•	Database creation and configuration via HeidiSQL </br>

<h2>Results & Takeaways</h2>
•	Successfully deployed and configured osTicket on Azure Windows VM</br>
•	Gained practical experience with IIS, PHP, MySQL, and application stack setup</br>
•	Strengthening troubleshooting and environment configuration skills</br>

