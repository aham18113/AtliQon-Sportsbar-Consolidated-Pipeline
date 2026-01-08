# AtliQon-Sportsbar-Consolidated-Pipeline

## Project Architecture
<img src="Images/project_architecture.png" alt="Project Architecture" width="1200">

## Pipeline for the Job Run
<img src="Images/job_run.png" alt="Pipeline for the Job Run" width="1200">

### Repository Structure
├── 1_setup
│   ├── dim_date_table_creation
│   ├── setup_catalogs
│   └── utilities
├── 2_dimension_data_processing
│   ├── 1_customer_data_processing
│   ├── 1_pricing_data_processing
│   └── 1_products_data_processing
├── 3_fact_data_processing
│   ├── 1_full_load
│   └── 2_incremental_load_fact
├── images
│   ├── job_run.png
│   └── project_architecture.png
├── sql_query
├── README.md



