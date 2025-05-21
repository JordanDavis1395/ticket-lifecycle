<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial explains the lifecycle of a ticket from intake to resolution within the osTicket open-source help desk ticketing system.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (22H2)

<h2>List of Prerequisites</h2>

- Follow this complete [osTicket Installation Tutorial](https://github.com/JohnSomanza/osTicket-Prereqs.git) and [osTicket Post Installation Configuration Tutorial](https://github.com/JohnSomanza/Post-Install-Config.git) before starting this tutorial

<h2>Ticket Lifecycle Steps</h2>

<p></p>
<p>
</p>
<br />

<p>
</p>
<p>Step 1: To start to create the three example tickets go to localhost/osTicket/ in your VMs browser</p>
<img src="https://i.imgur.com/FdNdOi6.png">
<p>Step 2: Select open a new ticket -> Use Email Address: karen@osticket and Full Name: Karen Karen as contact information -> Help Topic: Business Critical Outage -> Ticket Details: “Entire Online banking system is down” -> Enter an example detail scenario like in one of the images below -> Click "Create Ticket"</p>
<img src="https://i.gyazo.com/d7cb241a44875fd1867902186e4994a5.png">
<img src="https://i.gyazo.com/5148b6dc6bed31a31690f14e9551a49e.png">
<p>Step 3: Select open a new ticket -> Use Email Address: ken@osticket and Full Name: Ken Ken as contact information -> Help Topic: Personal Computer Issues -> Ticket Details: “Accounting department can't use Adobe Reader” -> Enter an example detail scenario like in the image below -> Click "Create Ticket"</p>
<img src="https://i.gyazo.com/d7cb241a44875fd1867902186e4994a5.png">
<img src="https://i.gyazo.com/97c6f9ba05a47d24be55367dfd01c411.png">
<p>Step 4: Select open a new ticket -> Use Email Address: karen@osticket and Full Name: Karen Karen as contact information -> Help Topic: Equipment Request-> Ticket Details: “Question on new computer hardware” -> Enter an example detail scenario like in the image below</p>
<img src="https://i.gyazo.com/d7cb241a44875fd1867902186e4994a5.png">
<img src="https://i.gyazo.com/8aaab9811bfe47e16960678ecfa3773a.png">
<p>Step 5: Head to to localhost/osTicket/scp/login.php in your VM's browser and login using the admin account you created in the osTicket installation tutorial</p>
<img src="https://i.gyazo.com/255cf2560f9907342d99cb6fb5120444.png">
<p>Step 6: Select “Tickets -> Select the ticket titled “Entire online banking system is down” -> Set Priority to Emergency -> Set the SLA to SEV-C -> Assign the ticket to yourself -> Assign the ticket to the System Administrators department -> Write an example reply explaining what you did to help solve the ticket hypothetically like the image below of my example response. -> Set the “Ticket Status:” to “Resolved” -> Click “Post Reply”</p>
<img src="https://i.imgur.com/3DvCl4i.png">
<img src="https://i.imgur.com/G4nj1wD.png">
<img src="https://i.imgur.com/tPoCGyH.png">
<img src="https://i.imgur.com/kYckNdU.png">
<img src="https://i.imgur.com/jz0kwFJ.png">
<img src="https://i.gyazo.com/dd2033b5f9ecdf129ede4bc68c00de09.png">
<p>Step 7: Select “Tickets” -> Select the ticket titled “Accounting department can’t user Adobe Reader” -> Set Priority to High -> Leave the ticket assingned to the Support department -> Set the SLA to SEV-B -> Assign the ticket to “Jane Doe” -> Log out -> Log in as jane@osticket.com -> Click the “Accounting department can’t use Adobe Reader” ticket -> Write an example reply explaining what you did to help solve the ticket hypothetically like the image below of my example response. -> Set the “Ticket Status:'' to “Resolved" -> Click “Post Reply”</p>
<img src="https://i.imgur.com/K3qPgx9.png">
<img src="https://i.imgur.com/NBcDvLl.png">
<img src="https://i.imgur.com/Z2TeRpj.png">
<img src="https://i.imgur.com/kYTvGMw.png">
<img src="https://i.imgur.com/bMq1DCl.png">
<img src="https://i.gyazo.com/236fbc21255b246c623c7a13fc64d3ca.png">
<img src="https://i.imgur.com/NlBWlQW.png">
<img src="https://i.gyazo.com/7d8d77167a51aaed52bc70ab0a129b2f.png">
<p>Step 8: Log out of the Jane Doe account -> Log in to the user_admin account -> Select the “Question on new computer hardware” ticket -> Leave the Priority to Normal -> Assign the ticket to “John Doe” -> Set the SLA to SEV-C -> Logout -> Log in as john.doe -> Select the “Question on new computer hardware” ticket -> Write an example reply explaining what you did to help solve the ticket hypothetically like the image below of my example response.-> Set the “Ticket Status:” to “Resolved” -> Click “Post Reply”</p>
<img src="https://i.imgur.com/joufUWv.png">
<img src="https://i.gyazo.com/7fe6912a186d4076a6a3f71a46252cc9.png">
<img src="https://i.imgur.com/xlEgXUK.png">
<img src="https://i.imgur.com/lMOgc26.png">
<img src="https://i.imgur.com/QLhaePk.png">
<img src="https://i.imgur.com/LjTcPcF.png">
<img src="https://i.gyazo.com/aa9bca0cb54c35628589495a0fc7bb15.png">
<img src="https://i.imgur.com/ye5b9eS.png">
<img src="https://i.gyazo.com/792c6cd6181ba2e26380c36e87184eec.png">
<img src="https://i.imgur.com/QKAV2xz.png">
<p>Congrats you’ve just completed all of the steps for this osTicket ticket lifecycle tutorial!</p>
