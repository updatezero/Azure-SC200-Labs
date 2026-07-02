# Lab Notes

## What I learned

### Analytics Rules

Analytics Rules are responsible for detecting suspicious activity inside Microsoft Sentinel.

They continuously execute KQL queries against collected log data.

When the query matches predefined conditions, Microsoft Sentinel generates an alert or incident.

---

## Rule Types

- Scheduled Rules
- Microsoft Security Rules
- Near Real-Time (NRT) Rules
- Fusion Rules
- Machine Learning Rules

---

## Rule Wizard

The Analytics Rule Wizard consists of several stages:

1. General
2. Set Rule Logic
3. Incident Settings
4. Automated Response
5. Review + Create

---

## Rule Logic

Contains:

- KQL Query
- Entity Mapping
- Alert Details
- Custom Details
- Query Scheduling
- Alert Threshold

---

## Incident Settings

Controls:

- Incident creation
- Alert grouping
- Incident grouping
- Alert correlation

---

## Automated Response

Automation Rules or Logic Apps can automatically execute actions when an incident is created.

Examples:

- Send Teams notification
- Send Email
- Create ServiceNow ticket
- Trigger Logic App

---

## MITRE ATT&CK

Analytics Rules are mapped to MITRE ATT&CK tactics and techniques.

Examples:

- Persistence
- Credential Access
- Execution
- Discovery
- Lateral Movement

---

## KQL

Analytics Rules use Kusto Query Language (KQL) to search log data.

Example tables:

- SecurityAlert
- DeviceInfo
- DeviceEvents
- IdentityInfo

---

## Key Takeaways

- Analytics Rules are the core detection engine of Microsoft Sentinel.
- KQL is used to detect malicious behaviour.
- Entity Mapping improves investigations.
- Incident Settings control alert grouping.
- Automated Response enables SOAR automation.
- Analytics Rules can be reviewed before deployment without creating them.
