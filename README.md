<div align="center">

<img src="assets/profile.jpg" width="180" height="180" style="border-radius:50%;object-fit:cover;" alt="Jatin Patidar"/>

# Jatin Patidar

### Cybersecurity Researcher · Penetration Tester (in training)

*Breaking web apps and APIs in authorized scopes, writing it up properly, and learning the next class of bug.*

[![Email](https://img.shields.io/badge/Email-jatin.security%40gmail.com-0A66C2?style=flat-square&logo=gmail&logoColor=white)](mailto:jatin.security@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-jatin--patidar--portfolio-0A66C2?style=flat-square&logo=github&logoColor=white)](https://jatinpatel-hacker33.github.io/jatin-patidar-portfolio/)
[![Phone](https://img.shields.io/badge/Phone-%2B91%207697892082-0A66C2?style=flat-square)](tel:+917697892082)

</div>

---

## About Me

I'm a BCA student at **Amity University Noida**, and an independent security researcher focused on
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

---

## Security Research & Responsible Disclosure

All testing below was performed only against assets explicitly listed as in-scope by the program's
own scope files, under each program's rules of engagement (rate limits, no destructive testing, no
access to other users' data beyond minimal PoC).

### Swisscom Bug Bounty Program (`github.com/swisscom/bugbounty`)

| Asset | Vulnerability class | Status | Impact (confirmed) |
|---|---|---|---|
| MySwisscom (`www.swisscom.ch/myswisscom`) | BOLA / IDOR via HTTP Parameter Pollution on the `scn` customer identifier | **Submitted — under review** | Demonstrated cross-account access to another test account's customer record (name, DOB, address) using two tester-owned accounts only. No third-party data accessed. |
| `wp-prod.bluecinema.ch` (Blue Entertainment AG) | Broken access control — WordPress REST API `?context=edit` returning editor-only fields to anonymous requests on custom post types | **Submitted — under review** | Confirmed, low–medium severity. No write access demonstrated; impact bounded by public catalog content. |
| `wp-prod.bluecinema.ch` | Unauthenticated user/author enumeration via `/wp-json/wp/v2/users` | **Submitted — under review** | Confirmed, low/informational. |
| `empfang.jls.digital` (JLS Digital AG) | Next.js fingerprinting / version-disclosure review | **Assessed — no exploitable vulnerability found** | Documented honestly: fingerprint is consistent with a fully patched Next.js 15.5.x build; no RCE, DoS or auth-bypass demonstrated or claimed. |

I don't report payout amounts, CVSS scores beyond what's in the written report, or acceptance status
beyond "submitted / under review" until the program confirms them — those details will be updated
here once Swisscom's triage responds.

### Other programs

I've looked at scope for Google, Epic Games, Kia, Kagi and HML but have **no submitted or accepted
finding from any of them yet** — nothing in this section is a claim about those programs. I'll add
entries here only once I have a real, evidenced result.

---

## Selected Original Projects

| Project | Description |
|---|---|
| **[ReconFlow](https://github.com/jatinpatel-hacker33/ReconFlow)** | Authorized-scope recon result organizer — normalizes target lists, validates scope, parses existing scan output (not a scanner itself), exports structured JSON/CSV. |
| **[API-Sentinel](https://github.com/jatinpatel-hacker33/API-Sentinel)** | Structured API security assessment & evidence organizer — checklist-driven manual test case tracking with Markdown/JSON report generation, demoed against a local lab API. |
| **[PurpleTrace](https://github.com/jatinpatel-hacker33/PurpleTrace)** | Lab-based attack-simulation & detection-validation toolkit — generates benign test events for validating logging/detection rules, with documented investigation steps per scenario. |
| **[google-dork-generator](https://github.com/jatinpatel-hacker33/google-dork-generator)** | Google dork generator for authorized recon during bug bounty engagements. |
| **[v8-string-memory-research](https://github.com/jatinpatel-hacker33/v8-string-memory-research)** | Independent research + a runnable Node.js cross-check on V8 `SlicedString`/`ConsString` substring memory retention. |

> All three new projects are for **authorized testing and lab use only**. See each repo's README
> for scope and limitations.

---

## GitHub

- Profile: [github.com/jatinpatel-hacker33](https://github.com/jatinpatel-hacker33)
- Portfolio site: [jatinpatel-hacker33.github.io/jatin-patidar-portfolio](https://jatinpatel-hacker33.github.io/jatin-patidar-portfolio/)

## Contact

- **Email:** jatin.security@gmail.com
- **Phone:** +91 7697892082

---

<div align="center">
<sub>Built for authorized security research and responsible disclosure. No claim on this page is made without evidence I can reproduce.</sub>
</div>
