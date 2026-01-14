# SMILE Update Release Note

## About
This document purpose to provide information about enhancement and update feature of SMILE.

## Page Contents

### SMILE 5.0 -- December 23, 2025 

Feature Update Summary in this release:

#### Restricted Budget Source Usage in Global Setting
Super Admin can now create or edit budget sources by specifying usage as restricted or unrestricted as needed.

#### Increase Stock Transaction with Restricted Budget Source
When performing an increase stock transaction, users can view the list of budget sources along with restricted/unrestricted information. Budget sources marked as restricted cannot be selected for the transaction.

#### Decrease Stock Transaction with Restricted Budget Source
Users cannot perform a decrease stock transaction if using a budget source that is restricted.

#### Enhancement

1. Restricted Budget Source Usage in Global Setting 
This update adds a Restricted Usage column to the budget source setting, allowing Super Admin to define whether a budget source is restricted or unrestricted. This column is available on the Add, Edit, and Detail Budget Source pages, as well as on the Budget Source Detail in Program settings.

2. Increase Stock Transaction with Restricted Budget Source 
During the stock increase process, the system displays the usage status of each budget source. Budget sources with restricted (blocked) information cannot be selected to proceed with the transaction.

3. Decrease Stock Transaction with Restricted Budget Source 
Users cannot perform a decrease stock transaction for materials using a restricted budget source.

### SMILE 5.0 -- November 19, 2025

Feature Update Summary in this release:

#### Nomenclature
Updates and adjustments to words, terms, or wording used in the SMILE system.

#### Navigation Menu Navbar
Updated menu display to group features into relevant categories, improving user experience.

#### Notification
Added notification feature to display scheduling information and asset status, stock back to normal, and inactive entities. Notifications are displayed on devices and sent as summaries via email.

#### Asset Management

##### Asset Master Data
Changed menus for Asset Type, Asset Model, and Asset Vendor into one new menu. Additionally, Communication Provider master data is now merged into Asset Vendor master data.

###### PQS Code Master Data
PQS Code master data serves as a standard set by WHO for assets related to temperature storage. ​

###### Material Packaging Volume Master Data
Material Packaging Volume master data serves as a central management hub for standard packaging volume information for each material. ​

###### Asset Inventory
The Asset Inventory feature in the program has been moved to its own sub-menu under Asset Management, along with two new features: Temperature Monitoring Device Inventory and Storage Temperature Monitoring.

###### Temperature Monitoring Device Inventory
The Temperature Monitoring Device Inventory feature serves as a central management hub for temperature monitoring device information.

###### Storage Temperature Monitoring
The Storage Temperature Monitoring feature monitors temperature conditions on assets related to temperature monitoring devices over a specific period.

###### Disposal Instruction
The Disposal Instruction feature records disposal instructions for materials carried out by an entity, which are then processed through the Waste Management System (WMS). This feature is only displayed and accessible to users whose assigned entity is registered with the WMS module.

###### Inter-Program Relocation
The Inter-Program Relocation feature is used to move materials from one program to another within the same entity.

###### Stock Opname
Improvements to the stock opname addition process include:
- Sorting materials based on the highest stock quantity;
- Removal of mandatory SO marker;
- Addition of a confirmation pop-up before sending SO data. The system will automatically fill unentered stock values (stock 0) with 0 before data is sent.

###### Dashboard

- Order Response Time Dashboard

The Order Response Time Dashboard displays a summary of information related to order processing duration, from order creation to customer receipt.

- Order Variance Dashboard

The Order Variance Dashboard displays a summary of quantity or dose amounts at each stage of the order process, from order creation to customer receipt.

- Receipt & Distribution Dashboard

The Receipt & Distribution Dashboard displays a summary of the quantity received by an entity and the quantity distributed by an entity.

- Abnormal Stock Dashboard

The Abnormal Stock Dashboard displays a summary of abnormal stock conditions for each transaction in an entity over a specific period.

- Increase/Decrease Stock Dashboard

The Increase/Decrease Stock Dashboard displays a summary of material stock quantities for each increase and decrease stock transaction in an entity over a specific period.

- Disposal Dashboard

The Disposal Dashboard displays a summary of the total accumulated quantity/stock amount in disposal transactions for each reason in an entity over a specific period.
 

New Features and Enhancement

1. Nomenclature Enhancement 

Update from the previous version: updating words or terms (wording) to assist users who have difficulty finding terms that differ from the previous version.

Nomenclature changes in SMILE 5.0 are as follows:

