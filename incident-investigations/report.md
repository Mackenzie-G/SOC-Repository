### Phishing Email Investigation Report

## Case Information

- Case ID: Microsoft Action Required
- Date Investigated: 6/1/2026
- Analyst: Mackenzie Gurry
- Severity: Medium



## Executive Summary

- A suspicious email was reported by a user claiming to be from [Microsoft]. Initial analysis identified multiple indicators associated with phishing activity, including suspicious sender information, malicious URLs, and urgency to take action. The email's objective appeared to be credential theft.
- Verdict: Confirmed Phishing



## Alert Details

- Subject: [Action Required Now]
- Sender: [??]
- Recipient: [??]
- Reported By: [User or Security Tool]



## Initial Observations
#Red Flags Identified

- Urgent language designed to pressure the recipient.
- Sender domain does not match the legitimate organization.
- Hyperlinks redirect to suspicious domains.
- Authentication failures detected.

#Email Body Analysis
- Describe the message content and explain why it appears suspicious.

## Header Analysis
# Authentication Results
# Control	Result
- SPF	Pass / Fail
- DKIM	Pass / Fail
- DMARC	Pass / Fail

# Key Header Findings
- Field	Value
- Return-Path	
- Reply-To	
- Originating IP	
- Message-ID	



## Analysis
- Explain what the header information reveals about the sender and message routing.

## URL Analysis
#Extracted URLs
-URL:           
-Purpose:



## Investigation Results
- Detection Ratio
- Reputation

## URL Scan
- Screenshot Findings
- Redirect Chain

# Analysis
- Explain why the URLs are considered malicious or suspicious



## Domain and Infrastructure Analysis
# Domain Information

- Indicator
- Domain Name
- Registrar
- Registration Date
- Domain Age

## Reputation Checks
- Abuse IPDB
- Cisco Talos
- WHOIS Findings

# Analysis
- Summarize the trustworthiness of the domain and infrastructure



## Indicators of Compromise
# Domains
- example-phish.com

# URLs
- https://example-phish[.]com/login

# IP Addresses
- 192.xxx.xxx.xxx

# Email Addresses 
- example@attacker-phish.com

MITRE ATT&CK Mapping
#Technique ID
- TXXXX
- TXXXXX

# Rationale
- Explain why the identified techniques apply to this campaign




## Recommended Actions
- Immediate Actions
- Block malicious domains
- Block associated IP Addresses
- Quarantine similiar email
- Reset affected credentials if interaction occured.

# Long Term Improvements
- User Awareness training
- Enhanced email filtering
- DMARC enforcement
- Continuous monitoring

## Conclusion
- Based on header analysis, infrastructure reputation, and URL investigation, this email was determined to be a phishing attempt. The message was designed to deceive users into revealing credentials through a malicious website impersonating a legitimate service.

# Final Verdict: Confirmed Phishing
