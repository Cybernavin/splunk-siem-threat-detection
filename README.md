# Enterprise SIEM Monitoring & Threat Detection using Splunk, Sysmon and Linux Logs

## Overview

This project demonstrates the implementation of a Security Information and Event Management (SIEM) solution using Splunk Free to collect, analyze, and visualize security events from both Windows and Linux systems.

The objective is to simulate a Security Operations Center (SOC) environment by centralizing logs, detecting suspicious activity, and providing dashboards that help analysts investigate potential security incidents.

The project includes data collection, log parsing, custom SPL queries, interactive dashboards, and threat detection use cases based on Windows Security Logs, Sysmon, and Linux authentication logs.

---

## Features

* Windows Security Event Monitoring
* Sysmon Process Monitoring
* Linux Authentication Monitoring
* Failed SSH Login Detection
* Root Login Detection
* User Account Monitoring
* Windows Login Monitoring
* PowerShell Monitoring
* Command Prompt Monitoring
* Living-off-the-Land Binary (LOLBins) Detection
* Threat Investigation Dashboard
* Interactive Splunk Dashboards
* SPL-based Threat Hunting Queries

---

## Data Sources

### Windows

* Windows Security Logs
* Microsoft Sysmon
* Microsoft Defender Events

### Linux

* auth.log
* systemd-journald
* SSH Logs

---

## Dashboards

### Windows Authentication Dashboard

* Successful Logins
* Failed Logins
* Administrative Logins
* Account Lockouts
* RDP Monitoring
* Login Timeline

### Windows Process Monitoring (Sysmon)

* Process Creation
* PowerShell Activity
* CMD Activity
* Parent-Child Process Relationships
* LOLBins Detection
* Recent Process Events

### Linux Monitoring

* SSH Failed Logins
* Root Login Detection
* User Creation Events
* Authentication Timeline

### Threat Detection Dashboard

* Suspicious PowerShell Activity
* Microsoft Defender Alerts
* Malware Detection
* Targeted Users
* Affected Hosts
* Investigation Table

---

## Technologies Used

* Splunk Free
* Universal Forwarder
* Sysmon
* Windows Event Logs
* Linux Authentication Logs
* SPL (Search Processing Language)

---

## Skills Demonstrated

* SIEM Deployment
* Log Management
* Windows Security Monitoring
* Linux Log Analysis
* Threat Hunting
* Security Event Correlation
* Dashboard Development
* Detection Engineering
* Incident Investigation

---

## Future Improvements

* MITRE ATT&CK Mapping
* Sigma Rule Integration
* Risk-Based Alerting
* Email Notifications
* Brute Force Detection
* Lateral Movement Detection
* Ransomware Detection
* Persistence Detection
* Network Traffic Monitoring
* Threat Intelligence Integration

---

## Author

Navin Maurya
Cybersecurity Student | SOC Analyst | Threat Detection | Splunk | Blue Team
