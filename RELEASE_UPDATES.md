# SMILE Update Release Note

## About
This document provides information on the enhancement and update features of **SMILE**.

---

## Table Of Content
- [SMILE 5.0 -- December 23, 2025](#smile-50----december-23-2025)
- [SMILE 5.0 -- November 19, 2025](#smile-50----november-19-2025)

---

## Page Contents

### SMILE 5.0 -- December 23, 2025 

#### Enhancement

1. Restricted Budget Source Usage in Global Setting 

2. Increase Stock Transaction with Restricted Budget Source 

3. Decrease Stock Transaction with Restricted Budget Source 

---

### SMILE 5.0 -- November 19, 2025

Feature Update Summary in this release:

1. Nomenclature Enhancement 

Update from the previous version: updating words or terms (wording) to assist users who have difficulty finding terms that differ from the previous version.

Nomenclature changes in SMILE 5.0 are as follows:
|No   |Old   | New|
|---|---|---|
|1. |Penyedia (Provider) | 	Pengirim (Sender) |	 
|2. |Pelanggan (Customer)	| Penerima (Receiver) |	
|3. |Penerimaan Pengembalian (Return Receipt) |	Penerimaan Retur (Return Receipt)|	 
|4. |Stok di Tangan (Stock on Hand) |	Sisa Stok (Remaining Stock)|
|5. |Material  Zat Aktif (Active Ingredient Material) |	Material Produk Template (Product Template Material)	|
|6. |Material Merek Dagang (Branded Material) |	Material Produk Varian (Product Variant Material)	|
|7. |Nota Batch (Batch Note) |	Nota Alokasi (Allocation Note)	|
|8. |Pengembalian (Return)	| Retur (Return)	|
|9. |Pengembalian Faskes (Healthcare Facility Return)	| Retur Distribusi Akhir (Final Distribution Return)	|
|10. |Stok  Pembuka (Opening Stock)	| Stok Awal (Initial Stock)	|
|11. |Stok  Penutup (Closing Stock)	| Stok Akhir (Ending Stock)	|


2. Navigation Menu Navbar Enhancement 

3. Notification Enhancement

Update from the previous version: addition of a notification feature to be informed of asset scheduling (asset status, asset warranty, asset calibration, asset maintenance, and asset temperature excursion), stock back to normal, and inactive entity. Additionally, the updated notification feature appears on devices and via email.

The following are the updated notification types in SMILE 5.0:
| No | Notification |
|---|---|
|i.	|Asset Status Update	After an asset status update has been performed|​
|ii.	|Asset Warranty Reminder	When asset warranty exceeds the warranty date|​
|iii.	|Asset Calibration Reminder	- Asset calibration expires in 1, 7, or 14 days|
|  |- Upcoming calibration schedule before 1, 3, 7, or 14 days|​
|iv.	|Asset Maintenance Reminder	- Asset maintenance expires in 1, 7, or 14 days|​
|  |- Upcoming maintenance schedule before 1, 3, 7, or 14 days|
|v.	|Inactive Entity​	Entity has not performed transaction/consumption for 7, 14, 21 up to 60 days|​
|vi.	|Stock Back to Normal​	Material stock is between the minimum and maximum limits|​
|vii.	|Temperature Excursion	- Temperature below minimum limit continuously for 1 hour|

Notification types that users will receive via email include:

|No   |Notification Type   |
|---|---|
|1.	|Stock Out|
|2.	|Stock Below Minimum|
|3.	|Material Expiring Soon|
|4.	|Order Shipped|
|5.	|Inactive Entity|
|6.	|Asset Status Change|
|7.	|Asset Warranty Reminder|
|8.	|Asset Calibration Reminder|
|9.	|Asset Maintenance Reminder|
|10.	|Stock Back to Normal|

4. Asset Management -- Asset Master Data

5. Global Setting -- PQS Code Master Data 

6. Global Setting -- Material Packaging Volume 

7. Asset Inventory 

8. Temperature Monitoring Device Inventory 

9. Storage Temperature Monitoring 

10. Disposal Instruction : records disposal instructions for materials carried out by an entity, which are then processed through the Waste Management System (WMS).

11. Inter-Program Relocation : to move materials from one program to another within the same entity level in one area. 

12. Stock Opname  

Improvements to the stock opname addition process include:
- Sorting materials based on the highest stock quantity;
- Removal of mandatory SO marker;
- Addition of a confirmation pop-up before sending SO data. The system will automatically fill unentered stock values (stock 0) with 0 before data is sent.

13. Dashboard - Order Response Time Dashboard : summary of information related to order processing duration, from order creation to customer receipt.
    
14. Dashboard - Order Variance Dashboard: summary of quantity or dose amounts at each stage of the order process, from order creation to customer receipt. 

15. Receipt & Distribution Dashboard : summary of the quantity received by an entity and the quantity distributed by an entity. 

16. Abnormal Stock Dashboard : summary of abnormal stock conditions for each transaction in an entity over a specific period. 

17. Increase/Decrease Stock Dashboard : summary of material stock quantities for each increase and decrease stock transaction in an entity over a specific period. 

18. Disposal Dashboard : summary of the total accumulated quantity/stock amount in disposal transactions for each reason in an entity over a specific period. 
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
