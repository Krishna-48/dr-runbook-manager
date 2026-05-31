# DR Runbook Manager
Disaster Recovery runbook for AWS & On-prem Environments.
![DR Runbook Validation](https://github.com/Krishna-48/dr-runbook-manager/actions/workflows/validate-runbooks.yml/badge.svg)

## Overview
Enterprise DR runbooks for AWS multi-region and on-prem environments.
Manages RTO < 15 min and RPO < 5 min for Tier-1 workloads.

## Structure

runbooks/
├── aws/        # EC2, RDS, Route53 DR procedures
├── onprem/     # VMware backup & recovery
└── templates/  # BCP, BIA templates

## Tech Stack
AWS | Terraform | GitHub Actions | Python | Kubernetes

## CI/CD
GitHub Actions automatically validates all runbooks on every push.
Pipeline checks file existence, RTO/RPO definitions, and word count.

## Usage
git clone https://github.com/Krishna-48/dr-runbook-manager

## Author
Banda Krishna Reddy — Cloud & DR Engineer 
