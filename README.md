# ADF Data Ingestion Pipeline


# Azure Data Factory Data Ingestion Pipeline

This project demonstrates a basic data ingestion pipeline built in Azure Data Factory (ADF). I configured linked services, datasets, and pipeline activities to move structured data from a source file into a target destination, and used GitHub integration for version control of ADF artifacts.

## Project Objective
The goal of this project is to showcase hands-on experience with Azure Data Factory by building and documenting a simple ETL/data movement workflow as part of my data portfolio.

## Tools & Technologies
- Azure Data Factory
- GitHub integration with ADF
- CSV data
- Linked Services
- Datasets
- Data flows
- Copy Activity

## Project Workflow
1. Connected Azure Data Factory to GitHub for source control
2. Created linked services for source and target connections
3. Defined source and sink datasets
4. Built a pipeline to move data from source to target
5. Ran and validated the pipeline successfully
6. Stored ADF JSON artifacts in GitHub automatically

## Repository Structure
- `pipeline/` - ADF pipeline JSON files
- `dataset/` - ADF dataset JSON files
- `linkedService/` - linked service JSON files
- `factory/` - ADF factory-level configuration
- `screenshots/` - screenshots of the pipeline and execution
- `data/` - sample input data
- `docs/` - additional notes or diagrams

## Screenshots

### Pipeline Overview
![Pipeline Overview](screenshots/01-pipeline-overview.png)

### Data Flow Dataset
![Source Dataset](screenshots/02-dataflow.png)

### Source Dataset
![Source Dataset](screenshots/03-dataset-01.png)

### Sink Dataset
![Sink Dataset](screenshots/03-dataset-02.png)

### Linked Service
![Linked Service](screenshots/04-linked-service.png)

## Key Skills Demonstrated
- Azure Data Factory pipeline development
- Data ingestion and orchestration
- Linked service and dataset configuration
- Pipeline execution and debugging
- Parameterized pipelines
- GitHub-based version control for ADF

## Future Enhancements
- Add triggers and scheduling
- Add transformation logic
- Extend pipeline to Snowflake or Azure SQL
- Build a Power BI dashboard on top of the curated output

## Author
Akhila Dandu
