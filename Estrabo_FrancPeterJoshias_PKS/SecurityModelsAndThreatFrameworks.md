# Security Models and Threat Frameworks

## Assets

Assets are valuable resources that require protection.

### Tangible Assets
- Servers
- Laptops
- Networking devices
- Buildings

### Intangible Assets
- Customer data
- Intellectual property
- Reputation

## Vulnerabilities

Weaknesses that attackers can exploit.

Examples:
- Unpatched software
- Weak passwords
- Misconfigured firewalls
- Human error

## Threats

Events or actors that can cause harm.

Examples:
- Hackers
- Malware
- Insider threats
- Natural disasters

## Risk

Risk is the probability of a threat exploiting a vulnerability.

Formula:

Risk = Threat × Vulnerability × Impact

# CIA Triad

## Confidentiality

Ensures data is only accessible to authorized users.

Controls:
- MFA
- IAM
- Encryption
- Least Privilege

Violations:
- Data breaches
- Phishing
- MITM attacks

## Integrity

Ensures data remains accurate and unmodified.

Controls:
- Hashing
- Digital signatures
- File Integrity Monitoring

Violations:
- Data tampering
- Malware injection
- Spoofing

## Availability

Ensures systems remain accessible.

Controls:
- Backups
- Load balancing
- DDoS protection
- Redundancy

Violations:
- Ransomware
- Server outages
- DDoS attacks

# Threat Frameworks

## MITRE ATT&CK

A framework that documents real-world attacker techniques.

### Structure

#### Tactics
The attacker's goal.

Examples:
- Initial Access
- Credential Access
- Impact

#### Techniques
Specific methods used.

Examples:
- Phishing
- Credential Dumping
- Pass the Hash

## Case Study Summary

A phishing PDF infected a user, stole credentials, moved laterally, and deployed ransomware.

Mapped ATT&CK Tactics:
- Initial Access
- Credential Access
- Lateral Movement
- Impact