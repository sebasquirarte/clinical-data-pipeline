# Clinical Data Pipeline

## Overview
This repository demonstrates an **end-to-end clinical data engineering pipeline** using Python, Pandas, PySpark, SQL, and Azure.  It simulates a workflow used in **regulated clinical environments (CDISC/SDTM)** to transform raw clinical datasets into **validated, analysis-ready datasets**.

## Project Goals
- Load and validate raw clinical datasets (DM, AE, EX, VS).  
- Perform **structural and quality checks**.  
- Clean, standardize, and transform data.  
- Join clinical domains to create analysis-ready outputs.  
- Demonstrate modern tools for **data engineering in clinical trials**:  
  - **Python & Pandas** for data manipulation  
  - **PySpark** for distributed processing  
  - **SQL** for querying and validation  
  - **Azure** for cloud deployment and storage  

## Data
Simulated SDTM-formatted datasets were obtained from [CDISC Dataset](https://cdiscdataset.com/).  

- **DM.csv** – Demographics  
- **AE.csv** – Adverse Events  
- **EX.csv** – Exposure  
- **VS.csv** – Vital Signs  
