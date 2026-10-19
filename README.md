# SOC Analyst Notes

My working notes on the road to a SOC analyst role: alert-triage playbooks, investigation write-ups, and detection logic, written as I learn.

## About me

BCA student in Bangalore, India, working towards **SOC Analyst (L1) → Detection Engineering → Cloud Security**.

## Current focus (Oct 2026)

- **Google Cybersecurity Certificate**: in progress (Course 4 of 9, Linux and SQL)
- **TryHackMe SOC Level 1**: alert triage, SIEM (Splunk, Elastic), traffic analysis
- **Fundamentals**: networking (OSI, TCP/IP, subnetting) and Linux

**Next:** CompTIA Security+ (V8), an Elastic home lab, and Sigma detection rules mapped to MITRE ATT&CK.

## What's in this repo

| Folder | What goes in it |
| --- | --- |
| `playbooks/` | One page per alert type: what to check, what to query, when to close or escalate |
| `investigations/` | Write-ups of lab investigations |

Every investigation write-up follows the same format:

- **What happened:** who, what, when, where
- **Indicators:** IPs, domains, hashes, accounts
- **Verdict:** true positive, false positive or benign, and why
- **Next step:** close, escalate, or contain

## Tools I'm learning

Linux · Wireshark · Splunk · Elastic · MITRE ATT&CK · Python · SQL
