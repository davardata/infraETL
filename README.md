# infraETL
## Infraestructura General

[ Fuentes de Datos ]
     |      |      |
     v      v      v
[ MongoDB ] [ MariaDB ] [ CSV / API ] 
     |        |       
     v        v     
[ PySpark: Extracción y Transformación ]
     |
     v
[ Redis (cache opcional / pub-sub / control de flujo) ]
     |
     v
[ PostgreSQL como Data Warehouse ]
     |
     v
[ Airflow DAGs ]
     |
     v
[ Capa de Reporting / Visualización / Power BI / Grafos ]  [ ArangoDb ]

## Carpetas
etl-class/
├── docker-compose.yml
├── airflow/
│   └── dags/
├── spark/
│   └── notebooks/
├── data/
│   └── sample.csv
└── scripts/
    └── etl_pyspark.py

