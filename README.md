# SOC-Capstone-project-on-MediCore-Health-Systems
🛡️ Threat Detection in a Segmented Healthcare Network

Overview

This project showcases a complete Security Operations Center (SOC) workflow within a simulated healthcare environment. The objective was to strengthen the security posture of MediCore Health Systems by designing a segmented network, detecting malicious activity, and responding to security incidents using industry-standard cybersecurity tools.

Healthcare organizations manage highly sensitive patient information, making them attractive targets for cyberattacks. This capstone demonstrates how layered security controls, network segmentation, continuous monitoring, and threat detection can significantly reduce organizational risk.

---

Project Objectives

- Design a secure healthcare network architecture.
- Implement network segmentation using pfSense.
- Simulate real-world cyberattacks from Kali Linux.
- Capture and analyze malicious traffic using Wireshark.
- Detect and investigate security events with Wazuh SIEM.
- Recommend security improvements based on findings.

---

Technologies Used

- Draw.io
- pfSense
- Wazuh SIEM
- Ubuntu Server
- Kali Linux
- Wireshark
- Nmap

---

Project Workflow

Phase 1 – Network Design & Segmentation

Designed a secure healthcare network using Draw.io and implemented firewall policies in pfSense to isolate the WAN, LAN, and DMZ. This minimized lateral movement while protecting critical Electronic Health Record (EHR) systems.

Phase 2 – Attack Simulation & Traffic Analysis

Performed reconnaissance and authentication-based attacks using Kali Linux. Captured and analyzed network traffic with Wireshark to identify Indicators of Compromise (IoCs), suspicious communication, and attacker behavior.

Phase 3 – Security Monitoring & Incident Response

Monitored security events with Wazuh SIEM, correlated alerts with packet captures, investigated suspicious activities, and developed an incident timeline to support response actions.

---

Key Findings

- Identified overly permissive firewall rules.
- Detected unauthorized reconnaissance activities.
- Observed repeated authentication failures.
- Demonstrated how poor segmentation increases the risk of lateral movement and exposure of Protected Health Information (PHI).

---

Security Recommendations

- Implement least-privilege firewall policies.
- Harden SSH and EHR servers.
- Tune SIEM detection rules to reduce false positives.
- Develop incident response playbooks.
- Perform continuous monitoring and regular patch management.
- Strengthen healthcare cybersecurity awareness and training.

---

Skills Demonstrated

- Security Operations Center (SOC) Operations
- Threat Detection & Incident Response
- Network Segmentation
- Firewall Administration
- SIEM Monitoring
- Packet Analysis
- Log Correlation
- Network Traffic Investigation
- Vulnerability Assessment
- Cybersecurity Documentation

---

Key Takeaway

This project reinforced the importance of defense-in-depth within healthcare environments. By combining network segmentation, firewall controls, packet analysis, and SIEM monitoring, security teams can detect, investigate, and contain threats before they compromise critical patient data or healthcare services.

---

⭐ If you found this project interesting, feel free to explore the repository, leave feedback, or connect with me to discuss cybersecurity, SOC operations, and threat detection.
