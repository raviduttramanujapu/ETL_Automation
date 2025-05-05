# ETL_Automation
Teradata_Snowflake
ETL_Automation/
├── docs/
│   └── ETL_Validation_Framework_Teradata_Snowflake.docx
├── notebooks/
│   └── ETL_Validation_Framework_Teradata_Snowflake.ipynb


etl_validation_framework/
├── config/
│   └── connections.json
├── validators/
│   ├── row_count.py
│   ├── null_check.py
│   └── duplicate_check.py
├── main.py
├── logger.py
├── alerts.py (SNS/email)
└── requirements.txt
