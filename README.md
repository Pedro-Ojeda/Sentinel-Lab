# Sentinel-Lab
<h1>Azure Sentinel - Honeypot Home Lab</h1>

 ### [YouTube Demonstration](https://www.youtube.com/watch?v=k_Z-ty0xeno)

<h2>Description</h2>
</b></b>The PowerShell script in this repository is designed to parse Windows Event Log information for failed RDP attacks and utilize a third-party API to gather geographic information about the attacker's location.
<br />
<br />
In this demo, I will set up Azure Sentinel (SIEM) and connect it to a live virtual machine functioning as a honeypot. We will observe real-time RDP brute force attacks from around the globe. I will employ a custom PowerShell script to retrieve the attacker's geolocation information and display it on an Azure Sentinel Map.
<br />

<p align="center">
<br />
<img src="https://i.imgur.com/UR9BUhV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/4aGAja9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b>
- <b>ipgeolocation.io</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro, version 22H2</b>

<h2>Attacks From Netherlands Coming in; Custom logs being output with geodata</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/vktWO7B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br/>
  
<h2>World map of incoming attacks (built custom logs including geodata)</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/FSVlBvP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
<br/>
<img src="https://i.imgur.com/m5T3F5R.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
