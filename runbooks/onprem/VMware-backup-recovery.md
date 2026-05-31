# VMware On-Prem Backup Recovery Runbook

## RTO: 4 hours | RPO: 24 hours

## Overview
Recovery procedure for on-premises VMware servers using backup restoration.

## Recovery Steps
1. Identify failed server and notify Change Management
2. Access backup console and locate latest snapshot
3. Initiate restore to target host
4. Validate services post-recovery
5. Update DR report and notify stakeholders
