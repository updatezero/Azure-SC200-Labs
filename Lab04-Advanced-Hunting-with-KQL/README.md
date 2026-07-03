# Lab 04 - Microsoft Sentinel Data Connectors

## Objective

Learn how Microsoft Sentinel ingests security telemetry by exploring Data Connectors and the Microsoft Defender XDR integration.

---

## Lab Goals

- Understand the purpose of Data Connectors
- Explore Microsoft Defender XDR integration
- Review connector prerequisites
- Examine available Defender event tables
- Understand how security telemetry is collected

---

## Environment

- Microsoft Azure
- Microsoft Sentinel
- Microsoft Defender XDR
- Microsoft Learn Lab Tenant

---

## Screenshots

| # | Screenshot |
|---|------------|
| 01 | Data Connectors Overview |
| 02 | Microsoft Defender XDR Selected |
| 03 | Microsoft Defender XDR Connector Page |
| 04 | Microsoft Defender XDR Connect Events |

---

## Key Concepts

### Data Connectors

Data Connectors ingest security telemetry from various Microsoft and third-party services into Microsoft Sentinel.

Without Data Connectors:

- No Logs
- No Hunting
- No Analytics Rules
- No Incidents

---

### Microsoft Defender XDR

Microsoft Defender XDR aggregates security information from multiple Microsoft security products into a unified platform.

Integrated services include:

- Microsoft Defender for Endpoint
- Microsoft Defender for Identity
- Microsoft Defender for Office 365
- Microsoft Defender for Cloud Apps
- Microsoft Entra ID Protection

---

### Event Tables

Examples of collected telemetry include:

- DeviceInfo
- DeviceProcessEvents
- DeviceNetworkEvents
- DeviceRegistryEvents
- DeviceLogonEvents
- DeviceFileEvents

These tables are later queried using KQL for threat hunting and investigations.

---

## Skills Learned

- Navigate Microsoft Sentinel Data Connectors
- Understand connector configuration
- Review Microsoft Defender XDR integration
- Explore available Defender event tables
- Understand security data ingestion

---

## Outcome

Successfully explored Microsoft Defender XDR Data Connector configuration and understood how security telemetry is ingested into Microsoft Sentinel.
