# azure-data-engineering-labs

Practice repo for Azure Data Engineering at data-engineer level.
Hands-on labs following the ADF + Databricks + Synapse stack, with
notebooks, SQL, and notes committed as I progress.

## Structure

| Folder             | What's inside                                          |
|--------------------|-------------------------------------------------------|
| `00-fundamentals/` | Python basics, SQL basics, notes                      |
| `01-adf/`          | Azure Data Factory — pipelines, exercises, dataflows  |
| `02-databricks/`   | Spark/PySpark — core, spark-sql, optimization, delta-lake, streaming |
| `03-synapse/`      | Azure Synapse — notebooks, SQL                         |
| `04-fabric/`       | Microsoft Fabric — notes (later)                       |
| `99-project/`      | End-to-end migration project                          |
| `interview/`       | Interview questions, resume, mock notes               |

## Notes on storage

- Notebooks are committed as source (`.py` / `.ipynb`), not `.dbc`.
- `.dbc` backups (if any) live in `02-databricks/archive_dbc/`.
- No data files, secrets, or credentials are committed.

## Workflow

Write in Cursor / DBeaver → commit → push. Run code in Azure services;
Git stays the source of truth.
