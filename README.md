# 🖥️ Active Directory & Splunk Project

## 🛠️ Objective
To configure an Active Directory domain and integrate Splunk for monitoring, telemetry collection, and security analysis. This project involved setting up Sysmon for event logging, brute force testing using Crowbar, and analyzing failed login attempts.

---

## 🎓 Skills Learned
- **Active Directory Configuration**: Set up and managed a Windows 10 machine in an AD domain.
- **Log Management**: Installed and configured Splunk for data ingestion and log analysis.
- **Security Monitoring**: Used Sysmon to forward security and system logs for better visibility.
- **Brute Force Attack Simulation**: Employed Crowbar for brute forcing RDP and monitoring failed attempts.
- **Event Analysis**: Detected and analyzed security events using Splunk, particularly failed login attempts.

---

## 🔧 Tools Used
- **Active Directory**: Managed users, devices, and organizational units.
- **Splunk**: Monitored logs and analyzed security events.
- **Sysmon**: Captured detailed event telemetry from Windows systems.
- **Crowbar**: Performed brute force attacks on RDP.
- **Windows 10**: Added to the domain and used for endpoint security logging.

---

<h2>Screenshots:</h2>


<p align="center">
  <img src="https://i.imgur.com/EIF3pZr.png" alt="Network Diagram" /><br/>
  Network Diagram
</p>

<p align="center">
  <img src="https://i.imgur.com/tHc1TKl.png" alt="Splunk installed and configured" /><br/>
  Splunk installed and configured
</p>

<p align="center">
  <img src="https://i.imgur.com/1qwuicm.png" alt="Sysmon installed on Win 10 with Olaf config for telemetry transfer to Splunk" /><br/>
  Sysmon installed on Win 10 with Olaf config for telemetry transfer to Splunk
</p>

<p align="center">
  <img src="https://i.imgur.com/gI4cttD.png" alt="Configuring Splunk inputs.conf file to forward logs" /><br/>
  Configuring Splunk inputs.conf file to forward logs
</p>

<p align="center">
  <img src="https://i.imgur.com/pkfJY4B.png" alt="Added Win 10 machine to the domain" /><br/>
  Added Win 10 machine to the domain
</p>

<p align="center">
  <img src="https://i.imgur.com/gGAWhDe.png" alt="Created IT, HR Organizational Unit and added Win 10 to the domain" /><br/>
  Created IT, HR Organizational Unit and added Win 10 to the domain
</p>

<p align="center">
  <img src="https://i.imgur.com/KtzTa3U.png" alt="Configured Index to receive data on port 9997 and added index endpoint" /><br/>
  Configured Index to receive data on port 9997 and added index endpoint
</p>

<p align="center">
  <img src="https://i.imgur.com/NtffbnD.png" alt="Successfully added Windows 10 and domain controller endpoints" /><br/>
  Successfully added Windows 10 and domain controller endpoints
</p>

<p align="center">
  <img src="https://i.imgur.com/zoWWEzV.png" alt="Using Crowbar to brute force RDP" /><br/>
  Using Crowbar to brute force RDP
</p>

<p align="center">
  <img src="https://i.imgur.com/u2pkSD5.png" alt="Event ID 4625 showing failed logon attempts" /><br/>
  Event ID 4625 showing failed logon attempts from the Kali machine
</p>

</p>







<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
