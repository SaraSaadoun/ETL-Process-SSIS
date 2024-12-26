# ETL-Process-SSIS

This repository contains a data staging pipeline implemented using SQL Server Integration Services (SSIS). It prepares data for analytical and reporting purposes through data extraction, transformation, and loading into a staging area.

**Key Features:**

*   **SSIS Implementation:** Utilizes SQL Server Integration Services for robust data processing.
*   **Data Extraction:** Extracts data from AdventureWorks2022 dataset.
*   **Transformation Logic:** Applies necessary transformations to prepare data for analysis.
*   **Staging Area:** Loads transformed data into a designated staging area.

1. Extract Phase: From src (AdventureWorks2022) → To ods
   
**Control flow**:

![image](https://github.com/user-attachments/assets/fa1b6a7a-4b6d-4641-8c26-6359f6baad4e)


**Data Flow**:

![image](https://github.com/user-attachments/assets/6e1264b6-7945-4deb-9610-89f3516d5d0c)
![image](https://github.com/user-attachments/assets/f8447650-40f0-4d12-82c3-bad4ccfe389b)
![image](https://github.com/user-attachments/assets/5330c029-39bf-4cf3-89ee-96429ec2b4d6)


2. Transform Phase: From ODS database → to STG database.
   
**Control flow**:

![image](https://github.com/user-attachments/assets/ab5888c4-c7d0-42b4-888b-19d0d5bf0040)


**Data Flow**:

![image](https://github.com/user-attachments/assets/2eb0442d-e581-40c7-8167-2f59f30ddead)

3. Load Phase: From STG database → to DWH database.

**Current Status:**
The data extraction, transformation, and loading into the staging area are complete. Further work is in progress on the final step *after* the staging process.