Penyedia (Provider) &rarr; 	Pengirim (Sender)	 

Pelanggan (Customer)	&rarr; Penerima (Receiver)	

Penerimaan Pengembalian (Return Receipt) &rarr;	Penerimaan Retur (Return Receipt)	 

Stok di Tangan (Stock on Hand) &rarr;	Sisa Stok (Remaining Stock)

Material  Zat Aktif (Active Ingredient Material) &rarr;	Material Produk Template (Product Template Material)	

Material Merek Dagang (Branded Material) &rarr;	Material Produk Varian (Product Variant Material)	

Nota Batch (Batch Note) &rarr;	Nota Alokasi (Allocation Note)	

Pengembalian (Return)	&rarr; Retur (Return)	

Pengembalian Faskes (Healthcare Facility Return)	&rarr; Retur Distribusi Akhir (Final Distribution Return)	

Stok  Pembuka (Opening Stock)	&rarr; Stok Awal (Initial Stock)	

Stok  Penutup (Closing Stock)	&rarr; Stok Akhir (Ending Stock)	


2. Navigation Menu Navbar Enhancement 

Update from the previous version: the old menu display only had 3 main menus. The new menu display now has 5 main menus, with features grouped into relevant categories.


3. Notification Enhancement

Update from the previous version: addition of a notification feature to be informed of asset scheduling (asset status, asset warranty, asset calibration, asset maintenance, and asset temperature excursion), stock back to normal, and inactive entity. Additionally, the updated notification feature appears on devices and via email.

The following are the updated notification types in SMILE 5.0:

No	Notification Type	When Received
1	Asset Status Update	After an asset status update has been performed​
2	Asset Warranty Reminder	When asset warranty exceeds the warranty date​
3	Asset Calibration Reminder	- Asset calibration expires in 1, 7, or 14 days
- Upcoming calibration schedule before 1, 3, 7, or 14 days​
4	Asset Maintenance Reminder	- Asset maintenance expires in 1, 7, or 14 days​
- Upcoming maintenance schedule before 1, 3, 7, or 14 days
5	Inactive Entity​	Entity has not performed transaction/consumption for 7, 14, 21 up to 60 days​
6	Stock Back to Normal​	Material stock is between the minimum and maximum limits​
7	Temperature Excursion	- Temperature below minimum limit continuously for 1 hour
- Temperature above maximum limit continuously for 8 hours

INFORMATION

The notification types asset status change, asset calibration reminder, asset warranty reminder, asset maintenance reminder, and temperature excursion do not display the program type because assets are global and can be owned by more than one program.

EMAIL

Users can receive and view notification summaries via email daily.

WARNING​

Users who are not selected (ticked) to receive daily recap emails will not receive daily summary emails.​


Notification types that users will receive via email include:

No	Notification Type
1	Stock Out
2	Stock Below Minimum
3	Material Expiring Soon
4	Order Shipped
5	Inactive Entity
6	Asset Status Change
7	Asset Warranty Reminder
8	Asset Calibration Reminder
9	Asset Maintenance Reminder
10	Stock Back to Normal

4. Asset Management -- Asset Master Data

Master Data for Asset Type, Asset Model, and Asset Vendor are now combined into one new tab menu in Global Settings and are no longer available in Program Settings. Additionally, Master Data for Communication Provider has also been merged into Asset Vendor Master Data to centralize service provider data management.


5. Global Setting -- PQS Code Master Data 

The PQS Code Master Data feature serves as a standard set by WHO for assets related to temperature storage. ​This feature includes adding, editing, viewing details, and exporting PQS Code data.

6. Global Setting -- Material Packaging Volume 

The Material Packaging Volume Master Data feature serves as a central management hub for standard packaging volume information for each material. This feature includes adding, editing, viewing details, exporting, importing, and downloading templates for Material Packaging Volume within SMILE.

7. Asset Inventory 

The Asset Inventory feature in the program has been moved to its own sub-menu under Asset Management, along with two new features: Temperature Monitoring Device Inventory and Storage Temperature Monitoring.

8. Temperature Monitoring Device Inventory 

The Temperature Monitoring Device Inventory feature serves as a central management hub for temperature monitoring device information, which is part of asset management. This feature includes adding, editing, viewing details, and exporting temperature monitoring devices within SMILE.


9. Storage Temperature Monitoring 

The Storage Temperature Monitoring feature serves as a central hub for monitoring the temperature of assets that are related to temperature monitoring devices. This feature includes viewing details and exporting asset storage temperature data within SMILE.

