# End To End Machine Learning Pipeline CI/CD Pipeline with MLflow and DagsHub

## Table of Contents

1. [About The Project](#about-the-project)
   - [Built With](#built-with)
2. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
3. [Usage](#usage)
4. [References](#references)
5. [Contact](#contact)

---

## About The Project

The **End2End-ML-Pipeline** is a comprehensive, end-to-end machine learning workflow that automates the entire lifecycle of a machine learning project, from data ingestion to model deployment. It is designed to handle all the critical steps involved in building and maintaining machine learning models, ensuring efficiency, reproducibility, and scalability.

The **End2End-ML-Pipeline** automates the full machine learning lifecycle, from data ingestion to deployment. It starts by ingesting raw data from Mongo DB followed by data validation to ensure quality. The data is then preprocessed through normalization, encoding, and feature engineering for model training.

Machine learning models are built using libraries like **Scikit-learn** and **TensorFlow**, with hyperparameter tuning and performance evaluation based on metrics like accuracy and precision. **MLflow** tracks experiments, logs metrics, and manages model versioning, making it easy to compare and select the best model.

Once evaluated, the model is deployed for real-time predictions using **FastAPI**. **Docker** ensures consistent environments across development and production. **DagsHub** enables version control and collaboration, tracking datasets, models, and code for seamless team collaboration.

### Topics Implemented:
- Data Transformation
- Data Validation using Drift
- Model Training using Machine Learning Algorithms
- Model Evaluation
- Model Performance
- Logging Exceptions

---

## Built With

The tools that have been used in the project are:

- **MLflow**
- **DagsHub**
- **Docker**
- **AWS S3**
- **AWS EC2**

---

## Getting Started

### Introduction

Automated machine learning pipelines are required to provide a solution to handle huge data. A pipeline like this will make it easier to track experiments, maintain models, and deploy them into production. Whether you're working alone or as part of a team, this pipeline ensures that your machine learning models are developed, tested, and deployed in a consistent and streamlined manner.

![ML Pipeline]()

### Prerequisites

Before running this project, ensure you have the following installed on your system:

- **Python 3.7+** (Recommended: 3.8 or 3.9)
- **Docker** (For containerization)
- **Git** (For version control)
- **MLflow** (For model tracking and deployment)
- **DagsHub** (For versioning data, models, and code)
- **AWS Account** (For deployment)
- **Scikit-learn** (For model building)

### Installation

1. **Download Python Packages**  
   Install the necessary Python packages listed in `requirements.txt`:

   ```bash
   pip install -r requirements.txt


