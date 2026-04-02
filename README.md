# 🎮 PSN Data Breach Analysis & Incident Response

In April 2011, Sony's PlayStation Network was taken offline for 23 days following a breach that exposed the personal and financial data of approximately 77 million users. It remains one of the most studied cybersecurity failures in corporate history — not just because of its scale, but because of how long it went undetected and how poorly it was handled once discovered.

This case study breaks down what went wrong, why it went wrong, and what a stronger response would have looked like.

---

## What Happened

Attackers exploited unpatched network vulnerabilities — likely through SQL injection — to gain unauthorized access to Sony's infrastructure. Once inside, they moved through the network undetected, exfiltrating names, addresses, email addresses, passwords, and payment card data before Sony identified the intrusion.

The breach wasn't just a technical failure. Delayed detection, slow public disclosure, and an absence of encryption on sensitive data turned a serious incident into a reputational and regulatory crisis.

---

## Where Sony Failed

**Detection** — The intrusion went undetected long enough for attackers to exfiltrate data at scale. Stronger log monitoring and behavioral anomaly detection would have surfaced the attack earlier.

**Encryption** — Sensitive user data including passwords was not adequately protected at rest. Encryption would not have prevented the breach but would have significantly reduced its impact.

**Disclosure** — Sony waited several days after discovering the breach before notifying users, drawing regulatory scrutiny and eroding public trust at a critical moment.

**Incident Response** — The absence of a structured response plan meant containment and recovery were reactive rather than coordinated, extending the 23-day outage.

---

## How It Should Have Been Handled

Using the NIST Incident Response Lifecycle as a guide:

1. **Detect** — Anomaly detection and log monitoring flag unusual query patterns or data transfer volumes early
2. **Contain** — Affected systems isolated immediately; compromised accounts disabled
3. **Investigate** — Logs analyzed to identify attack vectors, scope, and exfiltrated data
4. **Notify** — Regulators and users informed promptly in line with disclosure obligations
5. **Eradicate & Recover** — Vulnerabilities patched, credentials reset, systems restored from clean backups
6. **Review** — Lessons learned session conducted; detection and response capabilities updated

---

## Framework Alignment

| Framework | Application |
|---|---|
| NIST SP 800-61 | Incident response lifecycle structure |
| MITRE ATT&CK | Attack technique mapping (initial access, lateral movement, exfiltration) |
| CIS Controls | Security gaps identified and remediation mapped |

---

## Artifacts & Outputs

- Breach timeline and attack analysis
- Incident response gap assessment
- Security improvement recommendations mapped to NIST, MITRE, and CIS

> 📌 *Breach timeline visualization coming soon.*

