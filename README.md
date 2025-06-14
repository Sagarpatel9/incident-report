# 🛡️ SecureTech Cybersecurity Incident Response  
**Phishing-Based Credential Theft – February 2025**  
_CPSC 455 – Web Security (Spring 2025)_

This project simulates a real-world incident response case involving a phishing and credential theft attack at **SecureTech Solutions**. It was completed individually as part of the **CPSC 455 – Web Security** course.

---

## 📄 🔥 Main Deliverable: [Incident_respond.docx](Incident_respond.docx)

This is the **executive-level incident report**, written to document:
- Attack timeline
- Indicators of compromise
- Financial impact (~$5,900)
- Response actions taken
- Lessons learned

It’s designed for stakeholders including executive leadership, legal, and IT security management.

---

## 🧠 Project Background

As an employee in the SecureTech Solutions SOC, you receive a report from an employee who believes they've received a phishing message from an internal user:


> **From:** Jason Robinson `<jrobinson@securetech.com>`  
> **To:** Stephanie Morgan `<smorgan@securetech.com>`  
> _"You have one (1) new message"_  
> 🔗 **Click here:** [srv-61.kim.johnson.biz/login]

You are provided access to:
- HTTP metadata logs
- Email logs
- Internal user inventory

Your task is to:
1. Analyze the data to determine what happened and when
2. Document your findings in a formal **Incident Report**
3. Provide a supporting **Investigation Log** with technical evidence and methodology

---

## 🗂️ Supporting Files (`/content` folder)

These files support the findings and recommendations presented in the main report:

### 🔍 Provided Log Data
- `http.log` – Web server metadata
- `mail.log` – Email activity logs
- `inventory.csv` – Internal user/device/IP mapping

These logs were used to trace account compromises, IP behavior, and attacker movement across the system.

### 🧪 My Investigation Artifacts
- `investigation_log.docx` – Full forensic walkthrough:
  - Log queries and patterns
  - IP tracking and HTTP method analysis
  - Attack timeline reconstruction


---

## 💼 Skills Demonstrated

- 🔍 **Log analysis & pattern detection**
- 🛠 **Incident response and containment planning**
- 🔐 **Web-layer threat understanding (HTTP misuse)**
- 📄 **Executive and technical documentation**
- 🧠 **Analytical thinking under simulated pressure**

---

## 🧑‍💼 Note: 

This project was designed to simulate a real-world security incident and demonstrate the end-to-end workflow of a SOC analyst:
- Evidence gathering
- Forensics
- Stakeholder reporting
- Risk communication

Feel free to review the [main report](Incident_respond.docx) and [investigation_log.docx](content/investigation_log.docx) to assess both technical and communication skills.

---

## ⚠️ Important Notice

> **This is a simulated academic project.**  
> All IPs, URLs (e.g., `srv-61.kim.johnson.biz`), and emails used are fictional and for instructional purposes only.

> 🚫 **Do not visit any links** or interact with any domains mentioned in the report. They may be inactive or unsafe.

---

📎 Developed as an individual assignment for **CPSC 455 – Web Security (Spring 2025)**
