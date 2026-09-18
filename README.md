<h1>Honeypot and SIEM detection pipeline</h1>


<h2>Description</h2>
Deployed a deliberately exposed Windows 10 VM in Microsoft Azure to attract real-world attack traffic, then built a full detection pipeline around it: centralized logging via Log Analytics Workspace, Microsoft Sentinel as the SIEM, KQL queries for log analysis, and GeoIP enrichment to map attacker origins in a live Sentinel workbook.
<br />


<h2>Languages and Utilities Used</h2>

- <b>KQL (Kusto Query Language)</b> 
- <b>Azure Virtual Machines</b>
- <b>Microsoft Sentinel</b>
- <b>Log Analytics Workspace</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> 

<h2>Overview:</h2>

<p align="center">
Deploy the Honeypot and
Confirm the Trap & Investigate Logs: <br/>
<img src="https://i.imgur.com/6hqxvb3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<img src="https://i.imgur.com/jbTBwLc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Centralize Logging & Deploy the SIEM: <br/>
<img src="https://i.imgur.com/u4ZGVnZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enrich Logs with Geolocation Data and Build the Attack Map:  <br/>
<img src="https://i.imgur.com/1KPQj2Q.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />




