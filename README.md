<div align="center">

<img src="assets/profile.jpg" width="180" height="180" style="border-radius:50%;object-fit:cover;" alt="Jatin Patidar"/>

# Jatin Patidar

### Cybersecurity Researcher · Penetration Tester 

*Breaking web apps and APIs in authorized scopes, writing it up properly, and learning the next class of bug.*

[![Email](https://img.shields.io/badge/Email-jatin.security%40gmail.com-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:jatin.security@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit%20Website-0A66C2?style=flat-square&logo=google-chrome&logoColor=white)](https://jatinsec.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-jatinsec-0A66C2?style=flat-square)](https://www.linkedin.com/in/jatinsec/)



</div>

---

## About Me

I'm an independent security researcher focused on
web application and API security. I spend most of my time on authorized bug bounty scopes — doing
careful, read-only recon and manual testing, writing reproducible reports, and learning from every
"not accepted" as much as every confirmed finding.

**Career objective:** land an entry-level penetration testing / AppSec role (or a strong bug bounty
track record) where I can keep building depth in web/API security under real program rules and
real accountability for evidence.

---

## Technical Skills

**Web & API Security**
`Authentication & Authorization` `IDOR / BOLA` `Business Logic Flaws` `JWT & OAuth2 misconfig`
`XSS` `SSRF` `CORS misconfiguration` `File-upload security` `HTTP Parameter Pollution`

**Reconnaissance & Enumeration**
`Subdomain enumeration` `DNS & network enumeration` `Attack-surface mapping` `Scope verification`

**Reporting**
`Reproducible PoC write-ups` `CVSS scoring` `Responsible disclosure workflow`

## Tools I Use

| Category | Tools |
|---|---|
| Interception / manual testing | Burp Suite, OWASP ZAP, curl |
| Recon / enumeration | Subfinder, HTTPX, Katana, Nmap |
| Fuzzing / scanning | ffuf, Nuclei |
| Environment | Kali Linux, Ubuntu / WSL |

I use these tools regularly for recon and manual testing — I'd call myself solidly competent with
Burp Suite, Subfinder/HTTPX/Nuclei and curl-based manual testing, and still building depth on the
rest. I'm not claiming expert-level mastery across the board.

## 🎓 Certifications

CEH · eCPPT · eWPTX · eJPT

---

## 🏆 Achievements & Recognition

- **Swisscom Bug Bounty Hall of Fame** – BOLA/IDOR via HTTP Parameter Pollution on MySwisscom, plus 25+ valid findings on Swisscom assets
  - [View Hall of Fame](https://github.com/swisscom/bugbounty/tree/main/hall-of-fame)
- **Solo Securities Hall of Fame** – Security Research Recognition
  - [View Hall of Fame](https://solosecurities.com/hall-of-fame)

## Security Research & Responsible Disclosure

All testing below was performed only against assets explicitly listed as in-scope by the program's
own scope files, under each program's rules of engagement (rate limits, no destructive testing, no
access to other users' data beyond minimal PoC).

### 🛡️ Bug Bounty & Security Contributions

I actively participate in bug bounty programs, identifying and responsibly disclosing vulnerabilities to secure global enterprise infrastructure.

### 🇨🇭 Swisscom Bug Bounty Program ([Hall of Fame](https://github.com/swisscom/bugbounty/tree/main/hall-of-fame))

| Asset | Vulnerability Class |
| :--- | :--- |
| **MySwisscom** (`www.swisscom.ch/myswisscom`) | BOLA / IDOR via HTTP Parameter Pollution on `scn` customer identifier |
| **Swisscom Assets** (25+ Valid Findings) | Broken Access Control & User Enumeration |

#### 📁 Discovered Vulnerabilities
* Remote Code Execution (RCE)
* SQL Injection (SQLi)
* Command Injection
* Broken Authentication
* Hardcoded Credentials
* Server-Side Request Forgery (SSRF)
* Buffer Overflow
* Cross-Site Scripting (XSS)
* Insecure Direct Object References (IDOR)
* Cross-Site Request Forgery (CSRF)
* Information Disclosure
* Broken Object Level Authorization (BOLA)
* Security Misconfiguration
* Sensitive Data Exposure in URL

---

### 🌐 Other Recognized Programs

Identified and disclosed valid vulnerabilities for the following organizations:

* **Google**
* **Epic Games**
* **Kia**
* **Kagi**
* **HML**
* **Solo Securities**

### CVE research

[**jatinsec/my-cves**](https://github.com/jatinsec/my-cves)

---

## Selected Original Projects

| Project | Description |
|---|---|
| **[ReconFlow](https://github.com/jatinsec/ReconFlow)** | Authorized-scope recon result organizer — normalizes target lists, validates scope, parses existing scan output (not a scanner itself), exports structured JSON/CSV. |
| **[API-Sentinel](https://github.com/jatinsec/API-Sentinel)** | Structured API security assessment & evidence organizer — checklist-driven manual test case tracking with Markdown/JSON report generation, demoed against a local lab API. |
| **[PurpleTrace](https://github.com/jatinsec/PurpleTrace)** | Lab-based attack-simulation & detection-validation toolkit — generates benign test events for validating logging/detection rules, with documented investigation steps per scenario. |
| **[google-dork-generator](https://github.com/jatinsec/google-dork-generator)** | Google dork generator for authorized recon during bug bounty engagements. |
| **[v8-string-memory-research](https://github.com/jatinsec/v8-string-memory-research)** | Independent research + a runnable Node.js cross-check on V8 `SlicedString`/`ConsString` substring memory retention. |

> These tools are for **authorized testing and lab use only**. See each repo's README
> for scope and limitations.

---

## Contact

- **Email:** jatin.security@gmail.com
- **Portfolio:** [jatinsec.github.io](https://jatinsec.github.io/)
- **LinkedIn:** [linkedin.com/in/jatinsec](https://www.linkedin.com/in/jatinsec/)


---

<div align="center">
<sub>Built for authorized security research and responsible disclosure. No claim on this page is made without evidence I can reproduce.</sub> <div></div>
</div>
