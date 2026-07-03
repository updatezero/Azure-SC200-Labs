# Lab 04 Notes

## What are Data Connectors?

Data Connectors import security telemetry into Microsoft Sentinel.

Without connected data sources, Sentinel cannot detect threats or generate incidents.

---

## Microsoft Defender XDR

Acts as a unified security platform by combining data from:

- Defender for Endpoint
- Defender for Identity
- Defender for Office 365
- Defender for Cloud Apps
- Entra ID Protection

---

## Security Data Flow

Endpoints

↓

Microsoft Defender

↓

Microsoft Defender XDR

↓

Microsoft Sentinel

↓

Analytics Rules

↓

Incidents

↓

SOC Investigation

---

## Important Event Tables

DeviceInfo

Inventory of onboarded devices.

---

DeviceProcessEvents

Process execution telemetry.

---

DeviceNetworkEvents

Network connections.

---

DeviceRegistryEvents

Registry modifications.

---

DeviceLogonEvents

Authentication activity.

---

DeviceFileEvents

File creation and modification events.

---

## Why Data Connectors Matter

No Connector

↓

No Data

↓

No Analytics Rules

↓

No Alerts

↓

No Incidents

↓

No Threat Hunting

---

## Practical Takeaways

- Data Connectors are the foundation of Microsoft Sentinel.
- Microsoft Defender XDR centralizes Microsoft security telemetry.
- Event tables become available for KQL hunting after ingestion.
- Proper connector configuration is required before analytics rules can generate incidents.
