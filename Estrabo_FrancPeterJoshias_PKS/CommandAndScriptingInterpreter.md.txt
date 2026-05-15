# Command and Scripting Interpreter (T1059)

## Execution Tactic

Execution techniques allow attackers to run malicious code on systems.

## T1059 Overview

Attackers abuse:
- PowerShell
- Command Prompt
- JavaScript
- VBScript

These are legitimate administrative tools often trusted by security software.

## PowerShell Abuse

PowerShell is heavily abused because it can:
- Download payloads
- Execute encoded commands
- Run fileless malware

Common indicators:
- Base64 encoded commands
- Hidden execution
- Invoke-Expression usage

## JavaScript and VBScript

Used in:
- Malicious Office documents
- PDFs
- HTML attachments

## GootLoader

JavaScript malware loader that:
- Creates persistence
- Executes second-stage payloads
- Launches PowerShell payloads

## Windows Command Shell

Batch files:
- Automate commands
- Execute scripts
- Perform repetitive operations

## Defensive Strategies

### Script Block Logging
Enable PowerShell Event ID 4104.

### Execution Policies
Use constrained language mode.

### Command Monitoring
Detect suspicious arguments.

### Application Control
Restrict scripting interpreters.