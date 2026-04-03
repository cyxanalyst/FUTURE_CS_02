# Task 2 — Phishing Email Detection and Awareness

## Overview
This repository contains the work completed for Task 2 of the 
Future Interns Cybersecurity Internship Program.
The goal was to analyze real phishing email samples and create 
a professional awareness report.

## Tools Used
- **PhishTank** — Collect real confirmed phishing samples
- **MXToolbox** — Analyze sender domains and DNS/DMARC records
- **VirusTotal** — Scan URLs for malicious content

## Analysis Approach
1. Collected 3 phishing samples from PhishTank
2. Analyzed each domain using MXToolbox (DNS + DMARC)
3. Verified each URL using VirusTotal
4. Identified phishing indicators for each sample
5. Classified risk levels (High / Critical)
6. Created prevention guidelines for users

## Samples Analyzed
| Sample | Domain | Risk Level |
|--------|--------|------------|
| 1 | allegro-lokalnie.pl-378928.digital | Critical |
| 2 | ulys.services-facture.com | Critical |
| 3 | best-change.xyz | High |

## Files
- `Phishing_Detection_Report_FINAL.pdf` — Full analysis report

## Key Findings
- All 3 samples confirmed as malicious
- Common indicators: fake domains, missing DNS/DMARC, malicious URLs
- Best defense: user awareness and verification
