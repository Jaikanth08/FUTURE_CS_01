# FUTURE_CS_01

# 🛡️ Future Interns – Task 1 (Cyber Security Track)

## 🔍 Task: Web Application Security Testing
This repository contains my submission for **Task 1** under the **Cyber Security Internship** offered by **Future Interns**.

### ✅ Objective
To identify and document common web application vulnerabilities in **OWASP Juice Shop**, including:
- SQL Injection
- Authentication Flaws
- Cross-Site Scripting (XSS)

---

## 🧪 Vulnerabilities Identified

### 1. SQL Injection – Authentication Bypass
- Bypassed login using:
Email: ' OR 1=1--
Password: anything
- Successfully accessed user area without credentials.

### 2. Authentication Flaw – Default Admin Credentials
- Used credentials:
Email: admin@juice-sh.op
Password: admin123

- Gained admin-level access.

### 3. Cross-Site Scripting (XSS)
- Attempted Stored XSS via Feedback and Product Reviews
- Inputs were stored but sanitized by the app
- No script execution observed

---

## 🧰 Tools Used

- **OWASP Juice Shop** (target application)
- **Burp Suite** (interception and manipulation)
- **Firefox** (browser)
- **Kali Linux VM** (testing environment)
- **Git & GitHub** (documentation)

---

## 📁 Files in this Repository

- `report/Task1_Report.docx` – Full vulnerability report
- `screenshots/` – Proof-of-concept images from tests
- `README.md` – This file

---

## 📢 Note
This task was completed as part of a self-paced internship with Future Interns (Track Code: CS). The findings and documentation are entirely original and demonstrate understanding of common web security testing techniques.


