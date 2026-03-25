# Active Directory Home Lab

## Objective
[Brief Objective - Remove this afterwards]

The purpose of this project is to build a simulated business environment using Active Directory, Splunk, and Kali Linux to gain hands-on experience in system administration and cybersecurity. This lab was designed to provide real-world scenarios by configuring a domain, generating security events, and monitoring activity through a SIEM for threat detection. The end goal is to develop practical skills in both defensive and offensive security by analyzing attack behavior and improving detection skills in a controlled environment.

### Skills Learned
[Bullet Points - Remove this afterwards]

- Configuration and management of an Active Directory domain environment.
- Construction and networking of multiple virtual machines.
- Deployment and configuration of a SIEM for security monitoring.
- Simulation of real-world cyber attacks and analysis of resulting telemetry.
- Ability to detect and investigate security events such as failed and successful login attempts.
- Troubleshooting and problem-solving skills.

### Tools Used
[Bullet Points - Remove this afterwards]

- VirtualBox for creation of virtual machines.
- Windows Server (Active Directory Domain Services) for configuration of the Domain Controller.
- Windows 10 / Client Machine for generating logs and simulating user activity.
- Splunk Enterprise (SIEM) for centralizing log collections and security event analysis.
- Splunk Universal Forwarder for sending logs to the Splunk server for monitoring.
- Sysmon (System Monitor) for generating endpoint telemetry for security analysis.
- Kali Linux for simulating real-world cyber attacks against the environment.

## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*

Step 1
  - Created a network diagram to map out the lab environment and show how the machines would connect.
     
    
Step 2
  - Set up the virtual lab in VirtualBox by creating the Windows Server.    
    
Step 3
  - Configured the network by setting up the NAT network, assigning IP addresses, and making sure the systems could communicate.
    
Step 4
  - Installed and configured Active Directory by promoting the Windows Server to a Domain Controller and creating the domain environment.
  - active directory/domain controller pic
    
Step 5
  - Created and managed users and systems inside Active Directory, including joining the Windows client to the domain.
  - test users pic
    
Step 6
  - Set up logging and monitoring with Splunk, the Universal Forwarder, and Sysmon to capture activity from the environment.
  - splunk pic
    
Step 7
  - Simulated an attack from Kali Linux, such as an RDP brute-force attempt, to generate security events.
  - show hydra pic
    
Step 8
  - Reviewed and analyzed the logs in Splunk to detect the attack activity and understand what happened.
  - show siem pic
    
Step 9
  - Troubleshot issues such as DNS, connectivity, authentication, and log forwarding to keep the lab functioning properly.
