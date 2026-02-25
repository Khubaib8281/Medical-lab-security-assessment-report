# SOC Assessment Report – Redacted

**Author:** Muhammad Khubaib Ahmad – AI/ML Applied Research & SOC Engineering
**Date:** 25 February 2026

## Overview

This repository contains a redacted security assessment report of a public diagnostic laboratory web portal. The assessment focused on sensitive data transmission over HTTP, highlighting potential risks to user credentials and medical reports.

> Important: No patient, personal, or confidential data has been included. All findings are based on ethical, authorized testing using personal test accounts.

## Tools & Methodology

- Network Traffic Inspection: Wireshark (packet capture and analysis)
- Scope: Authorized access only; no data from other users accessed
- Target: Public medical web portal (unnamed)

## Key Observations:

- Login credentials transmitted in clear text over HTTP
- PDF medical reports delivered unencrypted

## Vulnerability Details

- Type: Sensitive Data Exposure
- OWASP Category: A02 – Cryptographic Failures
- Attack Vector: Network sniffing / Man-in-the-Middle (MITM)

## Report Contents

- Executive Summary
- Technical Findings
- Risk & Impact Analysis

- Evidence (high-level, screenshots placeholders)
- Recommendations & Remediation
- Responsible Disclosure Statement

> File: Security_Assessment_Report.pdf

## Usage

This report is intended for educational purposes and professional demonstration. It provides insight into:

- SOC assessment methodology
- Identifying transport-layer vulnerabilities
- Secure handling of sensitive data in web applications

## Contact

**Muhammad Khubaib Ahmad**

**Email**: muhammadkhubaibahmad854@gmail.com

[LinkedIn](https://wwww.linkedin.com/in/muhammad-khubaib-ahmad-) 
