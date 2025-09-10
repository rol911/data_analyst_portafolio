# Measure Equipment Inventory

This project is an integrated solution for managing measurement equipment, developed in Power Apps  with integration to Power BI, Power Automate, and Excel. It allows companies to efficiently manage their measurement instruments inventory, calibration schedules, and access to certificates.

## Main Features

- Equipment Management:
  - Registration of new instruments with key data:
    - Unique ID  
    - Type  
    - Location  
    - Status and condition  
    - Department  
    - Calibration date  
    - Equipment image  
    - Calibration certificate (link/file)

- Automation:
  - Automatic email notifications whenever equipment is added or updated.  
  - Dynamic export of selected information to Excel.  

- Power BI Dashboard:
  - Indicators of expired and active equipment.  
  - Distribution of equipment by location and department.  
  - Summary of calibrations scheduled for the current month.  
  - Interactive visualizations for audits and quality control.  

## Solution Architecture

- Power Apps - Interface for equipment registration and queries.  
- Dataverse/Excel - Structured data storage.  
- Power Automate  - Workflows for notifications and automated reporting.  
- Power BI - Dashboard with KPIs and real-time analysis.  

## Data Export
- Option to export filtered equipment records to an Excel file.  
- Compatible with internal reports and calibration audits.  

## Notifications
- Each time equipment is added or updated, the app sends an automatic email with the details of the update to the designated personnel.  

## Technologies Used
- Microsoft Power Apps - Main management application.  
- Power BI - Data visualization and KPIs.  
- Power Automate - Automation of notifications and exports.  
- Excel - Data storage and export support.  

## Benefits
- Centralized control of all measurement equipment.  
- Reduced risk of using equipment that is out of calibration.  
- Transparency during audits with easy access to certificates.
- Efficiency through automated reports and notification
