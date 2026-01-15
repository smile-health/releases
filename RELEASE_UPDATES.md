# SMILE Update Release Note

## About
This document provides information on the enhancement and update features of **SMILE**.

---

## Table Of Content
- [SMILE 5.0 - December 23, 2025](#smile-50----december-23-2025)
- [SMILE 5.0 - November 19, 2025](#smile-50----november-19-2025)
- [SMILE 5.0 - August 15, 2025](#smile-50----august-15-2025)
- [SMILE 5.0 - July 16, 2025](#smile-50----july-16-2025)
- [SMILE 5.0 - June 18, 2025](#smile-50----june-18-2025)
- [SMILE 5.0 - May 27, 2025](#smile-50----may-27-2025)
- [SMILE 5.0 - February 28, 2025](#smile-50----february-28-2025)
- [SMILE 5.0 - October 29, 2024](#smile-50----october-29-2024)
- [SMILE 5.0 - September 20, 2024](#smile-50----september-20-2024)
- [SMILE 5.0 - August 2, 2024](#smile-50----august-2-2024)
- [SMILE 5.0 - July 22, 2024](#smile-50----july-22-2024)
- [SMILE 5.0 - July 9, 2024](#smile-50----july-9-2024)
- [SMILE 5.0 - March 15, 2024](#smile-50----march-15-2024)
- [SMILE 5.0 - February 7, 2024](#smile-50----february-7-2024)

---

## Page Contents

### SMILE 5.0 -- December 23, 2025 
[SMILE 5.0 - Release Version 5.1.2] [Download Application Android Version](https://play.google.com/store/apps/details?hl=id&id=com.logistikimunisasi.mobile) 

[SMILE 5.0 - Release Version 5.1.2] [Download Application iOS Version](https://apps.apple.com/id/app/smile-indonesia/id1597558819)

[SMILE 5.0 - Release Version 5.1.2] [SMILE Web](https://smile.kemkes.go.id/)

## Summary of the Feature Updates in this release

- **Restricted Usage of Budget Sources in Global Settings** *Enhancement*  
  Super Admins can now create or change budget sources by specifying the use of budget sources, which are **restricted** or **unrestricted** according to needs.

- **Add Stock Transactions with Restricted Budget Sources** *Enhancement*  
  When create add stock transactions, users can see a list of budget sources along with limited or unlimited information. Budget sources with **restricted** information cannot be selected for transactions.

- **Reduce Stock Transactions with Restricted Budget Sources** *Enhancement*  
  Users cannot create reduce stock transactions if they use **restricted budget** sources.

### Enhancement Features

## Restricted Usage of Budget Sources in Global Settings

This update adds a **Restricted Usage** column to the budget source in Global Settings, allowing Super Admins to determine whether a budget source is **restricted** or **unrestricted** as needed.
This column is available on Create Budget Source, Edit Budget Source, Budget Source Detail page, Budget Source Detail in Program Settings.

![Detail Sumber Anggaran](images/1.1.png)


## Add Stock Transactions with Restricted Budget Sources 
In the add stock transactions, the system displays information on the status of each budget source. Budget sources with limited (restricted) information cannot be selected to proceed with the add stock transaction. 

![Image](images/1.2.png)
![Image](images/1.3.png)

## Reduce Stock Transactions with Restricted Budget Sources
Users cannot perform stock reduction transactions for materials that use restricted budget sources.

![Image](images/1.4.png)

---

## SMILE 5.0 -- November 19, 2025

[SMILE 5.0 - Release Version 5.1] [Download Application iOS Version](https://apps.apple.com/id/app/smile-indonesia/id1597558819)

[SMILE 5.0 - Release Version 5.1] [SMILE Web](https://smile.kemkes.go.id/)

### Summary of the Feature Updates in this release

- Nomenclature <sup>_Enhancement_</sup>  
  Updates and adjustments to the **words, terms, or wording** used in the SMILE system.

- Navbar Navigation Menu** <sup>_Enhancement_</sup>  
  Updated menu view to group features by relevant categories, improving the user experience.

- Notifications <sup>_Enhancement_</sup>  
  Added notification features to display scheduling information and asset status, normal restock, and inactive entities. Notifications are also displayed through the device and sent in the form of a recap via email.

- Global Setting – Assets
  - Global Setting – Asset <sup>_Enhancement_</sup>  
    Changes to the menus on *Asset Type*, *Asset Model*, and *Asset Vendor* to a new menu. In addition, the master data of *communication providers* is now merged into the *Asset Vendor* master data.

  - Global Setting – Asset – PQS Code <sup>_New Feature_</sup>  
    The *PQS Code* master data serves as a standard set by the WHO for assets related to temperature storage.

- Global Setting – Material Volume Packaging <sup>_New Feature_</sup>  
  The *Material Packaging Volume* master data serves as the center for managing the standard information of the packaging volume for each material.

- Asset Inventory <sup>_Enhancement_</sup>  
  The Asset Inventory feature in the program is moved to a separate sub-menu under Asset Management, along with two new features: Monitoring Device Inventory and Storage Temperature Monitoring.
  - Monitoring Device Inventory <sup>_New Feature_</sup>  
  Serves as a centralized feature for managing temperature monitoring device information.

- Storage Temperature Monitoring <sup>_New Feature_</sup>  
  Functions to monitor temperature conditions of assets that are connected to temperature monitoring devices at specific times.

- Disposal Instructions <sup>_New Feature_</sup>  
  Records material destruction instructions carried out by the entity and processes them through the Waste Management System (WMS). This feature is only accessible to users whose entities are assigned to the WMS module.

- Relocation between Programs <sup>_New Feature_</sup>  
  Used to move materials from one program to another within the same entity.

- Stock Taking <sup>_Enhancement_</sup>  
  Improvements to the add stock taking process include:
  - Sorting materials based on the highest stock quantity
  - Removal of the mandatory SO marker
  - Addition of a confirmation pop-up before submitting stock taking data  
    The system automatically fills unentered stock values (stock 0) as **0** before submission.

- Dashboard <sup>_New Feature_</sup>

  - Order Response Time Dashboard <sup>_New Feature_</sup>  
    Order Response Time Dashboard displays a summary of information related to the duration of the order process, from the time the order was placed to the customer's receipt.
    
  - Order Difference Dashboard <sup>_New Feature_</sup>  
    The Order Difference Dashboard functions to display a summary of the amount of quantity or dosage information at each stage of the order process, from the time the order is placed to received by the customer.

  - Reception & Distribution Dashboard <sup>_New Feature_</sup>  
    The Reception & Distribution dashboard serves to display a summary of information on the amount of quantity received by the entity as well as the amount of quantity distributed by the entity.

  - Stock Abnormal Dashboard <sup>_New Feature_</sup>  
    The Abnormal Stock Dashboard functions to display a summary of the abnormal material stock condition of each transaction in an entity in a given period.

  - Add/Remove Stock Dashboard <sup>_New Feature_</sup>  
    The Add/Remove Stock dashboard displays a summary of the amount of material stock each transaction of adding and decreasing stock to an entity in a given period.

  - Discard Dashboard <sup>_New Feature_</sup>  
    The Discard Dashboard functions to display a summary of the total accumulated quantity/amount of stock in disposal transactions for each reason on an entity in a given period.



---

## SMILE 5.0 - New🌟

### Overview

We are proud to announce the launch of SMILE 5.0, a significant milestone in the evolution of the SMILE application, transforming into a service-based modular architecture. Using a strangling strategy, this transformation is carried out gradually so that modules in SMILE 3.0 are replaced by independent services that provide better scalability and flexibility.

 
Key Points in This Release

- Service Modularization: Core modules have been transformed into standalone services, facilitating application management, development, and performance improvement.
- Iterative Release Strategy: SMILE 5.0 is launched gradually, so migration from SMILE 3.0 is not done all at once in one major release.
- New Features & Enhancements: Addition of program selection Homepage, Stock Transfer, Relocation features, along with user experience and user interface (UI/UX) improvements that provide a consistent look and easier access to important information.
- Refactoring and Scalability: Code has been refactored to improve stability, performance, and application readiness in a cloud environment.
- Fulfillment of Non-Functional Requirements: Aspects such as scalability, cloud readiness, and CI/CD automation standards in accordance with DPG (Digital Public Goods) guidelines have been comprehensively implemented.

### Background

This transformation is a strategic step to present a SMILE application that is more prepared to accommodate future needs, with a modern technological foundation that allows for faster and easier service integration and development.

 ### New Features and Enhancement

#### Program Homepage 🌟

The Program Homepage feature, as the main display that facilitates users to access various modules and functions in an integrated manner, is still under development and will be added in the next release soon.

#### Relocation Feature 🌟

The relocation feature is accessed via the Orders > Relocation Request menu, supporting stock transfers between locations with better management.

#### Stock Transfer Feature 🌟

The stock transfer feature is accessed via the Inventory > Stock Transfer menu, allowing precise and easy stock transfers between programs.

#### Main Feature Simplification

Process simplification for the following features:

- Report Incident
- Reconciliation
- Stock Opname
- Cash/Goods Asset Inventory
- Disposal Shipment
- Self-Disposal

---

### August 15, 2025

1. Annual Commitment vs Realization Dashboard 
The "Annual Commitment vs Realization" feature monitors the quantitative achievement of commitment allocations and buffer stocks for vaccines and other logistics set by the Indonesian Ministry of Health for each province during one fiscal year.​
​

2. Email Notification for Stock <50% of National Quarterly Need: Every day, the system checks stock availability and compares it with the national quarterly need. If vaccine or BMHP stock is less than 50% of the total national quarterly need, the system will send an email notification to users registered in the Indonesian Ministry of Health, BioFarma, and UNDP entities.​

---

### July 16, 2025 

1. Create Dengue Expenditure Transaction with New Form 

2. Annual Planning and Master Data Development 

3. Notification and Daily Recap Email Development 

4. Setting daily recap recipients using User settings

5. Changing wording in 4 notifications

6. Changing wording and logic in temperature above maximum and below minimum notifications

7. Adding 3 new notifications

---

### June 18, 2025

1. Addition of Filter and KFA 92 Data on Transaction Monitoring Dashboard 

2. Material Expiry Notification at 60 and 90 days 

Users can now record the following information:
| Notification|
|---|
|Warranty start and end dates|
|Last maintenance date|
|Maintenance interval|
|Last calibration date|
|Calibration interval|


Based on the last maintenance date and the set interval, the system will send a reminder notification for the next maintenance schedule 1 day before (H-1).
Based on the last calibration date and the set interval, the system will send a reminder notification for the next calibration schedule 1 day before (H-1).


3. Order Integration with SIHA (HIV/AIDS Information System) and SITB (Tuberculosis Information System) 

---

### May 27, 2025

1. Addition of Filter and KFA 92 Data on Stock Opname List 

2. Change in Progress and Entity Compliance Calculation 

3. Stock Opname Dashboard Versioning 

---

### February 28, 2025

1. Addition of Material Setting for Dengue  

2. Create Dengue Expenditure Transaction 

---

### October 29, 2024


1. Add Annual Commitment from Ministry of Health to Province 

2. Annual Commitment from Ministry of Health to Province Dashboard 

3. Temperature Monitoring Dashboard 

4. Account Profile Data Change 

5. Force Password Change 

6. Update Menu Grouping 

7. Update Rabies Sequence 

8. Update Reminder Notification for Rabies Patients 

9. Update Rabies Dashboard 

10. Formula Adjustment for Stock Availability and Replenishment from Stock Out 

11. iOS Training & Production Logistic 

12. Center Shipment Update 

---

### September 20, 2024
1. Update process for adding stock opname 

2. View recap of stock opname process for a specific period 

3. Download stock book report based on province, district/city, health center, and entity for the required period 

---

### August 2, 2024

1. Perform confirmation to stop Rabies Vaccination notifications 

2. View assets with more than one temperature range and capacity 

---

### July 22, 2024

1. Perform rabies vaccine expenditure with prevention type 

2. Change cold chain temperature limit and view logger activity history 

---

### July 9, 2024

1. View stock with KFA level 

2. Order material with KFA level 

3. View Stock Dashboard with KFA level 

---

### June 13, 2024
1. View Coldchain Capacity with capacity projection 

2. View Capacity for Annual Planning 

3. View Coldchain Capacity Projection in Order 

---

### March 15, 2024


1. View SMILE vs SMDV Dashboard 

2. Perform Asset Inventory in SMILE Logistic 

3. Update flow for performing stock opname in SMILE Immunization 

4. Update Rabies/VAR expenditure feature in SMILE Immunization 

5. View Asset Inventory Dashboard in SMILE Immunization 

6. View Stock Dashboard in SMILE Immunization and Logistic 

7. Addition of Stock Opname Dashboard tab for Ministry of Health in SMILE Immunization 

---

### February 7, 2024

1. View Transaction Monitoring Dashboard in SMILE Logistic 

2. Perform allocation and shipment according to activity flow settings 

3. Download Request Letter, Confirmation Note, and Batch Note documents in the Order detail menu 
