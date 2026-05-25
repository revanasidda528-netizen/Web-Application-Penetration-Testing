**Submitted by:Revanasidda.VH**

**Course:B.Tech CSE**

**College:JSPM UNIVERSITY PUNE**

**Introduction:**

Web applications are widely used in modern systems for online shopping, banking, education, and communication. Many web applications contain security weaknesses that attackers can exploit. Penetration testing helps identify such vulnerabilities before attackers misuse them.

OWASP ZAP (Zed Attack Proxy) is a popular open-source security testing tool used by cybersecurity professionals and beginners for finding vulnerabilities in web applications.

**Objectives:**

To learn web application penetration testing

To understand common web vulnerabilities

To perform vulnerability scanning using OWASP ZAP

To analyze security risks in web applications

To generate a security testing report

Tools and Technologies Used

**Tool Used:**

Java JRE/JDK

OWASP ZAP

**About OWASP ZAP:**

OWASP ZAP is an open-source web application security scanner developed by OWASP (Open Web Application Security Project). It helps security testers identify vulnerabilities in web applications using automated and manual testing methods.

About OWASP Juice Shop

OWASP Juice Shop is a deliberately vulnerable web application designed for security training and penetration testing practice. It contains multiple security flaws for learning purposes.

Demo Website:demo.owasp-juice.shop

**Methodology:**

The following methodology was followed during the project:

Install Java

Install OWASP ZAP

Configure browser proxy

Open demo website

Perform passive scanning

Run active scanning

Analyze vulnerabilities

Generate report

**Implementation Steps:**

Step 1: Install Java

Java Runtime Environment (JRE) was installed because OWASP ZAP requires Java to run.

Command used for verification:

Bash

java -version

Step 2: Install OWASP ZAP

OWASP ZAP installer was downloaded and installed successfully.

Official Website:

&#x20;

zaproxy.org

Step 3: Launch OWASP ZAP

The application was opened and a new session was created.

Step 4: Open Demo Website

The OWASP Juice Shop demo website was opened inside the ZAP browser.

Step 5: Passive Scanning

Passive scanning was performed by browsing the application pages. ZAP automatically analyzed requests and responses.

Step 6: Active Scanning

An active scan was launched on the target demo website.

The scan tested:

SQL Injection

Cross-Site Scripting (XSS)

Broken Authentication

Missing Security Headers

**Vulnerabilities Identified:**

1\. Cross-Site Scripting (XSS)

Description:

XSS occurs when malicious scripts are injected into web pages.

Risk Level:

Medium

Impact:

Attackers can steal user sessions and manipulate webpages.

Prevention:

Input validation

Output encoding

Content Security Policy

2\. SQL Injection

Description:

SQL Injection allows attackers to manipulate database queries.

Risk Level:

High

Impact:

Sensitive database information may be exposed.

Prevention:

Parameterized queries

Prepared statements

Input sanitization

3\. Missing Security Headers

Description:

Some HTTP security headers were missing.

Risk Level:

Low

Impact:

Can increase vulnerability to attacks.

Prevention:

Add headers such as:

Content-Security-Policy

X-Frame-Options

X-Content-Type-Options

**Results:**

The penetration testing process successfully identified multiple vulnerabilities in the demo web application. OWASP ZAP provided detailed alerts and risk levels for each issue.

The project improved understanding of:

Web application security

Vulnerability assessment

Ethical hacking basics

Security testing tools

**Advantages of Penetration Testing:**

Helps identify vulnerabilities

Improves application security

Prevents cyber attacks

Enhances user trust

Supports secure software development

**Limitations:**

Testing was performed only on a demo application

Some vulnerabilities require manual verification

Real-world applications may have additional protections

**Conclusion:**

This project demonstrated the process of web application penetration testing using OWASP ZAP. The testing identified common vulnerabilities such as XSS, SQL Injection, and security misconfigurations. The project provided practical knowledge of ethical hacking and web security testing in a controlled environment.
