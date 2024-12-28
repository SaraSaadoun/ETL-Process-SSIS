# ETL-Process-SSIS

This repository contains a data staging pipeline implemented using SQL Server Integration Services (SSIS). It prepares data for analytical and reporting purposes through data extraction, transformation, and loading into a staging area.

**Key Features:**

*   **SSIS Implementation:** Utilizes SQL Server Integration Services for robust data processing.
*   **Data Extraction:** Extracts data from AdventureWorks2022 dataset.
*   **Transformation Logic:** Applies necessary transformations to prepare data for analysis.
*   **Staging Area:** Loads transformed data into a designated staging area.
*   **DWH Conversion:** Converts data from the staging area (STG) to the Data Warehouse (DWH) format.
  
1. Extract Phase: From src (AdventureWorks2022) → To ods
   
**Control flow**:

![image](https://github.com/user-attachments/assets/7375f839-02b5-4378-b47e-15b3c08af0b3)


**Data flow**:

![image](https://github.com/user-attachments/assets/319605ae-c669-4a16-81c0-1f5b64ad957d)
![image](https://github.com/user-attachments/assets/f35e0864-530a-4cd9-b36b-1f0be8056d03)
![image](https://github.com/user-attachments/assets/4c090b0e-2e5b-492c-ab47-6e4e7c0762c6)
![image](https://github.com/user-attachments/assets/6b5ed32c-cf05-4b69-9c27-33bc9610e36b)
![image](https://github.com/user-attachments/assets/10f3d624-cd01-4555-9d58-fa284e1a2154)
![image](https://github.com/user-attachments/assets/87e437ee-9b9e-4fcc-957c-8ec6d36c845a)



2. Transform Phase: From ODS database → to STG database.
   
**Control flow**:

![image](https://github.com/user-attachments/assets/92b7f75c-227f-400d-8f24-68e0b5aeffd9)



**Data flow**:

![image](https://github.com/user-attachments/assets/8b113bc0-5d82-4d1a-99c2-15c7287f4157)


3. Load Phase: From STG database → to DWH database.
   
**Control flow**:

![image](https://github.com/user-attachments/assets/9f4d45e9-cfe3-41b7-97d5-e9e502c72b23)


**Data flow**:

![image](https://github.com/user-attachments/assets/f115f7dd-dd50-42aa-858d-858b0be02c87)

