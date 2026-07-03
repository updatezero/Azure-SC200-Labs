# Lab 05 Notes

## What I learned

Advanced Hunting allows security analysts to search large amounts of security telemetry using Kusto Query Language (KQL).

KQL is Microsoft's query language used throughout:

- Microsoft Sentinel
- Microsoft Defender XDR
- Azure Monitor
- Log Analytics

Even when no telemetry exists, successfully executing a query confirms that:

- syntax is valid
- table exists
- query engine is working

---

## Common KQL commands

Take first rows

```kusto
DeviceInfo
| take 10
```

Filter data

```kusto
AlertInfo
| where Severity == "High"
```

Project selected columns

```kusto
DeviceInfo
| project DeviceName, OSPlatform
```

Sort data

```kusto
DeviceInfo
| sort by Timestamp desc
```

Count rows

```kusto
DeviceInfo
| count
```

---

## Important takeaway

No results do **not** necessarily indicate an error.

Possible reasons include:

- no devices onboarded
- no telemetry collected
- empty Microsoft Learn sandbox
- selected time range contains no events

---

## Skills gained

- Basic KQL syntax
- Executing hunting queries
- Understanding Microsoft Sentinel hunting workflow
- Working with Microsoft Defender XDR
- Interpreting empty query results
