# databricks_lakehouse_project

🏗️ Architecture
The project follows the medallion architecture:

Bronze layer: the raw files, stored as Delta tables as they arrive.
Silver layer: the data cleaned, standardized and typed.
Gold layer: a dimensional model, ready for BI and analysis.
Tools: Databricks, Apache Spark, PySpark, Spark SQL, Delta Lake and Unity Catalog.



