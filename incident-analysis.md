# Incident Analysis

## Background

MOVEit Transfer is a managed file-transfer product used by organisations to transfer sensitive information.

In 2023, a critical SQL-injection vulnerability in MOVEit Transfer was exploited at scale. The incident demonstrated how a vulnerability in a widely used third-party application can create significant downstream risk.

## Attack Concept

At a high level:

1. A vulnerable internet-facing application is identified.
2. The attacker exploits the application vulnerability.
3. Unauthorised access to application data becomes possible.
4. Data is targeted and potentially exfiltrated.
5. Affected organisations investigate and respond.

This repository intentionally does **not** provide exploit instructions.

## Security Principles Affected

### Confidentiality

Sensitive information may be accessed or disclosed without authorisation.

### Integrity

Organisations must verify whether systems or data were altered.

### Availability

Incident response and remediation can affect the availability of business systems.

## Lessons

- Internet-facing software requires rapid vulnerability management.
- Third-party risk must be included in security governance.
- Monitoring and incident-response processes need clear ownership.
- Asset inventories should identify exposed applications and versions.
