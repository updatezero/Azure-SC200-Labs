# Lab 05 – Microsoft Sentinel Advanced Hunting with KQL

## Objective

Explore the Microsoft Sentinel Advanced Hunting interface and execute basic Kusto Query Language (KQL) queries against available data sources.

---

## Environment

- Microsoft Defender Portal
- Microsoft Sentinel
- Microsoft Learn Sandbox
- Advanced Hunting
- Kusto Query Language (KQL)

---

## Tasks completed

- Opened Microsoft Defender Advanced Hunting
- Explored the schema explorer
- Executed the first KQL query
- Tested additional hunting queries
- Verified query execution
- Investigated available hunting tables

---

## Sample KQL Query

```kusto
DeviceInfo
| take 10
```

Additional queries tested:

```kusto
AlertInfo
| take 10
```

```kusto
DeviceProcessEvents
| take 10
```

```kusto
DeviceEvents
| take 10
```

---

## Observations

The Microsoft Learn training tenant does not contain endpoint telemetry.

Although all KQL queries executed successfully, the environment returned:

> No results found in the specified time frame.

This behaviour is expected within the limited Microsoft Learn sandbox environment and confirms successful query execution without available telemetry.

---

## Skills practiced

- Microsoft Sentinel
- Microsoft Defender XDR
- Advanced Hunting
- Kusto Query Language (KQL)
- Threat Hunting
- Security Investigation
- Query Validation
