# Lab 06 - Microsoft Defender XDR Custom Detection

## Objective

Create a custom detection rule in Microsoft Defender XDR using an Advanced Hunting KQL query.

## Tasks Completed

- Created a new custom detection.
- Configured the detection name and description.
- Added the KQL query:
  ```kusto
  AlertInfo
  | take 10
  ```
- Configured alert severity and category.
- Configured alert title and description.
- Reviewed the entity mapping requirements.

## Result

The current Microsoft Defender XDR detection wizard requires at least one mapped entity (for example Device or IP address). The sample query does not expose a valid device-related column, therefore the detection cannot be completed without modifying the query.

The lab objective of understanding the custom detection workflow was successfully achieved.
