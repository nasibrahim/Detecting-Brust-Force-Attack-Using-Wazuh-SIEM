Detecting Brute Force Attack Using Wazuh SIEM

Introduction:
This project demonstrates how to detect brute force login attempts using Wazuh SIEM. A Windows machine was monitored using the Wazuh agent, and multiple failed login attempts were simulated to generate security alerts.

Tools Used:
Wazuh
Windows 11
VirtualBox

Setup:
Wazuh server was installed and configured on a virtual machine.
Wazuh agent was deployed on a Windows 11 system and successfully connected to the server.

Attack Simulation:
Multiple failed login attempts were generated using the runs command on Windows. This simulated a brute force attack where an attacker tries different passwords.

Detection:
Wazuh successfully detected the failed login attempts and generated alerts. These alerts included details such as username, timestamp, and source of the login attempt.

Findings:

The system detected repeated failed authentication attempts, indicating a possible brute force attack.
Conclusion:
Wazuh SIEM can effectively detect brute force attacks in real time, helping security analysts respond quickly to potential threats.
