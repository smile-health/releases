# SMILE Update Release Note

## About
This document provides information on the enhancement and update features of **SMILE**.

---

## Table Of Content
- [SMILE 5.0 - December 23, 2025](#smile-50---december-23-2025)
- [SMILE 5.0 - November 19, 2025](#smile-50---november-19-2025)
- [SMILE 5.0 - September 15, 2025](#smile-50---september-15-2025)
- [SMILE 3.0 - August 15, 2025](#smile-50---august-15-2025)
- [SMILE 3.0 - July 16, 2025](#smile-30---july-16-2025)
- [SMILE 3.0 - June 18, 2025](#smile-30---june-18-2025)
- [SMILE 3.0 - May 27, 2025](#smile-30---may-27-2025)
- [SMILE 3.0 - February 28, 2025](#smile-30---february-28-2025)
- [SMILE 3.0 - October 29, 2024](#smile-30---october-29-2024)
- [SMILE 3.0 - September 20, 2024](#smile-30---september-20-2024)
- [SMILE 3.0 - August 2, 2024](#smile-30---august-2-2024)
- [SMILE 3.0 - July 22, 2024](#smile-30---july-22-2024)
- [SMILE 3.0 - July 9, 2024](#smile-30---july-9-2024)
- [SMILE 3.0 - March 15, 2024](#smile-30---march-15-2024)
- [SMILE 3.0 - February 7, 2024](#smile-30---february-7-2024)

---

## SMILE 5.0 - December 23, 2025 

[SMILE 5.0 - Release Version 5.1.2] [Download Application Android Version](https://play.google.com/store/apps/details?hl=id&id=com.logistikimunisasi.mobile) 

[SMILE 5.0 - Release Version 5.1.2] [Download Application iOS Version](https://apps.apple.com/id/app/smile-indonesia/id1597558819)

[SMILE 5.0 - Release Version 5.1.2] [SMILE Web](https://smile.kemkes.go.id/)

### Summary of the Feature Updates in this release
----
- **Restricted Usage of Budget Sources in Global Settings** *Enhancement*  
  Super Admins can now create or change budget sources by specifying the use of budget sources, which are **restricted** or **unrestricted** according to needs.

- **Add Stock Transactions with Restricted Budget Sources** *Enhancement*  
  When create add stock transactions, users can see a list of budget sources along with limited or unlimited information. Budget sources with **restricted** information cannot be selected for transactions.

- **Reduce Stock Transactions with Restricted Budget Sources** *Enhancement*  
  Users cannot create reduce stock transactions if they use **restricted budget** sources.

### Enhancement Features
----
#### Restricted Usage of Budget Sources in Global Settings

This update adds a **Restricted Usage** column to the budget source in Global Settings, allowing Super Admins to determine whether a budget source is **restricted** or **unrestricted** as needed.
This column is available on Create Budget Source, Edit Budget Source, Budget Source Detail page, Budget Source Detail in Program Settings.

![Detail Sumber Anggaran](images/1.1.png)


#### Add Stock Transactions with Restricted Budget Sources 
In the add stock transactions, the system displays information on the status of each budget source. Budget sources with limited (restricted) information cannot be selected to proceed with the add stock transaction. 

![Image](images/1.2.png)
![Image](images/1.3.png)

#### Reduce Stock Transactions with Restricted Budget Sources
Users cannot perform stock reduction transactions for materials that use restricted budget sources.

![Image](images/1.4.png)

---

## SMILE 5.0 - November 19, 2025

[SMILE 5.0 - Release Version 5.1] [Download Application iOS Version](https://apps.apple.com/id/app/smile-indonesia/id1597558819)

[SMILE 5.0 - Release Version 5.1] [SMILE Web](https://smile.kemkes.go.id/)

### Summary of the Feature Updates in this release
----
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

### New Features & Enhancement
----
#### Nomenclature Enhancement
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

#### Notification Enhancement
The update from the previous version is the addition of a notification feature to showed the scheduling of assets (asset status, asset warranty, asset calibration, asset maintenance and asset temperature excursion), normal stock and inactive entities. In addition, updates feature notifications appear via device and email. 

**Application**
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

**Email**
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


#### Global Setting - Assets
The Asset Type, Asset Model, and Asset Vendor Data Master are now merged into one new menu tab in Global Settings and are no longer available in Program Settings. In addition, the Communication Provider Master Data has also been merged into the Asset Vendor Master Data to centralize the management of service provider data.
![Image](images/2.11.webp)

#### Global Setting - Assets - PQS Code
The PQS Code Master Data feature serves as a standard set by the WHO for assets related to temperature storage. This feature includes adding, changing, viewing details, and exporting PQS Code.
![Image](images/2.12.webp)

#### Global Setting - Material - Material Volume Packaging
The PQS Code Master Data feature serves as a standard set by the WHO for assets related to temperature storage. This feature includes adding, changing, viewing details, and exporting PQS Code.
![Image](images/2.13.webp)

#### Asset Inventory
The Asset Inventory feature in the program is moved to a separate sub-menu under Asset Management, along with two new features: Monitoring Device Inventory and Storage Temperature Monitoring.
![Image](images/2.14.webp)
![Image](images/2.15.webp)
![Image](images/2.15.1.png)
![Image](images/2.16.webp)
![Image](images/2.16.1.png)

#### Monitoring Device Inventory
The Monitoring Device Inventory feature serves as a temperature monitoring tool information management center that is part of asset management. This feature includes adding, changing, viewing details, and exporting monitoring device within SMILE.

![Image](images/2.17.webp)
![Image](images/2.18.webp)

#### Storage Temperature Monitoring
The Storage Temperature Monitoring feature functions as a temperature monitoring center for assets that have a relationship with monitoring devices. This feature includes viewing details, and exporting asset on storage temperature within SMILE.

![Image](images/2.19.webp)
![Image](images/2.19.1.png)
![Image](images/2.19.2.png)


#### Disposal Instructions
The Disposal Instructions feature serves to record material disposal instructions carried out by the entity and will then be processed through the Waste Management System (WMS).

The Disposal Instructions menu will appear and be accessible if the entity assigned by the user is already registered in the Waste Management program. If the user entity is not yet registered to the WMS module, then the menu displayed is Self-Destruction.
![Image](images/2.20_disposal.webp)
![Image](images/2.21.webp)
![Image](images/2.22.webp)
![Image](images/2.23.webp)


#### Relocation between Program
The Relocation between Program feature is used to move materials from one program to another within the same entity. This feature is equipped with acknowledgement in the form of a checkbox that must be filled in as confirmation that the material transfer has been known by the destination program.
![Image](images/2.24.webp)
![Image](images/2.25.webp)

#### Stock Taking
- Improvements to the add stock taking process include:
  - Sorting materials based on the highest stock quantity;
  - Remove of the mandatory SO marker;
  - Addition of a confirmation pop-up before submitting stock taking data. The system will automatically fill in any unentered stock values (stock 0) as 0 before the data is submitted.

![Image](images/2.26.webp)
![Image](images/2.27.webp)


#### Order Response Time Dashboard
The Order Response Time Dashboard displays a summary of information related to the duration of the order process, from the time the order was placed to being received by the customer. This feature helps monitor service performance and order handling speed by material, entity, and region.

![Image](images/2.28.webp)

#### Order Difference Dashboard
The Order Difference Dashboard displays a summary of the quantity or dosage amount information at each stage of the order process, from the time the order is placed to being received by the customer. Through this dashboard, users can quickly monitor and compare differences in quantity/dosage by material, entity, or region.

![Image](images/2.29.webp)

#### Reception & Distribution Dashboard
The Reception & Distribution Dashboard displays a summary of the information of the quantity received by the entity as well as the quantity distributed by the entity. Through this dashboard, users can monitor and compare the movements of incoming stock (all types of receipts) and outbound stock (including distribution, transfer to other entities, returns, and final distributions) by material, entity, or region.

![Image](images/2.30.webp)

#### Abnormal Stock Dashboard
The Abnormal Stock Dashboard displays a summary of the abnormal material stock conditions of each transaction on an entity in a given period. Through this dashboard, users can monitor the number of abnormal stock events of each transaction and the total number of abnormal event days in a given period in real time based on the material, entity, or region.

![Image](images/2.31.webp)

#### Add/Remove Stock Dashboard
The Add/Remove Stock Dashboard displays a summary of the amount of material stock each transaction of adding and decreasing stock on an entity in a given period. Through this dashboard, users can monitor the amount of material stock from the add stock transaction and reduce stock in real terms based on the material, entity, or region.

![Image](images/2.32.webp)

#### Discard Dashboard
The Discard Dashboard displays a summary of the total accumulated quantity/amount of stock in a disposal transaction for each reason on an entity in a given period. Through this dashboard, users can monitor the total discharge stock in real time by material, entity, or region.

![Image](images/2.33.webp)

---

## SMILE 5.0 - New🌟 (September 16th, 2025)

### Overview
----
We are proud to announce the launch of SMILE 5.0, a significant milestone in the evolution of the SMILE application, transforming into a service-based modular architecture. Using a strangling strategy, this transformation is carried out gradually so that modules in SMILE 3.0 are replaced by independent services that provide better scalability and flexibility.

 
### Key Points in This Release
----
- **Service Modularization**: Core modules have been transformed into standalone services, facilitating application management, development, and performance improvement.
- **Iterative Release Strategy**: SMILE 5.0 is launched gradually, so migration from SMILE 3.0 is not done all at once in one major release.
- **New Features & Enhancements**: Addition of program selection Homepage, Stock Transfer, Relocation features, along with user experience and user interface (UI/UX) improvements that provide a consistent look and easier access to important information.
- **Refactoring and Scalability**: Code has been refactored to improve stability, performance, and application readiness in a cloud environment.
- **Fulfillment of Non-Functional Requirements**: Aspects such as scalability, cloud readiness, and CI/CD automation standards in accordance with DPG (Digital Public Goods) guidelines have been comprehensively implemented.

### Background
----
This transformation is a strategic step to present a SMILE application that is more prepared to accommodate future needs, with a modern technological foundation that allows for faster and easier service integration and development.

### New Features and Enhancement
----
- Homepage Program
- Relocation Feature
- Stock Transfer Feature 

### New Features
----
#### Homepage Program 
The Homepage Program  feature as the main display that makes it easier for users to access various modules and functions in an integrated manner is still under development and will be added soon in the next release.
![Image](images/3.1.png)
![Image](images/3.2.png)
![Image](images/3.3.png)

#### Relocation Features 
The relocation feature is accessed through the Order > Relocation Request menu, supporting the movement of stock between locations with better management.
![Image](images/3.4.png)
![Image](images/3.5.png)

#### Stock Transfer Features 
The stock transfer feature is accessed through the Inventory > Stock Transfer menu, allowing stock transfer between programs to be precise and easy.
![Image](images/3.6.png)
![Image](images/3.7.png)

#### Key Features Simplification

- Process simplification on features:
  - Ticketing System
  - Reconciliation
  - Stock Taking
  - Asset Inventory
  - Disposal Shipped
  - Self-Disposal

---

## SMILE 3.0 - August 15, 2025

### Feature Updates in this release
----
- Annual Commitment vs Realization v2 Dashboard *Enhancement*

### Enhancement Features
----
#### Annual Commitment vs Realization v2 Dashboard 
The **Annual Commitment vs Realization** feature monitors the achievement in quantity of vaccine and other logistics allocation and buffer commitments that have been set by the Indonesian Ministry of Health to each province for one fiscal year.

- **Total Annual Requirement**: The number of vaccine needs (dose units and vials) derived from annual planning by considering the number of targets, number of administrations, coverage targets and Utilization Index (IP).
- **Total Annual Commitment**: The number of vaccine commitments (dose units and vials) from all contracts with the Vaccine Provider and BMHP Vaccine according to the selected year. The commitment amount is the accumulation of the allocation and buffer that has been specified in the contract.
- **Annual Requirements and Remaining Stock**: Displays the overall development of vaccine fulfillment and BMHP Vaccine based on total needs, current stock and consumption expenditure.
- **Annual Commitment vs Realization – National**: Displays the overall progress of the realization of vaccine procurement shown for allocation and buffer based on the value of the commitment stated in the contract. The value of the commitment (unit dose and vial) for the procurement of vaccines based on the approved annual contract. The value of the commitment in the contract is shown for allocation and buffer. Fulfillment/realization is the value of the commitment in the contract that has been delivered. The value that has not been delivered is the difference between the value of the commitment stated in the contract and the value of the commitment that has been realized.
- **Realization and Target**: Displaying the overall progress of the realization of vaccine procurement shown for the allocation has been sent and the buffer has been sent. Undelivered commitments are procurement that refers to allocations in contracts that have not been delivered.
- **Annual Commitment vs Realization – Province**: Display the progress of the realization of vaccine procurement shown for allocation and buffer based on the value of commitments stated in the contract for each province.
![Image](images/4.1.png)
- **Stock Notification Email <50% National Quarter Needs**: Every day, the system checks the availability of stock and compares it with the needs of the national quarter. If the vaccine stock or BMHP is less than 50% of the total national quarter needs, the system will send an email notification to users registered with the Indonesian Ministry of Health, BioFarma, and UNDP entities.​
![Image](images/4.2.png)
![Image](images/4.3.png)

---

## SMILE 3.0 - July 16, 2025 

[Smile Immunization - Release Version 3.8.1] Download App

### Feature Updates in this release
----
- Create Distribution Dengue Transaction with New Form *Enhancement*
- Development of Annual Planning and Master Data *Enhancement*
- Notification Development and Daily Email Recap *Enhancement*

### Enhancement Feature
----
#### Create Distribution Dengue Transaction with New Form 
- Transaction Process:
  - Select Material
    - Distribution → Entity > Activity > Material > Select Material Batch
  - Data Input:
    - NIK
    - NIK is used by the system to recommend vaccine doses and to search patient data in the database.
    - Select the vaccine sequence (Dose I / II). The vaccine sequence is automatically filled by the system based on the NIK.
    - If the patient transaction is not found, the system fills in Dose I.
    - If the patient’s last transaction is Dose I, the system fills in Dose II.
    - If the user changes the selected Dose, the system will display a confirmation pop-up.
    - Total Distribution (only 1 per transaction)
    - Reaction after vaccination (Fever, Red Rash, Seizure, No Reaction, Other)
    - If the reaction = Other, an additional field appears for manual input.
  - Patient Data Verification:
    - If the patient is not yet registered → Click Fill Form
    - If the patient is already registered → The button changes to "View Patient Form"
  - When Submitting a Transaction
    - If Dose II is submitted first & there is no Dose I, the system requests the input of Dose I data first.
  - Patient Data:
    - Generated from NIK: Gender and Date of Birth
    - Entered by the user: Full Name, Marital Status, Last Educational, Occupation, Religion, Ethnic (optional), WhatsApp Number (optional), Medical History & Prevention

![Image](images/5.1.png)
![Image](images/5.2.png)

- Addition of Adverse Event Following Immunization (AEFI):
  a. Click "View Transaction"
  b. Click "View AEFI History" on the desired transaction
  c. Click + on the top right of the screen
  d. The content of the reaction after vaccination and the actual date of the reaction

![Image](images/5.3.png)
 

#### Development of Annual Planning and Master Data
- Percentage Customization on the Grant Amount Data Master as one of the calculations
- Ability to change master data in the middle of the annual planning process
- Change of "Distribution Per Month" formula from 1 Month + 1 Week to 1 Month only

 

#### Notification Development and Daily Email Recap 
- Set up daily recap recipients using User settings
- Change sentences in 4 notifications
- Change sentences and logic in temperature notifications over maximum and less than minimum
- Added 3 new notifications

---

## SMILE 3.0 - June 18, 2025

[Smile Logistics - Release Version 1.4.1] Download App

### Feature Updates in this release
----
- Addition of 92 Filters and Data to the Transaction Monitoring Dashboard  *Enhancement*
- Notification of Expired Material in 60 and 90 days  *Enhancement*
- Maintenance, Calibration, and Warranty Information on Asset Inventory *Enhancement*
- Order Integration with SIHA and SITB *New Feature*

### New Feature & Enhancement
----
#### Addition of 92 Filters and Data to the Transaction Monitoring Dashboard
- On the Transaction Monitoring List page of the Complete Entity tab, users can now view the parent material data (KFA 92) of each transaction in the table.

![Image](images/6.1.png)
 

- In addition, now users can also filter the Transaction Monitoring Dashboard data based on the level of the KFA Material.

![Image](images/6.2.png)
- If the selected Material KFA Level is Active Substance + Strength (92), then the user can search based on the Active Substance + Strength material. If the selected Material KFA Level is Trademark (93), then the user can search based on the Trademark material.

![Image](images/6.3.png)
- In addition, the material grouping data on the Consumption Per Material chart also follows the selected KFA Filter.

![Image](images/6.4.png)
#### Notification of Expired Material in 60 and 90 days
Previously, notifications for materials that were close to expiration were sent on the 30th, 14th, 10th, 3rd, and 1st day before the expiration date. Now, notifications will also be sent 60 and 90 days before the material expires.

![Image](images/6.5.png)
#### Maintenance, Calibration, and Warranty Information on Asset Inventory
- Currently users can record the following information:
  - Warranty start and end dates
  - Last date of maintenance
  - Maintenance time interval
  - Last calibration date
  - Calibration time interval

![Image](images/6.6.png)
 

![Image](images/6.7.png)
- Based on the last date of maintenance and the specified interval, the system will send a notification reminding you of the next maintenance schedule on D-1.

![Image](images/6.8.png)
![Image](images/6.9.png)
- Based on the last calibration date and the specified interval, the system will send a reminder notification of the next calibration schedule on D-1.

![Image](images/6.10.png)
![Image](images/6.11.png)

#### Order Integration with SIHA and SITB
- In the integration of SMILE with the HIV AIDS INFORMATION SYSTEM (SIHA) and the Tuberculosis Information System (SITB), the process begins with SIHA or SITB making a request to the SMILE API to make an order. The status of the Order made will be a Draft 

![Image](images/6.12.png)
- SMILE users validate by entering the validated amount for each material. Then click Save Submit Validation. 

![Image](images/6.13.png)
- SMILE users can enter a mail number and a message (if applicable). Then click Submit. 

![Image](images/6.14.png)
- Orders on SMILE change to Pending. In addition, SMILE also sent information to SIHA and SITB that the order had been validated. 

![Image](images/6.15.png)
- Ideally, the confirmation process is carried out from SIHA and SITB, then sends data to SMILE through the API that has been provided to change its status to "Confirmed". 

![Image](images/6.16.png)
- The user allocates each material. Now, the amount of batch material allocated can be different from the previously confirmed amount. 

![Image](images/6.17.png)
- Once allocated, users can place order delivery. One of the fields changed its wording. Previously was "Order Taken? Yes/No", now "Shipping Process. Picked/Shipped 

![Image](images/6.18.png)
- SIHA and SITB will get the latest data by hitting the GET API for SMILE Order data.
- In the Allocation/Distribution order type, SIHA and SITB get the latest data by hitting the GET API for the SMILE Order data. There are now updated_from_date and updated_to_date filters to filter the Order list based on the date last updated (updated_at)

---

## SMILE 3.0 - May 27, 2025

[Smile Logistics - Release Version 1.4.1] Download App

### Feature Updates in this release
----
- Addition of 92 Filters and Data to the Stock Taking List  Enhancement
- Changes to Entity Progress and Compliance calculations  Enhancement
- Stock Taking Dashboard Versioning Enhancement

### Enhancement Feature
----
#### Addition of 92 Filters and Data to the Stock Taking List
- On the Stock Taking List page, users can see the name of the variant or material of the active substance + the strength of each line of data.

![Image](images/7.1.png)
- Users can also search based on material 92 or 93 by first selecting the KFA Material Level. If the selected Material KFA Level is Active Substance + Strength (92), then the user can search based on the Active Substance + Strength material. If the selected Material KFA Level is Trademark (93), then the user can search based on the Trademark material.

![Image](images/7.2.png)
 

#### Changes to Entity Progress and Compliance calculations
- On the Stock Taking Dashboard page, the "Stock Taking Results per Active Substance + Strength Material" tab, there is a change in the formula in calculating the progress of stock taking for each entity. Users can see the rightmost column named "Mandatory Material Progress".
- Material progress must contain numerator (top) and denominator (bottom) data. The counter is the amount of material that has been taken stock of the entity in activities related to its materials. The denominator is the amount of material managed by the entity & is required to carry out Stock Taking.
- The materials managed by an entity are seen from whether the entity has ever had a transaction with the material or not. Specifically for BMHP Screening activities, materials managed by entities are seen from the relationship between entities and their materials.

![Image](images/7.3.png)
- On the Entity Compliance tab, users can now see the number of entities that have done stock taking, have not done stock taking, and the total.
- An Entity is categorized as "Stock Taking" if it has done Stock Taking on all required materials
- Example
  - Example 1: If a new entity performs stock taking on 31 materials out of the 40 required materials, then this entity is said to have not performed stock taking.
  - Example 2: If a new entity performs stock taking on 8 of the required 8 materials, then this entity is said to have done stock taking.
  - Example 3: If an entity has 10 materials that are mandatory Stock Taking. However, the entity performs stock taking on 9 mandatory materials + 2 non-mandatory materials. So, the entity is still categorized as "Not doing stock taking" until all the materials that must be stock taken are taken.

![Image](images/7.4.png)
#### Stock Taking Dashboard Versioning
- All changes in this release are version 2 of the stock taking dashboard.

![Image](images/7.5.png)
- If there is a need to view the old version, then the user can access it by omitting /v2 from the URL. So, it becomes /dashboard/stock-opname.

![Image](images/7.6.png)
 

---

## SMILE 3.0 - February 28, 2025

[Smile Immunization - Release Version 3.8.0] Download App 

### Feature Updates in this release
----
- Addition of Material Setting for Dengue  *New Feature*
- Create Dengue Distribution Transaction  *New Feature*

### New Feature
----
#### Addition of Material Setting for Dengue
-  **New Features**: Users can now add materials with Dengue activities.
-  **Rules:**
  -  If the user selects Activity = "Dengue" and Type = "Vaccine" (Yes), then the Need Vaccine Sequence of Dengue field will appear
  -  This field will always be displayed but in a non-editable state (disabled) to maintain consistency with the Rabies feature.
  -  In the case of Dengue, this field always requires a sequence, so it cannot be changed by the user.

![Image](images/8.1.png)
#### Create Dengue Distribution Transaction
- Transaction Process:
  - Select Material:
    - Expenditure > Entity > Activity > Materials > Select Batch Materials
  - Data Input:
    - Patient diagnosis
    - If diagnosed (Yes) → Fill in the Month & Year
    - Select the vaccine sequence (Dose I/II)
    - Total amount (only 1 per transaction)
    - NIK & reaction after vaccine (Fever, Red Rash, Seizures, Others)
    - If reaction = Other, an additional field appears for manual input
  - Patient Data Verification:
    - Click "Fill in the Form"
    - If the patient is not yet registered → Navigate to the patient form
    - If the patient is already → the button changes to "View Forms"
  - When submitting a transaction:
    - If Dose II is sent first & there is no Dose I, the system requests Dose I data input first.
  - Patient Data:
    - Generated from NIK: Gender, Date of Birth, and Age
    - User input: Name, Marital Status, Education, Occupation, Religion, Ethnic (optional), WhatsApp Number (optional), Medical History

![Image](images/8.2.png)
![Image](images/8.3.png)


---

## SMILE 3.0 - October 29, 2024

[SMILE Immunization - Release Version 3.7.6] Download App
[SMILE Logistics - Release Version 1.3.6] Download App

### Feature Updates in this release
----
- Annual Commitment from the Ministry of Health to the Province  *New Feature*
- Annual Commitment Dashboard from the Ministry of Health to the Province  *New Feature*
- Temperature Monitoring Dashboard *New Feature*
- Changes to Account Profile Data *Enhancement*
- Force Change Password *Enhancement*
- Update Grouping Menu *Enhancement*
- Update Sequence Rabies *Enhancement*
- Reminder Notification Updates for Rabies Patients *Enhancement*
- Rabies Dashboard Update *Enhancement*
- Adjustment Formula for Stock Availability and Filling from Out of Stock *Enhancement*
- iOS Training & Production Logistics *Enhancement*
- Central Delivery Update *Enhancement*

### New Feature & Enhancement
----
#### Annual Commitment from the Ministry of Health to the Province
Specific users can add annual commitments per material (for allocations and buffers) in the selected year, based on the contract number and province that has been specified.

![Image](images/9.1.png)
#### Annual Commitment Dashboard from the Ministry of Health to the Province
Certain users can view the progress dashboard of material realization that has been delivered based on the value of the commitments listed in the contract (for allocation and buffer), both at the national and provincial levels.

![Image](images/9.2.png)
#### Temperature Monitoring Dashboard
Users can view temperature monitoring chart information that is actively registered and connected to Remote Temperature Monitoring Devices (RTMD) in SMILE.

![Image](images/9.3.png)
#### Changes to Account Profile Data
Feature changes so that users can change data information such as emails, passwords, and others in their SMILE account independently

![Image](images/9.4.png)
#### Force Change Password
Feature changes to make it easier for Admins to ask users to change their passwords through the system.

![Image](images/9.5.png)
#### Update Group Menu
Changes to the navbar menu in Immunization and logistics, previously there were 7 menus, now there are 4 menus

![Image](images/9.6.png)
 

![Image](images/9.7.png)
#### Update Sequence Rabies
- Update on the separation of vaccination types into 3, namely pre-exposure, post-exposure and booster.
- Addition of Intra Dermal (ID) & Intra Muscular (IM) methods for post-exposure and booster vaccination types
- IM booster sequence changes: day 0 maximum 1 dose, day 3 maximum 1 dose. ID booster method: day 0 = 4 doses, so no booster is needed on day 3. If the ID booster on day 0 is <4 doses, then the booster on day 3 = 1 dose
- Dosage filling for PEP vaccine IM method: PEP day 0 dose quantity = 2. If you will fill 1 dose, please use the pre-exposure vaccination type.

![Image](images/9.8.png)
#### Rabies Dashboard Update
- Changing the Sankey diagram to a stacked bar diagram
- Additional number of hospital entities in the program coverage section

![Image](images/9.9.png)
#### Adjustment Formula for Stock Availability and Replenishment from Out of Stock
- Formula adjustments for stock availability, replenishment from out of stock and abnormal stock
- Formula adjustments for stock availability exports, replenishment from out of stock and abnormal stock
- Additional Per Material Entity tab on stock availability, replenishment from out of stock and abnormal stock pages

![Image](images/9.10.png)
#### iOS Training & Production Logistic

- iOS Logistics Training is now available on the App Store with the search keyword "SMILE Logistics Training"
- iOS Production Logistics is still unlisted, it can be accessed via the following link: Click here

![Image](images/9.11.png)
#### Central Delivery Update
- Additional delivery types include " Regular " (for allocation delivery) and " Central Buffer " (for buffer delivery)
- Addition of Contract Number column

![Image](images/9.12.png)

---

## SMILE 3.0 - September 20, 2024
[SMILE Immunization - Release Version 3.7.5] Download Application
[SMILE Logistics - Release Version 1.3.3] Download Application

### Feature Updates in this release
----
- Update the flow to add stock taking *Enhancement*
- View the recapitulation of the stock taking process for each specific period *Enhancement*
- Download stock book reports by province, district/city, health center and entity for the required period *Enhancement*

### Enhancement Feature
----
#### Update the flow to add stock taking
Updating the flow of adding stock take so that users can focus on materials, not on activities and users can get markers for which materials have been stock taken.

![Image](images/10.1.png)
#### View the recapitulation of the stock taking process for each specific period
Users can view and download a summary of the stocktaking process for each specific period.

![Image](images/10.2.png)
#### Download stock book reports by province, district/city, health center and entity for the required period
Users can download material stock reports based on province, district/city, health center and entity for the required period.

![Image](images/10.3.png)

---

## SMILE 3.0 - August 2, 2024

[SMILE Immunization - Release Version 3.7.4] Download Application

### Feature Updates in this release
----
- Confirm to stop the Rabies Vaccination notification *New Feature*
- View assets that have more than one temperature range and capacity *New Feature*

### New Feature
----
#### Confirm to stop the Rabies Vaccination notification
Users can confirm to stop the Rabies Vaccination notification.

![Image](images/11.1.png)
#### View assets that have more than one temperature range and capacity
Users can view Assets that have more than one Temperature Range and Capacity, such as Freezers and Vaccine Refrigerators.

![Image](images/11.2.png)
 


---

## SMILE 3.0 - July 22, 2024

[SMILE Immunization - Release Version 3.7.2] Download Application
[SMILE Logistics - Release Version 1.3.1] Download Application

### Feature Updates in this release
----
- Distribution rabies vaccines with a pre-exposure type  *New Feature*
- Change the cold chain temperature limit and view the logger activity history  *New Feature*

### New Feature
----
#### Distribution rabies vaccines with a pre-exposure type
Carrying out rabies vaccine distribution with pre-exposure types consisting of Intra-Muscular and Intra Dermal.

![Image](images/12.1.png)
#### Change the cold chain temperature limit and view the logger activity history
Change cold chain temperature limits and view logger activity history by displaying cold chain status and temperature limits.

![Image](images/12.2.png)

---

## SMILE 3.0 - July 9, 2024

[SMILE Logistics - Release Version 1.3.0] Download the Application

### Feature Updates in this release
----
- View stocks with KFA levels  *New Feature*
- Create material orders with KFA levels  *New Feature*
- View the Stock Dashboard with KFA levels  *New Feature*

### New Feature
----
#### View stocks with KFA levels
View the stock of material level Active Ingredients & Strength (KFA 92) and Trademarks (KFA 93)

![Image](images/13.1.png)
#### Create material orders with KFA levels
Create material orders with material levels of Active Ingredients & Strength (KFA 92) and Trademarks (KFA 93)

![Image](images/13.2.png)
#### View the stock dashboard with KFA levels
View the stock dashboard with material levels of Active Ingredients & Strength (KFA 92) and Trademarks (KFA 93).

![Image](images/13.3.png)

---

## SMILE 3.0 - June 13, 2024

[SMILE Immunization - Release Version 3.7.1]

### Feature Updates in this release
----
- View Coldchain Capacity with capacity projections  *New Feature*
- View Capacity for Annual Planning  *New Feature*
- View Coldchain Capacity Projections in Orders  *New Feature*

### New Feature
----
#### View Coldchain Capacity with capacity projections
Added coldchain capacity projections related to maximum data of each stock

![Image](images/14.1.png)
#### View Capacity for Annual Planning
Comparing the actual cold chain with the total needs from the annual planning.

![Image](images/14.2.png)
#### View Coldchain Capacity Projections in Orders
Added coldchain capacity projections in order details to inform users about the estimated capacity used once the order is fulfilled.

![Image](images/14.3.png)


---

## SMILE 3.0 - March 15, 2024

[SMILE Immunization - Release Version 3.6.3]

### Feature Updates in this release
----
- View the SMILE vs SMDV Dashboard  *New Feature*
- Asset Inventory at SMILE Logistic  *New Feature*
- Update the flow of stock taking at SMILE Immunization  *Enhancement*
- Update the Rabies/VAR distribution feature in SMILE Immunization *Enhancement*
- View the Asset Inventory Dashboard in SMILE Immunization *New Feature*
- View the Stock Dashboard on SMILE Immunization and Logistics *New Feature*
- Addition of Stock Taking Dashboard tab for Ministry of Health on SMILE Immunization *Enhancement*

### New Feature & Enhancement
----
#### View the SMILE vs SMDV Dashboard
Seeing the difference in stock comparison data in smile with the stock comparison in biofarma's shipments for immunization vaccines.

![Image](images/15.1.png)
#### Asset Inventory at SMILE Logistic

Adding an inventory of assets contained in each entity  in SMILE Logistics both via the Mobile and Web applications

![Image](images/15.2.solve.png)
 

![Image](images/15.3.solve.png)


![Image](images/15.4.solve.png)
 

#### Update the flow of stock taking at SMILE Immunization
Flow update for doing stock taking without selecting activities

![Image](images/15.5.solve.png)
#### Update the Rabies/VAR distribution feature in SMILE Immunization
Add NIK/Non NIK and the date of the rabies vaccination sequence

![Image](images/15.6.solve.png)
 

![Image](images/15.7.solve.png)
 

![Image](images/15.8.solve.png)
 

#### View the Asset Inventory Dashboard in SMILE Immunization
New dashboard showing asset inventory input results

![Image](images/15.9.png)
#### View the Stock Dashboard on SMILE Immunization and Logistics
New dashboard showing summary of remaining stock & stock not received

![Image](images/15.10.png)
#### Addition of Stock Taking Dashboard tab for Ministry of Health on SMILE Immunization
Dynamic data feature for the Ministry of Health on the Stock Taking Dashboard

![Image](images/15.11.png)


---

## SMILE 3.0 - February 7, 2024

[SMILE Immunization - Release Version 3.6.0]

### Feature Updates in this release
----
- View the Transaction Monitoring Dashboard on SMILE Logistics  *New Feature*
- Allocated and Shipped in accordance with activity flow activities *Enhancement*
- Download the Request Letter, Confirmation Nota, and Batch Nota documents in the Order details menu  *New Feature*

### New Feature & Enhancement
----
#### View the Transaction Monitoring Dashboard on SMILE Logistics
New dashboard showing a summary of consumption transactions

#### Allocated and Shipped in accordance with activity flow activities
Dynamic allocation and shipped features based on activities

#### Download the Request Letter, Confirmation Nota, and Batch Nota documents in the Order details menu
Adding supporting documents to the order
