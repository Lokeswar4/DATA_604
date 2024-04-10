# DATA_604
# Database Management 

## Project Overview

As InsureYours, our company aims to transform the healthcare industry by providing patients with a sophisticated platform to identify the most suitable insurance coverage based on gender, age, and medical condition. With the increasing number of health challenges globally, insurance prices rise accordingly. We believe in offering optimal insurance providers tailored to individual patient profiles to ensure informed decisions about insurance coverage. Through our innovative approach, we seek not only to provide solutions for individual patients but also to revolutionize patient treatment worldwide.

## Database System

Utilizing the Healthcare Dataset, we provide accurate insights and analysis for patients based on gender, age, and medical conditions. By leveraging Prasad Patil’s dataset, we generate insights to aid patients in making optimal decisions regarding their insurance provider. We've designed an Entity Relationship Diagram to depict relationships between values within tables. Employing Extract, Transform, and Load (ETL) processes, we pull data from an online source into our SQL Server virtual database. Visualization tools like Power BI facilitate connectivity between code and insights, ensuring the database reflects incoming data through our ETL process, thus limiting risk.

## Data Processes

- **Data Extraction and Storage**: Data extracted is stored in a SQL Server virtual database. We maintain two main tables: Patient Information and Insurance Information.
  
- **Data Entry and Analysis**: A user-friendly interface enables healthcare providers to enter patient details such as gender, age, and medical conditions. Upon entry, patients receive visualizations suggesting the best insurance provider for their specific medical condition.

## Requirements

### Data Used

- Data sourced from Prasad Patil’s dataset.
- Insights generated to assist patients in optimal choices within hospitals.

### Data Storage Requirements

1. **Patient Information**:
   - PatientID (INT)
   - Name (VARCHAR)
   - Gender (VARCHAR)
   - Age (INT)
   - BloodType (VARCHAR)
   - Medical_Condition (VARCHAR)
   
2. **Insurance Information**:
   - InsuranceID (INT)
   - Insurance_Provider_Name (VARCHAR)

### Data Entry/Capture Process

- **Patient Registration**: User-friendly interface for healthcare providers to input patient details.
- **Insurance Recommendation Input**: After patient details are entered, the system recommends the best insurance provider based on patient profiles.

### Data Types and Validations

- **Data Types**: Appropriate data types (e.g., VARCHAR, INT) ensure consistency with collected data.
- **Validation Rules**: Implemented rules ensure data integrity, including validated age ranges, gender entries, and insurance provider names.

### Reporting Requirements

- **Insurance Recommendations Report**: Displays data on insurance recommendations and associated costs.

## Hardware

To manage large volumes of data while creating analyses, we require a robust virtual machine with features such as 20 Cores, 80 GB of RAM, and 160 GB of Temporary Storage, costing $5,942.46 per month and $71,309.52 per year.
