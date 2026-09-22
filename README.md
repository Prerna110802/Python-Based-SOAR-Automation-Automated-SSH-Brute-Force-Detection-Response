# Python-Based SOAR Automation

## 📌 Project Overview

This project demonstrates a lightweight **SOAR-inspired automated incident response workflow** using Python, Ubuntu SSH logs, and the UFW firewall.

The system detects repeated failed SSH login attempts, identifies the source IP address, and automatically blocks the suspicious IP when the defined threshold is reached.

## 🛠️ Technologies Used

* Python 3
* Ubuntu Linux
* Kali Linux
* SSH / OpenSSH
* UFW Firewall
* Linux `journalctl` logs

## 🔄 Workflow

**Kali Linux**
↓
Multiple Failed SSH Login Attempts
↓
**Ubuntu SSH Logs**
↓
**Python Detection Script**
↓
3 Failed Attempts Detected
↓
**Automatic UFW IP Block**
↓
**Response Log Generated**

## ⚙️ Key Features

* Monitors recent SSH authentication logs
* Detects repeated failed login attempts
* Extracts the source IP address
* Uses a threshold of 3 failed attempts
* Automatically blocks the suspicious IP using UFW
* Records the response action in `response.log`

## 📂 Project Files

```text
python-soar-ssh-automation/
│
├── soar_response.py
├── response.log
├── README.md
│
└── screenshots/
    ├── 01-kali-failed-ssh.png
    ├── 02-ubuntu-ssh-logs.png
    ├── 03-soar-detection-response.png
    └── 04-automated-response-evidence.png
```

## 📸 Project Evidence

### 1. Kali – Failed SSH Login Attempt

![Kali Failed SSH](screenshots/01-kali-failed-ssh.png)

### 2. Ubuntu – SSH Logs

![Ubuntu SSH Logs](screenshots/02-ubuntu-ssh-logs.png)

### 3. SOAR Detection & Automated Response

![SOAR Detection](screenshots/03-soar-detection-response.png)

### 4. Automated Response Evidence

![Automated Response](screenshots/04-automated-response-evidence.png)

## 🎯 Learning Outcome

This project demonstrates practical understanding of **security monitoring, log analysis, SSH brute-force detection, firewall-based response, and security automation** in a controlled lab environment.

## ⚠️ Disclaimer

This project was created in a controlled home lab environment for **cybersecurity learning and defensive security automation**.


