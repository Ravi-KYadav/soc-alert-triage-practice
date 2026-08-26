# SOC Alert Triage Practice

A collection of simulated SOC alert investigations completed on LetsDefend and CyberDefenders, documented using a structured triage methodology consistent with real-world SOC L1 workflows.

## 🎯 Objective

To build muscle memory for the alert triage process a SOC L1 analyst performs dozens of times per shift: receive an alert, gather context, assess severity, decide true/false positive, and escalate or close with clear documentation.

## 🧰 Platforms Used

- [LetsDefend](https://letsdefend.io) — SOC Analyst Learning Path, simulated SIEM alert environment
- [CyberDefenders](https://cyberdefenders.org) — Blue team investigation challenges

## 🔧 Triage Methodology

Every alert in this repo was worked through the same structured process:

1. **Initial Alert Review** — What triggered the alert? Source, destination, timestamp, alert type.
2. **Context Gathering** — Pulled related logs, checked asset/user context, cross-referenced with threat intel where relevant.
3. **Analysis** — Determined whether the activity was malicious, suspicious-but-benign, or a false positive.
4. **Severity Classification** — Rated the alert (e.g., Informational / Low / Medium / High / Critical) based on impact and confidence.
5. **Decision & Escalation** — Documented whether the case was closed, monitored, or escalated to L2 — and why.
6. **Reporting** — Wrote a short incident summary as if handing off to the next shift or an L2 analyst.

## 📋 Case Log

| Case # | Alert Type | Platform | Verdict | Severity |
|---|---|---|---|---|
| 1 | *<!-- e.g. Brute Force Login Attempt -->* | LetsDefend | *<!-- True Positive / False Positive -->* | *<!-- e.g. Medium -->* |
| 2 | *<!-- e.g. Suspicious PowerShell Execution -->* | CyberDefenders | *<!-- ... -->* | *<!-- ... -->* |
| 3 | *<!-- add more rows as you document each case -->* | | | |

*<!-- Replace with your actual completed cases. Link each row to its own write-up file in a /cases folder if you want per-case depth, e.g. cases/case-01-brute-force.md -->*

## 🔍 Example Investigation Write-Up

*<!-- Pick your strongest case and expand it fully below as a worked example -->*

**Alert:** *<!-- alert name -->*
**Source/Destination:** *<!-- IPs, hostnames -->*
**Timeline:** *<!-- what happened, in order -->*
**Analysis:** *<!-- your reasoning -->*
**Verdict:** *<!-- True Positive / False Positive, with justification -->*
**Screenshot:** *<!-- add screenshot of the alert/investigation from the platform -->*

## 🧠 Skills Demonstrated

- Structured alert triage under a repeatable methodology
- True positive / false positive determination
- Severity and impact assessment
- Escalation decision-making
- Incident documentation for handoff

## 📚 What I Learned

*<!-- 3-4 sentences: what surprised you about triage, which alert types you found trickiest to assess, how your speed/confidence improved across cases -->*

## 🔗 Related

Part of a 5-project SOC Analyst portfolio. See also: [Wazuh SIEM Home Lab](https://github.com/Ravi-KYadav/wazuh-siem-home-lab) · [Phishing Email Analysis](https://github.com/Ravi-KYadav/phishing-email-analysis)
