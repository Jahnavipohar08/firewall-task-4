# Task 4 – Setup and Use a Firewall (Windows)

## 📌 Overview
This project demonstrates the configuration and testing of basic firewall rules on a Windows system as part of a **Cyber Security Internship**.  
The objective is to understand how firewalls filter network traffic by allowing or blocking communication based on predefined security rules.

---

## 🎯 Objective
- Configure Windows Firewall to control inbound network traffic
- Block an insecure service port (Telnet – Port 23)
- Test and validate firewall behavior
- Restore the firewall to its original state
- Document the complete process

---

## 🛠 Tools & Technologies
- **Operating System:** Windows 10 / Windows 11  
- **Firewall:** Windows Defender Firewall  
- **Terminal:** PowerShell / Command Prompt  
- **Editor:** Visual Studio Code  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure
firewall-task-4/
│
├── README.md
├── firewall_steps.txt
├── commands_used.txt
└── screenshots/
├── firewall_rules_before.png
├── block_port_23.png
└── remove_rule.png

yaml
Copy code

---

## 🔧 Firewall Configuration Steps

### 1. Verify Firewall Status
Checked whether Windows Defender Firewall is enabled for all profiles.

### 2. View Existing Firewall Rules
Listed all inbound and outbound firewall rules to understand the current configuration.

### 3. Block Inbound Traffic on Port 23 (Telnet)
Created a firewall rule to block **TCP inbound traffic on port 23**, which is commonly used by Telnet and is considered insecure due to lack of encryption.

### 4. Test the Firewall Rule
Attempted to connect to port 23 locally to verify that the firewall rule successfully blocked the connection.

### 5. Remove Test Rule
Deleted the firewall rule after testing to restore the system to its original configuration.

---

## 🚫 Why Block Port 23 (Telnet)?
Telnet transmits data in **plain text**, including usernames and passwords, making it vulnerable to interception and man-in-the-middle attacks.  
Blocking this port helps reduce exposure to common network-based threats.

---

## 📸 Evidence
Screenshots showing:
- Existing firewall rules
- Successful blocking of port 23
- Removal of the firewall rule

(All screenshots are included in the `screenshots` folder.)

---

## 📘 Key Concepts Learned
- Firewall rule creation and management
- Inbound vs outbound traffic filtering
- Port-based access control
- Importance of disabling insecure services
- Basic Windows firewall administration

---

## ✅ Outcome
Successfully configured and tested firewall rules, gaining hands-on experience in **network traffic filtering and system security hardening**.

---

## 👩‍💻 Author
**Jahanavi Pohar**  
Cyber Security Intern
