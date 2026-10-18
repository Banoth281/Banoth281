<!-- Custom SVG portfolio for Santhosh Banoth. All artwork is stored in this repository. -->
<p align="center">
  <img src="./assets/security-operations-3d.svg" width="100%" alt="Santhosh Banoth — SOC Analyst, Threat Detection and Incident Response" />
</p>

<a id="about"></a>

<p align="center"><img src="./assets/profile-v2-about.svg" width="100%" alt="About me: 3+ years of SOC experience across MSSP and enterprise environments. Focused on Sentinel, Defender XDR, identity investigations, tested detection logic, and clear reporting." /></p>

<a id="projects"></a>

<p align="center"><img src="./assets/profile-v2-windows.svg" width="100%" alt="Windows Authentication Detection: PowerShell Event 4625 collection, correlation, validation, deduplication, and CSV/HTML reports. 31 hosted regression checks passed; local collection recorded 2 unique events and 0 threshold alerts." /></p>

[Read case study](https://github.com/Banoth281/soc-login-lab/blob/main/windows-event-investigation/CASE-STUDY.md) · [Source code](https://github.com/Banoth281/soc-login-lab/tree/main/windows-event-investigation/powershell) · [Local evidence](https://github.com/Banoth281/soc-login-lab/blob/main/windows-event-investigation/evidence/LOCAL-V2-VALIDATION.md)

[![Windows test status](https://github.com/Banoth281/soc-login-lab/actions/workflows/powershell-tests.yml/badge.svg)](https://github.com/Banoth281/soc-login-lab/actions/workflows/powershell-tests.yml)

<p align="center"><img src="./assets/profile-v2-phishing.svg" width="100%" alt="Phishing Email Investigation: synthetic sample hashing, header and URL extraction, JSON/HTML reporting, and separate analyst assessment. 10 extraction checks passed; additional reporting and encoding checks are documented in validation." /></p>

[Read case study](https://github.com/Banoth281/soc-login-lab/blob/main/phishing-email-investigation/CASE-STUDY.md) · [Source code](https://github.com/Banoth281/soc-login-lab/tree/main/phishing-email-investigation) · [Validation](https://github.com/Banoth281/soc-login-lab/blob/main/phishing-email-investigation/VALIDATION.md)

[![Email test status](https://github.com/Banoth281/soc-login-lab/actions/workflows/phishing-tests.yml/badge.svg)](https://github.com/Banoth281/soc-login-lab/actions/workflows/phishing-tests.yml)

<p align="center"><img src="./assets/profile-v2-python.svg" width="100%" alt="Multi-Account Failure Detection: Python rolling-window correlation of distinct accounts by source IP, UTC normalisation, duplicate rejection, and structured alerts. 18 tests passed on Windows and Linux; 12 valid synthetic records produce 1 alert." /></p>

[Explore repository](https://github.com/Banoth281/soc-password-spray-lab) · [Investigation](https://github.com/Banoth281/soc-password-spray-lab/blob/main/investigation.md) · [Technical audit](https://github.com/Banoth281/soc-password-spray-lab/blob/main/AUDIT.md)

[![Python test status](https://github.com/Banoth281/soc-password-spray-lab/actions/workflows/python-tests.yml/badge.svg)](https://github.com/Banoth281/soc-password-spray-lab/actions/workflows/python-tests.yml)

<sub>Controlled personal labs: Windows includes actual local test events; phishing and multi-account fixtures are synthetic. Counts describe documented validation runs; badges show current workflow status. No production deployment or confirmed intrusion is claimed.</sub>

<br /><br />

<a id="data-engineering"></a>

<p align="center"><img src="./assets/data-engineering-overview.svg" width="100%" alt="Data engineering and analytics: hands-on projects in streaming, storage, validation, data modelling, and reporting." /></p>

<p align="center"><img src="./assets/data-projects-1.svg" width="100%" alt="UK Transport Intelligence: TfL arrivals → Kafka / Redpanda; PostgreSQL → dbt → FastAPI; Streamlit transport analytics. Learning focus: Event streaming and tested data marts. Stack: Python · Kafka · PostgreSQL · dbt. Fraud Detection Lakehouse: Synthetic banking event ingestion; MinIO Bronze and PostgreSQL Silver; dbt Gold models and fraud rules. Learning focus: Replay safety and data quality contracts. Stack: Python · Kafka · MinIO · dbt." /></p>

[Explore UK Transport Intelligence](https://github.com/Banoth281/uk-live-transport-intelligence) · [Explore Fraud Detection Lakehouse](https://github.com/Banoth281/real-time-fraud-detection-lakehouse)

<p align="center"><img src="./assets/data-projects-2.svg" width="100%" alt="Commerce Data Pipeline: Synthetic orders and schema validation; Dead-letter handling and safe replays; Revenue and latency metrics via API. Learning focus: Idempotent writes and offset management. Stack: Python · Redpanda · PostgreSQL. UK Energy Intelligence: UK carbon-intensity API collection; Regional storage and validation; FastAPI and Streamlit energy insights. Learning focus: API ingestion and relational modelling. Stack: Python · PostgreSQL · FastAPI." /></p>

[Explore Commerce Data Pipeline](https://github.com/Banoth281/real-time-commerce-data-pipeline) · [Explore UK Energy Intelligence](https://github.com/Banoth281/live-uk-energy-intelligence)

<p align="center"><img src="./assets/data-projects-3.svg" width="100%" alt="Crypto Streaming Pipeline: Bitcoin market data ingested via REST; Kafka event transport and processing; PySpark Streaming and Streamlit. Learning focus: Streaming ingestion and transformation. Stack: Python · Kafka · PySpark · Docker. Personal Finance Tracker: Bank CSV cleaning and categorisation; Duplicate and unusual-payment checks; PostgreSQL-backed spending analytics. Learning focus: Schema validation and transaction IDs. Stack: Python · PostgreSQL · Streamlit." /></p>

[Explore Crypto Streaming Pipeline](https://github.com/Banoth281/realtime-crypto-pipeline) · [Explore Personal Finance Tracker](https://github.com/Banoth281/smart-personal-finance-tracker)

<p align="center"><img src="./assets/data-projects-4.svg" width="100%" alt="UK Retail Sales Analytics: Synthetic retail transaction analysis; Revenue, profit, returns and segments; Excel dashboards, SQL and Python. Learning focus: Data quality and analytical SQL. Stack: Excel · SQL / SQLite · pandas. Retail Decision Studio: Browser-based CSV validation; Sales and repeat-customer analysis; Separate ONS context and scenarios. Learning focus: Validation and transparent data context. Stack: JavaScript · Python · CSV." /></p>

[Explore UK Retail Sales Analytics](https://github.com/Banoth281/uk-retail-sales-analytics) · [Explore Retail Decision Studio](https://github.com/Banoth281/retail-growth-retention-decision-studio)

<sub>Personal engineering and learning projects. Summaries follow the linked repository documentation; this profile update does not independently verify runtime or deployment status. Commerce, banking, and retail examples use synthetic data. Some hosted dashboards use saved demo snapshots when their backend is unavailable.</sub>

<br /><br />

<a id="skills"></a>

<p align="center"><img src="./assets/profile-v2-stack.svg" width="100%" alt="Technology stack. Platforms: Sentinel, Defender XDR, Entra ID, Splunk, Elastic Security. Detection: KQL, MITRE ATT&CK, threat hunting, phishing analysis. Development: PowerShell, Python, Bash, SQL, REST APIs, Logic Apps. Engineering: Git, GitHub Actions, validation and regression testing. Identity and networking: IAM, MFA, Conditional Access, TCP/IP, DNS, Wireshark. Governance: NIST CSF, ISO 27001, CIS Controls, vulnerability management. Professional skills reflect my CV." /></p>

<a id="experience"></a>

<p align="center"><img src="./assets/profile-v2-experience.svg" width="100%" alt="CV-listed experience. SOC Analyst, Silverspace, September 2025–Present, remote: 2,800+ alerts, 140 escalated incidents, 22 KQL rules, 9 Sentinel playbooks. Junior SOC Analyst, Vizva Consultancy Services, September 2021–August 2023, India: 650 phishing emails analysed, 220 validated incidents escalated, 140 remediation tickets coordinated." /></p>

<a id="credentials"></a>

<p align="center"><img src="./assets/profile-v2-credentials.svg" width="100%" alt="CV-listed qualifications: Microsoft Security Operations Analyst Associate SC-200; CompTIA Security+; MSc Advanced Computer Science, University of Liverpool, 2023–2025; B.Tech Computer Science, Guru Nanak Institutions Technical Campus, 2017–2021. Public credential verification links are not yet included." /></p>

<p align="center"><img src="./assets/profile-v2-learning.svg" width="100%" alt="Planned development: broader detection test fixtures; Windows collector integration and evidence traceability; robust MIME parsing and richer email training samples." /></p>

<a id="contact"></a>

<p align="center"><img src="./assets/profile-v2-connect.svg" width="100%" alt="Interested in SOC Analyst, Cybersecurity Analyst, and Security Operations roles. Technical feedback and collaboration are welcome." /></p>

<p align="center">
<a href="https://www.linkedin.com/in/banoth281/"><b>Connect on LinkedIn</b></a> &nbsp; · &nbsp;
<a href="mailto:Santhoshbanoth971@gmail.com"><b>Email Santhosh</b></a> &nbsp; · &nbsp;
<a href="https://github.com/Banoth281?tab=repositories"><b>Browse all repositories</b></a>
</p>
