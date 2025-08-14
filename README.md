# Research-and-Develop-a-Proof-of-Concept-for-SQL-Injection-Detection
#  SQL Injection Detection Tool (PoC)

A Python-based tool for detecting **SQL Injection (SQLi)** vulnerabilities in web applications.  
It supports detection of:

-  Classic SQL Injection (Error-based)
-  Boolean-Based Blind SQL Injection
-  Time-Based Blind SQL Injection  
-  Generates a detailed PDF report (with graphs and CVE mapping)

---

## Features

-  Detects vulnerable URLs via GET/POST payloads
-  Identifies error-based, blind, and time-based SQL injection
-  PDF report includes:
  - Scan results
  - Exploited parameters
  - Payloads used
  - Detection logic
  - Real-world CVEs (2022–2024)
  - Prevention recommendations
-  Export results as pie charts and vulnerability tables

---

## Setup Instructions

### 1. Requirements

- Python 3.8+
- `requests`
- `reportlab`
- `matplotlib`
- `beautifulsoup4`

### 2. Install Dependencies

```bash
pip install requests reportlab matplotlib beautifulsoup4

