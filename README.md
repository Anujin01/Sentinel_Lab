<h1>SIEM Analytics: Failed Logins & GeoData in Sentinel</h1>


<h2>🌎Description</h2>
<b>This project sets up a honeypot using an Azure Virtual Machine (VM) with Remote Desktop Protocol (RDP) exposed to the internet. It logs failed RDP login attempts, extracts attacker IP addresses, and maps them to geographic locations using Azure Sentinel.

Unlike traditional methods that rely on PowerShell scripts for geolocation lookup, this project ingests a pre-existing IP-to-Geolocation dataset into Sentinel, making log queries faster, cleaner, and more scalable.</b>

<h2>📌 Features:</h2>

<b>Real-time attack visualization using Microsoft Sentinel.</b><br>
<b>IP Geolocation tracking of potential attackers.</b><br>
<b>Custom KQL queries for log analysis.</b><br>
<b>Simulated vulnerable services to attract attackers.</b>
<p align="center">
<img width="1013" alt="honeypot-map" src="https://github.com/user-attachments/assets/6de6f281-55d7-40c0-9ebf-3ee0af615f5b" />
</p>

<h2>🔧 Setup Guide</h2>


<h2>Languages used</h2>
<b> Kusto Query Language (KQL) – Used in Azure Sentinel for querying and analyzing logs.</b>
