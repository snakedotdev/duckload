# duckload
The fastest and easiest way to load data to duckdb. Any database or data lake. No coding required.

## Goals
- YAML based configuration
- High performance, parallel loading

## Supported Sources
### Duckdb native
- Postgresql
- Sqlite
- Mysql
- CSV, Parquet & JSON, local or S3

### Duckdb Extensions
- SAP
- Iceberg
- Delta Lake

### connector-x

via https://github.com/sfu-db/connector-x
- Postgres
- Mysql
- Mariadb (through mysql protocol)
- Sqlite
- Redshift (through postgres protocol)
- Clickhouse (through mysql protocol)
- SQL Server
- Azure SQL Database (through mssql protocol)
- Oracle
- Big Query
