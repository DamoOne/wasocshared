# Palo Alto Expedition - Admin Account Takeover Vulnerability - 20240712001

## Overview

Palo Alto Networks, has released a critical security advisory related to Palo Alto Expedition configuration management tool.

Missing authentication for a critical function in Palo Alto Networks Expedition can lead to an Expedition admin account takeover for attackers with network access to Expedition.

Note: Expedition is a tool aiding in configuration migration, tuning, and enrichment. Configuration secrets, credentials, and other data imported into Expedition is at risk due to this issue.

## What is vulnerable?

| Product(s) Affected  | Version(s) Affected   | CVE                                                             | CVSS | Severity     |
| -------------------- | --------------------- | --------------------------------------------------------------- | ---- | ------------ |
| Palo Alto Expedition | 1.2 lower than 1.2.92 | [CVE-2024-5910](https://nvd.nist.gov/vuln/detail/CVE-2024-5910) | 9.3  | **Critical** |

## Recommendation

The WA SOC recommends administrators apply the solutions as per vendor instructions to all affected devices within expected timeframe (refer [Patch Management](../guidelines/patch-management.md)):

## Reference(s)

- Palo Alto: <https://security.paloaltonetworks.com/CVE-2024-5910>

## Additional Reference(s)

- SecurityOnline: <https://securityonline.info/cve-2024-5910-critical-vulnerability-threatens-palo-alto-networks-expedition/>

### Change Log

- 2024-July-12: Initial publication.
- 2024-November-11: Update of vulnerability information.
