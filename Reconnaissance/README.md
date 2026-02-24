# Reconnaissance – MITRE ATT&CK Tactic Overview

## What is Reconnaissance?

Reconnaissance is the first tactic in the MITRE ATT&CK framework. It represents the phase where an adversary gathers information about a target organization before attempting initial access.

Unlike later stages, reconnaissance does not directly compromise systems. Instead, it focuses on intelligence collection that helps an attacker plan and prepare for an intrusion.

Reconnaissance is typically followed by the Resource Development tactic.

---

## Why Attackers Use Reconnaissance

Attackers (and penetration testers) use reconnaissance to:

- Identify weaknesses and vulnerabilities
- Understand an organization’s structure and technologies
- Gather employee information
- Learn about exposed infrastructure
- Prepare for phishing or credential attacks

The more information an adversary gathers, the higher their chance of successfully executing later attack stages.

---

## Reconnaissance Techniques (MITRE ATT&CK)

Below are key techniques within the Reconnaissance tactic:

- **T1590 – Gather Victim Network Information**
- **T1591 – Gather Victim Organization Information**
- **T1592 – Gather Victim Host Information**
- **T1593 – Search Open Websites/Domains**
- **T1594 – Search Victim-Owned Websites**
- **T1595 – Active Scanning**
- **T1596 – Search Open Technical Databases**
- **T1597 – Search Closed Sources**
- **T1598 – Phishing for Information**
- **T1599 – Gather Victim Identity Information**

These techniques range from passive OSINT collection to active infrastructure probing.

---

## How Reconnaissance Supports Later Attacks

Information gathered during reconnaissance can enable:

- Spear-phishing attacks through impersonation
- Password guessing based on personal details
- Infrastructure targeting based on known technologies
- Avoidance of security controls
- Physical intrusion planning

Reconnaissance often determines how effective later tactics (Initial Access, Credential Access, etc.) will be.

---

## Defensive & Mitigation Strategies

Because reconnaissance often occurs externally, prevention and visibility are key.

### Organizational Controls
- Limit publicly available sensitive information
- Train employees on cybersecurity awareness
- Enforce strong password hygiene
- Educate staff on phishing risks
- Restrict oversharing on social media

### Technical Controls
- Monitor website traffic for unusual spikes
- Identify repeated requests from single IP sources
- Use email authentication and anti-spoofing mechanisms
- Monitor for domain lookalikes
- Review web metadata and referral sources

Monitoring external visibility is just as important as monitoring internal logs.

---

## Analyst Perspective

From an analyst standpoint, reconnaissance is difficult to detect because much of it occurs outside internal systems.

However, analysts should:

- Monitor abnormal web traffic patterns
- Watch for signs of active scanning
- Track domain spoofing attempts
- Correlate recon indicators with later suspicious activity

Reconnaissance detection becomes more valuable when correlated with follow-on behavior.

---

## Key Takeaways

- Reconnaissance is intelligence gathering, not exploitation.
- It significantly increases the likelihood of successful compromise.
- Limiting publicly available data reduces attacker advantage.
- Early detection of reconnaissance can disrupt the attack lifecycle.