10. Disposal Instruction 

The Disposal Instruction feature records disposal instructions for materials carried out by an entity, which are then processed through the Waste Management System (WMS). 
The Disposal Instruction menu will appear and be accessible if the entity assigned to the user is registered in the Waste Management program. ​If the user's entity is not registered with the WMS module, then the displayed menu is Self-Disposal.


11. Inter-Program Relocation 

The Inter-Program Relocation feature is used to move materials from one program to another within the same entity. 
This feature includes an acknowledgement in the form of a checkbox that must be filled as confirmation that the material transfer has been acknowledged by the destination program.

12. Stock Opname  

Improvements to the stock opname addition process include:
- Sorting materials based on the highest stock quantity;
- Removal of mandatory SO marker;
- Addition of a confirmation pop-up before sending SO data. The system will automatically fill unentered stock values (stock 0) with 0 before data is sent.

13. Dashboard - Order Response Time Dashboard 

The Order Response Time Dashboard displays a summary of information related to order processing duration, from order creation to customer receipt. This feature helps monitor service performance and order handling speed based on material, entity, or region.

14. Dashboard - Order Variance Dashboard 

The Order Variance Dashboard displays a summary of quantity or dose amounts at each stage of the order process, from order creation to customer receipt. Through this dashboard, users can quickly monitor and compare quantity/dose differences based on material, entity, or region.


 15. Receipt & Distribution Dashboard 

The Receipt & Distribution Dashboard displays a summary of the quantity received by an entity and the quantity distributed by an entity. Through this dashboard, users can monitor and compare incoming stock movement (all types of receipts) and outgoing stock movement (including distribution, transfer to other entities, returns, and final distribution) based on material, entity, or region.


16. Abnormal Stock Dashboard 

The Abnormal Stock Dashboard displays a summary of abnormal stock conditions for each transaction in an entity over a specific period. Through this dashboard, users can monitor the number of abnormal stock incidents per transaction and the total days of abnormal incidents over a specific period, in real-time, based on material, entity, or region.


17. Increase/Decrease Stock Dashboard 

The Increase/Decrease Stock Dashboard displays a summary of material stock quantities for each increase and decrease stock transaction in an entity over a specific period. Through this dashboard, users can monitor material stock quantities from increase and decrease stock transactions in real-time based on material, entity, or region.


18. Disposal Dashboard 

The Disposal Dashboard displays a summary of the total accumulated quantity/stock amount in disposal transactions for each reason in an entity over a specific period. Through this dashboard, users can monitor the total disposal stock in real-time based on material, entity, or region.


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

### August 15, 2025

1. Annual Commitment vs Realization Dashboard v2 
The "Annual Commitment vs Realization" feature monitors the quantitative achievement of commitment allocations and buffer stocks for vaccines and other logistics set by the Indonesian Ministry of Health for each province during one fiscal year.​

Total Annual Need: The vaccine need amount (in doses and vials) derived from annual planning, considering target population, number of administrations, coverage targets, and Usage Index (IP).

Total Annual Commitment: The vaccine commitment amount (in doses and vials) from all contracts with Vaccine Providers and Vaccine BMHP according to the selected year. The commitment amount is the accumulation of allocation and buffer determined in the contract. ​

Annual Need and Remaining Stock: Displays the overall progress of vaccine and Vaccine BMHP fulfillment based on total need, current stock, and consumption expenditure​.

Annual Commitment vs Realization - National: Displays the overall progress of vaccine procurement realization shown for allocation and buffer based on the commitment value stated in the contract. The commitment value (in doses and vials) for vaccine procurement is based on the approved annual contract. The commitment value in the contract is shown for allocation and buffer. Fulfillment/realization is the committed value in the contract that has been delivered. The undelivered value is the difference between the commitment value stated in the contract and the committed value that has been realized.

Realization and Target: Displays the overall progress of vaccine procurement realization shown for allocation delivered and buffer delivered. Undelivered commitment refers to procurement based on allocation in the contract that has not been delivered.

Annual Commitment vs Realization -- Province: Displays the progress of vaccine procurement realization shown for allocation and buffer based on the commitment value stated in the contract for each province.​


Email Notification for Stock <50% of National Quarterly Need: Every day, the system checks stock availability and compares it with the national quarterly need. If vaccine or BMHP stock is less than 50% of the total national quarterly need, the system will send an email notification to users registered in the Indonesian Ministry of Health, BioFarma, and UNDP entities.​


