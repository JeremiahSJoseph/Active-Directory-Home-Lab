# Active Directory Home Lab

## Objective

The purpose of this project is to build a simulated business environment using Active Directory, Splunk, and Kali Linux to gain hands-on experience in system administration and cybersecurity. This lab was designed to provide real-world scenarios by configuring a domain, generating security events, and monitoring activity through a SIEM for threat detection. The end goal is to develop practical skills in both defensive and offensive security by analyzing attack behavior and improving detection skills in a controlled environment.

### Skills Learned

- Configuration and management of an Active Directory domain environment.
- Construction and networking of multiple virtual machines.
- Deployment and configuration of a SIEM for security monitoring.
- Simulation of real-world cyber attacks and analysis of resulting telemetry.
- Ability to detect and investigate security events such as failed and successful login attempts.
- Troubleshooting and problem-solving skills.

### Tools Used

- VirtualBox for creation of virtual machines.
- Windows Server (Active Directory Domain Services) for configuration of the Domain Controller.
- Windows 10 / Client Machine for generating logs and simulating user activity.
- Splunk Enterprise (SIEM) for centralizing log collections and security event analysis.
- Splunk Universal Forwarder for sending logs to the Splunk server for monitoring.
- Sysmon (System Monitor) for generating endpoint telemetry for security analysis.
- Kali Linux for simulating real-world cyber attacks against the environment.

## Steps

Step 1
  - Created a network diagram to map out the lab environment and show how the machines would connect.
    
Step 2
  - Set up the virtual lab in VirtualBox by creating four VMs: Windows (target), Windows Server (AD), Splunk, Kali Linux (Penetrator).
        
Step 3
  - Configured the network by setting up the NAT network, assigning IP addresses, and making sure the systems could communicate.
    
Step 4
  - Installed and configured Active Directory by promoting the Windows Server to a Domain Controller and creating the domain environment.
    
Step 5
  - Created and managed users and systems inside Active Directory, including joining the Windows client to the domain.
    
Step 6
  - Set up logging and monitoring with Splunk, the Universal Forwarder, and Sysmon to capture activity from the environment.
    
Step 7
  - Simulated an attack from Kali Linux, such as an RDP brute-force attempt, to generate security events.
    
Step 8
  - Reviewed and analyzed the logs in Splunk to detect the attack activity and understand what happened.
    
Step 9
  - Troubleshot issues such as DNS, connectivity, authentication, and log forwarding to keep the lab functioning properly.

## References

*Ref 1: Network Diagram*

<img width="692" height="722" alt="image" src="https://github.com/user-attachments/assets/34486a20-626c-47d4-93b9-a570e911ec7e" />


*Ref 2: VM Setup*

<img width="1010" height="634" alt="image" src="https://github.com/user-attachments/assets/ecd9ef07-65b3-4951-81f6-e470176e391c" />


*Ref 3: Network Configuration*

<img width="1128" height="868" alt="image" src="https://github.com/user-attachments/assets/a371fc34-2b2b-47c1-8c51-db9f95614dc9" />


*Ref 4: Active Directory Configuration*

<img width="998" height="772" alt="image" src="https://github.com/user-attachments/assets/3048938f-2e06-4d2f-9e66-e00ea985ef58" />


*Ref 5: User Management*

<img width="1018" height="734" alt="image" src="https://github.com/user-attachments/assets/3f00df03-d978-45ce-9ef6-ab1fdcd23a0f" />


*Ref 6: Splunk-Server Configuration*

<img width="952" height="762" alt="image" src="https://github.com/user-attachments/assets/2eea2367-92e8-4b10-90b3-678def5171bf" />


*Ref 7: Kali Linux Brute-Force Attack*

<img width="964" height="782" alt="image" src="https://github.com/user-attachments/assets/9d2acfc9-4371-4011-b3b5-30fcafa76d77" />


*Ref 8: SIEM Monitoring*

<img width="988" height="642" alt="image" src="https://github.com/user-attachments/assets/b2e230a2-69fd-431c-841e-3251b15bf14f" />

