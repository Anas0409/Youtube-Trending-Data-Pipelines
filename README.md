# Youtube-Trending-Data-Pipelines
Pipeline ETL serverless sur AWS qui ingère les données YouTube trending de 10 pays via la YouTube Data API v3, les transforme via une architecture Medallion (Bronze→Silver→Gold) avec contrôle qualité, orchestré par Step Functions. Tables analytiques interrogeables avec Athena. (S3 · Lambda · Glue · PySpark · SNS)
