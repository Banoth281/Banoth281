<p align="center">
  <img src="./assets/security-operations-3d.svg" width="100%" alt="Santhosh Banoth — SOC Analyst, Threat Detection and Incident Response" />
</p>

<p align="center">
  <a href="#about">About</a> ·
  <a href="#projects">Projects</a> ·
  <a href="#skills">Skills</a> ·
  <a href="#experience">Experience</a> ·
  <a href="#credentials">Credentials</a> ·
  <a href="#contact">Contact</a>
</p>

<a id="about"></a>
## About

Based in **London, United Kingdom**, with **3+ years of SOC experience** across MSSP and enterprise environments. My work focuses on Microsoft Sentinel, Defender XDR, identity investigations, and security automation.

This portfolio demonstrates how I collect telemetry, validate evidence, build detection logic, and document findings for analyst review.

<a id="projects"></a>
## Featured projects

### 01 · Windows Authentication Detection

A PowerShell toolkit for collecting **Windows Security Event 4625**, correlating repeated failures, and generating CSV and HTML investigation reports. Includes host/domain/account/IP grouping, event deduplication, and configurable rolling windows.

**Validation:** 31 hosted regression checks passed. Local collection recorded 2 unique events and 0 threshold alerts.

[Case study](https://github.com/Banoth281/soc-login-lab/blob/main/windows-event-investigation/CASE-STUDY.md) · [Source code](https://github.com/Banoth281/soc-login-lab/tree/main/windows-event-investigation/powershell) · [Evidence](https://github.com/Banoth281/soc-login-lab/blob/main/windows-event-investigation/evidence/LOCAL-V2-VALIDATION.md)

[![Windows tests](https://github.com/Banoth281/soc-login-lab/actions/workflows/powershell-tests.yml/badge.svg)](https://github.com/Banoth281/soc-login-lab/actions/workflows/powershell-tests.yml)

### 02 · Phishing Email Investigation

An evidence-led workflow for hashing a synthetic email sample, extracting headers and URLs, and generating structured JSON and HTML reports. Extracted facts remain separate from the analyst assessment.

**Validation:** 10 extraction checks passed, with additional report-generation and HTML-encoding checks documented.

[Case study](https://github.com/Banoth281/soc-login-lab/blob/main/phishing-email-investigation/CASE-STUDY.md) · [Source code](https://github.com/Banoth281/soc-login-lab/tree/main/phishing-email-investigation) · [Validation](https://github.com/Banoth281/soc-login-lab/blob/main/phishing-email-investigation/VALIDATION.md)

[![Phishing tests](https://github.com/Banoth281/soc-login-lab/actions/workflows/phishing-tests.yml/badge.svg)](https://github.com/Banoth281/soc-login-lab/actions/workflows/phishing-tests.yml)

### 03 · Multi-Account Failure Detection

A Python detector that identifies one source IP failing against multiple distinct accounts within an inclusive rolling window. Includes input validation, UTC normalisation, duplicate rejection, and JSON alerts.

**Validation:** 18 tests passed on Windows and Linux. The synthetic fixture produces 1 alert from 12 valid records.

[Repository](https://github.com/Banoth281/soc-password-spray-lab) · [Investigation](https://github.com/Banoth281/soc-password-spray-lab/blob/main/investigation.md) · [Technical audit](https://github.com/Banoth281/soc-password-spray-lab/blob/main/AUDIT.md)

[![Python tests](https://github.com/Banoth281/soc-password-spray-lab/actions/workflows/python-tests.yml/badge.svg)](https://github.com/Banoth281/soc-password-spray-lab/actions/workflows/python-tests.yml)

*These are controlled personal labs. Windows evidence includes actual local test events; email and multi-account fixtures are synthetic. Test counts describe documented runs; badges show current workflow status.*

<a id="skills"></a>
## Technical skills

| Area | Technologies and practice |
|---|---|
| Security platforms | Microsoft Sentinel, Defender XDR, Entra ID, Splunk, Elastic Security |
| Detection and investigation | KQL, MITRE ATT&CK, threat hunting, log correlation, phishing analysis |
| Development and automation | PowerShell, Python, Bash, SQL, REST APIs, Azure Logic Apps |
| Engineering | Git, GitHub Actions, input validation, regression testing, structured reporting |
| Identity and networking | IAM, MFA, Conditional Access, TCP/IP, DNS, Wireshark |
| Governance | NIST CSF, ISO 27001, CIS Controls, vulnerability management |

*Skills reflect my CV; repository links demonstrate the specific lab implementations described above.*

<a id="experience"></a>
## Professional experience

### SOC Analyst · Silverspace
**September 2025–Present · Remote**

Microsoft Sentinel and Defender XDR investigations, identity security, threat hunting, and response automation.

- Triaged **2,800+ alerts** and escalated **140 confirmed incidents**.
- Developed **22 KQL analytic rules** and **9 Sentinel playbooks**.

### Junior SOC Analyst · Vizva Consultancy Services
**September 2021–August 2023 · India**

24/7 security monitoring, phishing investigation, evidence-based escalation, and remediation coordination.

- Analysed **650 phishing emails** and escalated **220 validated incidents**.
- Coordinated **140 remediation tickets** and documented procedures for analyst handovers.

*Employment details and achievements are drawn from my CV.*

<a id="credentials"></a>
## Certifications and education

| Qualification | Issuer or institution |
|---|---|
| Security Operations Analyst Associate · SC-200 | Microsoft |
| Security+ | CompTIA |
| MSc Advanced Computer Science · 2023–2025 | University of Liverpool, UK |
| B.Tech Computer Science · 2017–2021 | Guru Nanak Institutions Technical Campus, India |

*CV-listed qualifications; public credential verification links are not yet included.*

## Current development

Expanding detection test fixtures, improving Windows collector integration checks, and exploring robust MIME parsing and evidence provenance.

<a id="contact"></a>
## Contact

Interested in **SOC Analyst**, **Cybersecurity Analyst**, and **Security Operations** opportunities.

[LinkedIn](https://www.linkedin.com/in/banoth281/) · [Email](mailto:Santhoshbanoth971@gmail.com)

---

<p align="center"><sub>Investigate with context. Automate with care. Document with evidence.</sub></p>
