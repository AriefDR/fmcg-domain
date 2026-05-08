# Data Integration Project – Atlikon & Sport Bar

This project demonstrates a real-world **data integration scenario** between a mature enterprise system and a newly acquired startup company using a modern Data Warehouse approach.

---

# 🏢 Project Background

**Atlikon** is a global manufacturing company specializing in sports equipment.  
It operates a **mature ERP-driven data system** that is well-structured, stable, and highly reliable.

Recently, Atlikon acquired a fast-growing startup called **Sport Bar**, which operates in the **energy bar and athletic nutrition industry**.

Unlike Atlikon, Sport Bar data is:
- Not fully standardized  
- Stored in multiple CSV files with inconsistent structure  
- Requires cleaning and harmonization before analysis  

---

# 🎯 Project Objective

The goal of this project is to **integrate data from Atlikon and Sport Bar into a unified analytical data platform** using the Medallion Architecture.

- Atlikon → already structured, processed directly into the Gold layer  
- Sport Bar → requires full ETL pipeline development (Bronze → Silver → Gold)

---

# 🏗️ Architecture

This project follows the **Medallion Architecture**:
![Data Architecture](datasets/architecture/project_architecture.png)

## 🥉 Bronze Layer
- Raw ingestion of CSV files from Sport Bar
- Data is loaded as-is without transformation
- Serves as the landing zone for raw datasets

## 🥈 Silver Layer
- Data cleaning and standardization
- Handling missing values, duplicates, and inconsistent formats
- Aligning Sport Bar data structure with Atlikon standards

## 🥇 Gold Layer
- Final business-ready data model
- Integrated dataset between Atlikon and Sport Bar
- Optimized for analytics and reporting

---

# 📊 Data Characteristics

## 🏭 Atlikon Data
- Mature ERP-based system
- Highly structured and consistent
- Directly processed into Gold layer

## 🥤 Sport Bar Data
- Provided as multiple CSV files
- Requires data cleansing and transformation
- Contains:
  - Historical data (past records)
  - Incremental / latest data updates

---

# ⚙️ Key Challenges Solved

- Standardizing inconsistent CSV structures  
- Cleaning and transforming raw startup data  
- Aligning startup data model with enterprise schema  
- Integrating two different data maturity levels  
- Building a unified analytics-ready dataset  

---

# 🛠️ Technologies Used

- Databricks  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Medallion Architecture  

---

# 📌 Key Concepts Applied

- Data Lakehouse architecture  
- ETL pipeline design  
- Data cleaning and standardization  
- Dimensional modeling  
- Data integration (enterprise + startup data)  
- Medallion architecture implementation  

---

# 🚀 Outcome

At the end of this project:
- Atlikon and Sport Bar data are unified into a single data model  
- Raw CSV data is transformed into structured analytical tables  
- Data quality issues are resolved in Silver layer  
- Gold layer provides business-ready datasets for analytics  

---


# 🌟 About Me

Hi, I'm **Arief Dwi Rachmadian** 👋  

I am a **Data Engineer** with hands-on experience building scalable data pipelines and modern data warehouse solutions using:

- PostgreSQL  
- Python  
- AWS (S3, ECS, ECR, Lambda)  
- Docker  
- SQL-based ETL pipelines  

Let’s build reliable data systems together 🚀