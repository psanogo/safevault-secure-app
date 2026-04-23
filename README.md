# 🔐 SafeVault Secure Application

SafeVault is a security-focused web application developed to demonstrate secure coding practices, including safe input handling, authentication, authorization, and vulnerability mitigation.

---

## 📘 Project Overview

This project was created as part of a secure software development assignment. The application was intentionally reviewed and hardened against common security threats such as SQL injection and cross-site scripting (XSS).

---

## 🚨 Identified Vulnerabilities

- SQL Injection through unsanitized database queries
- Cross-Site Scripting (XSS) via unvalidated user input
- Unauthorized access due to missing role enforcement

---

## 🛠️ Security Fixes Implemented

- Parameterized SQL queries to prevent injection attacks
- Input validation and output encoding to mitigate XSS
- Secure authentication with password hashing
- Role-Based Access Control (RBAC) for authorization enforcement

---

## ✅ Security Testing

Automated test cases were implemented to validate:
- Resistance to SQL injection attacks
- Prevention of unauthorized access
- Proper handling of invalid or malicious input

All tests passed successfully, confirming the effectiveness of the applied security controls.

---

## 🤖 Role of Microsoft Copilot

Microsoft Copilot assisted with:
- Identifying vulnerable code patterns
- Suggesting secure coding practices
- Refactoring unsafe logic
- Generating security-focused test cases

Copilot improved development efficiency while reinforcing security best practices.

---

## 📌 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/safevault-secure-app
