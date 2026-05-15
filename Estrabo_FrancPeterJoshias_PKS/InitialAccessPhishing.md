# Initial Access - Phishing

## Overview

Phishing is a social engineering attack used to trick victims into revealing sensitive information or executing malicious content.

## Goal of Phishing

Attackers aim to:
- Steal credentials
- Gain initial access
- Deploy malware

## Types of Phishing

### Spam
Bulk unsolicited messages.

### Phishing
General credential theft attacks.

### Spear Phishing
Targets specific individuals.

### Whaling
Targets executives.

### Smishing
SMS phishing.

### Vishing
Voice-call phishing.

## Characteristics of Phishing Emails

- Spoofed sender addresses
- Urgent language
- Hidden malicious links
- Fake attachments

## How Email Works

1. Email is composed
2. SMTP server sends message
3. DNS locates destination
4. MX server receives email
5. Inbox receives message

## Email Header Analysis

Headers contain authentication information.

### SPF
Verifies sender IP legitimacy.

### DKIM
Verifies message integrity.

### DMARC
Defines handling policy for failed checks.

## Analysis Tools

### Header Analysis
- MXToolbox
- Google MessageHeader
- MailHeader

### URL/IP Analysis
- VirusTotal
- AbuseIPDB
- Talos Intelligence
- URLVoid

## REMnux

REMnux is a Linux toolkit for malware analysis.

Useful tools:
- emldump
- msg-extractor
- msgconvert
- mail-parser