Project Title : SOC Lab using Wazuh SIEM (Attack Detection Project)

Description :-
This project demonstrates the setup of a complete Security Operations Center (SOC) lab using Wazuh SIEM to monitor system activity, collect logs, and detect security threats in real time.
The system is built using a virtualized environment where an Ubuntu Server (22.04) acts as the Wazuh server and a Windows machine acts as the monitored endpoint (agent). The Wazuh server collects logs from the agent, analyzes them using predefined and custom rules, and generates alerts that are visualized in the dashboard.

The workflow of the system :-
-The Windows machine generates logs (login attempts, system activity, etc.)
-The Wazuh agent installed on Windows collects these logs
-Logs are securely sent to the Wazuh Manager running on Ubuntu
-The manager analyzes logs using detection rules
-Alerts are generated for suspicious activities
-Data is stored in the indexer and visualized in the dashboard

Use of this project :-
-Monitor endpoint activity in real time
-Detect brute-force attacks and unauthorized access
-Analyze security logs centrally
-Understand how SIEM tools work in real environments
-Practice SOC analyst skills

Attack Simulation & Detection :-
-Multiple failed login attempts were generated on the Windows machine
-This simulates a brute-force attack
-Wazuh detected repeated authentication failures
-Alerts were triggered and visible in the dashboard

What I Did :-
-Installed Wazuh SIEM on Ubuntu
-Configured Windows agent
-Collected logs (system, authentication)
-Created custom detection rules
-Simulated brute-force attack (multiple failed logins)
-Wazuh detected and generated alerts
-Logs visualized in dashboard

Results :-
-Detected unauthorized login attempts
-Real-time alerts generated for suspicious activities
-Logs successfully collected from Windows agent
-Attack patterns (failed logins) identified
-Dashboard visualization of security events

Why This Project :-
-This project shows practical understanding of:
-SIEM tools used in real companies
-Log analysis and threat detection
-SOC workflow and monitoring
-Cybersecurity fundamentals beyond theory

Tools Used :-
-Wazuh
-Elasticsearch
-Kibana
-Ubuntu Server 22.04
-Windows 10