### July 16, 2025 

1. Create Dengue Expenditure Transaction with New Form 

*Transaction Process: *

Select Material:

Expenditure > Entity > Activity > Material > Select Material Batch

Input Data:

National ID Number (NIK)

NIK is used by the system to recommend vaccine dose and search for patient data in the database.

Select vaccine sequence (Dose I / II). Vaccine sequence is automatically filled by the system based on NIK

If no previous transaction is found for the patient, the system fills Dose I

If the patient's last transaction was Dose I, the system fills Dose II

If the user changes the Dose selection, the system will display a confirmation pop-up.

Expenditure Amount (only 1 per transaction)

Reaction after vaccination (Fever, Red Rash, Seizure, None, Other)

If reaction = Other, an additional field appears for manual input

Verify Patient Data:

If patient is not registered → Click Fill Form

If patient already exists → Button changes to "View Patient Form"

When Submitting Transaction:

If Dose II is sent first & there is no Dose I, the system requests input of Dose I data first.

Patient Data:

Generated from NIK: Gender and Date of Birth

Input by user: Full Name, Marital Status, Last Education, Occupation, Religion, Ethnicity (optional), WhatsApp Number (optional), Medical History & Prevention


*Addition of Post-Immunization Adverse Event (KIPI): *

Click "View Transaction"

Click "View KIPI History" on the desired transaction

Click + on the top right of the screen

Fill in reaction after vaccination and actual reaction date


2. Annual Planning and Master Data Development 

Customization of Percentage in Number of Administrations Master Data as one calculation parameter

Capability to change master data mid-annual planning process

Change of "Monthly Distribution" formula from 1 Month + 1 Week to just 1 Month

3. Notification and Daily Recap Email Development 

Setting daily recap recipients using User settings

Changing wording in 4 notifications

Changing wording and logic in temperature above maximum and below minimum notifications

Adding 3 new notifications



### June 18, 2025

Addition of Filter and KFA 92 Data on Transaction Monitoring Dashboard 


On the Transaction Monitoring List page, Complete Entity tab, users can now see parent material (KFA 92) data for each transaction in the table.

Additionally, users can now filter Transaction Monitoring Dashboard data based on KFA Material level.

If the selected KFA Material Level is Active Ingredient + Strength (92), users can search based on the Active Ingredient + Strength material. If the selected KFA Material Level is Brand Name (93), users can search based on the Brand Name material.

Furthermore, material grouping data on the Consumption Per Material chart also follows the selected KFA Filter.

Material Expiry Notification at 60 and 90 days 

Previously, notifications for materials nearing expiry were sent 30, 14, 10, 3, and 1 day before the expiry date. Now, notifications will also be sent 60 and 90 days before the material expires.

Maintenance, Calibration, and Warranty Information in Asset Inventory 

Users can now record the following information:

- Warranty start and end dates
- Last maintenance date
- Maintenance interval
- Last calibration date
- Calibration interval


Based on the last maintenance date and the set interval, the system will send a reminder notification for the next maintenance schedule 1 day before (H-1).
Based on the last calibration date and the set interval, the system will send a reminder notification for the next calibration schedule 1 day before (H-1).


Order Integration with SIHA and SITB 
In the integration of SMILE with the HIV AIDS Information System (SIHA) and Tuberculosis Information System (SITB), the process begins with SIHA or SITB making a request to the SMILE API to create an Order. The status of the created Order will be Draft.


SMILE users perform validation by entering the validated quantity for each material. Then click Save Validation Send.


SMILE users can enter the letter number and message (if any). Then click Send.


The Order in SMILE changes to Pending. Additionally, SMILE also sends information to SIHA and SITB that the order has been validated.


Ideally, the confirmation process is done from SIHA and SITB, then they send data to SMILE via the provided API to change its status to "Confirmed".


The user performs allocation for each material. Now, the quantity of material batches allocated can differ from the previously confirmed quantity.

After being allocated, the user can perform order shipment. One field wording has changed. Previously "Order Picked Up? Yes/No", now it's "Shipping Process. Picked Up/Shipped".

SIHA and SITB will get the latest data by hitting the SMILE Order Data GET API.

For Allocation/Distribution order types, SIHA and SITB get the latest data by hitting the SMILE Order Data GET API. Now there are filters updated_from_date and updated_to_date to filter the Order list based on the last updated date (updated_at).

### May 27, 2025

1. Addition of Filter and KFA 92 Data on Stock Opname List 

