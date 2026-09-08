## Help Desk Ticketing & Management Lab

## Objective


This project was to deploy and configure a functional help desk ticketing environment using osTicket, Docker, and MySQL. The lab simulated a basic IT support workflow by configuring departments and ticket settings, submitting user support requests, reviewing tickets through the Staff Control Panel, and responding to reported issues. 

### Skills Learned

- Help desk ticket creation, triage, assignment, and resolution.
- Ticket queue and lifecycle management using osTicket.
- Configuration of departments, priorities, SLAs, and ticket settings.
- End-user communication and technical support documentation.
- Basic MySQL database and environment variable configuration.

### Tools Used

- **osTicket** - Help desk ticketing and incident management platform.
- **Docker Desktop** - Deployed and managed the containerized lab environment.
- **MySQL** - Database backend for storing osTicket application data


<h2>Program walk-through:</h2>

<p align="center">
 
Checked Docker version Via Powershell
<br/>


<img src="https://i.imgur.com/pMXoenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
created a folder, "C:\Dockerlabs\osticket-lab"  directory to organize all files
<br/>


<img src="https://i.imgur.com/RPt7rZq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/4xNFmbM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
  
 Inside the 'osticket-lab' directory, I created two configuration files:<br/>
  - '.env' : For storing environment variables required for the MySQL database configuration<br/>
  - 'docker-compose.yml' : Defines how the osTicket application and database containers are deployed
<br/>


<img src="https://i.imgur.com/IcGftcq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

**env stored data:** 

<img src="https://i.imgur.com/2ISIGie.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

**docker-compose.yml stored data:**
<img src="https://i.imgur.com/Z380Aqh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
After creating the Docker Configuration files, I navigated to the lab directory and ran:<br/>
- docker compose up -d: **Reads the docker-compose.yml file and lauches the osTicket and MySQL services**
<br/>


<img src="https://i.imgur.com/zwqkaf7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">

 After launching the services, I opened OsTicket via Localhost(Web browser)
<br/>


<img src="https://i.imgur.com/aWWRw6W.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/EYstOBG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
Upon signing in, I created Departments & Configured Admin settings.
<br/>


<img src="https://i.imgur.com/RV0i8ul.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/3Tvgrhe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/tB5mu8M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/RvxyDcW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
Checked Docker version Via Powershell
<br/>


<img src="https://i.imgur.com/pMXoenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
Checked Docker version Via Powershell
<br/>


<img src="https://i.imgur.com/pMXoenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
Checked Docker version Via Powershell
<br/>


<img src="https://i.imgur.com/pMXoenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<p align="center">
 
Checked Docker version Via Powershell
<br/>


<img src="https://i.imgur.com/pMXoenn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
