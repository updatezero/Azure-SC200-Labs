# Notes - Lab 06

## What I learned

- Microsoft Defender XDR uses KQL queries for custom detections.
- Custom detections require:
  - Detection name
  - Severity
  - Category
  - Alert settings
- The new detection wizard requires entity mapping.
- Entity mapping needs a valid device or IP related column.
- Simple demonstration queries such as:

```kusto
AlertInfo
| take 10
```

may not provide the required fields.

## Key Takeaways

- Advanced Hunting queries are the foundation of custom detections.
- Entity mapping improves incident correlation.
- Not every KQL query can immediately be converted into a detection rule.