On the Stock Opname List page, users can see the variant name or active ingredient + strength material for each row of data.

Users can also search based on material 92 or 93 by first selecting KFA Material Level. If the selected KFA Material Level is Active Ingredient + Strength (92), users can search based on the Active Ingredient + Strength material. If the selected KFA Material Level is Brand Name (93), users can search based on the Brand Name material.

2. Change in Progress and Entity Compliance Calculation 

On the Stock Opname Dashboard page, "SO Results per Active Ingredient + Strength Material" tab, there is a change in the formula for calculating each entity's stock opname progress. Users can see the rightmost column named "Mandatory Material Progress".

Mandatory Material Progress contains numerator (top) and denominator (bottom) data. The numerator is the number of materials that have undergone stock opname in that entity for activities related to the material. The denominator is the number of materials managed by the entity & required to undergo Stock Opname.

Materials managed by the entity are seen from whether the entity has ever had a transaction for that material or not. Specifically for BMHP Screening activities, materials managed by the entity are seen from the relationship between the entity and its material.


On the Entity Compliance tab, users can now see the number of entities that have performed stock opname, have not performed stock opname, and the total.

An Entity is categorized as "Have performed Stock Opname" if they have performed Stock Opname on all mandatory materials.

Examples

- Example 1: If an entity has only performed stock opname on 31 out of 40 mandatory materials, then this entity is said to have Not performed stock opname.
- Example 2: If an entity has performed stock opname on 8 out of 8 mandatory materials, then this entity is said to have performed stock opname.
- Example 3: If an entity has 10 materials mandatory for SO. However, the entity performed stock opname on 9 mandatory materials + 2 non-mandatory materials. Then, the entity is still categorized as "Have not performed stock opname" until all materials mandatory for stock opname are done.

3. Stock Opname Dashboard Versioning 

- All changes in this release are version 2 of the stock opname dashboard.



### February 28, 2025


1. Addition of Material Setting for Dengue  

New Feature: Users can now add material with Dengue activity.

Rules:

- If the user selects Activity = "Dengue" and Type = "Vaccine" (Yes), then the field Need Vaccine Sequence of Dengue will appear.
- This field will always be displayed but in a non-editable (disabled) state to maintain consistency with the Rabies feature.
- For Dengue cases, this field always requires a sequence, so it cannot be changed by the user.


2. Create Dengue Expenditure Transaction 

*Transaction Process: *

Select Material:

Expenditure > Entity > Activity > Material > Select Material Batch

Input Data:

Patient diagnosis

If diagnosed (Yes) → Fill in Month & Year

Select vaccine sequence (Dose I / II)

Total amount (only 1 per transaction)

NIK & reaction after vaccination (Fever, Red Rash, Seizure, Other)

If reaction = Other, an additional field appears for manual input

Verify Patient Data:

Click "Fill Form"

If patient is not registered → Directed to patient form

If patient already exists → Button changes to "View Form"

When Submitting Transaction:

If Dose II is sent first & there is no Dose I, the system requests input of Dose I data first.

Patient Data:

- Generated from NIK: Gender, Date of Birth, and Age
- Input by user: Name, Marital Status, Education, Occupation, Religion, Ethnicity (optional), WhatsApp Number (optional), Treatment History


### October 29, 2024


1. Add Annual Commitment from Ministry of Health to Province 

- Certain users can add annual commitment per material (for allocation and buffer) in the selected year, based on the contract number and determined province.

2. Annual Commitment from Ministry of Health to Province Dashboard 

- Certain users can view a dashboard of material realization progress that has been delivered based on the commitment value stated in the contract (for allocation and buffer), both at national and provincial levels.

3. Temperature Monitoring Dashboard 

- Users can view information on temperature monitoring graphs that are actively registered and connected to Remote Temperature Monitoring Devices (RTMD) in SMILE.

4. Account Profile Data Change 

- Feature change to allow users to independently change information such as email, password, etc., in their SMILE account.

5. Force Password Change 

- Feature change to facilitate Admins requesting users to change passwords via the system.

6. Update Menu Grouping 

- Change in navbar menu in Immunization and Logistic, previously there were 7 menus, now reduced to 4 menus.

7. Update Rabies Sequence 

