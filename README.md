### ETL в hdfs кластере Arenada

#### copy_to_staging description:
1.Extracting and Loading
- Загружаю в datawarehouse, в hive хранилище данные из бд mysql и локальных файлов в формате csv и json  
- код выполнен в Zeppelin ноутбуке с интерпретаторами bash, hive и python

#### spark_snowflakes.ipynb
2. Transforming
- С помошью Apache Spark трансформирум данные из хранилища в 'снежинку' для BI-аналитиков и
в датасет для data scientist

#### airflow.txt
3. В Apache Airflow создаю DAG для всего процесса обработки данных.


