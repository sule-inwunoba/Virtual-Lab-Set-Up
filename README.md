# Virtual Lab Setup: Multi-OS Cybersecurity Environment

## Objective

The Virtual Lab project aimed to establish a controlled, multi-operating system environment to simulate cyber attacks, detect threats, and enhance understanding of security operations. This environment focused on ingesting and analyzing logs through a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. The goal was to deepen knowledge of network security, attack vectors, and defensive strategies using various virtual machines (Kali Linux, Ubuntu, Wazuh, OPNSense, and Windows 10).


### Skills Learned

- Proficient use of SIEM (Wazuh) for log ingestion, correlation, and threat detection.
- Ability to configure firewalls (OPNSense) to control traffic and detect anomalies.
- Advanced understanding of attack patterns using Kali Linux for penetration testing.
- Expertise in network traffic analysis and interpretation with Wireshark.
- Practical experience in endpoint security with Windows 10 configurations.
- Developed critical thinking and problem-solving skills in complex cybersecurity environments.

### Tools Used

- SIEM (Wazuh): For log collection, monitoring, and threat detection.
- OPNSense: Firewall configuration and network traffic management.
- Kali Linux: Penetration testing and generating attack scenarios.
- Wireshark: Capturing and analyzing network traffic.
- Ubuntu: As a general-purpose system for running services and analyzing security configurations.
- Windows 10: Endpoint for testing security configurations and monitoring events.

## Steps
1. Virtual Machine Setup: Created and configured VMs for Kali Linux, Ubuntu, Wazuh, OPNSense, and Windows 10.

![Screenshot 2024-09-20 120204](https://github.com/user-attachments/assets/fae9a636-b38e-4331-81c3-2e2264243bd0)

Ref 1: Network Diagram

2. Firewall Configuration: Deployed OPNSense + Zenarmor to manage traffic and monitor for suspicious behavior.
![VirtualBox_OPNsense Firewall_20_09_2024_12_09_43](https://github.com/user-attachments/assets/83479e7d-0303-4af1-82cf-b5dc4e36b8e4)
![VirtualBox_KaliLinux2024 2_20_09_2024_12_55_47](https://github.com/user-attachments/assets/57aa429f-b96f-4b98-8f93-67265024ddf0)
![VirtualBox_KaliLinux2024 2_20_09_2024_12_54_49](https://github.com/user-attachments/assets/f2fc4667-f68f-4b1e-ad99-85756b8bfd97)

Ref 2: OPNSense Firewall Configuration

3. SIEM Deployment (Wazuh): Installed and configured Wazuh for log aggregation and real-time analysis.
![VirtualBox_KaliLinux2024 2_20_09_2024_13_00_49](https://github.com/user-attachments/assets/50bd5d4b-a31e-4aa4-aa89-f5365b6727b8)

Ref 3: Wazuh SIEM Dashboard

4. Log Analysis: Ingested logs from Windows 10 and Ubuntu systems into Wazuh for threat detection.
![VirtualBox_KaliLinux2024 2_20_09_2024_13_04_15](https://github.com/user-attachments/assets/030790e0-1198-43ac-b326-5569b73c1546)
![VirtualBox_KaliLinux2024 2_20_09_2024_13_05_47](https://github.com/user-attachments/assets/4d14dfb2-d9a8-4300-8cf6-4f065204a623)

Ref 4: Log Ingestion and Event Correlation
