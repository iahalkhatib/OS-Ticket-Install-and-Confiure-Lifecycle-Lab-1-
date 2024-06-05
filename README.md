# OS-Ticket-Prerequisites, Installation, and Post-Installation Configuration

<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/3f65ae5d-12df-482c-b00b-b9e6887394ac)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Installation Steps</h2>

# 1. Task 1. Create a new Rescource Group in Azure

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/5e0773ef-4db0-443d-9927-2317e7b46f03)


# 2. Task 2. Create a new Virtual Machine (VM) running Windows 10

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/8a0ffd9f-4371-4c5b-be6b-42a968fd867a)

# 3. Task 3. Use RDP to connect to the (VM) Virtual Machine 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/d1d8d519-fa7c-443f-9aa3-b8a9dbab3b30)

# 4. Task 4. Inside of VM go to control panel, programs, Turn Windows Features On and Off 

World Wide Web Services -> Application Development Features ->
  [X] CGI
  [X] Common HTTP Features

Internet Information Services -> Web Management Tools -> IIS Management Console
	[X] IIS Management Console


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/366e4761-ad61-4539-8d41-320d93a980b5)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/30a43f69-5e38-4e52-8533-00feb896b651)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/450e5136-426a-44fd-8101-d4e2fdc9d49a)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/c39ae54a-1460-4ed0-bcd6-fc23207495fe)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/eee73adc-99b2-4060-afe9-709d2c519b3a)


# 5. Task 5. Verify ISS is live 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/72e2fb54-5547-482b-9ca3-a412c3e885e7)

# 6. Task 6. Download and Install PHP Manager for IIS 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/02599e24-7518-485b-83aa-1e81420c3443)

# 7. Task 7. Download and Install Rewrite Module 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/bf5c2bbf-5f4e-4e7f-bc54-05b146611f77)

# 8. Task 8. Create the Directory C:\PHP

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/afd173f2-e7d8-4d09-b4b8-b9fb43c269af)

# 9. Task 9. Download PHP 7.3.8 and unzip the contents into the C:\PHP

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/7c35af07-10de-48b5-8a50-e6c42fd47167)

# 10. Task 10. Download and Install VC__redist.x86.exe

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/28654e4b-219e-4e72-9fa7-cf964a74f147)

# 11. Task 11. Download and Install MySQL 5.5.62

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/b827f964-3a45-4bd1-a7db-84c33230b68e)

# 12. Task 12. Open IIS as Administrator

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/241c866e-20de-437b-8170-6631c5937c65)

# 13. Task 13. Register PHP from within IIS

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/0332554f-ed30-43ed-ba84-c35d27e7986e)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/1df51142-6678-4378-9711-3a93706ec352)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/f1ab3de8-1858-4dc7-ba4e-f13859d7c815)

# 14. Task 14. Restart the IIS Server
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/583a5cd3-8601-4129-be28-80cceac68fa5)

# 15. Task 15. Download and Install osTicket v1.15.8, extract and copy "upload" folder to the c:\inetpub\wwwroot, rename "upload" to "osTicket" within c:\inetpub\wwwroot

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/9b3c9a0a-a03a-4646-89f2-875527f9611c)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/d9ff49f1-f851-4ce5-b728-5f5691473dae)

# 16. Task 16. Restart the IIS Server

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/454927d7-258e-4ca2-a87f-4ee803f02a64)

# 17. Task 17. osTicket on the right click on "browse" find ":80"

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/9c38c634-09c2-4b0f-9bf7-d774be1da725)

# 18. Task 18. In ISS Enable some extentsions using PHP Manager 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/3f3c2580-baee-44ec-bab5-ef2659c0b76c)

# 19. Task 19. In ISS Enable some extentsions using PHP Manager 

Enable: php_imap.dll
Enable: php_intl.dll
Enable: php_opcache.dll

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/01a7c118-213b-4a1a-8f0f-5a313adbb271)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/d027b970-29fb-4b93-92bf-c90067f08509)


# 20. Task 20. Rename "ost-config.php" from C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php to C:\inetpub\wwwroot\osTicket\include\ost-config.php


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/e1f9f435-b743-4516-9a68-d0a636d60075)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/59d1a2d3-6119-4dd8-986e-2fc258cbcfa1)

# 21. Task 21. Adjust permissions to ost-config.php, right click, properties, security, advanced. Disable Inheritance, Remove All 

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/b08a0b6d-b812-49ec-83ae-993791fb3e13)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/710ab3f3-ee09-4042-b25b-cf2bcd718a40)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/f188ec84-e9f4-45db-b4c0-e61fa1cd525a)

# 22. Task 22. Add new permisions to allow access to all users
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/908d15d8-a251-4dd0-bc15-a7852699b573)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/6c7cd8ad-893f-45f0-84e2-f057df1e1ab4)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/b1a8a468-417a-4118-8679-6ef620b0ac78)


# 23. Task 23. Continue to install and configure osTicket in the browser 
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/f73a1040-cee3-455e-b33d-22e20902eb3e)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/6d479a4c-394e-497d-8659-cbae7ddb8c25)


# 24. Task 24. Download and install "Heidi SQL" and create a new session using user and password 


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/5c1ae17e-700d-4226-b094-7fcd906b5ab8)

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/eb9d75ef-c9ab-4d1e-8af4-67f31eb7519c)


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/8b44b7de-a3d2-4db9-95fb-632693864290)


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/e8bbd280-61df-4fd0-bbee-4b68a09650e4)


# 25. Task 25. Create a new database called "osTicket"

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/ea02eb84-0659-449c-9912-f42aaea02eec)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/7ddb2c93-c6c3-4cbc-ba3c-f0483a7d4902)

# 26. Task 26. Continue configuring osTicket in the browser 

MySQL Database: osTicket
MySQL Username: root
MySQL Password: Password1
Click “Install Now!”


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/dd1f682e-28ac-4595-8c26-1237bb62afe4)
![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/fe0d5590-8104-4352-bcef-1a75b99d04d4)


# 27. Task 27. Install clean up 

Delete: C:\inetpub\wwwroot\osTicket\setup

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/7a8dfb5d-cdac-4040-8a9f-c0d387011ab5)

Set Permissions to “Read” only: C:\inetpub\wwwroot\osTicket\include\ost-config.php

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/f9dabdfd-c233-4d85-baff-104762f02f3b)

![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/98b46140-be4c-4a57-ba10-d1e24477f0d7)


# 28. Task 28. Access admin osTicket using "//localhost/osTicket/scp/login.php"


![image](https://github.com/iahalkhatib/OS-Ticket-Install-and-Confiure-Lab-1-/assets/170050432/815afbe0-1b11-4423-8f9d-543a84501cc4)


