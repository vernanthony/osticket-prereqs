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

- Installed / Enabled IIS in Windows WITH CGI
World Wide Web Services -> Application Development Features -> [X] CGI

- Installed MySQL / Setup Username and Password
- Configured Permissions and Installed osTicket
  

<h2>Installation Steps</h2>

![Screenshot 2025-01-21 194218](https://github.com/user-attachments/assets/28f865f9-a697-4f51-b64e-8902c26b1cac)



<p>
</p>
<p>
The image above showcases the setup of a virtual machine in Microsoft Azure, configured for installing and running osTicket. Key configurations include selecting a **Windows 10 Pro** operating system, a **Standard_D2as_v4** size (2 vCPUs, 8GB RAM), and creating a virtual network. Networking settings include a public IP for remote access. This setup enables the deployment and management of the osTicket helpdesk system.
</p>
<br />

![Screenshot 2025-01-21 194951](https://github.com/user-attachments/assets/db6f9b8e-6476-4405-9638-8c53743ce4c1)


<p>
</p>
<p>
The image above demonstrates enabling Internet Information Services (IIS) in Windows, specifically configuring the CGI feature under World Wide Web Services -> Application Development Features. This setup is essential for running web applications, including osTicket, on a Windows server.</p>
<br />

![Screenshot 2025-01-21 195625](https://github.com/user-attachments/assets/c3cb73e5-bbec-4fd2-9491-d9a1828f5feb)


<p>
</p>
<p>The image above shows the installation process for **MySQL Server 5.5** using the setup wizard. During the setup, users can create a personal username and password for securing the database, which is essential for managing and storing application data, such as osTicket configurations and user details.
</p>
<br />


![Screenshot 2025-01-21 200346](https://github.com/user-attachments/assets/c45e0197-5d8e-4939-ba8d-96f9c2b95aa8)
In the Image Above During the osTicket installation, I assigned specific permissions to ensure everything runs smoothly. I set write permissions for files like `ost-config.php` and adjusted directory access for storing attachments and logs. These steps were crucial to getting osTicket configured and ready for use.


![Screenshot 2025-01-21 200022](https://github.com/user-attachments/assets/4c7e69f7-9046-4326-8c63-e69980d252c7)

![Screenshot 2025-01-21 200912](https://github.com/user-attachments/assets/bcf206b9-e194-463e-b303-af9644fa2b93)
After setting the necessary permissions, installing MySQL, and configuring the C++ Redistributable, I successfully completed the osTicket installation. The system is now fully configured and ready to manage support tickets efficiently.
