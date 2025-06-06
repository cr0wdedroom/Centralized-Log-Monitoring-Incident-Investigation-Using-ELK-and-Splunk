# Centralized-Log-Monitoring-Incident-Investigation-Using-ELK-and-Splunk

This is a centralized log monitoring and incident response project that utilizes the ELK Stack and Splunk to provide visibility into Windows endpoint activity in a simulated SOC environment. Logs from a Windows 11 ARM VM are collected, parsed, and analyzed using custom dashboards and detection logic, while attacker behavior is simulated from a Kali Linux VM to generate real-world security telemetry.

🛡️Project Objectives:

Deploy a centralized log monitoring lab using ELK Stack (via Docker) and Splunk Cloud.

Forward Windows logs (Sysmon + Event Logs) to ELK and Splunk for analysis and visualization.

Simulate real-world attacks from Kali (e.g., brute-force logins, suspicious PowerShell commands).

Create dashboards and write detection queries to surface anomalous behaviors and attack chains.

Showcase core SOC skills: log forwarding, detection engineering, dashboarding, and incident investigation.
