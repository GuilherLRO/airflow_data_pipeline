# airflow_first_project

For this project I want to orchestrate a data pipiline using airflow, docker and postgress. Also create visualizations with an opens ource BI tool called metabase.

## Pipeline current state:
![alt text](https://github.com/GuilherLRO/airflow_data_pipeline/blob/main/image_ckeckpoints/2024-01-07%20full%20pipeline.png?raw=true)

## Checkpoints:

2023-12-17
 - Created and tested the docker environment using a airflow dag to insert records in the database and visualize it in pgadmin.

2023-12-24
 - Implemented functions to extract data via api.

2023-12-29
 - Inserting data into db, creating 'raw" tables and first sql statement to create a 'consumer' tabla

2024-01-07
- Creating "curated" zone with tables ready to be consumed. Simplified download to raw process that was making some transformations now made in the database.
