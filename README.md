# SOC Alert Triage Practice

**SOC Analyst L1 Lab · Alert Investigation · Incident Triage**

> 🟢 **Status: Active — case library is being expanded**

### 🧰 Stack
<img src="https://img.shields.io/badge/LetsDefend-Training-555555" alt="LetsDefend"> <img src="https://img.shields.io/badge/CyberDefenders-Training-555555" alt="CyberDefenders"> <img src="https://img.shields.io/badge/SOC-Alert_Triage-555555" alt="SOC Alert Triage">

## 🎯 Objective
Build repeatable L1 triage habits: understand what fired, gather the right context, decide whether the activity is malicious, and leave a clear handoff for the next analyst.

## 🗺️ Repository map

| Path | Purpose |
|---|---|
| [`docs/01-triage-standard.md`](docs/01-triage-standard.md) | Standard L1 investigation sequence |
| [`cases/`](cases/) | Individual investigations and reusable case template |
| [`evidence/`](evidence/) | Evidence quality and sanitisation rules |

## 🔎 Triage workflow

1. **Initial review** — alert type, timestamp, source, destination, asset and user.
2. **Context gathering** — related logs and identity/asset context.
3. **Analysis** — expected, suspicious or malicious?
4. **Verdict** — True Positive / False Positive / Suspicious.
5. **Severity** — confidence, impact and urgency.
6. **Decision** — close, monitor or escalate with justification.
7. **Handoff** — concise evidence-backed notes for L2 or the next shift.

## 🗂️ Case documentation standard

| Field | Analyst output |
|---|---|
| Alert | What triggered the investigation |
| Evidence | Relevant logs, IPs, users, hosts, processes or domains |
| Timeline | Important events in order |
| Verdict | True Positive / False Positive / Suspicious |
| Severity | Informational / Low / Medium / High / Critical |
| Action | Close / Monitor / Escalate |
| Rationale | Evidence supporting the decision |

## 🧠 Skills being practised
**Alert triage • evidence collection • false-positive analysis • severity assessment • escalation decisions • incident documentation**

## Scope & ethics
All investigations are performed in authorised educational or simulated environments. Sensitive data and live malicious content are not published.
