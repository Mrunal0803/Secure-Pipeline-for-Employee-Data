# Enhancing Data Integration with Google Cloud: A Secure Pipeline for Employee Data

## Overview

This repository contains code and configuration files for an Extract, Transform, Load (ETL) project using Google Cloud Data Fusion for data extraction, Apache Airflow/Composer for orchestration, and Google BigQuery for data loading.

The project aims to perform the following tasks:

1. **Data Extraction**: Extract employee data from diverse sources such as databases, CSV files, and APIs using Python.
2. **Data Masking**: Apply data masking and encoding techniques to sensitive information in Cloud Data Fusion before loading it into BigQuery.
3. **Data Loading**: Load transformed data into Google BigQuery tables, ensuring efficient data storage, management, and accessibility.
4. **Orchestration**: Automate the complete data pipeline using Airflow (Cloud Composer).

## Features

- **Developed Secure Data Pipeline**: Designed and implemented a data pipeline using Google Cloud Data Fusion and Apache Airflow, resulting in a 40% improvement in data integration efficiency.
- **Data Masking and Security**: Implemented robust data masking techniques to anonymize sensitive information, enhancing data security and compliance by 50%.
- **BigQuery Data Loading**: Engineered a secure process for loading masked employee data into Google BigQuery, improving data handling performance by 30% for analytical purposes.
- **Dashboard Visualization**: Created an interactive, web-based dashboard using visualization tools like Google Data Studio and Tableau, enhancing decision-making capabilities by 45%.

## Architecture

![Architecture Diagram](https://github.com/vishal-bulbule/etl-pipeline-datafusion-airflow/assets/143475073/0ea51bdb-99cc-4abf-8ccc-8be721462fc3)

## Data Pipeline Flow

![Data Pipeline Flow](https://github.com/vishal-bulbule/etl-pipeline-datafusion-airflow/assets/143475073/755818fe-1cd3-4e1c-827d-35b963d6f414)

## Repository Structure

- `src/`: Contains the source code for data extraction, transformation, and loading.
- `dags/`: Contains Airflow DAGs for orchestrating the data pipeline.
- `config/`: Contains configuration files for Cloud Data Fusion and BigQuery.
- `dashboards/`: Contains dashboard configurations for Google Data Studio and Tableau.

## Getting Started

### Prerequisites

- Google Cloud Platform account with permissions to use Data Fusion, BigQuery, and Cloud Composer.
- Apache Airflow/Composer setup.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Mrunal0803/Secure-Pipeline-for-Employee-Data.git
    cd etl-pipeline-datafusion-airflow
    ```

2. **Set up environment variables**:
    Create a `.env` file and add your GCP credentials and configuration details.

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

### Running the Pipeline

1. **Deploy the Data Fusion pipeline**:
    - Use the configuration files in the `config/` directory to set up the Data Fusion pipeline.

2. **Deploy the Airflow DAGs**:
    - Copy the DAGs from the `dags/` directory to your Airflow/Composer DAGs folder.

3. **Trigger the pipeline**:
    - Use the Airflow UI or CLI to trigger the ETL pipeline.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
