# RDS Backup Restore Runbook

## RTO: 1 hour | RPO: 5 minutes

## Steps
1. Identify RDS instance failure via CloudWatch alarm
2. Navigate to RDS Console > Snapshots
3. Select latest automated snapshot
4. Restore to new RDS instance
5. Update connection strings and validate application
