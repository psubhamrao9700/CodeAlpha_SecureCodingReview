# 🔐 Secure Coding Review

## 🛡️ CodeAlpha Cyber Security Internship Project

This project was developed as part of the **CodeAlpha Cyber Security Internship**. The objective of this project is to review a Python login application, identify security vulnerabilities, analyze potential risks, and recommend secure coding practices to improve application security.

---

## 📖 Project Overview

Secure coding is an essential part of cybersecurity. Poor coding practices can introduce vulnerabilities that attackers may exploit to gain unauthorized access, steal data, or compromise systems.

This project reviews a simple Python login application and highlights common security weaknesses along with recommended solutions.

---

## 🎯 Objectives

✅ Identify security vulnerabilities in source code

✅ Understand common coding mistakes

✅ Analyze security risks

✅ Recommend secure coding practices

✅ Improve application security awareness

---

## 📂 Project Files

* 📄 vulnerable_login.py
* 📄 security_findings.txt
* 📄 README.md

---

## 💻 Vulnerable Code Example

The reviewed application contains a simple login system with hardcoded credentials.

### Issues Found:

* Hardcoded username and password
* Plain text password storage
* No password hashing
* No login attempt restriction
* Missing input validation

---

## 🚨 Security Vulnerabilities Identified

### 1️⃣ Hardcoded Credentials

**Issue:**
Username and password are directly stored inside source code.

**Risk:**
Anyone with access to the code can view sensitive credentials.

---

### 2️⃣ Plain Text Password Storage

**Issue:**
Passwords are stored without encryption.

**Risk:**
Passwords can be exposed if the source code is leaked.

---

### 3️⃣ Lack of Password Hashing

**Issue:**
No hashing mechanism is implemented.

**Risk:**
Attackers can easily read stored passwords.

---

### 4️⃣ No Login Attempt Restriction

**Issue:**
Unlimited login attempts are allowed.

**Risk:**
Makes brute-force attacks possible.

---

### 5️⃣ Missing Input Validation

**Issue:**
User input is not validated.

**Risk:**
Unexpected or malicious input may be accepted.

---

## ✅ Recommended Security Improvements

🔹 Use password hashing (bcrypt, SHA-256)

🔹 Store credentials securely

🔹 Implement Multi-Factor Authentication (MFA)

🔹 Validate user inputs

🔹 Apply strong password policies

🔹 Limit login attempts

🔹 Follow secure coding standards

---

## 📸 Project Screenshots

### 1️⃣ Vulnerable Login Code

![Vulnerable Login Code](vulnerable-login-code.png)

### 2️⃣ Security Findings Analysis

![Security Findings](security-findings.png)

---

## 🛠️ Tools Used

* 🐍 Python
* 💻 Visual Studio Code / Notepad
* 🐙 GitHub
* 🔐 Cyber Security Concepts

---

## 📊 Review Summary

| Security Issue               | Risk Level |
| ---------------------------- | ---------- |
| Hardcoded Credentials        | High       |
| Plain Text Passwords         | High       |
| Missing Password Hashing     | High       |
| No Login Attempt Restriction | Medium     |
| Missing Input Validation     | Medium     |

---

## 🚀 Project Outcome

This project successfully identified multiple security weaknesses within a Python login application. By reviewing the code and recommending security improvements, the project demonstrates the importance of secure coding practices in software development.

---

## 👨‍💻 Developed By

** P Subham Rao**

CodeAlpha Cyber Security Internship
