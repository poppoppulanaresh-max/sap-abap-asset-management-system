# sap-abap-asset-management-system


## Project Overview

This project is developed using SAP ABAP to manage employee asset allocation within an organization.
The system maintains employee records, asset details, and allocation tracking using custom SAP database tables.

Smart Forms are used to dynamically generate asset allocation documents.

---

## Technologies Used

* SAP GUI
* ABAP Programming
* SE11 Data Dictionary
* SE38 Reports
* Smart Forms
* Driver Programs
* ALV Reports

---

## Project Features

* Employee Management
* Asset Management
* Asset Allocation Tracking
* Dynamic Smart Form Generation
* Database Integration
* ALV Reporting

---

## Custom Database Tables

### Employee Table

`ZEMPLOYEE_DT1`

Fields:

* EMP_ID
* EMP_NAME
* DEPARTMENT
* PHONE
* EMAIL
* STATUS

---

### Asset Table

`ZASSET_DT1`

Fields:

* ASSET_ID
* ASSET_NAME
* CATEGORY
* PURCHASE_DATE
* STATUS

---

### Allocation Table

`ZALLOC_DT1`

Fields:

* ALLOC_ID
* EMP_ID
* ASSET_ID
* ALLOC_DATE
* RETURN_DATE
* STATUS

---

## Reports Developed

### ZEMPLOYEE_REPORT_DT1

* Employee management report

### ZASSET_REPORT_DT1

* Asset management report

### ZEMPLOYEE_ALV_DT1

* Interactive ALV report

---

## Smart Form

### Smart Form Name
`ZASSET_FORM_DT1`

### Driver Program
`ZCALL_SMARTFORM_DT1`
Features:
* Dynamic data fetching
* Smart Form preview generation
* Database integration
* Asset allocation document generation
---
## Screenshots
Project screenshots are available inside the `Screenshots` folder.
---
## Documentation
Detailed project documentation is available inside the `Documentation` folder.
---
## Author

Naresh Poppoppula
