# Python-Based SOAR Automation

## 📌 Description

A lightweight SOAR-inspired security automation project that detects repeated SSH failed login attempts and automatically blocks the source IP using UFW.

## 🛠️ Tools Used

* Python
* Ubuntu Linux
* Kali Linux
* SSH
* UFW Firewall

## 🔄 Workflow

**Kali → Failed SSH Attempts → Ubuntu Logs → Python Detection → UFW IP Block → Response Log**

## 📂 Files

* `soar_response.py` – Detection and automated response script
* `response.log` – Response activity log
* `screenshots/` – Project evidence

## 📸 Evidence

### 1. Kali – Failed SSH Login

![Kali](screenshots/01-kali-failed-ssh.png)

### 2. Ubuntu – SSH Logs

![SSH Logs](screenshots/02-ubuntu-ssh-logs.png)

### 3. SOAR Detection & Response

![SOAR Detection](screenshots/03-soar-detection-response.png)

### 4. Automated Response Evidence

![Response](screenshots/04-automated-response-evidence.png)

