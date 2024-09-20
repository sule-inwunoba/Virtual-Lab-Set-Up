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
https://github.com/user-attachments/assets/33df9cc3-4fc2-4577-be1d-654a9a0e13b0
![Screenshot 2024-09-20 120204](https://github.com/user-attachments/assets/fae9a636-b38e-4331-81c3-2e2264243bd0)


   Ref 1: Network Diagram
3. Firewall Configuration: Deployed OPNSense + Zenarmor to manage traffic and monitor for suspicious behavior.

   Ref 2: OPNSense Firewall Configuration
4. SIEM Deployment (Wazuh): Installed and configured Wazuh for log aggregation and real-time analysis.

   Ref 3: Wazuh SIEM Dashboard
6. Penetration Testing (Kali Linux): Simulated attacks to test system vulnerabilities and monitor logs.

   Ref 4: Kali Linux Attack Simulation
8. Log Analysis: Ingested logs from Windows 10 and Ubuntu systems into Wazuh for threat detection.
    Ref 5: Log Ingestion and Event Correlation
