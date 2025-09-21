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

---
## 🧩LAB STEPS
## Set Up
- The first step I took was to create a proxy server to build a connection between the OWASP ZAP and the incoming and outgoing traffic from the web application (WEBGOAT/WEBWOLF). This will display all the traffic flow for vulnerability analysis. For this process, I used FoxyProxy. I created a name for the proxy, the type of protocol to be used, the hostname, and an assigned port number.
- Next, I ran the web application on Linux to complete the connection to receive network traffic from the Host and for this traffic to be displayed on the OWASP ZAP. 
- <img width="700" height="10000" alt="proxy" src="https://github.com/user-attachments/assets/807277b8-73f1-4758-b5c5-8da68bebfdf5" />
- <img width="660" height="400" alt="image" src="https://github.com/user-attachments/assets/dce5ff18-148a-4bdf-b81d-e7debf0a232a" />

## 🔎 Analyze Traffic
- The next step I took was to analyze incoming and outgoing traffic for vulnerabilities in the web application. 
- <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/96074d77-ae1c-45ee-8e29-c89e7317daa7" />
- <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/03ea7c3d-5a8f-40ee-8760-d65a5cd56889" />
## Task
- I completed hands-on tasks with WebGoat alongside scans in OWASP ZAP. Working through WebGoat’s labs helped me actively exploit and fix vulnerabilities so I really understand how attackers think — and how defenders respond.

-🔍 What I worked on (WebGoat tasks):

-  SQL Injection — crafting injection strings, observing data exfiltration, and validating parameterized queries.

-  Cross-Site Scripting (XSS) — identifying reflected and stored XSS and applying output encoding mitigations.

-  Broken Authentication & Session Management — testing login flows, session fixation, and improving session handling.

-  Cross-Site Request Forgery (CSRF) — exploiting state-changing requests and implementing anti-CSRF tokens.

-  Insecure Direct Object References / Broken Access Control — enumerating IDs, testing access checks, and enforcing authorization.

-  Insecure Deserialization — understanding how untrusted input can lead to remote code execution and how to mitigate it.

-  Security Misconfigurations — discovering default credentials, unnecessary services, and insecure headers.

- <img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/b5d45d80-a5bf-42fd-9d47-c4e09d61345c" />
- <img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/c9a3079b-d070-4378-86aa-7e4af9124531" />
- <img width="700" height="500" alt="image" src="https://github.com/user-attachments/assets/1e26ad9f-1610-40b5-aad5-69ea18589f51" />
---

## ✅ Key outcomes:

-Gained practical, repeatable steps to identify and reproduce common web vulnerabilities.

-Learned how to recommend concrete mitigations (input validation, least privilege, secure session cookies, CSP, etc.).

-Strengthened my investigative and remediation mindset — skills directly relevant to detection, triage, and incident response in a SOC.
##

I’m excited to apply these skills in real-world environments and continue my SOC Analyst journey.
