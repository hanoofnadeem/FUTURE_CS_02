# FUTURE_CS_02 - Phishing Email Detection & Awareness System

## Track Code
CS (Cyber Security)

## Task Number
Task 2

## Date
May 1, 2026

## Author
Hanoof Nadeem

## Emails Analyzed

### Email #1: 419 Advance Fee Fraud (Joseph Camarah Vieira)
- **From:** JOSEPH CAMARAH VIEIRA <vieria@aol.com>
- **Reply-To:** carrr444@yahoo.com
- **Subject:** Dear Sir/Madam.
- **Key Red Flags:** Reply-To mismatch, $60 million offer, poor grammar, undisclosed recipients

### Email #2: Brand Impersonation Scam (Fake Lowe's/DeWalt)
- **From:** Lowess <qdnmqypsp@eagleacct.com>
- **Subject:** Pending - Order [#21499-01]
- **Key Red Flags:** Fake sender domain, no DMARC, no DKIM, BCL:9 spam score

## Tools Used
- **MXToolbox Email Header Analyzer** - SPF, DKIM, DMARC verification
- **Manual email header analysis** - Reply-To mismatch, domain inspection

## Key Findings

| Email | Type | Risk |
|-------|------|------|
| Email #1 | 419 Advance Fee Fraud | **PHISHING** |
| Email #2 | Brand Impersonation | **PHISHING** |

## Repository Contents
- `report.pdf` - Phishing Detection & Awareness Report
- `/evidence` - Email samples, headers, and MXToolbox screenshots

## How to View the Report
Download `report.pdf` to see complete analysis and prevention guidelines.
