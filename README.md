# Read-Only Vulnerability Assessment

## Future Interns – Cyber Security Task 1 (2026)

### Overview

This project documents a read-only security assessment of the Altoro Mutual demonstration banking application hosted at `testfire.net`.

### Objectives

* Review common TCP port exposure using Nmap.
* Inspect HTTP response headers using Chrome DevTools.
* Review session cookie security attributes.
* Check HTTP-to-HTTPS redirection.
* Document security-hardening recommendations.

### Tools Used

* Nmap 7.991
* Google Chrome DevTools
* Web browser

### Findings

* Explicit SameSite cookie attribute not observed.
* HSTS header not observed.
* Clickjacking protection headers not observed.
* X-Content-Type-Options header not observed.
* Server technology banner disclosure observed.

### Project Structure

* `Vulnerability_Assessment_Report.pdf` – Final assessment report.
* `Evidence/` – Screenshots supporting the assessment findings.
* `README.md` – Project overview and methodology.

### Scope and Ethics

The assessment was limited to passive, read-only checks. No exploitation, brute-force testing, denial-of-service testing, or modification of website data was performed.

OWASP ZAP scanning was not completed because Windows Security blocked the downloaded package.

### Disclaimer

This project is for educational and internship documentation purposes. Findings reflect the limited observations recorded during the assessment and do not establish exploitability.
