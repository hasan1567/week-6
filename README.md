## Week 6: Final Security Audit, Compliance, and Penetration Testing (May 13–14, 2025)

### ✅ Task 1: OWASP ZAP Vulnerability Scan
- Performed an automated web vulnerability scan on the NodeGoat app using **OWASP ZAP**.
- Identified common issues such as missing security headers, cookie flags, and outdated libraries.
- Documented all findings and categorized them based on severity (High, Medium, Low).
- Mitigation strategies were applied where applicable (e.g., adding security headers like `X-Content-Type-Options`, `X-Frame-Options`, and `Content-Security-Policy`).

### ✅ Task 2: Nikto Web Server Scan
- Used **Nikto** to assess the web server for known vulnerabilities and misconfigurations.
- Detected server banners, insecure HTTP methods, and directory listings.
- Remediated issues by updating server configurations and restricting dangerous methods (e.g., `TRACE`, `OPTIONS`).

### ✅ Task 3: Final Penetration Testing (Metasploit)
- Conducted a full manual penetration test using **Metasploit Framework**.
- Validated prior vulnerabilities and tested for any unpatched exploits.
- Simulated common attack vectors (SQL injection, session hijacking) to evaluate resilience.
- All identified vulnerabilities were logged, explained, and patched accordingly.

### 🔒 Security Improvements Summary
- Hardened the Node.js app with secure HTTP headers.
- Patched known vulnerabilities from automated scanners.
- Reduced attack surface through Docker containerization and minimal base images.
- Strengthened deployment pipeline with system auditing tools and scans.

### 🛠 Tools Used
- OWASP ZAP
- Nikto
- Metasploit Framework
- Kali Linux
- Docker

### 📂 Deliverables
- Final Report (this file)
- GitHub Repository with Updated README and Source Code
- Secured NodeGoat App (Running on Docker)
- 4–5 Min Video Walkthrough (Voice-over)

