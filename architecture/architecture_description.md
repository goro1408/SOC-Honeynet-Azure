# Architecture Description

The SOC and Honeynet are deployed in Microsoft Azure. The architecture consists of the following components:

- **Virtual Network (VNet)**: Provides network isolation and security.
- **Honeypot VMs**: Decoy systems to attract cyber attacks.
- **Azure Monitor and Log Analytics**: Collect and store logs from honeypots.
- **Azure Sentinel**: Analyze and correlate log data, create alerts, and automate incident response.

![Architecture Diagram](architecture_diagram.png)

