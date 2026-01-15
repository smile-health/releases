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

## New Features & Enhancement
### Nomenclature Enhancement
An update from the previous one, namely an update to the wording or terminology to make it easier for users who experience difficulties when encountering terms that differ from the previous version.
| Old Term                     | New Terms                    | Platform        |
|------------------------------|------------------------------|-----------------|
| Platform                     | Vendor                       | Web             |
| Sender                       | Customer                     | Web & Mobile    |
| Receiver                     | Receiver                     | Web & Mobile    |
| Return Acceptance            | Return                       | Web             |
| Stock on Hand                | Remaining Stock              | Web & Mobile    |
| Active Substance Material    | Product Template Material    | Web & Mobile    |
| Trademark Material           | Product Variants Material    | Web & Mobile    |
| Batch Notes                  | Allocation Notes             | Web             |
| Return of Health Facilities  | Return of Last Mile          | Web & Mobile    |

![Image](images/2.1.webp)
![Image](images/2.2.webp)
![Image](images/2.3.webp) ![Image](images/2.4.webp)


### Navbar Navigation Menu Enhancement
The update from the previous was that the old navbar menu only had 3 main menus. The new navbar menu now has 5 main menus, with feature grouping based on relevant categories.

![Image](images/2.5.webp)
![Image](images/2.6.webp) 

> ℹ️ To see the mapping of the appearance of the **old navbar menu** and the **new navbar menu**, please refer to the **Quick Guide**.

### Notification Enhancement
The update from the previous version is the addition of a notification feature to showed the scheduling of assets (asset status, asset warranty, asset calibration, asset maintenance and asset temperature excursion), normal stock and inactive entities. In addition, updates feature notifications appear via device and email. 

#### Application
Here are the notification type updates in SMILE 5.0:
| No. | Notification Type                   | When to Get Notification                                                                 |
|-----|-------------------------------------|------------------------------------------------------------------------------------------|
| 1   | Asset Status is Changed             | Assets have been updated in asset status                                                 |
| 2   | Asset Warranty Reminder             | Asset warranty past the warranty date                                                    |
| 3   | Asset Calibration Reminder          | Asset calibration will expire in 1, 7, or 14 days<br>Schedule the calibration of upcoming assets before 1, 3, 7, or 14 days |
| 4   | Asset Maintenance Reminder          | Asset maintenance will expire in 1, 7, or 14 days<br>Upcoming asset maintenance schedule before 1, 3, 7, or 14 days |
| 5   | Inactive Entity                     | Entity does not transact/consume for 7, 14, 21 to 60 days                                |
| 6   | Stock Levels Returned to Normal     | Material stocks are between the minimum and maximum limits                               |
| 7   | Temperature Excursion               | Asset temperature below the minimum limit for 1 hour non-stop<br>Asset temperature above the maximum limit for 8 hours non-stop. |


![Image](images/2.7.webp) 
![Image](images/2.8.webp) 
![Image](images/2.9.webp) 

> ℹ️ The asset status change notification, asset calibration reminder, asset warranty reminder, asset maintenance reminder and temperature excursion do not display the program type because the asset is global and the asset can have more than 1 program.

### Email
Users can receive and view a summary of notifications via email at daily times.
> ⚠️ Users who are not selected (checked) to receive a daily recap email will not receive a daily summary email.

![Image](images/2.10.webp)
The types of notifications that users will get via email consist of:
| No. | Notification Type                   |
|-----|-------------------------------------|
| 1   | Zero Stock                          |
| 2   | Less Stock                          |
| 3   | Expired Material                    |
| 4   | Order Shipped                       |
| 5   | Inactive Entity                     |
| 6   | Asset Status is Changed             |
| 7   | Asset Warranty Reminder             |
| 8   | Asset Calibration Reminder          |
| 9   | Asset Maintenance Reminder          |
| 10  | Stock Levels Returned to Normal     |


### Global Setting - Assets
The Asset Type, Asset Model, and Asset Vendor Data Master are now merged into one new menu tab in Global Settings and are no longer available in Program Settings. In addition, the Communication Provider Master Data has also been merged into the Asset Vendor Master Data to centralize the management of service provider data.
![Image](images/2.11.webp)

### Global Setting - Assets - PQS Code
The PQS Code Master Data feature serves as a standard set by the WHO for assets related to temperature storage. This feature includes adding, changing, viewing details, and exporting PQS Code.
![Image](images/2.12.webp)

### Global Setting - Material - Material Volume Packaging
The PQS Code Master Data feature serves as a standard set by the WHO for assets related to temperature storage. This feature includes adding, changing, viewing details, and exporting PQS Code.
![Image](images/2.13.webp)

### Asset Inventory
The Asset Inventory feature in the program is moved to a separate sub-menu under Asset Management, along with two new features: Monitoring Device Inventory and Storage Temperature Monitoring.
![Image](images/2.14.webp)
![Image](images/2.15.webp)
![Image](images/2.15.1.png)
![Image](images/2.16.webp)
![Image](images/2.16.1.png)

### Monitoring Device Inventory
The Monitoring Device Inventory feature serves as a temperature monitoring tool information management center that is part of asset management. This feature includes adding, changing, viewing details, and exporting monitoring device within SMILE.

![Image](images/2.17.webp)
![Image](images/2.18.webp)

### Storage Temperature Monitoring
The Storage Temperature Monitoring feature functions as a temperature monitoring center for assets that have a relationship with monitoring devices. This feature includes viewing details, and exporting asset on storage temperature within SMILE.

![Image](images/2.19.webp)
![Image](images/2.19.1.png)
![Image](images/2.19.2.png)


### Disposal Instructions
The Disposal Instructions feature serves to record material disposal instructions carried out by the entity and will then be processed through the Waste Management System (WMS).

The Disposal Instructions menu will appear and be accessible if the entity assigned by the user is already registered in the Waste Management program. If the user entity is not yet registered to the WMS module, then the menu displayed is Self-Destruction.
![Image](images/2.20_disposal.webp)
![Image](images/2.21.webp)
![Image](images/2.22.webp)
![Image](images/2.23.webp)


### Relocation between Program
The Relocation between Program feature is used to move materials from one program to another within the same entity. This feature is equipped with acknowledgement in the form of a checkbox that must be filled in as confirmation that the material transfer has been known by the destination program.
![Image](images/2.24.webp)
![Image](images/2.25.webp)

### Stock Taking
- Improvements to the add stock taking process include:
  - Sorting materials based on the highest stock quantity;
  - Remove of the mandatory SO marker;
  - Addition of a confirmation pop-up before submitting stock taking data. The system will automatically fill in any unentered stock values (stock 0) as 0 before the data is submitted.

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
