# 🔐 Web Security Testing with OWASP ZAP

## 📝Overview
This project demonstrates automated vulnerability scanning using [OWASP ZAP](https://www.zaproxy.org/). It focuses on detecting and analyzing common web application vulnerabilities in a controlled lab environment using Kali Linux:
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Cross-Site Request Forgery (CSRF)

In this exercise, I simulated how an attacker could gain unauthorized access to a Windows share (HR on MS10) by leveraging weak/reused credentials.

## 📌 Objectives

- Learn and apply OWASP ZAP for security assessments
- Identify common vulnerabilities in a sample web application
- Generate and interpret automated security reports

---

## 🛠️ Tools & Technologies

- **OWASP ZAP**: Security scanner for web apps
- **Python/JavaScript**: Used in test web app
- **Burp Suite**: Cross-checking findings
- **WebGoat/WebWolf**: A vulnerable web application for testing
## 🧩LAB STEPS
- The first step I took was to create a proxy server to build a connection between the OWASP ZAP and the incoming and outgoing traffic from the web application. This will display all the traffic flow for vulnerability analysis. For this process, I used FoxyProxy. I created a name for the proxy, the type of protocol to be used, the hostname, and an assigned port number.
- <img width="500" height="600" alt="proxy" src="https://github.com/user-attachments/assets/807277b8-73f1-4758-b5c5-8da68bebfdf5" />
- <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/96074d77-ae1c-45ee-8e29-c89e7317daa7" />
- <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/03ea7c3d-5a8f-40ee-8760-d65a5cd56889" />
- <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b5d45d80-a5bf-42fd-9d47-c4e09d61345c" />



---

## 🚀 Getting Started.........
