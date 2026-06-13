# Task 10: Detailed Security Assessment Report for a Network

This repository contains the submission deliverables for Task 10 of the Oasis Infobyte Cybersecurity Internship. The objective of this project is to conduct a local network security assessment using network scanning and packet analysis tools.

## 📋 Project Objective
* Perform a network infrastructure scan to discover active hosts and open ports.
* Capture and analyze active network traffic.
* Identify potential security flaws, misconfigurations, or software vulnerabilities.

## 🛠️ Tools Used
* **Nmap:** Used for network discovery, port status checking, service version detection, and OS fingerprinting.
* **Wireshark:** Used to capture live TCP/IP network packets during the active scanning phase.
* **Operating System:** Kali Linux

## 📂 Repository Contents & Deliverables
This repository contains the following three mandatory files required for evaluation:

1. **`network_security_assessment.md`**: The official detailed security assessment report. It breaks down the executive summary, vulnerabilities found (Apache version disclosure), and remediation steps.
2. **`nmap_result.txt`**: The raw text output generated directly from the Nmap CLI scanner targeting the host.
3. **`wireshark_capture.pcap`**: The packet capture data file recording the exact network traffic interaction during the probe.

## 🔍 Key Findings Summary
* **Target Scanned:** 127.0.0.1 (Localhost)
* **Open Ports:** Port 80/tcp (HTTP)
* **Active Service:** Apache httpd 2.4.66 running on a Debian Linux kernel.
* **Primary Risk:** The web server publicly broadcasts its exact software version banner. This allows potential attackers to look up known CVEs to target the system.

---

## 👤 Intern Information
* **Name:** [Akshita Sunil Avadhan]
* **Domain:** Cybersecurity Internship
* **Task Number:** Task 10
* **Batch:** [JUNE 15 2026 - JULY 15 2026]
