### ETL в hdfs кластере Arenada

#### copy_to_staging description:
1.Extracting
- Переносим в data lake в hive хранилище из бд mysql и локальных файлов в формате csv и json  
- код выполнен в Zeppelin ноутбуке с интерпретаторами bash, hive и python

#### spark_snowflakes.ypunb
2. Transforming
- С помошью Apache Spark трансформирум данные из хранилища в снежинку для BI-аналитиков и
в датасет для data scientist


