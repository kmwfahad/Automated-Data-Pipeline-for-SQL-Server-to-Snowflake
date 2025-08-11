# Automated-Data-Pipeline-for-SQL-Server-to-Snowflake
To ensure uninterrupted data access during integration failures, I built a semi-automated backup ETL pipeline. The goal was to restore .bak (backup) files into a SQL Server instance, extract the relevant tables as CSVs, and upload them into Snowflake — all without relying on third-party services like Fivetrans during outages.
