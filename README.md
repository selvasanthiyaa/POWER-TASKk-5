POWER-BI-TASK_5 Healthcare Data Analysis using Power BI

Project Overview This Power BI task focuses on preparing and organizing healthcare data for analysis. The data model includes a healthcare dataset, patient details, doctor details, hospital details, admission records, and a date dimension. These tables help organize healthcare information and support date- and entity-based analysis.

Tools Used Microsoft Power BI Desktop Power Query Editor for data preparation and transformation Model view for organizing tables and relationships Report view for presenting data

Tables in the Data Model The PBIX file contains the following tables:

healthcare_dataset – the source healthcare dataset. DimPatient – patient-related details. Dim Doctor – doctor-related details. Dim Hospital – hospital-related details. FactAdmission – admission/transaction records. DimDate – date dimension for date-based analysis. 4. Operations Performed 4.1 Imported healthcare data Loaded the healthcare dataset into Power BI as the source for the report and data model.

4.2 Prepared data in Power Query Used Power Query to organize the data and prepare the required columns for modeling. Review the Applied Steps in Power Query for the exact transformations saved in the file.

4.3 Created dimension tables Organized patient, doctor, hospital, and date information into separate dimension tables. This separates descriptive information from admission records and makes the model easier to understand.

4.4 Created a patient identifier Prepared patient details using fields such as Name, Age, Gender, and Blood Type to support matching patient records. A patient identifier such as PatientID can be used as a key for the patient dimension.

4.5 Merged patient details Used a merge/join operation to match patient records with the patient dimension using the available patient attributes. A left outer join keeps all rows from the primary table and brings in matching details from the patient dimension.

4.6 Organized admission data Kept admission-related records in the FactAdmission table and descriptive attributes in the dimension tables to create a structured data model.

4.7 Added a date dimension Included DimDate to support date-related analysis, such as grouping and filtering information by date or month.

4.8 Organized the data model The model contains separate fact and dimension tables: FactAdmission, DimPatient, Dim Doctor, Dim Hospital, and DimDate, along with the original healthcare_dataset table. Check Model view in Power BI to review the actual relationships and cardinalities.

4.9 Configured report page The report includes a page named Page 1, configured with the Fit to Page display option.

4.10 Applied report settings and theme The report uses the Fluent 2 theme. Report settings also allow summarized data export and support filter/drill interactions.

Concepts Practiced Importing data into Power BI Data preparation using Power Query Creating dimension tables Creating a patient identifier Merging tables using a Left Outer Join Fact and dimension table organization Date dimension Data modeling Report page configuration and theme settings 6.Screenshot Screenshot 2026-10-13 202433
Conclusion This task demonstrates how healthcare data can be prepared and organized in Power BI. By separating patient, doctor, hospital, date, and admission information into dedicated tables, the data model becomes easier to maintain and use for analysis. The report can be extended with appropriate charts, cards, slicers, and other visuals as required.
Note This README is based on the tables and report settings found in the supplied PBIX file and the patient-table merge workflow. The stored report definition does not expose a list of report visuals, so this README does not claim that particular charts, cards, or slicers were created. Confirm the exact Power Query Applied Steps and Model view in Power BI Desktop before submitting if your instructor requires a complete operation-by-operation record.
