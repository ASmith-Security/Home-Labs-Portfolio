
# 🔍 Nmap Reconnaissance Simulation

## 🎯 Objective

Simulate attacker reconnaissance using Nmap from Kali Linux and analyze whether activity is detected by Wazuh.

---

## 🖥️ Environment

- **Attacker:** Kali Linux
- **Target:** Windows Server (DC01)
- **SIEM:** Wazuh
- **Network:** Internal lab network

---

## 🛠️ Tools Used

- Nmap
- Kali Linux
- Wazuh SIEM
- Windows Server (DC01)

---

## ⚙️ Steps Performed

1. Logged into Kali Linux attacker machine
2. Identified target IP address (DC01)
3. Executed Nmap SYN scan against target network:

```bash
nmap -sS 192.168.250.8/24