- Update separating vaccination type into 3: pre-exposure, post-exposure, and booster.
- Addition of Intra Dermal (ID) & Intra Muscular (IM) methods for post-exposure and booster vaccination types.
- Change in booster sequence for IM method: day 0 maximum 1 dose, day 3 maximum 1 dose. Booster ID method: day 0 = 4 doses, then no Booster Day 3 needed. If Booster ID day 0 < 4 doses, then Booster day 3 = 1 dose.
- Dose entry for PEP vaccine IM method: PEP day 0 dose quantity=2. If entering 1 dose, please use pre-exposure vaccination type.

8. Update Reminder Notification for Rabies Patients 

- Added phone number column (with WhatsApp) on rabies expenditure input.
- User can contact patients via WhatsApp from the rabies reminder notification.

9. Update Rabies Dashboard 

- Change from sankey diagram to stacked bar diagram.
- Added number of Hospital entities in the program coverage section.

10. Formula Adjustment for Stock Availability and Replenishment from Stock Out 

- Adjustment of formulas for stock availability, replenishment from stock out, and abnormal stock.
- Adjustment of formulas in exporting stock availability, replenishment from stock out, and abnormal stock.
- Added Per Entity Material tab on the stock availability, replenishment from stock out, and abnormal stock pages.

11. iOS Training & Production Logistic 

12. Center Shipment Update 

- Added shipment types including "Regular" (for allocation shipments) and "Center Buffer" (for buffer shipments).
- Added Contract Number column.

### September 20, 2024
1. Update process for adding stock opname 

Updated the process for adding stock opname so users can focus on materials, not activities, and users can see markers for which materials have undergone stock opname.

2. View recap of stock opname process for a specific period 

Users can view and download a recap of the stock opname process for a specific period.

3. Download stock book report based on province, district/city, health center, and entity for the required period 

Users can download material stock reports based on province, district/city, health center, and entity for the required period. ​

### August 2, 2024

1. Perform confirmation to stop Rabies Vaccination notifications 

Users can perform confirmation to stop Rabies Vaccination notifications.

2. View assets with more than one temperature range and capacity 

Users can view Assets with more than one Temperature Range and Capacity, such as Freezers and Vaccine Refrigerators.

### July 22, 2024

1. Perform rabies vaccine expenditure with prevention type 

Perform rabies vaccine expenditure with prevention type consisting of Intra Muscular and Intra Dermal.

2. Change cold chain temperature limit and view logger activity history 

Change cold chain temperature limit and view logger activity history displaying cold chain status and temperature limits.

### July 9, 2024

1. View stock with KFA level 

View material stock at Active Ingredient & Strength (KFA 92) and Brand Name (KFA 93) levels.

2. Order material with KFA level 

Order material at Active Ingredient & Strength (KFA 92) and Brand Name (KFA 93) levels.

3. View Stock Dashboard with KFA level 

View Stock Dashboard at Active Ingredient & Strength (KFA 92) and Brand Name (KFA 93) levels.

### June 13, 2024
1. View Coldchain Capacity with capacity projection 

Added coldchain capacity projection related to the maximum data of each stock.

2. View Capacity for Annual Planning 

Compare actual coldchain with total needs from annual planning.

3. View Coldchain Capacity Projection in Order 

Added coldchain capacity projection in order detail to provide users with information on estimated capacity usage after the order is fulfilled.

### March 15, 2024


1. View SMILE vs SMDV Dashboard 

View data comparison differences between stock in SMILE and stock in BioFarma shipments for immunization vaccines.

2. Perform Asset Inventory in SMILE Logistic 

Added asset inventory available in their respective entities in SMILE Logistic both via Mobile and Web applications.

3. Update flow for performing stock opname in SMILE Immunization 

Update flow for performing stock opname without selecting activities.

4. Update Rabies/VAR expenditure feature in SMILE Immunization 

Added NIK/Non NIK and date sequence for rabies vaccination administration.

5. View Asset Inventory Dashboard in SMILE Immunization 

New dashboard displaying asset inventory input results.

6. View Stock Dashboard in SMILE Immunization and Logistic 

New dashboard displaying remaining stock & unreceived stock summary.

7. Addition of Stock Opname Dashboard tab for Ministry of Health in SMILE Immunization 

Dynamic data feature for Ministry of Health in the Stock Opname Dashboard.

### February 7, 2024

1. View Transaction Monitoring Dashboard in SMILE Logistic 

New dashboard displaying consumption transaction summary.

2. Perform allocation and shipment according to activity flow settings 

Dynamic allocation and shipment feature based on activity.

3. Download Request Letter, Confirmation Note, and Batch Note documents in the Order detail menu 

Added supporting documents to orders.
