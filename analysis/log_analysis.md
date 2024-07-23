# Log Analysis

## Analyzing Logs from Honeypots
1. Open Azure Monitor and navigate to `Logs`.
2. Use Kusto Query Language (KQL) to query the logs:
   ```kusto
   // Example KQL query
   SecurityEvent
   | where TimeGenerated > ago(24h)
   | summarize count() by bin(TimeGenerated, 1h)

