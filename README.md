# aws-risk-data-platform

AWS data lake for financial risk analytics using a Medallion Architecture  
(Bronze / Silver / Gold)

## 🏗️ Architecture
- Data sources → S3 Bronze (raw)
- AWS Glue (ETL & Crawlers)
- S3 Silver (cleaned, standardized)
- S3 Gold (analytics-ready)
- Athena / Redshift for querying & BI

## 📁 Repository structure
```text
aws-risk-data-platform/
├── terraform/
│   ├── main.tf
│   ├── variables.tf
│   ├── versions.tf
│   ├── outputs.tf
│   └── README.md
├── diagrams/
│   └── architecture.drawio
└── README.md
