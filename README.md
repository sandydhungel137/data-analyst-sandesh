# data-analyst-sandesh
# Data Wrangling Analysis
<image "Picture1.png">

## Project Title: Implementation of Data Wrangling Analysis of City of Vancouver

### Project Description
The project uses cloud computing services to execute extensive data wrangling procedures when analyzing data about City of Vancouver. This project relies on AWS Glue together with Amazon S3 and additional cloud-based tools to attain accurate and usable consolidated data through cleaning and transformation of data sourced from multiple city-related datasets.

### Objective
The goal of this project is to perform scalable and automated data wrangling for the City of Vancouver (Block numbers) datasets and utilize cloud computing solutions for efficient and cost-effective data processing.

### Background
The City of Vancouver maintains complete datasets about block numbers that incorporate zoning details along with land use documentation and infrastructure records and municipality service data. By using data wrangling techniques, this project aims to enhance data quality, scalability, and automation, ensuring better utilization of datasets for policy-making and research.

### Dataset
City of Vancouver block numbers contain data sets which include zoning information together with land use maps along with property boundary information and road infrastructure and utility network details. Urban planning and public service analysis benefits from data on demographics together with business activity statistics and environmental factors as well as crime information and property details.

### Methodology
#### 1. Data Collection & Ingestion
- Store raw data in Amazon S3 for scalable and secure storage.
- Use AWS Glue Crawlers to automatically detect schema and populate the AWS Glue Data Catalog.

#### 2. Data Assessment
- AWS Glue DataBrew to identify missing values, duplicates, and inconsistencies.
- Document data types, formats, and discrepancies across datasets.
- Log data issues using Amazon CloudWatch Logs for monitoring.

#### 3. Data Cleaning
- Handle missing values using imputation methods in AWS Glue.
- Standardize categorical variables using AWS Lambda.

#### 4. Data Transformation
- Convert data types using AWS Glue ETL scripts.
- Compute new features such as Average Daily Traffic Volume.
- Aggregate data at different levels (monthly/quarterly environmental trends).

#### 5. Data Consolidation
- Ensure data integrity and consistency by linking datasets via unique identifiers.
- Merging of data sources and leveraged DataBrew jobs.

#### 6. Documentation & Validation
- Document the entire data wrangling process in AWS Glue Data Catalog.
- Validate transformed data using Amazon Athena and ensuring data quality.

### Tools & Technologies: Cloud Service Used
- **Amazon S3** - Data Storage
- **AWS Glue, AWS Glue DataBrew, AWS Lambda** - Data Wrangling and Cleaning
- **AWS Glue Data Catalog, Amazon Athena** - Data Profiling and Validation
- **Amazon CloudWatch, AWS CloudTrail** - Monitoring and Logging

### Deliverables
- A cleaned and transformed city dataset stored in Amazon S3 for analytics.
- Challenges encountered & solutions applied.
- Data wrangling process overview for cleaning, merging, and transformation.
- Amazon QuickSight visualizations illustrating traffic trends, air quality analysis, and city service efficiencies.

### Project Timeline
| Phase | Duration |
|--------|----------|
| Data Collection & Assessment | 1 Week |
| Data Cleaning & Transformation | 1 Week |
| Data Consolidation & Validation | 1 Week |
| Documentation & Dashboard Creation | 1 Week |
| **Total Project Duration** | **4 Weeks** |

### Expected Outcomes
- **Enhanced Data Quality**: The analysis of data provides cities with better planning capabilities, transportation control, environmental protection, and public services improvement.
- **Automated & Scalable Workflow**: AWS services ensure minimal manual intervention and high performance.
- **Better Urban Planning**: High-quality data supports infrastructure planning and predictive modeling.

---

# Data Quality Control Analysis

## Project Title: Implementation of Data Quality Control Measures of City of Vancouver

### Project Description
This project aims to build a Data Quality Control (DQC) framework for City of Vancouver block numbers data through cloud computing technologies. The initiative utilizing AWS services works to protect the reliability, consistency, and accuracy of datasets supporting city planning, zoning, and infrastructure development.

### Objective
The main goal of this initiative involves deploying a thorough Data Quality Control framework for block number information at City of Vancouver. Cloud-based solutions rely on this framework to boost data correctness as well as consistency while maintaining complete information which supports urban planning, infrastructure management, and municipal service delivery.

### Background
The City of Vancouver maintains comprehensive records of block numbers together with zoning rules, land utilization information, and infrastructure specifics. The extraction of meaningful findings becomes difficult due to multiple data format inconsistencies, repeating records, unfilled fields, and distributed source databases. The quality issues within data sources trigger negative effects on urban development planning, public services delivery, and violations of regulatory standards. This project will tackle these problems through automatic data quality monitoring processes that combine AWS Glue and Amazon S3 with monitoring solutions which rely on AWS CloudWatch.

### Scope
This project focuses on the following areas:
- **Data Cleansing**: Implementing automated processes to eliminate duplicates.
- **Data Profiling**: Assessing existing datasets to determine the level of quality.
- **Data Validation**: Applying validation rules for ensuring data integrity.
- **Monitoring and Reporting**: Creating dashboards and alerts to track data quality metrics.
- **Training and Awareness**: Educating employees for maintaining high-quality data.

### Methodologies
- **Data Profiling**: Using AWS Glue DataBrew to evaluate data accuracy, completeness, and consistency and identify duplicates, anomalies across datasets.
- **Data Cleaning**: Using AWS Glue ETL to remove duplicates and format inconsistencies.
- **Monitoring and Reporting**: Setting up AWS CloudWatch alerts to flag anomalies in block number data and scheduling automated reports to review data quality over time.
- **Data Quality Metrics**: Tracking duplicate records, missing values, and schema violations using AWS CloudWatch logs.
- **Training and Practices**: Data validation techniques and cloud-based data governance for educating employees.

### Tools and Techniques
- **Data Storage** - Amazon S3
- **Data Validation & Governance** - AWS Lambda, AWS CloudTrail
- **Data Profiling & Cleaning** - AWS Glue, AWS Glue DataBrew
- **Monitoring & Reporting** - AWS CloudWatch, AWS CloudTrail

### Deliverables
- **High-quality block number dataset** stored in Amazon S3.
- **Comprehensive Data Quality Report** covering data quality improvements and challenges addressed.
- **Alerts and Monitoring Dashboard** visualizing error rates, missing values, and geospatial inconsistencies.
- **Educational materials and workshops** on cloud-based data governance for training resources.

### Project Timeline
| Phase | Duration |
|--------|----------|
| Data Profiling and Assessment | 1 Week |
| Data Monitoring & Reporting | 1 Week |
| Data Cleaning & Validation | 1 Week |
| Documentation and Training | 1 Week |
| **Total Project Duration** | **4 Weeks** |

### Expected Outcomes
- **Improved Data Quality**: Reduction in duplicate records and missing values for better planning and infrastructure management.
- **Automated Monitoring**: Real-time alerts to flag data inconsistencies.
- **Data-Driven Decision Making**: High-quality datasets enhance decision-making in urban development and resource allocation.
