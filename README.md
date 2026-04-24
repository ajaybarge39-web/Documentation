YSM - Hired Screen 
In hired worker screen fixed id bug initial it was taking integer change to string
YSM - Vehicle Pass
In vehicle pass valid till date input it was not available.
TKS - OT Finalization screen 
OT Final value if updated it was remaining as it now it is updated
 
 
Release Notes

Project Name: Navyojana
Module Name: Salary and Wages (SWM): PAY and GPF
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release includes important updates and fixes related to reporting, withdrawal display, and grid headings for improved accuracy and formatting.

2. New Features / Updates
NSO 94 Report:
Correct print functionality has been released exclusively for Industrial employees. (Support for Non-Industrial employees will be provided next week.)

Application Fund Withdrawal:
In the landing grid, the Withdrawal Amount is now displayed with commas as thousand separators following the INR currency format.

Closing Balance:
The main grid heading has been corrected to display EMP ID as per the standard format (previously displayed as EMP No).

Project Name: Navyojana
Module Name: Medical Health Management System (MHMS)
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release addresses improvements and bug fixes related to bill booking, cash handling, and LTC claim approval processes.

2. New Features / Updates
Bill Booking AMA Cash:
Insert, update, and view modes are now fully complete and functional.

LTC - Claim CDA Approval:
Resolved an error occurring in update mode related to fetching values from the API.

Project Name: Navyojana
Module Name: Leave and Travel Compensation (LTC)
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release includes a fix for the LTC Claim CDA Approval process related to an API error in update mode.

2. Bug Fixes
LTC - Claim CDA Approval:
Fixed an error in update mode where values were not being retrieved correctly.
The issue was resolved on the API side.

Project Name: Navyojana
Module Name: Yard Security Management (YSM)
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release includes a bug fix related to the Hired Worker screen.

2. Bug Fixes
YSM - Hired Screen:
Fixed an ID bug where the system was initially treating the ID as an integer. The data type has now been changed to string to ensure proper handling

Project Name: Navyojana
Module Name: Time Keeping
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release addresses a fix in the OT Finalization screen.

2. Bug Fixes
TKS - OT Finalization Screen:
Fixed an issue where updated OT final values were not being saved correctly. Now, changes to the OT final value are properly updated.

Project Name: Navyojana
Module Name: Financial Management System (FMS)
Version: v1.12.14 [Major version, Minor version, Patch version] 
Release Date: 2025-07-18

1. Overview
This release includes enhancements, interface terminology updates, improved form usability, and dashboard segmentation. Several modules—including Module Header, Initiate Proposal, CFA Approval, and Work Order—have been updated to improve clarity, consistency, and workflow efficiency.

2. Screen Updates
Module Header
UI Terminology Standardization
Replaced all occurrences of "FMMS" with "FMS" throughout the user interface to improve consistency.
Status: Completed

Screen: Initiate Proposal Transaction
BOQ Response Enhancement
Added an option to choose "Register Vendor" or "Not".

If the vendor is registered, data is fetched from the Vendor Master.

If not registered, users can manually enter vendor details.
Status: Completed
Note: Calculation errors are under review in: Financial Bid, POEV, L1 Update, Price Negotiation, and Benchmarking.

EMD Columns Added

Introduced a column to display Earnest Money Deposit (EMD).

Added a field to identify whether the requirement is for Goods or Service.
Status: Completed

Default Focus on New Activity
When a user adds a new activity form, the cursor now defaults to the most recently added entry.
Status: Completed

Esc Key Cursor Fix
Corrected cursor behavior on Esc key action.
Status: Completed

View Notings and Enclosures Together
Users can now view Notings and Enclosures simultaneously.
Status: Completed

Vendor Re-fetch for Price Negotiation
The system now re-fetches vendors as selected in previous activities. Only the L1 vendor is shown.
Status: Completed
Note: Some calculation logic remains under review.

EMD Field Removal
Removed the EMD total field from the Tender Participation and EMD Update activities.
Status: Completed

Activity Order Fix
Activities are now entered and displayed in the correct order.
Status: Completed

Total Amount Column Added
Introduced a Total Amount column to grids displaying rates, percentages, and amounts.
Status: Completed
Note: Some backend calculation issues are still under resolution.

Screen: CFA Approval Transaction
Dashboard Label Updates
Updated CFA Dashboard to be labeled as FA Dashboard.

Pending assignments now appear under FA.

CFA continues to act solely as the approving authority.
Status: Completed

Dashboard Segmentation
The original CFA dashboard has been split into:

FA Dashboard

FA Team Dashboard

CFA Dashboard (now limited to approvals categorized under AIP Accordance and Sanction)
Status: Completed

Screen Segregation for CFA Approval
Implemented a separate approval screen for Integrated Financial Advisor (IFA) and CFA, allowing only CFA to approve the transaction.
Status: Completed

Work Order
PBG Due Date Automation
The Performance Bank Guarantee (PBG) due date is now automatically set to one month after the start date.
Status: Completed



Version: v1.12.15
Release Date: 2025-07-23
1. Overview
This release includes usability enhancements that allow users to manage row data more efficiently. The update enables deletion and reordering of rows across key transactional screens, improving user control and data entry flexibility.

2. Screen Updates
Statement of Work (SOW) Screen
Row Management Enhancement
Provision has been added to delete and re-arrange rows wherever applicable. This update is implemented in the following:

BOQ Criteria

Statement of Work (SOW)

Statement of Completion (SOC)

Version: v1.12.15
Release Date: 2025-07-23
1. Overview
This release improves usability by allowing users to delete and rearrange rows in statememt of completion screens. This makes data entry and editing in the screen.

2. Screen Updates: Statement of Completion (SOC)
Row Actions Enhancement
Users can now delete and reorder rows in the statement of completion screen

In addition, the login page has been updated to include a footer displaying the application version:
"App Version 1.0.0" and "LOGIN Version 1.0.0" for clear version tracking.


3. Known Issues
BOQ Criteria and Statement of Work Screen:
Further enhancements to row actions in BOQ Criteria and Statement of Work screens are planned. These updates will be included in the next release cycle.

Refit/OPS
Version: v1.12.15
Release Date: 2025-07-23

1. Overview
This release includes API enhancements, UI improvements, new screen developments, and bug fixes across various modules, including Refit Planning Program (RPP), Operational Defect (OPDEF), Defect List (DL), and Request Assistance (RA). These changes aim to improve system usability, performance, and data integrity.

2. Module-Wise Updates
Module Name: Refit Planning Program (RPP)
Screen: Work Instruction Transaction

Updated the Main Center Name API based on the PRM name.

Screen: Release Work Instruction Transaction

Fixed grid column filter issues for Main Center No. and Work Center No. by applying proper filter properties such as isNumber and matchMode.

Screen: Release Work Instruction Transaction 

Set the current date as the default for the PSD date field.
Added validation for DL Status field.

Module Name: Operational Defect (OPDEF)
Screen: OPDEF Centre Remark Transaction

Developed a new screen for opdef centre remarks as discussed.

Screen: OPDEF Finalization Transaction

Enabled OPDEF Status dropdown and resolved data-saving errors while saving.

All OPDEF Screens

Added DART No. column to the listing view for consistency and tracking.

Module Name: Defect List (DL)
Screen: Upload Services Transaction

Developed a new screen for uploading services related to defect entries.

Module Name: Request Assistance (RA)
Screen: RA Finalization Transaction 

Added Final MPC Remarks mapping in the grid.

Screen: RA Approve Transaction
Fixed grid width alignment issues.
Resolved multiple checkbox selection issue on the landing screen.

In addition, the login page has been updated to include a footer displaying in the Refit Planning Program(RPP), Quality Assurance (QAM), Shop Floor Management (SFM) version:
"App Version 1.0.0" and "LOGIN Version 1.0.0" for clear version tracking.

Implemented Footer In RPP Module. 
Implemented Footer In QAM Module.
Implemented Footer In SFM Module.

Manpower Booking (MPB)
Version: v1.12.15
Release Date: 2025-07-23

1. Overview
This release includes UI enhancements and fixes across reporting and transaction modules. Users can now generate PDF reports and experience improved stability in workflow transitions.

2. UI Enhancements and Fixes
Screen: Allocation Report

PDF generation functionality has been added. Users can now download the allocation report in PDF format.

Screen: OT Booking Report

PDF download option has been implemented for OT booking reports.

Screen: Monthly Un-Freeze Transaction

Resolved the issue with the transaction popup not displaying correctly during the Forward Transaction stage.

In addition, the login page has been updated to include a footer displaying the application version:
"App Version 1.0.0" and "LOGIN Version 1.0.0" for clear version tracking.


Yard Security Management (YSM)
Version: v1.12.15
Release Date: 2025-07-23
1. Overview
This release includes a backend fix to resolve data-saving issues during final approval in the Equipment and Tools module.

2. Backend Fix
Screen: Equipment and Tools

Resolved an issue where the system failed to save data during final approval by Gate Inc., Muster Gate, and Tiger Gate.

The issue was due to a missing tran_doc_no column and has been fixed on the API side.

Refit/OPS
Version: v1.12.17
Release Date: 2025-07-24

Module Name: Refit Planning Program
Screen Name: DL Center Remark

Observations & Fixed 
1. The existing screen should also include option of entering EMD: reference can be taken from existing PRM remark screen.
   Shown proposed EMD and QC Level in view mode in PRM Remarks grid, and add proposed EMD and QC Level in center remarks for adding details and done.
   Type of error: New requirement
2. The system is not reflecting accurate center code in the view remarks screen and other screens also now it is done.
   Type of error: Bug Fix

Module Name: Operational Defect (ODDEF)
Screen Name: PRM Remark

Observations & Fixed 
1. Main equipment and sub equipment details are required over the screen and is done.
   Shown the main equipment and sub equipment details.
   Type of error: New requirement
   

Refit/OPS
Version: v1.12.17
Release Date: 2025-07-24

1. Overview
This release includes new feature enhancements and bug fixes in the Refit Planning Program, Quality Check Managment (QCMS), Shop Floor Management (SFM), Operational Defect (ODDEF) modules.

2. Module-wise Updates
Module: Refit Planning Program
Screen: DL Center Remark

Enhancement:
Added fields for Proposed EMD and QC Level in the center remark screen to align with the PRM Remark screen. These values are also now visible in view mode.
Bug Fix:
Resolved issue where the system was not reflecting the accurate Center Code in the View Remarks screen and other related screens
Screen Name: DL Assign PRM
Required Field for Sub-equipment in the Grid and sequence of Grid should be:
Defect No-->Defect Class--> Equipment Name--> Sub-eqipment Name--> Defect Description--> Dart No.--> Ship remarks--> PRM--> PRM Name--> Proposed COSM--> Maintop No.--> Quick Update--> Detailed View done type of error: new requirment.

Screen Name: Work Instruction
Planned Start Date (PSD) now defaults to the current date and includes the option for users to edit the value as needed.
Bug Fix:
Corrected the issue where the Center Code was not accurately displayed in the view remarks and other related screens.
The Main Center, Work Center Field should show list for only selected Departments.
Module: Operational Defect (ODDEF)
Screen: PRM Remark

Enhancement:
Included Main Equipment and Sub-Equipment details in the PRM Remark screen to enhance traceability.

Module Name: Quality Check Management (QCMS)
Screen Name: Approve QAP Form

Screen: Approve QAP Form
Bug Fix:
Resolved missing critical data in QAP format, including activity description in chapter 3 and ambiguity in the QAP approval flow.

Enhancement:
Added inspection stages for WI/DIs

Screen Name: Approve QIS Form
Enhancement:
Resolved ambiguity in the flow of QIS approval to ensure a clear and standardized approval process.


Screen Name: Assign QC Inspector

Enhancements:

Added option to print the raised QC Request on the screen.
Included QC Observation field in the Assign QC Inspector screen.
Added Time Slot column in the grid with the sequence:
Request No → Center No → Proposed Inspection Date → Time Slot → Work Location → Ship Name → Job Description → WI No → Offloaded → WO/Rc No → No. of Time Requested

Screen Name: QC Level

Enhancements:

Included QC Observation field in the QC Level screen.
Added Time Slot column in the grid. Updated grid sequence:
Request No → Center No → Proposed Inspection Date → Time Slot → Work Location → Ship Name → Job Description → WI No → Offloaded → WO/Rc No → No. of Time Requested.
Shifted Job Detail column towards the left for better visibility. New column sequence:
DL No → WI No → Job Detail → DL Class → Equipment → DL Type → M.Center → W.Center → EMD → Offload → Proposed QC Level.
Bug Fix:
Resolved issue where the Details Page to view WI was not opening for users logged in with ID 85435Y.
Details Page to view WI is not being opened if logged in with '85435Y' done type of error: bug.
Updated the route-to popup to display only three sections: HULL, ENGG, and WEA&ELEC.
System now allows COSMs to create multiple WIs only after QC Level has been assigned by the QC department in the parent WI.
Added Centre and Centre Remarks columns in the grid to enhance data visibility.

Screen Name: Raise QC Request
Removed Form No. field from the screen.
Added validation to ensure Mobile No. field accepts exactly 10 digits.

Module Name: Shop Floor Management (SFM)
Screen Name: P1/O2 Rise/ P1/O2 Received

Enhancement:
The Main Center and Work Center fields now display lists filtered to show only the selected departments.

Refit/OPS
Version: v1.12.16
Release Date: 2025-07-23

Module-wise Update:

Module Name: Shop Floor Management (SFM)
Screen: P1/O2 Rise / P1/O2 Received Transaction
Enhancement:
Renamed the transaction title and initiating button from P1/O2 to Assistance WI for better clarity.

Screen: WI Progress Transaction
Enhancement:

Added a Refit / Operational toggle to filter WI types on the screen.

Module Name: OPRA
Screen Name: RA Assign PRM
Enhancements:

Updated filter sequence to:
SHIP → OPs Type → WO No. → OPRA No.
Fixed issue where OPRA No. field showed AMP/SMP numbers even when OPRA Type was selected as Normal.
Removed pagination for PRM and Center List to allow viewing all entries at once.
Added a new Sub Equipment field next to the Equipment field in the grid.
Removed the Equipment Location field as it is no longer required.
Updated column sequence in the grid to:
OPRA No → OPRA Class → Equipment Name → Sub-Equipment Name → OPRA Description → Dart No → Ship Remarks → PRM → PRM Name → Proposed COSM → Maintop No → Quick Update → Detailed View

Refit/OPS
Version: v1.12.18
Release Date: 2025-07-25

This release include improvements to the Shop Floor Management (SFM) module and Quality Management (QCMS), including better tracking, new filters, and added fields for more detailed information.

Module Wise Update
Module Name: Shop Floor Management (SFM)
Screen: P1/O2 Rise / P1/O2 Received
Enhancement:

Added a field to show the initiating center on the screen. This field is non-editable and helps track the source of the transaction.


Screen: CRF Request
Bug Fix:

Fixed an issue where CRF requests were showing for all ships. Now, the system reflects CRF requests only for the selected ship.

Enhancement:

Made the Work Order field mandatory and added filters for Ship and Work Order to improve data selection.

Screen: Approve CRF
Enhancement:

Added a “View Remarks” button on the details page to allow users to see remarks added during the CRF approval process.

Screen: CRF Details / History
Enhancement:

Added filters for WO (Work Order) and Refit Type (Refit/OPS) to help users narrow down CRF history more effectively.

Screen: Raise QC Request
Enhancement:

Added the following non-mandatory fields linked to Work Location to help track exact site details:

Contact Person

Mobile No.

Building No.

Landmark

Bug Fix:

Fixed the issue where Work Order Number (WO No.) was not displaying on the screen.

Added the WO No. column to the grid for better visibility.



Screen Name: CRF Request
Field for Work Order is required,  ship and wo filter required done error type: New requirment.

Screen Name: Approve CRF Rquest
The WO No. is not reflecting over the screen, add wo no in grid.


Version: v1.12.19
Release Date: 2025-07-28

Module Name: Shop Floor Management

Screen Name: CRF Request
Enhancement
Field for Work Order is required,  ship and wo filter required is done. 
Type of error: New Requirement.
The field of Revised PSD should be by default Present date, Current date will set only when it's between Period Of Refit is done 
type of error: New requirment.

Screen Name: Approve CRF
Bug Fix

The WO No. is reflecting over the approve CRF screen and added WO No. in the grid.

Version: v1.12.19
Release Date: 2025-07-28

Overview
This release includes key enhancements to the CRF Request and Approve CRF screens, as well as a bug fix to improve the functionality of Work Order (WO) handling and display.

Module Name: Shop Floor Management

1. Screen Name: CRF Request
Enhancement

A new Work Order field has been added and is now required. The Ship and Work Order Filter functionality has been implemented.

The Revised PSD field now defaults to the current date, and the date is set to the Current Date when it falls within the Period of Refit.

2. Screen Name: Approve CRF
Bug Fix

The Work Order Number (WO No.) now correctly reflects on the Approve CRF screen. Additionally, the WO No. has been added to the grid.

Version: v1.12.20
Release Date: 2025-07-29

Module Name: Refit Planning Program
Screen Name: Release Work Instruction

Description:
Enhancement to the Release Work Instruction screen functionality.

Details:

When PRM is selected from the drop-down on the Work Instruction screen and an EMD value is entered, upon saving the transaction:

The selected PRM value is correctly populated in the Release Work Instruction field and the entered EMD value remains unchanged and is retained.

Version: v1.12.21
Release Date: 30-07-2025

Module Name: Refit Planning (RPP)

Screen Name: DL Assign PRM
Type of Change: Bug Fix

Provided a delete option for PRM entries after assigning the defect list.

Resolved an issue where data was not displayed in the DL Assign PRM grid after applying DL Class and DL Type filters.

Screen Name: WI Details
Type of Change: Enhancement

In the Work Details grid, replaced the Work Order Number column with Defect Number.

Replaced Main Center Number and Work Center Number as a main center name and work center name in the Work Details grid.

Screen Name: Work Instruction Amendment
Type of Change: Bug Fix

Fixed an issue where data was not populating after applying DL type and DL Class filters on the Work Instruction Amendment screen grid.

Screen Name: Approve CRF Request
Type of Change: Bug Fix and Enhancement

Added the following columns to the Approve CRF Request grid:

Revised Proposed Start Date

Revised Proposed Completion Date

Revised EMD

Updated Job Detail column text alignment to wrap correctly for improved readability.


Version: v1.12.22
Release Date: 2025-07-31

Screen Name: DL Approve

Overview
This update fixes a redirection issue, ensuring accurate navigation to the selected Work Order from Quick Links.

Type of error: Bug
Resolved an issue where the redirection behavior was inconsistent. Now, the system correctly redirects to the specific Work Order (WO) only for the transaction selected via Quick Link 

Version: v1.12.22
Release Date: 2025-07-31

Overview

Module Name: Financail Managment
Screen Name: Initial Proposal

1. The proposal type GFR 149 AIP consists of three component i.e offload, MAT and Yard, should remaned in the dropdown as GFR 149 AIP Offload, GFR 149 AIP MAT and GFR 149 AIP Yard is done.
2. Rename the open document viewer as file viewer.

Overview
This release includes UI enhancements in the Financial Management module to improve clarity and usability within the Initial Proposal screen.

Module Name: Financial Management
Screen Name: Initial Proposal

Enhancements:

The Proposal Type dropdown for GFR 149 AIP has been updated to clearly list its components as:

GFR 149 AIP Offload

GFR 149 AIP MAT

GFR 149 AIP Yard

The Open Document Viewer has been renamed to File Viewer for improved clarity.

Vizag 
Version: v1.12.22
Release Date: 2025-07-31

Module Name: Operational Request Assistance (OPRA)
Screen Name: RA Assign PRM
Type of Error: Bug

In OPRA No. even after selecting OPRA type as Normal the OPRA no. field is reflecting AMP, SMP No. also., while saving ops wo need to check refit_type_code, Need to add new column in refit_type_mst refit_ops_flag = R/O, ] , need to change api and pass value R or O for dropdown ops type, UI - rename opra class to Defect class, new column add defect no is done

Module Name: Operational Request Assistance (OPRA)
Screen Name: RA Assign PRM
Type of Change: Bug Fix

Overview:
This release addresses multiple issues and enhancements in the RA Assign PRM screen within the OPRA module:

Bug Fixes and Enhancements:

Resolved an issue where, even after selecting the OPRA type as Normal, the OPRA No. field incorrectly displayed AMP and SMP numbers.

Implemented validation during Ops Work Order (WO) save to check the refit_type_code against a new flag.

Added a new column refit_ops_flag with values R/O in the refit_type_mst table.

Updated API to pass values R or O based on the dropdown selection for Ops Type.

UI Update:

Renamed OPRA Class to Defect Class.

Added a new column to display Defect No


Version: v1.12.24
Release Date: 2025-08-01

Module Name: Operational Request Assistance (OPRA)
Screen Name: RA Wrok Instruction 
Type of Error: New Requirement

1. If single center is assigned in "DL Assign PRM" screen; the same center should reflect in the field of Main center by default in "RA WI" screen. But if more than one is assigned it should be selected mannually is done.
2. System should show only center in Main center and Woek Center dropdown for selected department is done.

1. When a single center is assigned in the DL Assign PRM screen, that center is now automatically populated in the Main Center field on the RA Work Instruction screen.
If multiple centers are assigned, users is able to manually select the appropriate Main Center.


2. The Main Center and Work Center dropdowns on the RA Work Instruction screen now display only the centers that belong to the selected department.


Vizag
Version: v1.13.01
Release Date: 2025-08-01

Module Name: Operational Request Assistance (OPRA)
Screen Name: RA Wrok Instruction 

Type of Error: Enhancement
Enhancement
When a single center is assigned in the DL Assign PRM screen, the same center is now automatically populated in the Main Center field on the RA Work Instruction screen.
When multiple centers are assigned, users can now select the Main Center manually.
The system now filters and displays only relevant Main Center and Work Center options based on the selected department.

Version: v1.13.02
Release Date: 2025-08-04

Module Name: Refit Planning (RPP)
Screen Name: PRM Remarks

Type of Error: Enhancement
Added a direct toggle switch in the Assign PRM section, allowing the PRM to select options directly without assignment, if it is finalized.

Module Name: Operation Request (OPRA)
Screen Name: WI Details

Type of Error: Enhancement
Added new filters: OPRA Type and OPRA Number, and removed the date filter.


Vizag
Version: v1.13.03
Release Date: 2025-08-05

Module Name: Shop Floor Management (SFM)
Screen Name: CRF Details/History

Type of Error: Enhancement
Added Work Order Number field, Status field, Refit toggle, and OPS toggle for easier filtering, and also added a Status column to the grid.


Type of Error: Bug
Resolved an issue where incorrect data was displayed on the screen; it now reflects accurate information

Screen Name: WI Release  of the day

Type of Error: Enhancement
Updated the screen to show both 'CRF WI' and 'Normal WI'. Earlier, only 'Normal WI' was displayed.


Version: v1.13.02
Release Date: 2025-08-04

Module Name: Financial Management (FMS)
Screen Name: Initiate Proposal Screen

Overview
This release includes updates to the FMS module. It covers new field additions, label changes, and calculation improvements

Type of Error: Enhancement

What's New / Changed:

New fields added under New Proposal Activity:

Type of Purchase – Dropdown with options: Goods and Services

Reverse Auction and Re-Tendering – Toggle buttons added

All the BOQs renamed to BQ.

Field label updates:

Pre-Qualification Criteria is now Pre-Qualification Criteria / Vendor Evaluation Criteria

Draft RFP is now Draft RFP / GeM

All references to IFA have been updated to FA

Note:

While the dropdowns and toggle buttons are visible on the screen, saving the data for toggles is not yet functional and will be fixed in a future update.

Screen: Professional Officer Evaluation (POEV)
Error Type: Enhancement

The Escalated % amount is now correctly added to the Last Purchase Price, and the final amount is displayed on the screen.
Opening Balance

Revised screenshots of pages within the document

In WI screen WO  Number is not reflecting/Add new column Wo Number[1)prm remark screen--give hyperlink to center->onclick->set data to remarks dropdown, proposed emd, proposed qc] 2)and Dl finilazation screen-> once click on prm remark->set data to final cosom remark

Version: v1.13.04
Release Date: 2025-08-07
Overview
This release includes updates to the Refit Planning Program (RPP), Operational Request Assistance (OPRA), and Defect List (DL) modules. It includes new features and bug fixes.

Module Name: Operational Request Assistance (OPRA)
Screen Name: Work Instrcution Details

Type of Error: Bug Fixed
Fixed an issue where the work order number did not appear on the Work Instruction Details screen.

Module Name: Refit Planning (RPP)
Screen Name: PRM Remarks
Type of Error: Enhancement (New Feature)
Added a hyperlink in the PRM Remarks screen’s center section to provide quick access to Remarks, Proposed EMD, and Proposed QC drop-down fields

Module Name: Defect List (DL)
Screen Name: DL Finalization (New Feature)
Added functionality in the DL Finalization screen so that selecting PRM Remarks sets the data to the final CSOM remark.

Version: v1.13.08
Release Date: 2025-08-12

This release includes enhancements to the Shop Floor Management module, specifically the Assistant P1/O2 Raise and Assistant P1/O2 Received screens.
Module Name: Shop Floor Managment
Screen Name: Assistant P1/O2 Raise and Assistant P1/O2 Received 

Type of Error: Enhancement
Added an option in the existing screen to display the Center initiating the transaction. This field is view-only (non-editable).
Updated ship data retrieval logic to display only ships whose Work Orders (WO) are open under the respective Refit or Operational category.
In the header section, fields for Raised By PRM and Center will now also display Assistant Center and Assistant PRM as editable fields.
Header fields have been realigned as per the discussed layout.
Main Center and Work Center fields have been updated to display only the list of centers associated with the selected department. 


Version: v1.13.15
Release Date: 2025-08-22

Overview
This release introduces several enhancements across the Refit Planning Program (RPP), Shop Floor Management (SFM), and Operational Refit (OPRA) modules.

Module Name: Refit Planning Program (RPP)
Screen Name: Work Order - Refit

Enhancement
Added a drop-down list for the Refit Type field. Sequence of values:

GRDD (Guaranteed Repair Dry Docking)

SR

ESR (Extended Short Refit)

NR

MR

Mid-Life Update

MRMLU

ERDD

On the Transaction Dashboard, replaced the Create button with a Go button to let users move to the next screen.

Screen Name: Work Instruction
Enhancement:
Added a default value of 0 for the Estimated Mandays field.

Module Name: Shop Floor Managment (SFM)
Screen Name: P1/02 Rise / P1/02 Received
Enhancement:
Disabled the EMD field. 

Module Name: Operational Refit (OPRA)
Screen Name: Work Instrcution
Updated the Main Top and Dart No. fields to capture the print format.

Version: v1.13.17
Release Date: 2025-08-26

Overview
This release includes bug fixes and enhancements across multiple modules such as Operational Request (OPRA), Refit Planning (RPP), and Quality Check (QCMS).
Operational Request (OPRA)
Screen: RA – Assign PRM

Bug Fix

Resolved an issue where, after selecting the OPS Type or WO No. field filter, the grid now displays the correct records.

Screen: RA – Work Instruction

Enhancement

Added an assertive symbol for the Location Ship field.

Refit Planning (RPP)

Enhancement

Added the following columns in the grid sequence of values:

Center Remarks

Add Remarks

EMD

QC Level

PRM Remarks

Quality Check (QCMS)
Screen: Raise QC

Enhancement

Added a QAP Number field to the screen. 


Version: v1.13.19
Release Date: August 29, 2025

Module: Refit Planning (RPP)
Screen: DL Finalization

Enhancement

Added a hyperlink for PRM Remark in the Quick Update dialog and for Prm Name in detailed view.
When users click the PRM Remark or PRM Name hyperlink, the PRM remark and additional PRM remarks is auto-fetched into the COSM Final Remarks field along with the additional remark column.

Screen: Work Instruction

Enhancement
Job summary data entered during work order creation now defaults into the Job Detail field on the Work Instruction screen.

Screen: PRM Remarks
Enhancement

Added the option to change or delete the existing center assigned to the PRM.
Users can now add a new center when remarks are assigned to PRM.

Screen: DL – Assign PRM

Enhancement
1.Added pagination (up to 25 items) in the detailed view of DL – Assign PRM.
2.Users can now add PRMs more efficiently in the detailed view.


Location: Mumbai
Version: v1.13.19
Release Date: August 29, 2025

Module: Shop Floor Management (SFM)
Screen: CRF Approve 

Update
The Revised PCD and Revised PSD fields are no longer mandatory on the CRF Approve screen.

Screen: Approve CRF Request
Enhancement
Users can now request changes in any of the three fields in the CRF Request: Revised_PSD, Revised_PCD, and Actual_AMD. When one field is selected, the other fields are automatically disabled.
The selected field, such as Date or EMD Raised from PRM, is now reflected on the Approve CRF Request screen.



Module Name: Financial Management (FMS) 
Screen: New propsal transaction
Data

Transaction Dashboard Condition handled for both division for draft tab


Module Name: Refit Planning (RPP)
Screen Name: DL Finalization

Enhancement
Added hyperlink for PRM remarks in the quick update dialog by clicking PRM Remark hyperlink auto fetched PRM remarks comment in the COSM final Remarks with additional remark. column 
Screen Name: Work Instrcution
Enhancement 
Data entered for job summary while creating the work order same is reflected in the Job detail feild by deafult on work instruction screen.

Enhancement
Screen Name: PRM Remarks
Once assigned, If User wants to change the assigned center or add new center the system should allow User to change; currently it is throuwing error as "center alredy assigned.
Added the provision to change the assigned center, add new one center name once it is assigned to PRM to add remarks.  

Screen Name: DL -Assign PRM 
Enhancement
Added Pagination upto 25 allows user to add the PRM in the detailed view of DL - Assign PRM. 
In detailed view: assign PRM pagination should be increased to 25 (by default) 

Mumbai
Version: v1.13.19
Release Date: 2025-08-29

Module Name: Shop Floor Management (SFM)
Screen Name: CRF Approve 
While raising CRF request 'Revised PCD' & 'Revised PSD' is not mandatory but in 'CRF Approve' screen these are mandatory fields.
Updated the field of revised PCD and Revised PSD are not mandatory fields on CRP Approve Screen.

Screen Name: Approve CRF Request
Enhancement
Give provision to highlight only those Field (Either date or EMD) on which the request has been raised by PRM.
The user selected field such as date or EMD raised from PRM is same reflected on the approve CRP Request screen if one field is selected then another field are disabled on the Approve CRF Request.

Version: v1.13.20
Release Date: 2025-09-02

Module Name: e-Seva
Screen Name: Bio-Data Master

Enhancements

Added a new Others text field when Other is selected in Specialization.

Updated Membership to NOI Membership.

Set India as the default value in Country field under Address.

Added Group dropdown field (non-mandatory).

Added Designation dropdown field (non-mandatory).

Changed Rank values to display from higher level to lower level.

Bug Fixes

Removed incorrect default dates (1970) from Past Appointments – From and To fields.

Screen: Board Master
Enhancements

Removed the following fields:

Authority No.

Authority Letter Date

Order No.

Description

Status

Updated Nominees List layout:

Rank and Designation are now separate columns.

Branch and Department are now separate columns.

Implemented functionality to generate the selected rank-wise officer list and forward it to the TA to ASD.

Made Board Status field non-mandatory.

Screen: Bio-Data Report
Enhancements

Updated report logic to display only active officers in the yard

Screen: Board Detail Report
Enhancements
Removed the Location column.
Added a Board Summary that shows the total number of boards per unit.

Screen: Social List Report
Bug Fixes
Resolved issue where saving caused a 500 internal server error.
Fixed issue where the Data not found message was displayed incorrectly.


 
 
Version: v1.13.20
Release Date: 2025-09-01

Overview
This release includes enhancements and bug fixes for the RPP and OPRA modules.

Module Name: Refit Planning (RPP)

Screen: Add DL Defects Transaction

Updated the Dart Ref Number field to be non-mandatory.

Screen: DL Assign PRM

Added pagination (up to 25 items) in the detailed view of DL – Assign PRM. Improved usability: users can now add PRMs more efficiently in the Assign detailed view.

Screen: PRM Remarks

Bug fix: 
Resolved an issue where the Assigned Centre field now allow users to add or edit the field when assigning PRM Remarks.

Module: Operational Refit (OPRA)
Screen: RA -Assign PRM

Bug fix: 
Resolved an issue where the MPC Remarks field allows MPC users to add or edit FMU remarks while logged into the system.



Version: v1.14.1
Release Date: 2025-09-02

Overview
This release includes both enhancements and bug fixes across the Refit Planning (RPP) and OPDEF modules.

Screen: PRM Remarks Transaction

Bug Fixes

Resolved an issue where the PRM Remarks hyperlink did not populate related data. The hyperlink now correctly displays values for Add Remarks, EMD, and QC Level, instead of showing only remarks.

Screen: WI Release for the Day Report

Enhancements

Added a WI column in the grid.

Added a filter option for Refit and Operational with the following mappings:

Ops Type → WO No. (OPS)

Ops Type → OPRA Number

Screen: PRM Remarks 

Enhancements

Added the following fields in the Quick Update pop-up:

Remarks

QC Level

EMD

Version: v1.14.1
Release Date: 2025-09-02

Overview
This release .

Module Name: Personnel
Screen Name: Employee Master 

Enhancement

Renamed the field OPS/GPF
Added button in the address accordian.

Screen Name: Employee Nominee Detail
Added new four accordian for insert mode.

Module Name: Leave 
Screen: Bulk Leave approval Transaction
Completed whole screen as per new requirment.

Screen Name: Leave Ammendment Transaction
Added column to calculate +/- leaves. 

Module Name: LTC 
Screen Name: LTC Advance 
Completed field mapping for edit mode.
Added new drop-down field.

Module Name: TY Duty
Screen Name: MRO TY Duty

Added new text fields for; MRO Ref. No., Mode of Payment
Renamed the field Refund Date to MRO Refund Date.

Module Name: Quatering
Screen Name: Under Vacation Transaction
Spell corrected of retention completion date field.

Hardcoded values of removed and added new drop-down value from MISC- Master.

Screen Name: Quater Application
Added new field as Data of Retirement.


Overview

This release introduces enhancements across Personnel, Leave, LTC, TY Duty, and Quatering modules. Updates include new fields, renamed fields, corrections, and improved screen functionality.

Personnel Module
Employee Master

Renamed the field OPS/GPF.

Added a button in the Address accordion.

Employee Nominee Detail

Added four new accordions for insert mode.

Leave Module
Bulk Leave Approval Transaction

Completed the screen redesign as per the new requirements.

Leave Amendment Transaction

Added a column to calculate positive and negative leave balances.

LTC Module
LTC Advance

Completed field mapping for edit mode.

Added a new drop-down field.

TY Duty Module
MRO TY Duty

Added text fields for MRO Ref. No. and Mode of Payment.

Renamed the field Refund Date to MRO Refund Date.

Quatering Module
Under Vacation Transaction

Corrected the spelling of the Retention Completion Date field.

Removed hardcoded values and updated drop-down values from MISC–Master.

Quarter Application

Added a new field: Date of Retirement.


Version: V1.14.2
Release Date: 2025-09-03

Module Name: Operational Refit (OPRA)
Screen Name: RA Assign PRM
Enhancement
Added a Sub-Equipment column in the grid next to the Equipment field.
Updated the column sequence as follows:
OPRA No.
OPRA Class
Equipment Name
Sub-Equipment Name
OPRA Description
Dart No.
Ship Remarks
PRM
PRM Name
Proposed COSM
Maintop No.
Quick Update
Detailed View
Fixes

Module Name: Operational Defect (OPDEF)
Screen Name: Raise OPDEF
Bug fix:
Resolved an issue where the Main Center and Work Center drop-downs did not reflect 
the selected PRM data (Main Center and Work Center). Both fields now display the correct selections of Main center and work center fields.

Module Name: OPRA and RPP
Screen Name: Work Instrcution

Enhancement
Added a Work Center patch for the Work Instruction screen. 
Prevoiusly the user has to select main work center from drop-down list while generating WI, now it is automatically fetched in the WI while generating WI.   


Version: V1.14.2
Release Date: 2025-09-03

Module Name: Financial Management System
Screen Name: Enclosure, Upload, BQ Criteria routing

Added delete functionality. 

Version: V1.14.2
Release Date: 2025-09-03

Module Name: Financial Management System
Screen Name: Enclosure, Upload, BQ Criteria routing

Added delete functionality. 

Version: V1.14.2
Release Date: 2025-09-03

Enhancements
Module: Quartering

Screen: Allotment Quartering

Added a new Allotment Type field as a dropdown.

Added NPS/PRAN field.

Module: Personnel

Screen: Annual Increment

Added two new fields in the grid:

Date of Next Increment

Remark in the grid

Fixes
Module: TY-Duty

Screen: Ty Duty Proposal

Fixed an issue where the Next Updator role was not getting saved.

Module: Leave

Screen: Apply Leave

Updated behavior for Leave Reasons section to show or hide based on the selected leave type.




Overview

This release introduces key fixes and enhancements to the Board Master and Bio-data Report screens in the E-SEVA module. The updates are focused on improving data accuracy, usability, and system reliability. Key changes include the addition of new data columns, restructuring of nominee details, report format alignment, and resolution of critical saving issues.

Module: E-SEVA

Enhancements
Screen: Bio-data Report

Added new columns to improve reporting and data completeness:

Branch, Designation, Group, Qualification, Specialization, Next of Kin (NOK), Anniversary, Birthday, State, City, Past Appointments, and Medical Category.

Enhanced Excel export functionality: Active service officers are now displayed.

Report column format updated to align with the existing application:

S.No | Name | ID | Rank | Designation | DOB | DOC | DOP | DOR | Photo.

Screen: Board Master

Nominees List has been improved:

Rank/Designation are now displayed as separate columns.

Branch/Department are now displayed as separate columns.

A rank-wise officer list is now generated and automatically forwarded to the relevant authority.

Bug Fixes
Screen: Board Master

Fixed issue where saved board details were not appearing in the data view.

Resolved a critical error where the system was unable to save data, showing 500 internal server error.


2025-08-01


Rough
Bug 
RA Assign PRM 
Bug Resolved data feteched 

RA PRM Remarks
Change Request : PRM Should see only his remarks details, other PRM details will not visible.

Release Notes

Version: V1.14.3
Release Date: 2025-09-04

Overview
This release include the bug fix for the OPRA module delivers stability improvements and a usability update.

Module Name: OPRA
Screen Name: RA Assign PRM

Bug fix

The system now correctly fetches data on the RA Assign PRM screen.

RA PRM Remarks

Change request: PRMs can now view only their own remarks. Other PRM details by other PRMs are no longer visible.


Version: V1.14.3
Release Date: 2025-09-04
SWM - PAY and GPF
Overview

This release for the SWM (Salary and Wage Management) module focuses on stability improvements and minor enhancements. The changes primarily address API integrations, cosmetic updates to reports, and improved handling of data transactions. 

Module Name: SWM - PAY
Fixes and Enhancements
Transaction – DA Arrears

Category: Enhancement

Integrated the Save, Update, and View API to ensure accurate data persistence when saving DA arrears transaction records.

Module Name: SWM GPF
Sanction Report

Update:

Improved the print-to-PDF functionality with minor cosmetic changes for better readability and alignment.

Tulip Report

Updated Excel export layout with cosmetic adjustments for clearer presentation of data.

Release Notes

Version: V1.14.3
Release Date: 2025-09-04

Module: Quatering
Retention Request

Enhancement: The hardcoded values in the Retention Request screen have been replaced with API integration.

Available options in the drop-down: Transfer Children, Education Purpose, Retirement, Death, VRS, CRS, Dismissal from Service, Termination of Service
Off Service, Resignation, and Quater Status

Enhancement: The Unit field drop-down is now integrated with API values.

Available options in the drop-down: ASD Pool Ulhasnagar, ASD Pool Powai, NHQ Pool Powai

Bug fix: The Show Data button now works as expected. Data is correctly displayed in the grid after filters are applied.


Module Name: TY Duty
TY Duty Proposal

Enhancement: The field TY Duty has been renamed to TY Duty Reporting Date.

Version: V1.14.3
Release Date: 2025-09-04

Module: Time Keeping (TKS)
Time Card

Bug fix: The employee location field now correctly fetches the logged-in employee’s user location.

Screen Name: Daily Attendance Report 

Enhancement: Screen updated based on new user requirements.

Enhancement: Added UI validation to enforce required field selection.

Change: The MPB Mustar OT report has been moved from MPB to TKS.


Version: V1.14.3
Release Date: 2025-09-04

This release delivers enhancements to the QAM Module, specifically targeting the Formats Registers and Reports and Internal & External Audit screens. The updates focus on improving data accuracy, introducing new configurable fields, and enhancing audit reporting capabilities. These changes provide users with greater flexibility, improved compliance tracking, and streamlined workflows.

Enhancements
Screen Name: Formats Registers and Reports

Updated the Record Code field to function as Register Number for improved consistency.

Added a Review Period field with options: Day, Week, Monthly, Quarterly, Half-Yearly, Yearly.

Introduced a Reviewer field and data automatically fetched from PIMS/E-Seva, ensuring accuracy and reducing manual entry.

Added Last Review and Next Review fields.

Enables users to monitor historical reviews and plan upcoming reviews.

Screen Name: Internal & External Audit

Added a dropdown to select between Internal and External audits.

Introduced an Auditee field for manual data entry.



Verison Number: 
Release Date: 2025-09-05
Module: Quatering
Retention Request

Enhancement: The hardcoded values in the Retention Request screen have been replaced with API integration.

Available options in the drop-down: Transfer Children, Education Purpose, Retirement, Death, VRS, CRS, Dismissal from Service, Termination of Service
Off Service, Resignation, and Quater Status

Enhancement: The Unit field drop-down is now integrated with API values.

Available options in the drop-down: ASD Pool Ulhasnagar, ASD Pool Powai, NHQ Pool Powai

Bug fix: The Show Data button now works as expected. Data is correctly displayed in the grid after filters are applied.


Note: When user choose a Send To option for article transportation, the TP/Hanger and Balance Onboard Life in Months fields becomes either editable or read-only.


Verison Number: V1.14.4
Release Date: 2025-09-05
Module: Financial Management System (FMS)

Screen Name: File Viewer
Added two new tab on the file viewer screen Editor and Routing UI Implement for Editor and in routing user interface completed. 
API call is pending to the 


Verison Number: V1.14.4
Release Date: 2025-09-05
Module: Leave 
Overview
This release of the Leave Module resolves Employee Popup issues across all leave screens and completes API integration. Payload values employee_code and role_code have been added to ensure accurate data handling and consistency

Bug Fixes

Screen Name: OLD CCL Screen

Resolved Employee Popup Issue in Leave OLD CCL Master screen.

Screen Name: OLD Encashment
Resolved Employee Popup Issue in Leave OLD Encashment screen.

Screen Name: Apply Leave
Resolved Employee Popup Issue in Leave Apply Leave screen.

Screen Name: Covering Leave Screen
Resolved Employee Popup Issue in Leave Covering Leave screen.

Screen Name: Leave Balance Amendment
Resolved Employee Popup Issue in Leave Balance Amendment screen.

Screen Name: Leave Dies Non
Resolved Employee Popup Issue in Leave Dies Non screen.

Screen Name: Leave Cancellation
Resolved Employee Popup Issue in Leave Cancellation screen.

Enhancements

Screen Name: OLD CCL Screen

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: OLD Encashment

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: Apply Leave

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: Covering Leave Screen

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: Leave Balance Amendment

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: Leave Dies Non

Completed API integration.

Added payload values: employee_code, role_code.

Screen Name: Leave Cancellation

Completed API integration.

Added payload values: employee_code, role_code.

Verison Number: V1.14.4
Release Date: 2025-09-05

Module Name: TY DUTY
Overview
This update addresses the Employee Popup issue in the TY Duty Proposal screen. API integration has been completed, and new payload values employee_code and role_code are included for improved accuracy and consistency

Bug Fixes

Screen Name: TY Duty Proposal

Resolved Employee Popup Issue in TY Duty Proposal screen.

Enhancements

Screen Name: TY Duty Proposal

Completed API integration.

Added payload values: employee_code, role_code.

Verison Number: V1.14.4
Release Date: 2025-09-05
Module Name: Berthing Management System (BTMS)
Overview
This release for the BTMS Module delivers fixes for data retrieval and export issues while enhancing dropdown options in the Moment Plan screen. The updates improve usability and ensure accurate reporting.
Bug Fixes

Screen Name: Moment Order

Resolved data retrieval issue for From Location and To Location fields in Moment Order screen.

Screen Name: Moment Status
Fixed export issues in Moment Status screen for Excel and PDF formats.

Enhancements

Screen Name: Moment Plan Screen
Updated dropdown values for Moment Position field in Moment Plan screen.

DD:
1)add new values orientation field dropdown dry dock booking screen
2)add new values orientation field dropdown dry dock plan screen
3)Add new values in dropdown draught dry dock plan
4)Rename draught field Trim BY dry dock plan screen
5)solve issue dry dock plan screen duplicate values
6)solve issue dry dock booking screen duplicate values

Verison Number: V1.14.4
Release Date: 2025-09-05

Module Name: Personnel
Bug Fixes
Screen Name: Employee Nomination Detail
Resolved insert and update mode issues in Nomination Detail screen.

Verison Number: V1.14.4
Release Date: 2025-09-05
Module Name: Operational Request (OPRA) 
Overview
This release for the OPRA Module addresses missing Status field values and resolves pop-up issues in the PRM Remark RA screen, improving data accuracy and usability.
Bug Fixes

Verison Number: V1.14.4
Release Date: 2025-09-05
Screen Name: PRM Remark RA
Resolved issue where the Status field value was empty.
Fixed pop-up functionality in PRM Remark RA screen.

Verison Number: V1.14.4
Release Date: 2025-09-05
Module Name: Opreational Defect (OPDEF)
This release for the OPDEF Module fixes the data duplication issue in the PRM Remarks screen, ensuring accuracy and consistency of records.

Screen Name: OPDEF PRM Remarks

Bug Fixes

Resolved data duplication issue in OPDEF PRM Remarks screen.

Verison Number: V1.14.4
Release Date: 2025-09-05

Module Name: Refit Planning (RPP)
Bug Fixes

Screen Name: Work Instruction

Resolved issue with Sub System field — data now fetched correctly in update mode.

Screen Name: WI Release
Fixed issue where EMD Mandays was not appearing — now displayed correctly.

Screen Name: WI Amendment
Corrected data issue in WI Amendment screen — data now displays accurately.

Enhancements

Screen Name: WI Release

Updated Main Centre and Work Centre columns: values now display column names instead of numbers 

Module Name: E-SEVA

Verison Number: V1.14.5
Release Date: 2025-09-07

Screen Name: Board Master
Board No. Column Should be as Manual entry field.
Screen Name: Board Master
Add the fields - Info(text box with Multi add), Nominated by (Dropdown) - Dept/TA to ASD",
Screen Name: Bio-Data Master
Print format is needed
Screen Name: Nominal Roll
Employee list pop-up is freezing. Not disappearing after deselecting all the employees and clicking Accept button.
Screen Name: Social List
Please update the system to remove the date field as a mandatory entry. All active officers should be displayed by default.

E-SEVA

Verison Number: V1.14.5
Release Date: 2025-09-07

Overview
This release introduces improvements to the Board Master and Social List screens, adds a print option in Bio-Data Master, and fixes the employee list pop-up issue in Nominal Roll.
Enhancements

Screen Name: Board Master

Changed the Board No. column to a manual entry field.

Added new fields:

Info (text box with multi-add option)

Nominated by (dropdown: Dept/TA to ASD)

Screen Name: Social List

Removed the Date field as a mandatory entry.

Updated the display to show all active officers by default.

New Features

Screen Name: Bio-Data Master

Introduced a print format option.

Bug Fixes

Screen Name: Nominal Roll

Fixed an issue where the Employee list pop-up froze and did not disappear after deselecting all employees and clicking Accept

Module Name: Manpower Booking (MPB)

Verison Number: V1.14.5
Release Date: 2025-09-07

Screen Name: Allocation Report 
Provide a row below the grid: to display the Total number of OT Hours.
Screen Name: Allocation Report 
Provide serial number and total number of Allocation hours in the PDF.
Screen Name: OT Booking 
Provide a row below the grid: to display the Total number of OT Hours.
Screen Name: OT Booking
Provide serial number and total number of OT hours in the PDF.
Screen Name: OT Booking 
Ministerial Employee data should come.
Screen Name: OT Bookig 
Validations handle with remaining hrs of employees.
Screen Name: OT Booking ammendment 
After ammendment of ot that employee come again in ot ammendment screen till OT finalization not done for that employees.


Manpower Booking (MPB)

Verison Number: V1.14.5
Release Date: 2025-09-07

Overview
This release enhances overtime booking and reporting in the Manpower Booking (MPB) module. It improves visibility of OT hours in reports, includes ministerial employees, strengthens validations, and resolves issues in the OT amendment process.

Enhancements

Screen Name: Allocation Report

Added a row below the grid to display the total number of OT hours.

Updated PDF output to include serial numbers and the total number of allocation hours.

Screen Name: OT Booking

Added a row below the grid to display the total number of OT hours.

Updated PDF output to include serial numbers and the total number of OT hours.

Included ministerial employee data in the report.

Bug Fixes

Screen Name: OT Booking

Fixed validation handling for remaining hours of employees.

Screen Name: OT Booking Amendment

Corrected an issue where employees reappeared in the OT amendment screen after amendments, until OT finalization was completed.


Module Name: Time Keeping (TKS)

Verison Number: V1.14.5
Release Date: 2025-09-07

Screen Name: Amend Attendance
Duplicate data showing in view transaction dashboard.
Screen Name: Print Pass Report
cancel pass should not come in data.
Screen Name: Daily Freeze  
Division Config new field added and handle this screen validation through that field value.
Screen Name: Assign Key Duty 
Validation handled for employees which have been assign will not come again between from and to date.
Screen Name: OT Finalization 
If actual OT hrs>= Booked OT then that employee should not be editable this validation handled.



Time Keeping (TKS)

Verison Number: V1.14.5
Release Date: 2025-09-07

Overview
This release improves validations in Daily Freeze, Assign Key Duty, and OT Finalization, while fixing issues in Amend Attendance and Print Pass Report for more accurate and reliable timekeeping.

Enhancements

Screen Name: Daily Freeze

Added a new field in Division Config and applied validations based on this field value.

Screen Name: Assign Key Duty

Implemented validation to ensure employees already assigned will not appear again within the specified date range.

Screen Name: OT Finalization

Added validation to restrict editing when actual OT hours are greater than or equal to booked OT hours.

Bug Fixes

Screen Name: Amend Attendance

Fixed an issue where duplicate data appeared in the View Transaction dashboard.

Screen Name: Print Pass Report

Corrected data to ensure canceled passes do not appear in the report.


VMS (Vendor Management System)

Overview

This release includes multiple fixes and enhancements to the Vendor Master screen. The changes improve vendor categorization, registration workflows, system validations, performance, and data accuracy.

Enhancements

Vendor Category Color Coding
Added different color codes for vendors based on their category (A, B, C, D, E).

Vendor Registration Improvements

Inclusion of Vendor Registration Module and Electronic Vendor Registration.

Provision for Temporary Registration with functionality identical to registered vendors.

UI and Field Updates

Added a Sub Type dropdown with values:
HULL (H)

ENGINEERING (E)

ELECTRICAL (L)

ELECTRONICS & WEAPONS (W)

2. Registration categories updated to:

R (Registered Vendors)

U (Unregistered Vendors)

Ty (Temporary Registered Vendors)

3. Turnover and financial capacity headers updated to: Turnover (in Lakhs) and Financial Capacity (in Lakhs)

4. Contact Person Details field is no longer mandatory.

5. Turnover Details field is not mandatory for temporary registration.

6. Allowed all special characters in the Address field.

7. Allowed special characters in Account Holder Name.

8. Removed auto-capping of characters in input fields.

Functional Issues Fixed

Restored Category B field for vendors who are registered but whose registration has expired.

Fixed error preventing saving vendor details during update stage (previously showing bank long name error).

Resolved issue where searching with IFSC Code incorrectly displayed numbers in the Bank Name field.

Performance Improvements

Improved loading performance for:

a. Vendor details in the grid.

b. Bank details in the Account Details tab.

Data Accuracy Fixes

Corrected vendor list count: registered vendors list now shows 124 entities instead of 205.

Ensured all vendor data is retrievable within the system.


Refit Planning (RPP)

Version Number: V1.14.6
Release Date: 2025-09-09

Overview
This release of the Refit Planning (RPP) module fixes reporting, finalization, and Work Instruction issues. 
The update improves DL visibility, report accuracy, and workflow efficiency.

Bug Fix
Screen Name: DL Summary Report
Fixed an issue where the Status Summary Report was not updating.
Pending with PRMS, pending to finalize remarks, and pending PRM remarks are now summarized correctly for higher management.

Screen Name: DL Finalization
Corrected color coding behavior after finalization.
Previously, finalized items continued to display as blue (Pending for Finalization – With PRM Remarks).
Now, the color changes to green after finalization, indicating completion to COSM.

Screen Name: DL Booklet Report
Resolved formatting issues in the downloaded DL Booklet.
Merged Columns and Added QC Level and Routine columns to improve clarity.

Screen Name: Work Instruction Release
Fixed an issue where the number of Work Instructions (WIs) released per day was not displayed.
Daily issued WIs are now visible and can be tracked.

Screen Name: Work Instruction
Fixed navigation issue after saving a Work Instruction.
The system now returns to the same page instead of resetting to page 1.

Screen Name: DL Finalization
Fixed an issue where several DLs were not visible in the DL Finalization screen.

Screen Name: Work Instruction
Resolved an issue where multiple DLs (for example, DL No. 00002 to 00016, DL No. 00018, etc.) were not visible in Work Instruction.

Screen Name: Work Instruction
Corrected an issue where Work Centre was not visible for numerous DLs.
Issue occurred due to PRMS not assigning DLs to centers. Manual entries are no longer required.

Screen Name: Work Instruction
Fixed a mismatch between the System Description field and the actual job/job summary.
Mandatory system descriptions now align with job details.


Module Name: Leave
Version Number: V1.14.6
Release Date: 2025-09-09
Overview
This release of leave module enhance and bug fixed across different screen leave entry, covering leave, and leave conversion. 
Screen Name: Leave Entry
Updated the Reason field logic to change dynamically based on the selected leave type in the Leave Apply screen.
Screen Name: Covering Leave
Fixed an issue where the current date (today’s date) was incorrectly enabled in the From Date and To Date fields.Screen Name: Leave Conversion
Leave Conversion:
Added Employee ID and Employee Name columns in the grid when selecting the Leave button.
Screen Name: Leave Conversion
Enhanced validation by displaying the last 30 days of applications in the pop-up.

LTC

Version Number: V1.14.6
Release Date: 2025-09-09

Overview
 The LTC module release introduces improvements to the Advance Proposal and Leave Encashment screens. The update hides unnecessary error messages, adds a designation field, and includes employee details for better clarity and usability.
Bug Fixes and Enhancements
Screen Name: LTC Advance Proposal
The “Bank not found” message is now hidden from the screen.
Screen Name: LTC advance proposal
Added a new field for Designation to improve proposal details.
Screen Name: LTC Leave Encashment
Added Employee ID and Employee Name columns for better visibility in the encashment screen..

Module Name: TY Duty

Version Number: V1.14.6
Release Date: 2025-09-09

Overview
This release of TY Duty module adds the travel_mode_yn field in the Duty Proposal screen to enhance proposal processing.

Screen Name: Ty Duty Proposal
Enhancement
Added the travel_mode_yn field from the Python side to support proposal processing.

LTC

Version Number: V1.14.6
Release Date: 2025-09-09

Screen Name: LTC Leave Encashment
Fixed an issue with employee popup data on the UI side.

Screen Name: LTC Leave Encashment
Updated the DA field as part of screen improvements. 

Module Name: Leave 
Screen Name: Leave Dies Non
Added Leave dies non-designation and center from api side.

Version Number: V1.14.6
Release Date: 2025-09-09


Brething Management (BTMS)

Overview

This release of the BTMS module improves flexibility by making the Crane dropdown non-mandatory and removing location validation in the Movement Plan screen.

Screen Name: Movement Order
Updated the Crane dropdown field to be non-mandatory.

Screen Name: Movement Plan
Movement Plan_validation to and from location remove.


Dry Dock

Version Number: V1.14.6
Release Date: 2025-09-09
Overview

This release of the Dry Dock module enhances scheduling by making the Planned From Date and Planned To Date fields mandatory.

Screen Name: Dry Dock Plan
Made the Planned From Date and Planned To Date fields mandatory


Overview

This release delivers fixes and enhancements to the PAY [Old CPF Recovery] functionality in the SWM module. The updates ensure accurate recovery calculations and automated processing based on date selection, improving reliability for UPS opted employees.

Issues Addressed and Enhancements
Module: SWM

Screen Name: PAY [Old CPF Recovery]

Enhancement: Implemented functionality for recovery of 10% CPF contribution from both Indian employees and Government in respect of UPS opted employees.

Fix: Automated calculation now begins automatically upon date selection.


Financial Management (FMS) (On Hold)
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

This release includes enhancements and fixes to the File Management System (FMS) module. Updates focus on improving file viewer functionality, routing stability, and proposal handling to ensure smoother operations and accurate data visibility.

Issue Addressed and Enhancements

Screen Name: File Viewer
•	Enhancement: New tabs Editor and Routing have been added to the file viewer.
•	Fix: Backend functionality for the newly added tabs is now fully operational.
Screen Name: Routing 
•	Fix: Routes added in a New Proposal are now automatically reflected in Initiate Proposal after a refresh or role change.
•	Fix: Issue where routing was not being saved in a new proposal has been resolved.
Screen Name: New Proposal
Fix: Files uploaded in the File Viewer are now correctly displayed in the viewer.


1.	Leave
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

This release of leave module enhance and bug fixes across different screen leave entry, covering leave, and leave conversion. 

Bug Fixes and Enhancements

Screen Name: Leave Entry
•	Updated the Reason field logic to change dynamically based on the selected leave type drop down in the Leave Apply screen.

Screen Name: Covering Leave
•	Fixed an issue where the current date (today’s date) is enabled in the From Date and To Date fields.

Screen Name: Leave Conversion
•	Added Employee ID and Employee Name columns in the grid when clicking the Select Leave button.
2.	LTC
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

The LTC module release introduces improvements to the Advance Proposal and Leave Encashment screens. The update hides unnecessary error messages, adds a designation field, and includes employee details for better clarity and usability.

Bug Fixes and Enhancements

Screen Name: LTC Advance Proposal
•	The “Bank not found” error message is now hidden from the screen.

Screen Name: LTC Leave Encashment
•	Fixed an issue with employee popup list of employee data on the UI side.

Screen Name: Leave Dies Non
•	Added Leave dies non designation and center from api side.

Screen Name: LTC Leave Encashment
•	Added Employee ID and Employee Name columns for better visibility in the encashment screen.

 
3.	TY Duty
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

This release of TY Duty module adds the travel_mode_yn field in the Duty Proposal screen to enhance proposal processing.

Enhancement

Screen Name: Ty Duty Proposal
•	Added the travel_mode_yn field from the Python side.

4.	Berthing Management (BTMS)
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

This release of the BTMS module improves flexibility by making the Crane dropdown non-mandatory and removing location validation in the Movement Plan screen.

Enhancements

Screen Name: Movement Order
•	Updated the Crane Used dropdown field to be non-mandatory.

Screen Name: Movement Plan
•	Movement Plan screen validation to and from location removed.
•	Users can now view the selected ship’s data in the right-side panel after choosing a ship name from the Ship dropdown list and clicking the    icon.

Screen Name: Movement Status Report
•	Added two columns, Planned Time and Actual Time, to the grid in the Movement Status Report screen.

 
5.	Dry Dock
Version Number: V1.14.5
Release Date: 2025-09-09

Overview

This release of the Dry Dock module enhances scheduling by making the Planned From Date and Planned To Date fields mandatory.

Screen Name: Dry Dock Plan

•	Made the Planned From Date and Planned To Date fields mandatory.



Screen Name: Work Instruction
•	Resolved an issue where multiple DLs were not visible in Work Instruction.

Screen Name: Work Instruction
•	Fixed a mismatch between the System Description field and the actual job/job summary.
Mandatory system descriptions now align with job details.


Refit Planning (RPP)

Version Number: V1.14.6
Release Date: 2025-09-10

This release fixes multiple defects in the RPP – DL Status PRM Wise and 
Work Instruction screens to ensure accurate data display, reliable report exports, and correct system mappings

Bug Fixes

Screen Name: RPP – DL Status PRM Wise
Defect – Incorrect on-screen message

In the DL Status PRM Wise report, when users entered a work order number, the screen displayed “Data not found.” 
The data appeared correctly only after downloading the Excel file. This defect has been fixed

Screen Name: Defect Blank PDF Export
Defect – Blank PDF report
When users downloaded the DL Status PRM Wise report as a PDF file, the report displayed blank details and 
did not fetch any data. This defect has been fixed.

Screen Name: Work Instruction
Defect – Missing DL records
In the Work Instruction screen, several DLs were not visible in ERP (for example, DL No. 00002 to 00016 and DL No. 00018). 
This defect has been fixed.

Screen Name: Work Instruction
Defect – System description mismatch
When issuing work instructions, the System description field was mandatory. 
However, in most cases, the system description did not match the job or job summary. This defect has been fixed.

When the user clicked the Back button, the entered Work Order number remained.
However, the defect list displayed random defects from other Work Orders.
The user had to click Show Data each time to view the correct defects for the selected Work Order.
This defect has been resolved.


VMS

Issue :
Users were unable to extract vendor lists in a structured manner.

Resolution:
A new feature download button has been implemented to allow export of vendor lists category-wise. This enables better data segregation and simplifies reporting.

Enhancement 2: Automatic Category Update on Expiry Date

Issue :
The vendor category was not updating automatically when the vendor’s registration expired.

Resolution:
The system has been updated to ensure that when the Date of Vendor Expiry is updated, the vendor category automatically changes from “B” (Registered but expired) to “A” (Registered).


VMS

Version Number: V1.14.6
Release Date: 2025-09-10

Enhancement

Screen name: Vendor Master
A new download button has been added to the UI to allow users to download data category wise the Excel sheet.

The system has been updated to ensure that when the Date of Vendor Expiry is updated, 
the vendor category automatically changes from “B” to “A”.


Defect List

Overview 
This release adds a Download Template button in the DL Upload screen to simplify defect entry and upload.

Screen Name: DL Upload

Enhancement

Added the downnload template button to download the file and fill the defect details within the file and upload through the upload button. 

Time Keeping (TKS)

Version Number: V1.14.6
Release Date: 2025-09-12


Screen Name: Daily Freeze
Division config new field added and handle this screen validation through that field value..

Screen Name: Assign Key Duty
assign -key Duty validation handled for emp which have been assign will come again between from date and to date.

Screen Name: Amendent Attendance and Punch Screen
Workflow parallel Muster ammendment option not available(in case if missed ounch or machine error.

Screen Name: Amendment Attendance Screen
 industrial and non industrial employees Are shown separately and it should be shown cumulative I.E on single selection.
 
Version Number: V1.14.6
Release Date: 2025-09-12

Overviw
This verison of Time Keeping (TKS) delivers key validation and workflow improvements, streamlining attendance management and enhancing usability across Daily Freeze, Assign Key Duty, and Amendment screens

Enhancements and Fixes
Daily Freeze

Added a new Division Config field.

Screen validation is now handled based on the value of this field.

Assign Key Duty

Improved validation for employees already assigned key duty.

Prevents duplicate assignments within the specified date range.

Amendment Attendance and Punch Screen

The Workflow Parallel Muster Amendment option is now unavailable if a punch is missed or in case of a machine error.

Amendment Attendance Screen

Previously, industrial and non-industrial employees were displayed separately.

Updated to display all employees cumulatively under a single selection.

Screen Name: Work Instruction

Error: Data Mapping / Configuration Error

During issue of Work Instruction Work Centre is not visible for numerous DLS may be due to PRMS have not assigned to centres and missed it, it had manually entered with experience.
 
Screen Name: Status Summary Report

Error: Data Refresh / Reporting Error
 
 Status Summary Report not getting updated due to which how much is pending with PRMS, pending to finalize remarks, pending to PRM remarks not been able summarized to higher management


Overview

This release of the Personnel module enhances the Employee Master by introducing a new dropdown in the Miscellaneous Master for appointment details, recruiter source, and recruitment agency. The update improves data consistency, simplifies record maintenance, and supports better reporting on employee recruitment information.

Personnel

Employee Master

Issue: The Miscellaneous Master did not include dropdown options for appointment, recruiter source, and recruit agency, limiting data capture and consistency.

Resolution: A new dropdown menu has been added in the Miscellaneous Master with fields for:

Appointment

Recruiter Source

Recruit Agency

This ensures standardized selection and improved data accuracy in employee records.


Version Number: V1.14.7
Release Date: 2025-09-14

Fixes and Enhancements
CRF Requested

Issue: Users could create multiple CRF requests (RSD, RED, ESM) before the previous one was approved, and QC Request handling was unclear.
Resolution:

Restricted CRF creation so only one request can exist until it is approved or rejected.

Added a read-only QC Request view with the option to submit a QC Level Change request.

Introduced an Additional Remarks column for users to explain QC Level Change requests.

Implemented a pop-up notification directing users to modify the existing CRF if one is already in progress.

CRF Details/History

Issue: No filtering options were available, and the displayed data was inaccurate.
Resolution:

Added a Status filter to improve data search.

Corrected the data logic to ensure accurate CRF details are displayed.

P1/02 Raise / P1/02 Received

Issue: The Main Center and Work Center fields displayed all values, regardless of department selection.
Resolution: Updated the fields to show only centers relevant to the selected department.

Approve CRF

Issue: Defect numbers were not displayed in the proper format (for example, “4” instead of “0004”).
Resolution: Standardized defect number formatting to include leading zeros.

WI Progress

Issue: Users could not filter Work Instructions effectively.
Resolution: Added Refit and Operational toggles to enable more precise filtering of Work Instructions.

P1/O2 Raise

Issue: The DL Type dropdown incorrectly included invalid sub-parts such as AWRF1, AWRF2, etc.
Resolution: Removed unnecessary sub-parts from the dropdown list

Module Refit Planning (RPP)

Screen Name: DL Assign PRM
System should only show uploaded defects types in "Defect type" drop down

Screen Name: DL Finalization 
In quick update; need hyperlink for PRM remarks to automatically copy the PRM remarks in COSM final remarks allong with additional remarks, EMD, QC Levels..

Required provision " when click on the remarks the same should reflect automatically over the  field of DL Final Remarks.

Screen Name: PRM Remarks
if clicking in center remarks hyperlink in "PRM Remarks" screen the data is only populating Remarks; it should also populate add. remarks, emds, QC Level automatically..


Screen Name: Release Work Instruction
Print option need to be enabled over the screen; Print format should be standard and Reference can be taken from existing screen of "WI Release for the day Center"- Report
1)WI view mode, wi grid transaction dashboard, release wi, release wi transaction dashboard, 
2)SFM CRF, P1/O2-Raise, P1/O2 Recived.

Module Name: Operational Defect (OPDEF)

Overview

This release enhances the OPRA module by improving ship and center selection, adding WI filters and columns, correcting AMP record mapping, and ensuring remarks and work order details are displayed accurately across screens.

Fixes and Enhancements
RA Assign PRM

Issue: Ship selection displayed all ships, including those not in the operational stage.
Resolution: Updated ship selection to display only ships currently in the operational stage.

RA Work Instruction

Issue: Main Center and Work Center dropdowns displayed all centers regardless of the selected department. Center dropdown lacked clear formatting.
Resolution:

Dropdowns now show only centers relevant to the selected department.

Center values are displayed as Center No. – Center Name for clarity.

WI Release for the Day

Issue: Work Instruction (WI) grid lacked a dedicated WI column.
Resolution: Added a WI column to the grid for improved tracking.

RA PRM Remarks

Issue 1: AMP records were incorrectly shown under Normal Work Orders.
Resolution: Corrected mapping so AMP records now appear under AMP Work Orders.

Issue 2: Center remarks did not appear in Quick Update pop-ups, and hyperlinks copied only remarks, excluding additional remarks.
Resolution:

Center remarks now display in Quick Update pop-ups.

Hyperlink function updated to copy both remarks and additional remarks into PRM remarks.

WI Progress

Issue: Users could not filter Work Instructions effectively.
Resolution: Added Refit and Operational toggles to enable filtering.


Module Name: Defect List (DL)

Fixes and Enhancements
Add Defect Lists

Issue: Main equipment data was displayed incorrectly on the screen, leading to inaccurate defect list entries.
Resolution: Corrected the data mapping so that main equipment details now display accurately on the Add Defect Lists screen.


Personnel

Screen Name: Employee Master
Enhancement: Added the Indian nationality in the field of personel information accordaian section. 

Manpower Booking (MPB)

Enhancements

Screen Name: Allocation & OT Booking Again

The Employee Type field now defaults to Industrial and is non-editable. 




Vendor Master

Issue 1: In the Address Details tab, the Address field did not accept certain special characters such as brackets, oblique, and others.

Resolution: The Address field now accepts all special characters as required.

Issue 2: When the Date of Vendor Expiry was updated, the vendor category did not change automatically from “B” to “A.”

Resolution: The system now updates the vendor category from “B” to “A” when the expiry date is modified.


Version Number: V1.14.8
Release Date: 2025-09-16

SWM - TAX 
Screen Name: IT Declaration

Overview

This update ensures that HRA exemption in the IT Declaration screen is displayed accurately as per system calculations, improving data correctness for employees.

Issue: HRA exemption values were not displayed as per calculation.

Resolution: After creating new data, HRA exemption is now appearing correctly based on calculations.

Module: Time Keeping (TKS)

Version Number: V1.14.8
Release Date: 2025-09-16
This release note introduces usability improvements and key bug fixes in the Time Keeping (TKS) module

Enhancements

Screen Name: OT Finalization

Issue: Employees with unsettled time were difficult to identify in the grid.

Resolution: Unsettled time entries now appear at the top of the grid, making it easier for users to review and complete Out Condone actions.

Bug Fixes

Screen Name: Amend Attendance Punches

Issue: Employees marked as Late In in the Time Card report continued to show as late even after transactions were amended.

Resolution: After completing amendments in the Amend Attendance Punches screen, the employee’s status now correctly updates to Present in the Time Card report.

E- Seva 

Version Number: V1.14.8
Release Date: 2025-09-16

Overview

This release introduces improvements in the E-Seva module to enhance data accuracy and usability across multiple screens. Key updates include refining nominee visibility, restructuring employee lists, and improving report ordering and filtering for better user experience.

Enhancements

Module: Board Master

Issue: The Nominees List pop-up displayed employees outside the required scope, making selection inconsistent.

Resolution: The pop-up now shows only active 157 officers and the following civilian officer roles: Foreman (GZ), Foreman, TA, JTO, JDO, SSO, ANSO, TO, AO-I, AO-II, SAO, AO.

Module: Bio Data Master

Issue: The landing page grid displayed employee records without clear prioritization of active and inactive employees.

Resolution: Grid data is now ordered with active employees listed first, followed by inactive employees.

Module: Social List Report

Issue: The employee pop-up list and report outputs did not consistently filter or order employee data, leading to difficulty in analysis.

Resolution:

Added a filter to include only active employees in the employee pop-up list.

Applied ordering by rank level, commission date, promotion date, and date of birth for both grid data and Excel export.



Overview

The SWM module has been enhanced to provide greater flexibility in managing CMP numbers. A new feature has been introduced that allows users to edit details when adding DV (Document Verification) entries to CMP numbers. This ensures improved accuracy and reduces manual correction efforts.

Bug fixes and Enhancement

Screen Name: Add DV to CMP No

Issue: Users were unable to modify DV entries once added to a CMP number, leading to incorrect or duplicate records.

Resolution: An Edit option has been introduced in the Add DV to CMP screen, enabling users to update DV details linked to CMP numbers as required.


Personnel

Version Number: V1.14.8
Release Date: 2025-09-16 

Screen Name: Employee Master

Issue: The field label displayed as Name as per Document.
Resolution: The field label has been updated to Name as per Document (SSC / Matriculation) for greater clarity.

LTC 

Version Number: V1.14.8
Release Date: 2025-09-16

Screen Name: LTC Advance Proposal
Bug Fixes

Issue: When users logged in with a department Manager ID, the system displayed LTC application data for all yard employees instead of restricting it to that department.
Resolution: The system now displays only the LTC application data relevant to the logged-in department.

Module Name: TAACS
Version Number: V1.14.9
Release Date: 2025-09-17

Overview
This release enhances the OT Finalization grid by displaying unsettled time at the top and.
Screen Name: OT Finalization 

Bug Fixes and Enhancement

Employees with unsettled time now appear at the top of the grid. This change helps users easily identify unsettled hours without scrolling.
Users can condone overtime hours if the actual overtime does not exceed the booked overtime.

Screen Name: Amend Attendance

Issue: In the Time Card Report, if an employee was marked late and the attendance record was corrected through the Attendance Punches screen, the status still appeared as late instead of updating to present.

Resolution
The Time Card Report now reflects updated attendance records. When an employee’s late entry is corrected in the Attendance Punches screen, the report displays the status as present

Personnel

Version Number: V1.14.9
Release Date: 2025-09-17

Overview

This release introduces an enhancement to the Annual Increment screen by updating the date field functionality. The field has been converted into a dropdown list to improve usability and reduce manual entry errors.

Bug Fixes

Issue
Previously, the Annual Increment screen used a date field that allowed free-text or calendar input. This design created inconsistencies and errors in data entry when users selected or typed unsupported dates.

Resolution
The date field on the Annual Increment screen has been converted into a dropdown list. The dropdown now contains two fixed values:
1 January
1 July

This change ensures standardized input and reduces the risk of data entry errors.

Leave

Version Number: V1.14.9
Release Date: 2025-09-17

Overview

This release fixes an issue on the Daily Leave Report screen where month-wise delayed leave data for all yard employees was not available.

Bug Fixes

Issue
The Daily Leave Report screen did not provide an option to view month-wise delayed leave for all yard employees, limiting reporting capabilities.

Resolution
Added the functionality to display month-wise delayed leave for all yard employees, ensuring complete and accurate leave reporting. 

Module Name: LTC
Version Number: V1.14.9
Release Date: 2025-09-17

Enhancement
The Pending Actions and Draft View grids now display only the data for the user’s own center. This change improves data security and ensures users access only relevant records

Module Name: Personnel 
Version Number: V1.14.9
Release Date: 2025-09-17

Screen Name: Employee Master

In the Personal Information accordian - Added nationality as Indian.

Issue 
In the Education, the Percentage/CPA field appeared twice, creating confusion.

Resolution
Removed the duplicate entry of the Percentage/CPA field, ensuring it appears only once.

Name as per document as per SCC articulation.

Module Name: Quatering 
 
Version Number: V1.14.9
Release Date: 2025-09-17

Screen Name: Priority Roster

Added from date and To date field in  Priority roaster it is non- mandatory.


This release (version 1.14.9) addresses an issue in the WO Amendment screen where transaction data was not displayed. The fix ensures that all relevant transaction data is now correctly visible to users



Module: SWM Tax
Overview

This release introduces new functionality in the Bonus module of SWM Tax. To improve transparency and reporting, a new Bonus Screen and a Bonus Report Screen have been added. These enhancements provide users with streamlined access to bonus details and reporting capabilities.

Enhancements

Screen Name: Bonus Screen
Resolution: A new Bonus Screen has been added to allow users to record, view, and manage bonus information.

Screen Name: Bonus Report
Resolution: A new Bonus Report Screen has been introduced, enabling users to generate structured reports of bonus data for review and decision-making.

FMS
Overview

This release introduces multiple enhancements and fixes in the File Management System (FMS) to improve usability, enforce access control, and streamline proposal handling and documentation processes. The updates include improvements to the Initiate Proposal, Document Viewer, Transaction Dashboard/Routing, and Sanction screens.

Enhancements and Fixes

Screen Name: Initiate Proposal

Issue Addressed: Enclosure descriptions with annexure numbers were not automatically reflected in the noting.

Resolution: The system now auto-picks the enclosure description along with the annexure number and reflects it in the noting section.

Issue Addressed: Files were editable by users even after submission, creating workflow inconsistencies.

Resolution: Files are now frozen under the user login until the proposal is approved by the BC.

Issue Addressed: No provision to restrict access at the activity level.

Resolution: Activity-level access control has been introduced (e.g., Expense Booking is restricted to MFS only).

Screen Name: Document Viewer

Issue Addressed: Lack of visibility into routing status and impact.

Resolution: Status and impact are now displayed within the routing section of the Document Viewer.

Screen Name: Transaction Dashboard / Routing

Issue Addressed: Users had no quick method to update the file status in routing.

Resolution: A new provision has been added for quick status updates of files from the transaction dashboard/routing screen.

Screen Name: Sanction

Issue Addressed: Print formats were unavailable for sanctioned documents.

Resolution: Print formats are now made available to support record-keeping and compliance needs.


TAACS
Overview

This release delivers usability improvements in the OT Finalization and De-Assign Shift screens of the TAACS module. These changes focus on enhancing data entry consistency and providing flexibility to users by refining field behavior.

Enhancements and Fixes

Screen Name: OT Finalization

Issue: The Reason column was a free-text field, leading to inconsistent data entry.

Resolution: The Reason column has been converted into a dropdown menu, ensuring standardized input and reducing errors.

Screen Name: De-Assign Shift

Issue: The Reason field was mandatory, restricting workflow flexibility.

Resolution: The Reason field has been updated to a non-mandatory field, allowing users to proceed without mandatory input when not required.

LTC

Version Number: V1.14.10
Release Date: 2025-09-18

Overview
This release delivers key enhancements to the LTC Advance Proposal and LTC Claim Application screens

Enhancements
Screen: LTC Advance Proposal

Validation enhancement – The system now prevents users from applying for LTC for the same dates if an application already exists. (Issue type: Enhancement – Business Rule Enforcement)

History feature – A new History button has been added. It displays the details of the last 5 LTC applications in a tabular format. 

Travel mode update – The travel mode field now supports multi-select.

Screen: LTC Claim Application

Designation field added – A new Designation field has been introduced to capture employee designation.


Leave

Version Number: V1.14.10
Release Date: 2025-09-18

This release introduces enhancements and fixes in the Leave Entry screen to improve leave calculation accuracy and maintain consistency in EL (Earned Leave) balances across different modules.

Bug Fixes

Screen: Leave Entry

Casual leave calculation fix – Casual leave no longer counts Saturday/Sunday when they fall between leave dates.

Bug Fix – Calculation Error

EL balance consistency fix – Resolved mismatch between Leave Registration EL balance and LTC Encashment EL balance.

Bug Fix – Data Consistency

Quartering 

Version Number: V1.14.10
Release Date: 2025-09-18

Overview
This release introduces refinements in the Priority Roaster screen to simplify employee data presentation and improve clarity in employee records.

Bug Fixes and Enhancement

Screen: Priority Roaster

Address column removed – The address column has been eliminated from employee master.

Issue type: Enhancement – UI Simplification

Field label update – The “Date of Relieving” field in Employee Master has been renamed to Retirement Date for better clarity.

Issue type: Enhancement – Terminology Improvement


OPRA 

Version Number: V1.14.10
Release Date: 2025-09-18

Overview
This release introduces updates to the RA Work Instruction and RA-DL Assign PRM screens to improve usability and ensure consistent terminology across the application.

Bug Fixes

Screen: RA Work Instruction

Default date setting – The PSD field now defaults to the current date.

Issue type: Enhancement – Usability Improvement

Screen: RA-DL Assign PRM

Label correction – In both Quick and Update modes, the label “COSM” has been replaced with MPC wherever it appears.

Issue type: Enhancement – Terminology Standardization

QCMS

Version Number: V1.14.10
Release Date: 2025-09-18

Bug Fixes

Screen: QC Level

Toggle button fix – Resolved an issue where the Refit and Operational toggle buttons were not working, and grid data was not loading as expected.

Issue type: Bug Fix – Functional Error

Shop Floor Managment (SFM)

This release enhances the CRF Request screen by providing visibility into Work Instruction (WI) details and enabling flexible print options.

Version Number: V1.14.10
Release Date: 2025-09-18

Enhancement
Screen: CRF Request

WI details provision – Users can now view Work Instruction details from the CRF Request screen.

Issue type: Enhancement – Feature Addition

Print functionality – Added the ability to print either a single WI or multiple WIs simultaneously.

Issue type: Enhancement – Usability Improvement

Operational Defect (OPDEF)


Version Number: V1.14.10
Release Date: 2025-09-18

Overview
This release introduces enhancements to the OPDEF PRM Remarks screen, improving usability and providing additional data visibility.

Enhancments
Screen: OPDEF PRM Remarks

Quick Update pop-up – A new Quick Update pop-up has been added to screen.

Issue type: Enhancement – Usability Improvement

Additional columns – EMD and QC Level columns have been added to the Center Remarks grid in both Quick Mode and Detailed Mode.

Issue type: Enhancement – Data Visibility

e-Seva

Overview
This release introduces an enhancement in the Board Master screen to improve the ordering of the Nominees List for better readability and logical arrangement.

Version Number: V1.14.10
Release Date: 2025-09-18

This release introduces an enhancement in the Board Master screen to improve the ordering of the Nominees List for better readability and logical arrangement.

Screen Name: Board Master
Nominees List ordering – Modified the Nominees List so that employees without a rank (created through Bio Data Master) are displayed last.
Issue type: Enhancement – Data Arrangement/Usability

Enhancements and Fixes

Screen Name: Initiate Proposal

Issue Addressed: Enclosure descriptions with annexure numbers were not automatically reflected in the noting.

Resolution: Auto-pick functionality for enclosure description with annexure number has been enabled.

Screen Name: Initiate Proposal

Issue Addressed: Proposal files could still be accessed in draft mode and edited by the creator after submission.

Resolution: Files are now frozen in the user login once submitted, until approval by the Budget Center . Post approval, the file is available only in view mode, eliminating edit provision in draft.

Screen Name: Document Viewer

Issue Addressed: Limited visibility of status and impact in routing.

Resolution: Provision has been added to display status and impact directly in the document viewer, improving transparency in routing.

Screen Name: Initiate Proposal

Issue Addressed: Lack of activity-level access restriction (e.g., expense booking should be restricted).

Resolution: Access limiting at the activity level has been implemented. For example, expense booking is now restricted to MFS only.

Screen Name: Transaction Dashboard / Routing

Issue Addressed: No quick mechanism to update the status of files from the dashboard.

Resolution: A new provision has been introduced to allow quick status updates of files directly from the transaction dashboard.

Screen Name: Sanction

Issue Addressed: Absence of standardized sanction letter print formats.

Resolution: Print formats for sanction letters have been developed and made available for use.

TAACS

Screen Name: OT Compare


DevTeamStatus
DevTeamStatus

100%
10
C3




TAACS

Version Number: V1.14.11
Release Date: 2025-09-19

Screen Name: OT Compare
 
Issue: In the report, the Actual OT column displayed data as 00, the Final OT column appeared blank, and the employee pop-up displayed data from all centers.

Resolution: Corrected the report to display accurate values in the Actual OT and Final OT columns, and limited the employee pop-up to show data only for the relevant center.
 
LTC

Version Number: V1.14.11
Release Date: 2025-09-19

Bug Fixes and Enhancement

Screen: MRO

Issue: When the GO button was selected without entering an employee ID and application ID, the system automatically fetched the employee name and LTC type.

Resolution: Updated the validation logic so that employee details and LTC type are fetched only when valid employee ID and application ID are provided.

Screen: LTC Advance Proposal

Implemented a special approval level flow for the LTC Advance Proposal screen to streamline approval processing.


 
e-Seva
 
Screen Name: Board Master
 
1. Nominee List - Leave/TY Duty Details Pop up issue- not open in update mode



Version Number: V1.14.11
Release Date: 2025-09-20

Overview
This release addresses issues with employee type filtering on the Allocation of Manpower Booking and Overtime Booking Non - Industrial screens
Fixes

Screen: Allocation of Manpower Booking / Overtime Booking Non - Industrial

Issue: When selecting Industrial or Non-Industrial employee types from the drop-down, both employee lists were not displayed only the displaying only industrial record.

Issue: On the Overtime Booking non industrial screen, when selecting non Industrial or Ministerial employee types, both employee lists were not displayed only the displaying non- industrialrecord.

Resolution: The filtering logic has been corrected. Now, displays the records corresponding to the selected both employee type appear in screens.

Version Number: V1.14.12
Release Date: 2025-09-20


e-Seva

Version Number: V1.14.12
Release Date: 2025-09-22

Overview
This release addresses the fixes to board master screen.

Screen Name: Board Master

Issue: In update mode of board master, if the non-mandatory field Authority Letter Date was left unselected, the system displayed a default date of 01-01-1970.

Resolution: The default date behavior has been corrected. The field now remains blank if no date is selected.


Personnel

Version Number: V1.14.12
Release Date: 2025-09-22
Overview
This release introduces a minor enhancement to the Employee Master screen.

Enhancement

Screen Name: Employee Master 
Issue: In the Appointment Details accordion, the field label was displayed as “Recruit Agency,”.
Update: In the Appointment Details accordion, the field label “Recruit Agency” has been updated to “Recruit Against.

LTC

Version Number: V1.14.12
Release Date: 2025-09-22
Overview
This release addresses enhancement and bug fixes accross MRO LTC and LTC advance proposal screen.

Enhancements and Bug Fixes

Screen Name: MRO LTC
Issue: On the MRP LTC Screen there is note. 
Resolution: Removed the note from MRO LTC screen.

Screen Name: LTC Advance Proposal Screen
Issue: When the LTC is selected for self and family the checkboxes for selected family member are not getting checked automatically.
Resolution: When the LTC is selected for self and family the checkboxes for selected family member are getting checked automatically.


RMM (Refit Monitoring Module)
Overview

This release delivers enhancements to the Refit Plan screen, addressing milestone visibility and export functionality. These improvements ensure better project tracking, visualization, and compatibility with external tools such as MS Project.

Fixes and Enhancements

Screen Name: Refit Plan

Issue 1 – Milestone and Summary Task Differentiation

There was no provision to indicate project milestones (e.g., DSD, DCD).

Milestones were being shown as regular tasks, instead of being represented by a unique icon (such as a rhombus in MS Project).

Summary tasks, which aggregate multiple subtasks, were also being displayed as normal tasks.

This caused difficulty in distinguishing between milestones, summary tasks, and regular tasks on the Gantt chart.

Resolution:

A new MILESTONE value has been introduced in the Type of Work Package dropdown.

Selecting this value now ensures milestones are displayed with a distinct symbol, clearly differentiating them from tasks and summary tasks.

Issue 2 – Export Functionality

Users requested the ability to export refit plan data for use in external tools such as MS Project.

While start and end dates are exporting correctly into XML format, the exported file has not been validated in MS Project due to the absence of an active subscription.

Resolution:

Export functionality has been provisioned for the Refit Plan screen.

Start and end dates are correctly included in the XML output.

Limitation: Validation on MS Project is pending and requires testing on an available licensed system (e.g., NUD MS Project).


Quartering 

Version Number: V1.14.12
Release Date: 2025-09-22

Overview
This release introduces an enhancement to the New Quarter Application.

Enhancement

Screen Name: New Quarter Application
Added an Employee Name field to the Pending grid in the New Quarter Application.

LTC 

Version Number: V1.14.12
Release Date: 2025-09-22

Screen Name: LTC Advance Proposal 
Enhancement

Screen Name: LTC Claim Application
Resolved an issue where Designation was not displayed in Update and View modes.

Personnel

Version Number: V1.14.12
Release Date: 2025-09-22

Screen: Employee Master

Added State selection through the Division Master.

Set India as the default country in the address field.

SWM - PAY

This release introduces key enhancements to the SWM module. A new HRA Court Details screen has been added for better case management and reporting. Improvements have been made to the IT Declaration upload functionality for smoother processing. Additionally, the Payment to Bank screen has been updated to support non-SBI bank details and includes a new Employee Status column for improved clarity.
Screen Name: HRA Court Details

Issue:
A new HRA Court Details screen has been added to allow users to record case information, export details to Excel, and manage related data.

Resolution:
The screen has been successfully implemented with features to input, view, and export HRA court details for effective tracking and reporting.

SWM - TAX

Screen Name: IT Declaration

Issue:
Enhancements were required in the single-file upload functionality to improve usability and ensure smoother processing of IT declaration submissions.

Resolution:
The single-file upload feature has been enhanced with additional functionality, enabling users to manage IT declaration uploads more efficiently.

SWM - NEFT

Screen Name: Payment to Bank

Issue:

In the Format column, if "Other" is selected, all bank details (except SBI) were not reflecting in the grid.

A new requirement was identified to add a column named Emp Status with values: Active and Inactive.

Resolution:

The system now correctly reflects all non-SBI bank details in the grid when "Other" is selected in the Format column.

A new Emp Status column has been added to display employee status as Active or Inactive.

OPDEF 

Version Number: V1.14.12
Release Date: 2025-09-22

Overview

This release enhances the OPDEF PRM Remarks screen by improving data handling and assignment features across Quick Mode and Detailed Mode.

Enhancements

Screen: OPDEF PRM Remarks

Issue 1: Data from the grid was not automatically copied into the PRM Remarks, Additional PRM Remarks, and Proposed EMD QC Level fields when selecting a center.
Resolution: Clicking the Center Name hyperlink now copies the corresponding data into these fields.

Issue 2: Users were unable to assign a center from both Quick Mode and Detailed Mode.
Resolution: Center assignment is now supported in both Quick Mode and Detailed Mode.

Issue 3: In Detailed Mode, data from the Assign Center Name hyperlink was not copied into the assigned PRM grid.
Resolution: Clicking the Assign Center Name hyperlink now correctly copies the data into the assigned PRM grid.


QCMS or (SFM)

Version Number: V1.14.12
Release Date: 2025-09-22

Overview

This update streamlines the DL Type dropdown by removing unnecessary subparts for AWRF.

Fix

Screen: P1/O2 Raise

Issue: The DL Type dropdown contained subparts for AWRF (such as AWRF1, AWRF2, etc.), which were not required.

Resolution: Removed the AWRF subparts options from the DL Type dropdown.

RPP

Version Number: V1.14.12
Release Date: 2025-09-22

Overview

This release enhances the Work Instruction screen to correctly reflect transactions from the DL-Finalisation screen based on PRM Remarks and DL Final Status conditions.

Enhancements

Screen: Work Instruction

Issue 1: Transactions with E&R set as PRM Remark and DL Final Status = Tentative did not appear in the Work Instruction screen.
Resolution: These transactions now reflect correctly in the Work Instruction screen.

Issue 2: Transactions with E&R set as PRM Remark and DL Final Status = Finalised were not displayed.
Resolution: Both the transaction and associated defect transaction now appear in the Work Instruction screen.

Issue 3: Transactions with PRM Remarks other than E&R and DL Final Status = Not Verified were incorrectly appearing.
Resolution: These transactions are now excluded from the Work Instruction screen.

Issue 4: Transactions with PRM Remarks other than E&R and DL Final Status = Not Verified were incorrectly displayed in the Work Instruction screen.
Resolution: These transactions are now excluded from the Work Instruction screen.

Issue 5: Transactions with PRM Remark DO and DL Final Status = Tentative were incorrectly appearing.
Resolution: These transactions are now excluded from the Work Instruction screen.

Issue 6: Transactions with PRM Remark E&R and DL Final Status = Not Verified were incorrectly appearing.
Resolution: These transactions are now excluded from the Work Instruction screen.



QCMS

Version Number: V1.14.12
Release Date: 2025-09-22

Screen: QC Level

Issue: On the landing page, only half of the data was visible.
Resolution: The screen now displays data in full-screen view.

Issue: The QC DL Type filter was not working; unrelated DL Types were displayed.
Resolution: The filter now displays only relevant DL Types.

Issue: When clicking the Operation/OpDef toggle, the Work Order field did not default to Normal Work Order.
Resolution: The Work Order field now defaults to Normal Work Order.

Issue: Clicking the X button on any filter did not remove the filter or refresh the data.
Resolution: The selected filter is now removed, and all data is displayed.

Issue: QC Level selected for a work instruction was not reflected in the next work instruction for the same defect.
Resolution: The selected QC Level now automatically carries over to the next work instruction for the same defect until manually changed by the user.

Screen: QC Level History
Note: Report data functionality is working as expected; no changes in this release

LTC 

Version Number: V1.14.13
Release Date: 2025-09-23

Overview
This release addresses a display issue in the LTC Advance Proposal screen.

Enhancement and Bug Fixes 

Screen Name: LTC Advance Proposal

Issue: The Extension Year field was not displayed in the Block Year section.

Resolution: Updated the screen to ensure the Extension Year field is now visible in the Block Year section.

Screen Name: LTC Advance CDA Approval

Issue 1: The Pending Action tab in the transaction dashboard grid is not reflecting any data.

Resolution: Fixed the dashboard to ensure that pending actions now display correctly in the grid. 
 
Issue 2: When no value was entered and saved, the system did not display an error message for required fields.

Resolution: Added validation to ensure that an error message appears when required fields are left blank.

Issue 3:  The Save function was not working.

Resolution: Corrected the functionality so that data can now be saved successfully.


Personnel

Version Number: V1.14.13
Release Date: 2025-09-23

Overview
This release introduces fixes and enhancements in the Employee Master screen.

Bug Fixes and Enhancement

Screen Name: Employee Master

Issue 1: Issues occurred while creating and editing employee nomination details.

Resolution: Fixed the functionality so that employee nomination details can now be created and edited without errors.

Issue 2: In the employee nomination section, only Relation was available. There was no option to capture Age or guardian details.

Resolution: Added an Age field beside Relation. If the entered age is less than 18, a new text field for Guardian is displayed

Manpower Booking (MPB)

Version Number: V1.14.13
Release Date: 2025-09-23

Overview

This release addresses issues related to employee allocation, freeze-center values, and overtime booking in the Manpower Booking module.

Bug Fixes

Screen Name: Allocation

Issue: When selecting and allocating 4 out of 30 employees, and then selecting another 4 and saving again, the system showed 8/30 allocated but duplicated the employees from the first batch.

Resolution: Updated the allocation logic to prevent duplicate entries. Employees are now allocated only once.

Screen Name: Monthly & Weekly Freeze

Issue: In the Monthly Freeze and Weekly Freeze centers, the system displayed the number 13 instead of (021) MIS.

Resolution: Corrected the display value so that (021) MIS now appears as intended.

Screen Name: Unfreeze, Allocation, Overtime Booking (Industrial and Non-Industrial)

Issue: After performing an unfreeze, manpower allocation worked correctly, but overtime booking (Industrial and Non-Industrial) did not function.

Resolution: Fixed the issue to ensure that overtime booking for both Industrial and Non-Industrial categories works properly after unfreezing.


Financial Management (FMS)
Overview

This release includes improvements and bug fixes in the File Viewer, Routing Form – File Viewer, and Enclosures screens. The updates focus on optimizing screen utilization, enhancing enclosure management, and fixing non-functional controls to improve overall usability and workflow efficiency.

Enhancements

Screen Name: File Viewer

Issue: Removed “Clear Selection” buttons (Select All and 1A, 2A) from the header.

Resolution: The redundant buttons have been removed to avoid user confusion and streamline selection functionality.

Screen Name: File Viewer

Issue: Screen utilization improvements – the remarks field was conflicting with the upload button position.

Resolution: The screen layout has been optimized by adjusting the position of the upload button and remarks field for better usability.

Screen Name: Enclosures

Issue: Enclosure name and remarks were missing from the activity-level enclosure list.

Resolution: The enclosure list has been updated to include enclosure names and remarks for better traceability.

Bug Fix
Screen Name: Routing Form – File Viewer

Issue: Add button in the Routing tab was not working.

Resolution: The button functionality has been restored. Users can now add routing entries without errors.

Request Assistance (RA)

Version Number: V1.14.13
Release Date: 2025-09-23


Screen Name: MPC View Remarks

1. In Defect List header filter: instead of defect type it is showing defect description.
2. In defect no. grid system is howing WO No.
3. MPC Remarks column should reflect remarks ("Remarks"- "Additional Remarks")
4. Unit Remarks column should reflect remarks ("Remarks"- (Additional Remarks").
5. Filter for Equipment in Grid is not filtering the data if we type last words from the sentence.
6. Showing Duplicate Enteris in the Grid.
7. System is showing data in only half of the screen even if we increaese the pagination.
8. Add OPRA Column In the Grid.
9. Add Defect No.  Column in the Grid.
10. Hide Sub Column from the grid.



Request Assistance (RA)

Version Number: V1.14.13
Release Date: 2025-09-23

Overview
This release fixes multiple grid and filter issues in MPC View Remarks and adds new columns for improved data visibility.

Screen Name: MPC View Remarks

Bug Fixes and Enhancement

1. Defect List header filter

   Issue: The header filter displayed defect descriptions instead of defect types.

   Resolution: Updated the filter to correctly display defect types.

2. Defect No. grid mapping

   Issue: The system displayed the Work Order (WO) number instead of the defect number in the Defect No. grid.

   Resolution: Corrected the mapping to display the defect number

3. MPC Remarks column
   
   Issue: The MPC Remarks column did not reflect both “Remarks” and “Additional Remarks.”

   Resolution: Modified the column to display both fields as intended.
   
4. Unit Remarks column

   Issue: The unit remark column did not reflect “Remarks” and “Additional Remarks.”

   Resolution: Updated the column to display both remark types.
   
5. Equipment filter in grid

   Issue: Filtering did not work if users typed the last word of the sentence.

   Resolution: Enhanced the filter to support partial and end-of-string searches.
   
6. Duplicate entries in grid

   Issue: Duplicate entries appeared in the grid.

   Resolution: Fixed the logic to prevent duplicate records.
   
7. Grid pagination display

   Issue: Data was shown in only half of the screen even after increasing pagination.

   Resolution: Corrected the display so the grid fully expands with pagination changes.
   
8. OPRA column addition

   Added an OPRA column to the grid.
   
9. Defect No. column addition

   Added a dedicated Defect No. column.
   
10. Sub column visibility

   Issue: The Sub column was visible in the grid.

   Resolution: Hide/Removed the Sub column from the grid.
   
   
LTC
   
Version Number: V1.14.14
Release Date: 2025-09-24

Overview
This release includes a bug fix to ensure the DA field calculation in the LTC Leave Encashment screen

Screen Name: LTC Leave Encashment

Issue: The DA field was not set with logic as * da% it showing value in percentage.

Resolution: The DA field logic has been corrected to calculate values as Basic Pay × DA%.


Personnel

Version Number: V1.14.14
Release Date: 2025-09-24


Screen Name: Annual Increment 
1. Provision should be provided to dealing clerk to add new Employee.
2. Dates are not showing like Last Increment, Due Increment & Date of next Increment.
3. Sub group should be added beside qualification.
4. In grid , add + button, so that the employee could be selected manually.
5. Center is showing blank, but department is already freezed.

Screen Name: Employee Master
1. Center is showing blank, but department is already freezed.
2. Nationality should freeze as Indian.

TY Duty

Version Number: V1.14.14
Release Date: 2025-09-24

Overview
This release addresses a data display issue in the TY Duty Proposal screen to ensure consistency across update and view modes.

Screen Name: TY Duty Proposal

Issue:
Data was not displaying in update and view modes.

Resolution:
The issue has been fixed. Data now reflects in both update and view modes.

Leave

Version Number: V1.14.14
Release Date: 2025-09-24

Screen Name: Leave Encashment Cancellation 
Developed new screen as per new requirement.

MPB/TKS

Version Number: V1.14.14
Release Date: 2025-09-24

Overview
This release addresses multiple bug fixes in the MPB/TKS modules to improve data visibility, validation, and sorting functionality.

Bug Fixes

Screen Name: MPB and TKS all Transaction Screen

Issue: Transaction data for all saved was missing and not visible in view/edit mode.

Resolution: The issue has been fixed. Transaction data now displays correctly in view/edit mode.

Screen Name: Monthly and Weekly

Issue: When freezing directly, Draft, Pending, and View states were not in use, and the Save button remained enabled. (Doubt)

Resolution: The issue has been fixed. Draft, Pending, and View states are no longer in use after freezing, and the Save button is disabled.

Screen Name: All Transaction Dashboard

Issue: Date sorting functionality was not working for MPB-related transactions.

Resolution: The issue has been resolved. Date sorting now works for all relevant MPB transactions.

Time Keeping (TKS)

Version Number: V1.14.14
Release Date: 2025-09-24

Overview 

This release ensures that attendance punches cannot be saved without an Employee ID, improving data accuracy and validation.

Screen Name: Amend Attendance Punches 

Issue: Employee ID was not manadatory field; while saving the transaction data error was displaying.
Resolution: Added Employee Id mandatory while saving the transaction now data is possible to save. 




Refit Planning (RPP)

Version Number: V1.14.15
Release Date: 2025-09-25

Overview
This release fixes issues in the WI amendment screen and DL finalization.

Screen Name: WI Ammendment
Issue: When user entered a last two digit number of defect number in the gird filter, no data was displayed.
Resolution: The issue has been fixed. User can now view defect related data when filtering with last two digit defect number. 

Screen Name: DL Finalization 
Issue: The data in PRM Remark and Final COSM column remark grid was not being retrieved.
Resolution: The issue has been fixed. The system now displays the fectched data in the PRM remark and Final COSM remark column grid. 

Personnel 

Overview

This release includes enhancements to the Employee Master screen to improve data consistency and usability.

Enhancements

Screen Name: Employee Master

In the Address accordion, the Country field is now set to India by default.

A Sub Group field has been added next to the Qualification.

The Nationality field is now fixed as Indian.

Leave

Version Number: V1.14.15
Release Date: 2025-09-25

Overview

This release introduces an enhancement to the Leave Balance Amendment screen.

Enhancements

Screen Name: Leave Balance Amendment

A Transaction Number field has been added to the screen.


Screen Name: Apply Leave

Issue: Leave data was not reflecting in Edit and View modes.

Resolution: This issue has been fixed. Leave data now displays correctly in both Edit and View modes.

LTC 

Version Number: V1.14.15
Release Date: 2025-09-25

Overview

This release includes an enhancement to the LTC Advance Proposal screen.

Enhancements

Screen Name: LTC Advance Proposal

The mandatory symbol has been removed from the Type of Request field.

Manpower Booking (MPB)


Overview

This release resolves multiple issues across Manpower Booking screens, including overtime booking, attendance reporting, and alignment corrections.

Enhancements

Screen Name: Unfreeze

Resolution: The alignment on the screen has been corrected.

Bug Fixes

Screen Name: Overtime Booking Non-Industrial

Issue: In Edit mode, an error occurred when saving data.

Resolution: The issue has been fixed. Data can now be saved successfully in Edit mode.

Screen Name: Overtime Booking Industrial

Issue: The page was automatically refreshing when attempting to change OT hours, preventing updates.

Resolution: The refresh issue has been resolved. Users can now update OT hours without interruption.

Issue: In Industrial Overtime Booking, when 2 hours of overtime were booked on 26-04-25 for employee 21099 (quarterly balance: 108, weekly balance: 18), the balances should have reduced accordingly. However, when checking the same employee’s balances for an earlier date (21-04-25), the reduction was not reflected (Quarterly: 106, Weekly: 16).

Resolution: The calculation logic has been corrected. Quarterly and weekly balances now update consistently across all dates.

Issue: An message was displayed in the OT Booking after clicking Show button.

Resolution: The message display has been corrected. The Show button now functions properly.

Screen Name: Attendance Detail Report

Issue: In the Excel Attendance Details Report, punch-in and punch-out times were displayed in date-time format instead of hours and minutes.

Resolution: The report format has been fixed. Punch-in and punch-out times are now displayed in hours and minutes.

Screen Name: OT Industrial and Non-Industrial OT Booking Report

Issue: After booking an employee’s overtime and verifying the entry in the OT Booking Report, when the same record was amended for the same employee and date through the sub-transaction amend process, the report did not display the updated (amended) information.

Resolution: The reporting logic has been fixed. Amended overtime booking records are now displayed correctly in the OT Booking Report.

Screen Name: Non-Industrial

Issue: If an employee’s overtime had already been booked under the Non-Industrial category, the same employee still appeared for booking on the same date.

Resolution: The booking validation has been corrected. Employees with existing overtime bookings no longer appear again for the same date

Time Keeping (TKS)

Version Number: V1.14.15
Release Date: 2025-09-25

Overview

This release resolves issues related to missing holiday data in shift assignments and attendance details reporting.

Bug Fixes

Screen Name: Assign Shift

Issue: Holiday List data was missing when assigning shifts.

Resolution: The issue has been fixed. Holiday List data is now displayed correctly during shift assignment.

Screen Name: Attendance Details

Issue: In the Attendance Details report, punch-in and punch-out data was shown even when an employee was absent.

Resolution: The issue has been fixed. Punch-in and punch-out data is no longer displayed for absent employees 


FMS

Version: V1.14.15
Release Date: 2025-09-25

Overview

This release introduces a business logic update in the FMS module. The change ensures proposal initiation aligns with IFA approval rules based on the estimated amount threshold.

Module: Financial Management System (FMS)
Screen: Initiate Proposal

Category: Enhancement

Issue: The proposal initiation process did not differentiate accordance requirements based on the estimated amount.

Resolution: Business logic updated:

If the estimated amount is ≥ 400,000, the proposal will be fetched with accordance of IFA role.

If the estimated amount is < 400,000, the proposal will be fetched without accordance of IFA role.



OPRA

Version: V1.14.15
Release Date: 2025-09-25

Overview

This release includes corrections and adjustments to the RA Assign Prm and RA PRM Remarks screens. The updates address mislabeled fields and improve the accuracy of displayed information.

Screen: RA Assign Prm
Issue: The grid displayed a column for Ship Remarks in the grid should have FMU Remarks.
Resolution: Replaced the Ship Remarks column with the FMU Remarks column.

Issue: The Defect Class field amendment to reflect Branch/Section categories (example., H, E, L&W).
Resolution: Updated the Defect Class field to display the correct Branch/Section values (example., H, E, L&W).

Screen: RA PRM Remarks

Issue: The field for AA/Command Remarks was not required.
Resolution: Removed the AA/Command Remarks field from the screen.


OPRA 

Version: V1.14.16
Release Date: 2025-09-26


Overview
This release resolves issues related to status updates and FMU remarks in the RA-RA FMU Remarks screen.

Bug Fixes
Screen: RA-RA FMU Remarks

Issue: The selected Pending status or other statuses were not reflected.
Resolution: Fixed the issue Pending and other selected statuses now display correctly.

Issue: When users entered remarks in the Quick Update screen, the DL status did not move to Assigned.
Resolution: Fixed the issue updated remarks in the Quick Update screen now correctly change the DL status to Assigned.

Issue: In the detailed view, selected FMU remarks displayed as Remarks UID and Remarks Name.
Resolution: Fixed the issue  FMU remarks now display correctly in the detailed view.

Issue: In the detailed view, users could not identify which OPRA number was opened.
Resolution: Fixed the issue so that the OPRA number is now visible in the detailed view. 

Enhancement
Screen: RA-Assign Prm

Added ALL, NOR, AMP, SMP, and DD options in the OPS RA Type drop-down field

LTC

Version: V1.14.16
Release Date: 2025-09-26

Overview
This release resolves an issue in the LTC Advance Proposal screen.

Screen Name: LTC Advance Proposal
Issue: When users selected the block year as 2022–2025 and the entitled block year as 2024–2025, the year of visit did not update correctly.
Resolution: Fixed the issue so that the year of visit now defaults to 2025 in this scenario.

Manpower Booking (MPB)

Version: V1.14.16
Release Date: 2025-09-26

Screen Name: Amend OT Booking

Issue: While amending OT bookings against a Work Item (WI), users were unable to increase OT hours. The system displayed errors such as:

"Maximum 1 OT hour is allowed" when attempting to change a 2-hour booking to 4 hours.

"Maximum 2 OT hours are allowed" when changing a 2-hour booking to 3 hours.
Issue: While amending OT bookings against a Work Item (WI), users were unable to increase OT hours. The system displayed errors such as:

"Maximum 1 OT hour is allowed" when attempting to change a 2-hour booking to 4 hours.

"Maximum 2 OT hours are allowed" when changing a 2-hour booking to 3 hours.

The error for OT is 4 hours showing as maximum hours.

Resolution: The issue has been fixed, and the error messages for 4 hours no longer appear on the screen.


Screen: OT – Report

Issue: Booked OT hours were not displaying for non-industrial and non-production departments (Industrial, Non-Industrial, Ministerial).
Resolution: Fixed the issue so that booked OT hours now display correctly for these departments.

Screen: Allocation of Manpower

Issue: The actual count of absentees was mismatched in the allocation of manpower.
Resolution: Fixed the issue so that the absentee count now displays accurately.





Version: V1.14.16
Release Date: 2025-09-26

Overview

This release introduces fixes and enhancements to the Transaction Dashboard tiles in the Financial Management System (FMS). The updates ensure that proposal tracking and approval statuses are accurately reflected on the dashboard for better visibility and monitoring.

Module: Financial Management (FMS)
Screen: Transaction Dashboard Tiles

Bug Fix

Issue: Tile data for “Number of cases where new proposals were created and not approved by the Budget Center” was not displaying correctly.

Resolution: Corrected backend logic to ensure the tile reflects accurate counts.

Enhancement

Issue: A tile for “Number of cases where the stage is not ‘AIP’ yet” was missing.

Resolution: Added a new tile to display all proposals not marked as AIP.


Issue: OPRA number should be by default.
Resolution: 

Retriement

Version: V1.14.16
Release Date: 2025-09-26

Enhancement

Screen Name: Data sheet
Resolution: Removed the handicapped child details and added family member details by fetching information from the Employee Master

Leave 

Version: V1.14.17
Release Date: 2025-09-29


Overview

This release introduces enhancements and fixes in the Leave Module. Updates include improvements to the transaction dashboard, leave conversion process, and leave application workflow.

Bug Fixes and Enhancement

The transaction dashboard now displays all transactions according to the logged-in user’s location.

2. Leave Conversion Screen

Added last 30 days of data to the Leave Conversion screen.

Included Employee ID and Employee Name in the Apply Leave button for better visibility.

3. Apply Leave Screen

Issue: Leave balances were not consistently updated when a request was saved as draft, forwarded, or approved. Additionally, cancellation was possible outside the Leave Cancellation process.
Resolution:

Leave balances now deduct correctly, regardless of whether a request is saved as draft, forwarded, or approved.

Leave cancellation can only be performed through the Leave Cancellation Transaction screen, ensuring proper control and consistency.


LTC

Version: V1.14.17
Release Date: 2025-09-29

This release includes enhancements to the LTC Advance Proposal and LTC Claim Application screens. The updates improve usability by guiding users in travel selections and providing additional functionality through new action buttons.

Issues and Resolutions
1. LTC Advance Proposal

Issue: Users could select an LTC option without first selecting a travel mode, leading to incorrect or inconsistent data entry.
Resolution: The process has been updated to enforce sequence:

Users must first select a travel mode.

Only if Train is selected as the travel mode, the LTC by which travel is proposed field becomes active.

For all other travel modes, the field remains inactive.

2. LTC Claim Application 

Issue: Users had no direct way to include extended leave in the claim process.
Resolution: An Extended Leave button has been added to the LTC Claim Application screen, enabling users to manage extended leave within the claim workflow.

3. LTC Advance Proposal

Issue: The LTC Advance Proposal screen lacked quick access to past proposals.
Resolution: A History button has been added, allowing users to easily view previous LTC advance proposals.


Refit Planning (RPP)

Version: V1.14.17
Release Date: 2025-09-29

Overview

This release addresses usability issues in the Work Order screen and fixes a filter problem in the COSM Remarks Report. The updates ensure accurate dropdown data, streamlined date handling, and functional reporting filters.

Issues and Resolutions
1. Work Order – COSM Dropdown

Issue: The COSM dropdown was displaying all department lists instead of only the valid COSM data.
Resolution: The COSM dropdown has been corrected to display only COSM records.

2. Work Order – Likely Start and Completion Dates

Issue: The Likely to Start Date and Likely to Complete Date fields were mandatory and required manual entry.
Resolution:

These fields are no longer mandatory.

By default, they are auto-filled with the DSD and DCD dates, with an option for users to edit them if needed.

3. COSM Remarks Report – Header Filter

Issue: The COSM Remark header filter was not functioning.
Resolution: The header filter has been fixed and now works as expected.

Manpower Booking (MPB)

Version: V1.14.17
Release Date: 2025-09-29

Overview

This release improves name display consistency across multiple reports and fixes issues in the OT Booking Against WI screen to ensure correct retention of selected data during allocation.

Issues and Resolutions
1. OT Booking Report – Name Column

Issue: Only the employee’s first name was displayed in the Name column.
Resolution: The full name of the employee is now displayed.

2. Allocation Report – Name Column

Issue: Only the employee’s first name was displayed in the Name column.
Resolution: The full name of the employee is now displayed.

3. Allocation of Manpower – Name Column

Issue: Only the employee’s first name was displayed in the Name column.
Resolution: The full name of the employee is now displayed.

4. OT Booking Against WI – Date and WI Selection

Issue: After selecting employees and saving, the page refreshed successfully, but the chosen Date and Work Instruction (WI) values changed unexpectedly.
Resolution: The selected Date and WI now remain unchanged until all employees are allocated for the day.



Screen Name: Work Order
The COSM drop down field should only reflect data of COSMs as of now showing all the department lists.


Manpower Booking (MPB)

Version: V1.14.18
Release Date: 2025-09-30

Version: V1.14.18
Release Date: September 30, 2025

Overview

This release improves the handling of error and warning messages on the All Transaction screen, ensuring they no longer persist across different transaction screens.

Issue

On the All Transaction screen in MPB, error and warning messages were not resetting properly. When users performed a transaction and received an error or warning message, the same message persisted across other transaction screens until the URL was refreshed.

Resolution

The system now handles error and warning messages independently on each transaction screen. Messages are cleared appropriately after each transaction, preventing them from carrying over to other screens.


Time Keeping (TKS)

Version: V1.14.18
Release Date: 2025-09-30

Screen Name: All Transaction Screen of TKS
Issue 1

On the All Transaction screen in TKS, error and warning messages were not resetting properly. When users performed a transaction and received an error or warning message, the same message persisted across other transaction screens until the URL was refreshed.

Resolution
The system now handles error and warning messages independently on each transaction screen. Messages are cleared after each transaction, preventing them from carrying over to other screens..

Screen Name: Non - Industrial 
user has already booked a OT for NON-Industrial case but system throws error Data not found even though booking exists.


Refit Planning (RPP)

Version: V1.14.18
Release Date: 2025-09-30

Overview
This release addresses an issue where P1 WIs approved by the center were not visible in the Release WI screen.

Bug Fixes and Enhancement

Screen: Release WI

Issue:
When a WI marked as P1 was approved by the center, it was not displayed in the Release P1 WI list.

Resolution:
The system now ensures that WIs marked as P1 and approved by the center are displayed correctly in the Release P1 WI list.


Screen Name: Work Order

1. Automatic costing calculation

Values entered in the costing field are now calculated automatically.

2. Forwarding to AGM(PL)

The system now forwards to AGM(PL) while creating a new work order in the transaction stage.

3. WI Progress and QC Remarks visibility

Added a provision to view WI Progress and QC Remarks before WI closure in grid view.

The following columns are displayed in order:

WI No.

WI Status

Progress %

Job Detail

Remaining columns


Manpower Booking (MPB)

Version: V1.14.18
Release Date: 2025-09-30

Overview

This release fixes false Data not found errors in non-industrial OT bookings and improves error and warning message handling across allocation and OT booking transaction screens.

Screen Name: 

Issue:
When a user booked OT for a non-industrial case, the system displayed an error message: Data not found, even though the booking existed.

Resolution:
The system now correctly recognizes and processes existing OT bookings for non-industrial cases without showing false error messages.

Screen: Allocation

Issue:
Error and warning messages displayed during transaction entries persisted across other transaction screens until the URL was refreshed.

Resolution:
Error and warning messages are now properly cleared after each transaction, ensuring they do not carry over to other screens.

Screen: OT Booking Industrial – Amend

Issue:
Error and warning messages triggered during industrial OT booking transactions remained visible on other screens until the URL was refreshed.

Resolution:
Error and warning messages are now handled correctly within the OT Booking Industrial screen and no longer persist across unrelated transaction screens.

Screen: OT Booking Non-Industrial – Amend

Issue:
Error and warning messages triggered during non-industrial OT booking transactions remained visible on other screens until the URL was refreshed.

Resolution:
Error and warning messages are now handled correctly within the OT Booking Non-Industrial screen and no longer persist across unrelated transaction screens.

Time Keeping (TKS)

Version: V1.14.18
Release Date: 2025-09-30

Overview

This release improves error and warning message handling across key Time Keeping transaction screens to ensure messages do not persist beyond the active transaction.

Screens: Amend Punch, Amend Attendance, OT Finalization, Assign Key Duty

Issue:
Error and warning messages displayed during transaction entries remained visible on other transaction screens until the URL was refreshed.

Resolution:
Error and warning messages are now handled correctly within each transaction screen and no longer persist across unrelated screens.

Personnel 

Version: V1.14.18
Release Date: 2025-09-30

Overview

This release fixes an issue in the Employee Master screen where the center field appeared blank even when the department was already frozen.

Screen: Employee Master

Issue:
The Center field displayed as blank while the Department field was already frozen.

Resolution:
The system now correctly displays the Center field in alignment with the frozen Department field in the Employee Master screen.


LTC 

Version: V1.14.18
Release Date: 2025-09-30

Overview

This release introduces an extended leave option in the LTC Claim Application and resolves an issue where LTC dates were not passing correctly in update mode.

Screen: LTC Claim Application

Enhancement:

Added an Extended Leave button to provide flexibility in managing leave extensions.

Issue:
In update mode, the From and To dates for LTC claims were not passed correctly.

Resolution:
The system now correctly processes and passes the From and To dates in update mode for LTC claim applications.

TY Duty

Version: V1.14.18
Release Date: 2025-09-30

Overview

This release resolves an issue in the Request for Advance screen where document numbers were not generated, and the confirmation popup did not appear upon saving a transaction.

Screen: Request for Advance

Issue:
On saving a transaction, the document number was not generated, and the confirmation popup did not open.

Resolution:
The system now correctly generates the document number and displays the confirmation popup when a transaction is saved.

Manpower Booking (MPB)

Version: V1.14.19
Release Date: 2025-10-01

Overview

This release addresses issues related to the OT Industrial Amend and OT Booking Industrial screens, ensuring proper validation, accurate data retrieval, and expected selection behavior.

Bug Fixes

Screen: OT Industrial Amend

Issue:
The screen allows directly to save entries after selecting a date without any validation or confirmation.

Resolution:
Validation and confirmation checks have been implemented to ensure that records cannot be saved without the required validations.

Screen: OT Booking Industrial

Issue:

The system displayed a “Data Not Found” message even when manpower had been allocated for the selected date.

While selecting a Work Instruction (WI), multiple WIs were being selected simultaneously.

Resolution:

The data retrieval process has been corrected to display allocated manpower details accurately.

The selection logic has been refined to ensure only the chosen WI is selected.


Time Keeping (TKS)

Version: V1.14.19
Release Date: 2025-10-01

Overview

This release addresses issues related to Punch Amendments, OT Finalization, and Pass Creation, ensuring accurate validations, error handling, and proper time formatting.

Bug Fixes

Screen: Amend Punches and Amendment

Issue:
Future dates were not allowed in ammend screen when amending punches.

Resolution:
The system now allows amendments with valid future dates as per business requirements.

Screen: OT Finalization

Issue:

Final OT values could become negative.

Resolution:

Validation has been added to ensure Final OT cannot be negative.

Issue:
Multiple repeated messages appeared when attempting to save without selecting a record.

Resolution: 
The system now displays a single, appropriate error message when saving without selecting a record.

Screen: Create Pass

Issue:

Morning session passes (10:00–13:00) it as as returnable.

Afternoon session passes (14:00–16:30, logout/shift end time) it as non-returnable.

The "From Time" field did not display the current system time.

Resolution:

The pass creation logic has been corrected to ensure returnability rules are applied consistently.

The "From Time" field now displays the current time by default.


LTC

Version: V1.14.19
Release Date: 2025-10-01

Overview

This release addresses issues with transaction confirmations, block year validations, and ensures smooth end-to-end user flow across multiple LTC processes.

Screen: MRO LTC

Issue:
After saving a transaction, the confirmation pop-up (“Data Saved”) was not displayed.

Resolution:
The confirmation message now appears after saving transactions.

Screen: LTC Advance Proposal

Issue:
Validation for the LTC Advance Block Year was not applied correctly.

Resolution:
Block Year validation has been implemented to ensure accurate proposal submissions.

Screens: LTC Advance Proposal, LTC Advance CDA Approval, LTC Claim Application, Claim CDA Approval, LTC Leave Encashment

Verification:
The complete user flow across the above modules has been verified to ensure that all processes function correctly from proposal to approval and claim stages


Refit Planning (RPP)

Version: V1.14.19
Release Date: 2025-10-01

Enhancement

Resolution: The color codes have been removed from the grid after applying filter options such as Assigned or Pending. 

OPRA

Version: V1.14.19
Release Date: 2025-10-01

Enhancement
The Equipment field has been added to the quick update mode.

Refit Planning (RPP)

Version: V1.14.20
Release Date: 2025-10-03

Screen Name: Work Order
Added user AGM(PL) while creating a new work order in the transaction stage.

Verification: 
Approval flow as mentioned is checked Planner(PL) forwards it to MPLS then to AGM(PL) then to GM(R).


Screen Name: Work Instruction
Issue: Work Instrcution progress status updated by the PRM is not displayed in the WI progress tab.
Resolution: Issuse has been resolved WI progress status is displayed in the WI progress tab.

Refit Planning (RPP)

Version: V1.14.20
Release Date: 2025-10-03

Overview
This release addresses bug fixes and enhancements for the Work Order and Work Instruction screens.

Screen Name: Work Order

Enhancement and Bug Fixes

Update:

Added user AGM(PL) while creating a new work order in the transaction stage.

Verification:

Approval flow has been checked: Planner (PL) → MPLS → AGM (PL) → GM (R).

2. Work Instruction Screen

Issue:

Work Instruction progress status updated by the PRM was not displayed in the WI progress tab.

Resolution:

Issue has been resolved; WI progress status is now correctly displayed in the WI progress tab.

Screen Name: All screen

Enhancement
The color codes have been removed from the grid after applying filter options such as Assigned or Pending. year condition based on previous year

Screen Name: Cardinal Event Master

Update mode issue has been resolved in the cardinal event.


LTC

Version: V1.14.20
Release Date: 2025-10-03

Overview
This release addresses bug fixes and enhancements for the LTC Advance Proposal, LTC Leave Encashment, and LTC CDA Approval screens.

Screen Name: LTC Advance Proposal

Issue:

In a block year (2022–2025), if an employee avails LTC in 2022–2023, the extension of 2022–2023 should not appear in the Entitled Block Year dropdown.

Resolution: Issue resolved; condition applied of year added based on previous year. 

Resolution:

Screen Name: LTC Leave Encashment

Issue: Selecting an Application ID did not automatically fetch the corresponding Employee ID.

Resolution: Employee ID now populates automatically when Application ID is selected.

Screen Name: LTC Claim CDA Approval

Removed mandatory symbol from Employee ID field.

Screen Name: LTC Leave Encashment CDA Approval

Added Employee ID and Employee Name in the Application ID table grid.


VMS

Overview

This release addresses multiple issues identified in the Vendor Management System (VMS) module. The updates focus on correcting missing data display, filter inconsistencies, and synchronization issues with vendor categories. These fixes improve data accuracy and usability across Vendor Master, Vendor Performance Rating, and Vendor Penal Action screens.

Bug Fixes
Screen: Vendor Master

Issue:
After a vendor is approved, the bank name is missing from the Account Details tab in both Update and View modes.

Resolution:
Corrected the data retrieval logic to ensure the bank name is displayed consistently in the Account Details tab in vendor Master.

Screen: Vendor Performance Rating

Issue:
The User Department filter was not working as expected.

Resolution:
Fixed the filter functionality so that the User Department selection now correctly applies to vendor performance results.

Screen: Vendor Penal Action – Vendor Master

Issue:
Blacklisted vendor categories were not being reflected correctly. After a vendor was blacklisted, the associated categories were not displayed in the Vendor Master.

Resolution:
Updated the synchronization between the blacklist process and the Vendor Master screen to ensure that all relevant blacklisted categories are displayed correctly.


Refit Planning (RPP)

Version: V1.14.21
Release Date: 2025-10-06

Overview

This release enhances the Refit Planning (RPP) module with improved filters, automated field updates, and better role-based visibility. The updates increase data accuracy and streamline refit planning workflows.

Screen Name: Dashboard Screen
Resolution: A new filter option has been added to the Dashboard Screen to display ships with completed refcom. The filter now retrieves and displays records of completed refits from the past 1 year.


Screen Name: Work Order - Refit
Issue:
Newly created ships linked to specific roles were not visible to users in MCAP and Planner CAP logins.

Resolution:
Newly created and linked ships now appear correctly in the assigned user roles for both MCAP and Planner CAP logins.


Screen Name: WO Ammendment

The REFCOM Date and DTG fields are now disabled in the WO Amendment screen. Their default values are set to null to maintain data accuracy

Screen Name: DL Finalization
Issue: The PRM Remarks filter must display only Tentative and Not Verified data. Finalized data must appear only under the Finalized filter.
Resolution: The PRM Remarks filter now displays only Tentative and Not Verified data. Finalized data is available exclusively under the Finalized filter.


Screen Name: Work Instruction
Issue: After selecting the WI Activity field, the corresponding dates must automatically populate in the PSD and PCD fields.
Resolution: The PSD and PCD fields now auto-populate based on the selected WI Activity, improving data consistency and user efficiency.


Screen Name: WI Ammendment
Issue: After releasing a Work Instruction, the PSD and PCD fields remained visible and editable and these must remain editable in screen.
Resolution: The WI Amendment screen has been updated to allow the PSD and PCD fields to remain visible and editable after a WI release.


Screen Name: COSM Remarks Report
Issue: For RPP, the report should be title of COSM Remarks Report instead of MPC View Remarks Report, and the excel export file must display COSM in place of MPC in the column headers.
Resolution: The report title has been corrected to COSM Remarks Report. The Excel export now displays “COSM” in the column headers to ensure consistency with the report title.


Manpower Booking (MPB)

Version: V1.14.21
Release Date: 2025-10-06

Overview:
This release enhances the Allocation of Man power screen by improving WI selection retention and ensuring pop-ups behave correctly based on PCD status.

Screen Name: Allocation of Man power
Issue 1: The selected WI and date must remain same until the user changes or all the employees are allocated.
Resolution: The system has been updated to retain the selected WI and date until the user makes any change or all employees are allocated.

Issue 2: WI pop-up the WI must be disappeared when the PCD is expired.
Resolution: The WI pop-up will now automatically disappear when the PCD is expired.

Screen Name: OT Booking Report
Issue: In a non-production scenario, the Industrial category displayed a pop-up message stating “Data not found".
Resolution: The data retrieval logic has been corrected. The OT Booking Report now properly displays records for Industrial entries in non-production scenarios.


Screen Name: OT Industrial, OT Non Industrial
Issue: In a non-production scenario, the system did not validate whether a 4-hour entry for Industrial and Non-Industrial categories was accepted.
Resolution: The system has been updated to correctly validate and accept 4-hour entries for both Industrial and Non-Industrial categories in non-production scenarios.




e-Seva

Version: V1.14.21
Release Date: 2025-10-06

Overview

This release resolves an issue where Bio Data records were not visible in Update or View mode.

Issue: In the Bio Data section, records were not displayed in Update or View mode.
Resolution: The issue has been resolved. Bio Data records now display correctly in both Update and View modes.


Time Attendence And Access Control (TAACS)

Version: V1.14.22
Release Date: 2025-10-07

Overview
This release of TAACS module addresses the bug fixes for Assign Shift, Muster & OT report, and Daily - Freeze. 

Screen Name: Assign Shift
Issue: After assigning a shift to an employee in the Assign Shift screen, the grid did not display the updated From Date and To Date fields unless the entire page was refreshed.
Resolution: The issue has been fixed. The grid now displays the updated From Date and To Date values for the assigned shift of the employee

Screen Name: Create Pass
Issue: In the update mode of Create Pass, the save functionality did not work. When a user attempted to save changes, the system failed to persist the updates, and no confirmation or error message was displayed.
Resolution: The issue has been fixed. The save functionality now works correctly in update mode, and the system displays an error if it fails to persist the updates.
Screen Name: Daily - Freeze
Issue: The future date must be disabled; currently, it is selectable.
Resolution: The future date is now disabled and cannot be selected.

Screen Name: Muster & OT report
Issue: The Muster and OT reports are downloading empty.
Resolution: The Muster and OT reports now download in Excel format with complete data.

Screen Name: Assign Shift
Update: A Ref Shift ID column has been added to the grid.

e-Seva

Version: V1.14.22
Release Date: 2025-10-07

Screen Name: Social List
Issue: Only the officer's data must appear on this screen and in the Excel sheet as well
Resolution: The issue has been fixed. Officers’ data now display correctly on the screen and in the downloaded Excel file.

Screen Name: Bio Data 
Resolution: The issue has been fixed. The text entered in the Others (in Specialization) field now displays correctly in both the Excel file and the entered field.


Quality Check Management (QCMS)

Version: V1.14.22
Release Date: 2025-10-07

Screen Name: CRF Approve QC
Issue:After clicking the Approve button, the data was not visible, and the screen appeared blank.
Resolution: Resolution: The issue has been fixed. The data is now visible, allowing the user to save successfully.


Personnel

Version: V1.14.22
Release Date: 2025-10-07

Screen Name: Annual Increment

Update: Enabled January and July options for the year 2026 in the date field.

Screen Name: Joining Back Deputed Employees

Update: Added a new field Employee Type with options such as Industrial and Non-Industrial.

Leave

Version: V1.14.22
Release Date: 2025-10-07

Leave Registration

Issue: Unable to save the transaction. The Save button was not working.

Resolution: The issue has been fixed. The transaction can now be saved, and the Save button functionality is working correctly.


Leave

Version: V1.14.23
Release Date: 2025-10-08

Bug fix and Enhancement

Screen Name: Leave Registration

Verification 1: Verified the validation logic for applied leave combinations.

Verification 2: Verified the approval workflow for all transactions within the Leave module.


Issue: The system should allow applying for Special Casual Leave even when the balance is zero.
Resolution: The issue has been fixed. The system now accepts Special Casual Leave applications even if the balance is zero.

Issue: Previously applied leave records were not appearing in update mode.
Resolution: The issue has been resolved, and the system now displays previously applied leaves correctly in update mode.

Screen Name: Leave cancellation

Added create, update and vieew functionality in screen.


Screen Name: Leave Balance Amendment

Removed decimal values from the grid.

The balance values are now displayed as only zero numbers.


LTC 

Version: V1.14.23
Release Date: 2025-10-08

Screen Name: LTC Claim Application

Added Employee ID and Employee Name in the Application ID pop-up.

These details are now visible in the grid table.


Screen Name: LTC Advance Proposal
Issue: When an employee selects Home Town, the TO STATION field should automatically be locked with the value of the nearest railway station, and the Place of Visit should be set to the employee’s Home Town.

Resolution: The issue has been resolved. The system now automatically locks the TO STATION field with the nearest railway station and sets the Place of Visit to the employee’s Home Town when Home Town is selected.


Time Keeping (TKS)

Version: V1.14.23
Release Date: 2025-10-08

Screen Name: Wages Report
Issue: Issue: In the Center No header field, the dropdown list is not appearing when clicked, and UI-related issues are occurring.
Resolution: This issue has been fixed. The dropdown list in the Center No header field now appears correctly when clicked, and the related UI issues have been resolved. 

e-Seva

Version: V1.14.23
Release Date: 2025-10-08

Screen Name: Bio Data Report
Issue: Issue: In the Bio-Data report, for fields that have the value "Others", a new column should be added in the Excel report to display the corresponding values..
Reolution: This issue has been fixed. A new column is now added in the Excel output to display the values for fields marked as "Others".

TKS

Version: V1.14.24
Release Date: 2025-10-09

Screen Name: Daily Freeze
Issue: When selecting a date on the Daily Freeze screen, the daily attendance data/report is not displayed in the grid..Resolution: 
Resolution: Fixed the functionality to display the daily attendance data in the grid upon selecting a date.

Screen Name: Muster Freeze
New Transaction where user can perform transaction unfreeze which is freeze by daily freeze screen.(Impact will be Amend Attendance Screen when we perform unfreeze then this screen we be able to perform transactions other remains freeze)
Screen will be same as UnFeeze screen but here give two date as From Date and To Date.

Screen Name: Ammend Attendance Punch
Issue 1: In the "Amend Attendance Punches", when user select the "MIS Location" and enter the employee code (Ecode), the system will allow you to amend attendance punches and make muster amendments.
Reolution: The issue has been fixed. The system now allows users to amend attendance punches and make muster amendments based on the selected MIS Location from the drop-down and the E-code from the corresponding field.


Issue 2:
When two employee codes are involved and the Muster Amendment option is selected, the Change Status field appears. This field displays a dropdown menu with relevant data once an employee is chosen.

Resolution:
The issue has been fixed. The Change Status field now appears correctly when the user selects the Amendment Punches option from the E-Code. 




Resolution:  

New Transaction:
A new transaction has been added where users can unfreeze data that was frozen from the Daily Freeze screen.

Impact:
When the unfreeze is done, the Amend Attendance screen will allow transactions for the unfrozen dates, while other dates will remain frozen.

Screen Details:
The screen will look similar to the existing Unfreeze screen but will have two date fields — From Date and To Date — to select the range for unfreezing.




Refit Planning (RPP)


Version: V1.14.24
Release Date: 2025-10-10

Overview
This release includes bug fixes and enhancements for two screens in the RPP Module. The system pop-up after saving has been corrected, fields have been disabled in both modes as intended, and a new column has been added in the View PRM pop-up.

Screen Name: DL Assign PRM

Issue:
The system displayed the message “Role Saved Successfully” after saving, which did not accurately reflect the data saved successfully.

Resolution:
The message has been updated to display “Data saved successfully” upon saving.


Screen Name: PRM Remarks
Issue: In both Quick Update and Detailed Mode, once finalization was completed for a particular defect, the system still allowed users to make further changes.
Resolution: The system has been updated to prevent any modifications once a defect is finalized.
After finalization, all related fields and actions are now disabled in both Quick Update and Detailed Mode screens.

Enhancement
Update: The Proposed QC Level column has been added to the View Remarks popup, and the QC Level provided by the center will now be displayed in this column.




Leave

Version: V1.14.25
Release Date: 2025-10-11

Overview
This release includes enhancements for two screens in the leave Module.

Screen Name: Bulk Leave Approval

Feature: Bulk Leave Approval Transaction Dashboard

Enhancements:

Dealing Clerk Field: The drop-down option for the Dealing Clerk field has been updated to Bulk Leave Approval based on the selected location from the Transaction dashboard.

Print Functionality: Print option has been enabled for saved records. This allows printing of all selected data, including center-wise details, with multiple approved employees.

Screen Name: Leave Registration
Implemented validation for combinations for leave.

FMS 

Version: V1.14.26
Release Date: 2025-10-13
Screen Name: Initiate Proposal

Issue: The existing file numbering sequence format was previously defined as: LP/BC Short Name/C. FY/Sequence No.
A new format has been introduced for better standardization and traceability.
The updated format is:
BC/Type of Case/Ship Name (or) Department Short Name/C. FY/Sequence No.

Resolution: The file number generation logic has been updated to implement the new sequence format.


Personnel

Version: V1.14.26
Release Date: 2025-10-13

Screen Name: Added validation more than two character provided for first name field.

LTC 

Version: V1.14.26
Release Date: 2025-10-13

Enhancement and Bug Fixes
Screen Name: LTC claim Application

Issue: The functionality to add employee details in the grid on the LTC claim application is not working, even though it was already fixed earlier
Resolution: The issue has been fixed. The add functionality is now working, and users can successfully add details in the grid.

Screen Name: Leave Encashment Report
Added print functionality in the view mode of the Leave Encashment module on the Transaction Dashboard. Users can now download the selected transaction report.

Leave

Version: V1.14.26
Release Date: 2025-10-13

Screen Name: Leave Balance Ammendment Report
Added print functionality in the view mode of the Leave Balance Amendment module on the Transaction Dashboard. Users can now download the selected transaction report.

Issue: The Create, Update, and View modes are not working on the Leave Balance Amendment screen.
Resolution: The issue has been fixed. The Create, Update, and View modes are now working properly.

Screen Name: Leave Registration
Issue: The Save button functionality is not working when the user tries to save data for the Commuted Leave type.
Resolution: The Save button functionality has been fixed, enabling users to save the data.

Quartering

Version: V1.14.26
Release Date: 2025-10-13

Screen Name: Allotment of Quarter
Added print functionality in view mode of leave cancellation on transaction dashbaord user can download the selected transaction report. 

Screen Name: Retention Request
Added print functionality in view mode of leave cancellation on transaction dashbaord user can download the selected transaction report. 

Screen Name: Vacation 
Added print functionality in view mode of leave cancellation on transaction dashbaord user can download the selected transaction report. 


SWM – PAY
Overview

This release includes updates and enhancements in the Pay Certificate and Tulip Report screens of the SWM–PAY module.

Enhancement

Screen Name: Pay Certificate

Issue: In the Pay Certificate Report (Retired Report PDF), after viewing the retired report, a watermark labeled “Naval Dockyard Visakhapatnam” should appear on the document.
[Employee ID: 11043I]

Resolution: A watermark displaying “Naval Dockyard Visakhapatnam” has been added to the Retired Report PDF to ensure report authenticity and source identification.

Screen Name: Pay Certificate

Issue: A new requirement for all reports specifies that the font size of report headings should be reduced for better alignment and readability. Additionally, the footer date format should be changed from DD-MM-YYYY to MMM YYYY (for example, 12-01-2025 → Jan 2025).

Resolution: Font sizes for all report headers have been standardized and reduced. The footer date format has been updated to MMM YYYY across all applicable reports.

Screen Name: Tulip Report

Issue: After selecting Annexure C from the Report Type dropdown, several structural and formatting updates were required in the Tulip report Excel sheet:

The GPF_PRAN column has been moved to the second position.

The PAY_LEVEL and PERSONAL_NO columns have been rearranged.

The GPF_MONTH column has been renamed to MONTH, and the date format has been changed to MM-YYYY.

Resolution:
The Tulip report Excel layout has been updated to reflect the new column sequence, naming conventions, and standardized date format for improved clarity and alignment with reporting requirements.

OPRA

Version: V1.14.27
Release Date: 2025-10-14

Overview
This release includes enhancements that rename two modes — Quick Update and Detailed.

Screen Name: RA - Assign PRM

Enhancement
The grid buttons Quick Update and Detailed View have been renamed to Assign PRM and View Status.

Refit Planning (RPP)

Overview

Version: V1.14.27
Release Date: 2025-10-14
This release includes bug fixes accross the DL Upload, DL Approve, and  Status Summary Report.

Screen Name: DL Upload 
Issue: In the RPP DL Upload screen, only the ships assigned to a COSM in the Role Master screen should be displayed in both the Upload screens.
Resolution: The DL Upload screen has been corrected to ensure that only the ships assigned to a COSM in the Role Master screen are displayed in both the Upload screens.

Screen Name: DL Approve
Issue: In the RPP DL Approve screen, only the ships assigned to a COSM in the Role Master screen should be displayed in both the Approve screens.
Resolution: The DL Approve screen has been corrected to ensure that only the ships assigned to a COSM in the Role Master screen are displayed in both the Approve screens.

Screen Name: Status Summary Report
Issue: In the Status Summary Report screen, the total number of defects shown in the grid should match and be displayed in the Defect Detail popup screen.
Resolution: The Status Summary Report has been updated so that the total number of defects displayed in the grid now correctly matches the number shown in the Defect Detail popup screen.


Time Keeping (TKS)

Version: V1.14.27
Release Date: 2025-10-14

Overview
This release includes one bug fix and one enhancement of Time keeping (TKS).

Enhancements and Bug Fixes
Screen Name: CDR Report

Issue: In the CDR Report, Ministerial Employee data is missing.
Resolution: The issue with missing Ministerial Employee data in the CDR Report has been fixed, and the report now displays the previously missing data correctly.

Screen Name: Time Card Report

Enhancement: Added a new column (Ref Shift ID) for the Mumbai location, allowing users to view it in the Time Card Report


e-Seva

Version: V1.14.27
Release Date: 2025-10-14

This release includes performance enhancements through server-side functionality update.


Screen Name: Bio Data Master
Issue: Server-side searching, sorting, and pagination changes.
Resolution: 

Issue: Server-side searching, sorting, and pagination changes in the Nominee Details pop up.
Resolution: 

Leave

Version: V1.14.27
Release Date: 2025-10-14

Screen Name: Leave Balance Ammendment
Issue: Leave Balance Ammendment changes
Resolution: 

Screen Name: Leave Accural 
Issue: Transaction was not getting saved.
Resolution: 

Quartering

Version: V1.14.27
Release Date: 2025-10-14

Screen Name: Under Maintanance
Issue: Not able to save transaction.

SWM – PAY

Version: V1.14.27
Release Date: 2025-10-14


Overview

This release includes updates and enhancements in the Pay Certificate, Tulip Report and Non-Industrial Pay Summary screens of the SWM–PAY module.

Enhancement

Screen Name: Pay Certificate

Issue: In the Pay Certificate Report (Retired Report PDF), after viewing the retired report, a watermark labeled “Naval Dockyard Visakhapatnam” should appear on the document.
[Employee ID: 11043I]

Resolution: A watermark displaying “Naval Dockyard Visakhapatnam” has been added to the Retired Report PDF to ensure report authenticity and source identification.

Screen Name: Tulip Report

Issue: After selecting Annexure A from the Report Type dropdown, several updates were required in the Tulip Report Excel sheet:

The PAY_MONTH column date format has been changed to MM-YYYY.

The DOB and DOA columns date format has been changed to YYYY-MM-DD.

Column mapping updates:

CGEIS_1 has been mapped to CGEGIS.

IT_REC has been mapped to ITAX.

EHCESS has been mapped to EDU_CESS.

Resolution:
The Tulip Report Excel sheet has been updated to reflect the new date formats and column mappings, ensuring alignment with payroll data standards.

Screen Name: Non-Industrial Pay Summary
Issue: After selecting any report from the Summary dropdown, the report screen should display the newly added fields — Total No. of Employees, Net Pay, and Net — for improved data presentation.

Resolution: The Non-Industrial Pay Summary report has been updated to include the new summary fields, which are now visible upon selecting a report from the dropdown.


Budget Management (BMS)

Version: V1.14.27
Release Date: 2025-10-14


Screen Name: Prepare Contract Master

Enhancement

Issue: A new screen has been added to facilitate the creation of rate contracts against vendors.

Resolution: The new screen for adding rate contracts against vendors has been successfully implemented. and made available under the Prepare Contract Master section.



Issue: Leave Balance Amendment workflow process error.

Resolution: Implemented the required code changes on the screen and workflow to ensure the process functions correctl

Issue: Transaction was not getting saved due to a backend database error.

Resolution: The issue has been fixed, and the data is now saving correctly.





e-Seva

Version: V1.14.28
Release Date: 2025-10-15

Overview
This release includes bug fixes and enhancements in the Bio-Data Master and Board Master screens. The UI issue has been resolved, and the print button functionality has been added.

Screen Name: Bio-Data Master
Issue: The Designation field drop-down displaying all designations of officer it should display only officer from drop down.
Resolution: An API filter has been applied to the Designation field to ensure only officer designations are displayed.

Screen Name: Board Master
Issue: The search filter field in the Nominee Details pop-up was not displaying due to a UI issue and it going back side of pop-up.
Resolution: The UI issue has been resolved. The search filter field is now visible in the Nominee Details pop-up.

Screen Name: Board Master
Issue: When the user searched by rank or any other column, the filtered list could not be printed. Additionally, the Print button was missing from the pop-up.
Resolution: The Print button has been added to the pop-up, and users can now print or download the filtered list based on their selection in rank or any column.




Manpower Booking

Version: V1.14.28
Release Date: 2025-10-15

Overview
This release addresses issues in the Allocation of Manpower and OT Booking Industrial screens.

Screen Name: Allocation of Manpower
Issue: The selected WI must me come first on the grid for pop for update and view mode.
Resolution: The issue is fixed able to view the selected work instruction on grid for both mode update and view.

Screen Name: OT Booking Industrial
Issue: The selected WI must me come first on the grid for pop for update and view mode.
Resolution: The issue is fixed able to view the selected work instruction on grid for both mode update and view.


Financial Management (FMS)

Version: V1.14.28
Release Date: 2025-10-15

Overview

This release introduces performance and usability improvements within the Financial Management (FMS) module. The updates focus on optimizing dropdown responsiveness and correcting minor text inconsistencies to enhance user experience.

Performance Improvement
Screen: Draft RFP

Issue: The "Prepared By" dropdown in the Draft RFP screen was slow when selecting an employee, affecting overall screen performance.

Resolution: Optimized the data loading and binding process for the "Prepared By" dropdown to improve response time and ensure smoother selection.

UI Correction / Text Fix
Screen: Tender Participation and EMD Update

Issue: A spelling error was identified in the field label "Received Date".

Resolution: The label spelling was corrected to ensure consistency and clarity across the interface.

Version: V1.14.28
Release Date: 2025-10-15

Budget Management (BMS)
Version: V1.14.28
Enhancement
Release Date: 2025-10-15
Screen Name: Prepare Contract Master
Issue: The Update mode permission was not available earlier in the Edit option of the screen, restricting users from making necessary updates.

Resolution: Update mode permission has now been enabled in the Edit option on the Prepare Contract Master screen, allowing authorized users to modify and save contract details efficiently.

Refit Planning (RPP)

Version: V1.14.28
Release Date: 2025-10-15

Overview
This release address enhancement and bug fixes accross two screen ship master and wi progress screen.

Screen Name: Ship Master
Issue: After creating a new ship from the Ship Master, the ship does not appear in the Work Order and DL Upload screens.

Resolution: The selected ship from the Ship Master now appears in both the Work Order and DL Upload screens.

Screen Name: WI Progress


Update: In the Work Instruction Progress screen, the Work Center and Main Center are now visible based on the user’s role:

When logged in with the PRM role, the Work Center and Main Center are visible regardless of the selected location.

When logged in with a Center role, only the data related to the specific Main Center and its associated Work Centers is visible based on the user’s assigned location.

Dry Dock

Version: V1.14.28
Release Date: 2025-10-15

Overview
This release includes enhancements and bug fixes across Dry Dock Planning to ensure data visibility, along with the addition of a new field on the screen.


Screen Name: Dry Dock Planning

Enhancement

The Trim By field now appears support with multi-selection functionality allow user to select option from drop-down.

Added History button beside the Ship/Submarine field allow users to view previous data of ship.

Added Dock Version dropdown field allow user to select the versions available from drop-down.

Added Dock Version and Transaction Number columns in the grid of dry dock planning transaction Dashboard.

Bug Fixes

Issue: The data entered and saved in Dry Dock Planning is not reflecting in Dry Dock Booking.

Resolution: The data saved in Dry Dock Planning is now visible on the Dry Dock Booking screen.



Leave

Version: V1.14.28
Release Date: 2025-10-15

Overview


Enhancement

Screen Name: Apply Leave

Created new E-code Bulk leave Approval AM option is available on apply leave transaction dashboard screen  functionality developed.


SWM-PAY

Overview

This release introduces functional enhancements and new reporting features in the SWM-PAY module. Key improvements include the addition of employee information columns in the Non-Industrial Pay Summary report and the introduction of a new Employee-wise Pay Slip report.

Enhancements and Fixes
Screen: Non-Industrial Pay Summary

Issue: In the Non-Industrial Pay Summary report, after selecting any report from the Summary dropdown, the first column—Emp Info and No. of Emps—was missing from the report output.

Resolution: The report structure was enhanced to include the Emp Info and No. of Emps column, ensuring accurate and complete data display.

Screen: Employee-wise Pay Slip

Issue: A new report for Employee-wise Pay Slip has been added.

Resolution: Developed functionality to enable users to view and generate pay slips for individual employees.





Leave

Version: V1.14.29
Release Date: 2025-10-16

Overview:
This release addressed an issue with the Bulk Approval - AM (e-Code) functionality.

Screen Name: Leave Entry
Issue: The Bulk Approval - AM e-code functionality was not working and was not visible to some roles.
Resolution: The issue has been fixed bulk approval - AM e-Code is now visible for the roles in leave module and the functionality is working properly.

LTC

Overview


Version: V1.14.29
Release Date: 2025-10-16

Screen Name: LTC 
Issue: The Forward and Save functionality of LTC Leave Encashment was not working, and users were unable to forward the request to the user (dealing clerk).
Resolution: The functionality issue has been fixed, allowing users to forward the request to the user (dealing clerk) and save the transaction.



Yard Utility (YUS)

Overview

This release includes functional enhancements and defect fixes in the Service Requisition and Service Request Export Report screens.

Resolved Issues

Functional Enhancement
Screen Name: Service Requisition
Issue: The “Service Type” field for Service Requests related to “Jetty Cranes” did not populate according to the selected location. The values for “Jetty Cranes” are dependent on location and should reflect this dynamically.
Resolution: Updated the “Service Type” field for “Jetty Cranes” and is populated based on the selected location, ensuring accurate and context-specific data display.

UI/Message Correction
Screen Name: Service Requisition
Issue: When saving data in Update Mode, the system displayed the message “Data is successfully saved.” instead of “Data updated successfully.”
Resolution: Modified the message text for Update Mode actions. The system now displays “Data updated successfully.” when a record is updated.

Report Filtering Issue
Screen Name: Service Request Export Report
Issue: The ‘Center’ dropdown filter in the report menu was not functioning as expected, preventing users from correctly filtering data.
Resolution: Corrected the filter logic in the report module. The ‘Center’ dropdown now filters report data accurately based on the selected value.

Financial Management System (FMS)

Overview

This release addresses key functional and system-level issues within the Routing and SOW screens of the Financial Management System (FMS). The updates ensure correct workflow routing behavior and improve system reliability during file import operations.

Resolved Issues

Functional Defect
Screen Name: Routing
Issue:
After a file was forwarded to the next updater role, the routing function did not work as expected. The Approval Stage dropdown displayed “N/A,” and the system incorrectly allowed the file to be routed to the next role.
Resolution:
Updated the routing validation logic to prevent files from being routed when the Approval Stage value is “N/A.” The system now enforces correct routing behavior based on the approval stage.

System Error
Screen Name: SOW
Issue:
An error occurred while importing the SOW file, interrupting the import process.
Resolution:
Resolved the file import issue by enhancing the import handling mechanism. The SOW file can now be imported successfully without errors.


Leave

Version: V1.14.29
Release Date: 2025-10-17

Screen Name: Leave Entry
Combination of leaves

OPRA/Ops

Version: V1.14.30
Release Date: 2025-10-17


OPRA

Version: V1.14.30
Release Date: 2025-10-17

Issue: By default, OPS was displaying on the Work Instruction screen instead of Normal, which should be displayed.
Resolution: The issue has been fixed. The Work Instruction screen now correctly displays Normal by default instead of OPS.

Issue: By default, center 064A was being selected even after choosing a different center on the WI Create screen. The same was displayed incorrectly on the Work Instruction Release screen.
Resolution: The issue has been fixed. The selected center now displays correctly on both the WI Create and Work Instruction Release screens.

Screen Name: Dashboard
Issue: Quick Link option of OPS Ship in MPC login not working.
Resolution: The issue has been fixed. The Quick Link is now working, and OPS Ship can be accessed in MPC login.

OPDEF

Version: V1.14.30
Release Date: 2025-10-17

Screen Name: OPDEF finalization
Issue: The OPDEF Finalization screen was not working.
Resolution: The issue has been fixed, and the screen is now fully functional.

 
SWM 

Version: V1.14.31
Release Date: 2025-10-24

Screen Name: IT Declaration
Issue: Issue: An unexpected error occurs while saving data as Save as Draft. The operation fails with the error.
Resolution: The "Save as Draft" functionality is now fully operational, and users can save drafts without any errors.

Screen Name: OT Report
Issue: Some updates have been made to the OT Report Excel sheet:
1. Column headers have been updated for better alignment (grid format).
2. The columns Basic, DA, HRA, S Amount, D Amount, Total Amount, S Hrs Rate and D Hrs Rate have been formatted in Indian currency.

Screen Name: Table Recovery Report
Issue: Some updates have been made to the Table Recovery Report Excel sheet:
1. Improved the column headers for better alignment (grid format).
2. Applied Indian currency formatting to the To be Deducted, Actual Deducted and Difference columns.
Resolution: 

Refit Planning (RPP)

Version: V1.14.31
Release Date: 2025-10-24

Screen Name: Release WI
Issue: By default, the header was displayed as Naval Dockyard Visakhapatnam when logged in from the Mumbai location after opening the WI Print screen.
Resolution: The issue has been fixed. The header now correctly displays the respective location based on the user’s login.

Screen Name: DL - Assign PRM
An update has been implemented such that, upon clicking the 'Quick Update' button, the field previously labeled 'HQNC' is now displayed as 'Cmd. HQ Remarks' across all screens.
 
Issue: When the "Assigned" status is selected for the first time and the "Show Data" button is clicked, some changes are not reflected in the system. By default, the system displays the "Pending" status in the grid, requiring the user to reselect "Assigned" and click "Show Data" again to view the correct data.
Resolution: The issue has been resolved. The system now correctly displays data for the "Assigned" status upon the first selection, without defaulting to "Pending." Users can view the correct data immediately after clicking "Show Data.


Screen Name: Release WI
Issue: By default, the header was displayed as Naval Dockyard Visakhapatnam when logged in from the Mumbai location after opening the WI Print screen.
Resolution: The issue has been fixed. The header now correctly displays the respective location based on the user’s login


Screen Name: OT Report
Update: OT Report Excel sheet
1. The alignment of the column headers displayed in the grid has been updated.
2. The column — Basic, DA, HRA, S Amount, D Amount, Total Amount, S Hrs Rate, and D Hrs Rate — have been updated to display values in Indian currency.

Screen Name: Table Recovery Report
Update: Table Recovery Report Excel sheet:
1. The alignment of column headers has been improved for better visibility.
2. Indian currency formatting has been implemented for the columns “To be Deducted,” “Actual Deducted,” and “Difference.”

Screen Name: Payroll Report
Update: Payroll Report PDF File
Added serial numbers and properly aligned the columns.

Screen Name: Employee Detail
Update – Employee Detail Excel file 
The alignment (grid format) of column headers has been updated for better visibility, and all amount fields are now displayed in a comma-separated format.

YUS

Version: V1.14.31
Release Date: 2025-10-24

Issue: Issue: When no center is selected and the Show Data button is clicked, the grid displays data, but the Export (Excel) option fails and shows the error message: “Data not found.”
Resolution: The issue has been resolved. Now, when no center is selected and the Show Data button is clicked, the Export (Excel) option works correctly and no longer displays the “Data not found” error.

Leave

Version: V1.14.31
Release Date: 2025-10-24


Validation for combination leave changes has been implemented as per the requirement functionality has been changed.





Refit Planning (RPP)

Version: V1.14.32
Release Date: 2025-10-27

Overview
This release addresses an issue related to user-configurable, role-based location selection upon login.

Screen Name: Release WI
Issue: By default, the header was displayed as Naval Dockyard Visakhapatnam when logged in from the Mumbai location after opening the WI Print screen.
Resolution: The issue has been fixed. The header now correctly displays the respective location based on the user’s login.

Screen Name: RPP-PRM Remarks

Enhancement
1. Enhanced the Quick Update section to display additional remarks reflecting the status entered by the RPP-assigned PRM, it was working before also

Validation: Rechecked and validated the Equipment Name column to confirm that the field data is correctly populated. The functionality was working as expected in the previous release as well. 
The Equipment name column rechecked and validated field data doesn't remains empty.

Screen Name: Assign PRM Remark

Issue: The system defaults to Pending status after clicking Show Data, even when Assigned was selected. Users need to manually reselect Assigned to view the correct data.
Resolution: The issue has been fixed. The system now correctly displays data in the grid based on the selected status to view data assigned PRM remarks.


Screen Name: DL - Center Remarks

Validation: Rechecked and validated the Equipment Name column to confirm that the field data is correctly populated. The functionality was working as expected in the previous release as well.


OPRA/OPS


Version: V1.14.32
Release Date: 2025-10-27

Overview
This release addresses an issue related to the Quick Link option.

Screen Name: Dashboard
Issue: Quick Link option of OPS Ship in MPC login not working.
Resolution: The issue has been fixed. The Quick Link is now working, and OPS Ship can be accessed in MPC login.

QCMS

Version: V1.14.32
Release Date: 2025-10-27

Overview
This release enhances the CRF Request QC screen by enabling it in a read-only format, with only two fields available for editing.

Screen Name: CRF Request QC

Update: The CRF Request QC screen is now available in read-only format.
Only two fields are editable — QC Level Change Request and Additional Remark.
These fields allow users to enter remarks and update the status of the change level request.


YUS

Version: V1.14.32
Release Date: 2025-10-27

Overview
This release includes an enhancement to the Service Requisition screen, adding edit functionality for TSOC users.

Screen Name: Service Requsition
Update: Added edit functionality for TSOC users to modify service requests before allocation (OP_ID - 6681).

SWM - PAY

Version: V1.14.32
Release Date: 2025-10-27

Overview
This release includes UI enhancements to improve readability and consistency.

Screen Name: Loan Wise Details Report

Update: Excel Sheet Loan wise details report
Improved column headers for improved alignment (grid format) and applied comma-separated formatting for all amount fields.


Leave 

Version: V1.14.32
Release Date: 2025-10-27

Screen Name: Leave Resgistration

Implemented combined leave validation in the Leave Registration screen when applying for leave.

SWM - PAY 

Screen Name: Payroll Report
Issue 1: Employee details such as Date of Birth (DOB), PAN Number, and other related information were not displaying.
Resolution: The issue has been resolved. The employee details now display in the report. 

Issue 2: In the report below the basic amount was displaying the pay bill number instead of the basic salary level.
Resolution: The issue has been fixed. The Basic Amount now correctly displays the Basic Salary Level.

Issue 3: In the paybill schedule, the overtime (OT) Amount should not be reflected.
Resolution: The issue has been fixed. The OT Amount field has been disabled as.

Issue 4: The NPS IND is appearing in the both header and middle of report should not reflect.
Resolution: The issue has been fixed. The NPS IND has been disabled.

Update: Employee ID–wise sorting enhancement is now available, enabling users to match the page-wise totals in the report.
 
Screen Name: Earning Deductions
Enhancement:
Added an Official Recovery toggle button that allows users to enable or disable the auto-effect feature.



Module: Refit Monitoring (RMM)

Version: V1.14.32
Release Date: 2025-10-28

Overview
This release focuses on stabilizing the Refit Plan screen by addressing issues related to data synchronization, hierarchy representation, dependency handling, and user interface interactions.

Screen Name: Refit Plan

Bug Fixes
Issue 1: Incorrect work package type displayed during edit.
Resolution: Corrected logic to ensure the appropriate work package type is retained and displayed when displaying.

Issue 2: Update not working error when submitting with invalid "body" and "parent_act_srno" fields. The system displayed the message: "Input should be a valid integer".
Resolution: Implemented input validation and corrected data binding for integer fields to prevent update failures.

Issue 3: In the hierarchy view, predecessors were incorrectly displayed as child activities.
Resolution: Updated hierarchy rendering logic to correctly differentiate predecessors and child nodes.

Issue 4: Scroll behavior not synchronized between Gantt chart and activity list.
Resolution: Improved scroll synchronization to ensure both Gantt chart and activity list move together.

Issue 5: Dates changed simultaneously for multiple activities unintentionally.
Resolution: Resolved the issue by isolating date change events to the selected activity. Users can now modify both the activity start date and end date simultaneously.

Issue 6: Deletion of an activity without reassigning its child to another parent caused inconsistency.
Resolution: When a user attempts to delete a parent activity, a pop-up appears prompting the user to reassign its child activities to another parent. Additionally, the system provides an option to delete the parent activity along with its linked child activities if desired.

Issue 7: No API call triggered when changing dates in edit mode and saving; dates remained unchanged.
Resolution: Restored the API integration for date updates and ensured proper event triggering upon saving.

Issue 8: Changing activity dates by dragging automatically altered the sequence order.
Resolution: Updated the drag logic in the Gantt chart to maintain sequence integrity during date adjustments.

Issue 9: Predecessor not added when defining dependencies.
Resolution: Fixed dependency management to ensure predecessors are properly created and displayed.



Manpower Booking (MPB)

Version: V1.14.33
Release Date: 2025-10-29

Overview
This release addresses bug fixes in the MPB module across the OT Booking, Non-Industrial, OT Amendment, and Weekly Statement screens.

Screen Name: OT Booking, Non-Industrial and OT Amendent

Issue: Quarterly OT available data is not updated post OT Amendment.
Resolution: The issue has been resolved. The system now updates the Quarterly OT data correctly after any OT Amendment.

Issue: After changing the OT hours for a particular employee and saving the record, the page refreshed but the system did not accept the updated OT hours. The change was applied only after reopening the page.
Resolution: The issue has been fixed. The system now correctly accepts and saves OT hour changes without requiring the page to be reopened.

Screen Name: Weekly Statement
Issue: The report layout needed to be updated as per the provided reference image, and the print format was also required.
Resolution: The issue has been fixed. The report and print format have been updated as per the provided specifications. 

Refit Planning (RPP)

Version: V1.14.33
Release Date: 2025-10-29

Overview
Enhancements and fixes have been implemented across the PRM Remarks and Work Order screens to improve usability and consistency.

Screen Name: PRM Remarks
Enhancement

Enhancement:

1. Disabled the “Cardinal Event” field in the detailed view of all transactions.

2. Removed the “PRM” and “PRM Name” columns from the grid view.

Issue: The system currently allows deleting a center only from the Detailed View. The delete option is not enabled in the Quick Update screen.
Resolution: The issue has been fixed. The Delete option is now enabled in the Quick Update screen, allowing users to delete a center directly from there.

Screen Name: Work Order

Enhancement

Added cardinal event allows user to fill the event details.



Module: SWM–PAY

Overview

This release focuses on resolving several issues identified in the Payroll Report screens, including discrepancies in report data, calculation inconsistencies, and incorrect display of employee details. The fixes improve data accuracy and ensure report consistency across various paybill and schedule reports.

Enhancement
Screen Name: Payroll Report

Issue 1: When changing the DA % (Dearness Allowance percentage) in the master and running the pay process, the updated percentage was not reflected in the new Paybill Report PDF.

Resolution: The logic for fetching DA % values has been corrected. The report now accurately reflects the latest DA % as defined in the master data.

Issue 2: In the Paybill Report PDF, additional salary heads (beyond the main heads) were not showing total values in the page-wise details section.

Resolution: The total calculation logic has been enhanced. The report now includes total amounts for all salary heads, including additional ones, in page-wise details.

Berthing Management (BTMS)

Overview
This release 

Enhancements

Dry Dock

Version: V1.14.33
Release Date: 2025-10-29

Screen Name: Doc Occupancy

Gantt chart added in the Doc Occupancy screen allow user to book the value for booking based on the day,monthly, qauter, and year

Berthing Management (BTMS)

Version: V1.14.33
Release Date: 2025-10-29

Overview 
This release includes enhancements to map visibility and field requirements across key BTMS screens

Screen Name: Jetty Overview 
Added the dry dock ships in the map and updated functionality to ensure that only ships with an active Movement Order are shown on the map as well as jetty reloation on map through movement order.

Screen Name: Movement Plan

The mandatory symbol requirement for these fields No. of tugs and position has been removed.

Screen Name: Movement Order

The mandatory symbol requirement for these fields tugs details, crane, crane reporting  time and actual number of tugs has been removed.

YUS 

Version: V1.14.33
Release Date: 2025-10-29

Overview 
This release introduces enhancements and fixes in the Service Requisition screen to improve usability and data accuracy.

Screen Name: Service Requisition

Update: Added dropdown values "Signal" and "Non-Signal" for the Signal Type field. This field is to be completed by TSOC/DOC.
When the user selects "Signal" from the "Signal Type" dropdown, the "Article Type" dropdown field becomes enabled. The available values for this field are "Article", "Non-Article", and "Loading Task". This field is to be completed by TSOC/DOC.

Screen Name: Service Requisition

Issue 1: Calendar data should function based on the selected E-Code.
Example: Crane service requests should be displayed on the calendar according to the Crane Services E-Code selected.
Resolution: Updated the calendar logic to filter and display data dynamically based on the selected E-Code. When a user selects a specific E-Code, only the corresponding service requests (e.g., Crane Services) will appear on the calendar. This ensures that the displayed calendar data accurately reflects the chosen E-Code category.

Issue 2: While raising a service requisition, the calendar icon should display holidays.
Resolution: Updated the calendar component to integrate holiday data.


Refit Planning (RPP)

Version: V1.14.34
Release Date: 2025-10-30
Division: Mumbai

Screen Name: PRM Remarks
In the detailed view, the Equipment Name has been added to the Defect Description section on the left side.

Screen Name: DL- Center Remarks
In the detailed view, the Equipment Name has been added to the Defect Description section on the left side.

Screen Name: Approve CRF
In the grid view, the Revised EMD Value column displayed the previous EMD value instead of the revised EMD value.
Resolution: The issue has been fixed. The Revised EMD Value column now correctly displays the updated (revised) EMD value in the grid view.

Screen Name: Release WI
Enhancement:

In the Work Instruction Details section, the fields System and Sub System on the screen are disabled.


Shop Floor Management (SFM)

Version: V1.14.34
Release Date: 2025-10-30
Division: Mumbai

Screen Name: CRF Request

Bug Fixes

Issue: In the grid view, both OPS and Refit Work Instructions are currently displayed. It should display "Refit" Work Instructions by default.
Resolution: The issue has been fixed. The grid view now displays only "Refit" Work Instructions by default.

Screen Name: P1 Receive

Bug Fixes

Issue: The P1 raised data was not being populated on the P1 Receive screen.
Resolution: The issue has been fixed. The data for the P1 raised now correctly populates and reflects on the P1 Receive screen.

Screen Name: P1 Receive
Issue: In the grid view of P1 Receive, the Main Center and Work Center that raised the request (Parent WI) were not displayed.
Resolution: The issue has been fixed. The grid view now correctly displays the Main Center and Work Center details of the request originator (Parent WI)

Enhancement

The QC Level field is set to disabled for editing.

In the Transaction Dashboard grid view, two fields — QC Level and WI Release Date — have been added for users to view.

Personnel 

Version: V1.14.34
Release Date: 2025-10-30

Screen Name: Employee Master
Enabled four accordian employee detail, appointment details, previous expreience, VII CPC on screen.

Dry Dock

Version: V1.14.34
Release Date: 2025-10-30
Division: Vizag

Screen Name: Dry Overview

Added new report.

Screen Name: Dry Undock 

Enhancement
Update: The fields From Date, To Date, Doc Version, Orientation, Ship Position, and Docking Type have been set to read-only for users.

YUS

Version: V1.14.34
Release Date: 2025-10-30

Bug Fixes

Screen Name: Service Requisition

Issue 1: The ship name should be displayed by default based on the ship that is logged in.
Resolution: This issue has been fixed. The ship name is now displayed by default based on the logged-in user in the system.

Division: Mumbai and Vizag

Issue 2: The system currently allows users to create a new service requisition for the same service (Request and Type) even if service feedback for a previous transaction has not been submitted.
Resolution: This issue has been fixed. The system now prevents users from creating a new service requisition for the same service until feedback for the previous transaction has been submitted.

Division: Vizag

Issue 3: In Crane Services, the system did not validate whether the Actual Start Time and Actual Completion Time were updated before completing the service allocation.
Resolution: This issue has been fixed. The system now ensures that both times are entered before the service allocation can be completed.

Division: Vizag

Issue 4: The system did not display dynamic data or columns after clicking the Show Data button.
Resolution: The issue has been fixed. The system now correctly displays the dynamic data and columns when the Show Data button is clicked.

Division: Mumbai and Vizag


Financial Management (FMS)

Version: V1.14.33
Release Date: 2025-10-30

Overview

This release focuses on improving data accuracy and enforcing mandatory field validations across multiple FMS screens. Additionally, enhancements were made to ensure proper data fetching and dropdown population.
Enhancement
Screen Name: Work Instruction

Issue: Previously, work instruction data was not being retrieved in the Financial Management (FMS) module, resulting in incomplete data visibility.

Resolution: The system logic has been updated to ensure that work instruction data is now correctly fetched and displayed within FMS. This change enhances consistency and ensures that all relevant financial and operational data are available to users for reporting and analysis.

Bug fixes
Division: Mumbai
Screen Name: New Proposal

Issue: The Minor Head dropdown in the New Proposal screen was missing certain data values, preventing users from selecting the appropriate minor head during proposal creation.

Resolution: The missing data entries have been restored. The Minor Head dropdown now displays all relevant options, ensuring accurate and complete data selection during proposal creation.

Screen Name: New Proposal

Issue: Duplicate entries appeared in the NI Annexure and NA Annexure sections.

Division: Vizag

Screen Name: POEV

Issue: Mandatory fields in the POEV screen were not enforced.

Resolution: All required fields have now been set as mandatory to ensure data completeness.

Screen Name: BQ Criteria

Issue: Mandatory fields were not properly enforced in the BQ Criteria screen.

Resolution: All essential fields are now marked as required to maintain data integrity.

Resolution: Duplicate data has been removed to ensure accuracy and prevent redundancy.

Division: Vizag and Mumbai

Screen: Noting / Viewer

Issue: Duplicate signatures and photos appeared during the approval process in the Noting screen.

Resolution: The issue has been resolved. The system now displays only a single instance of the signature and photo when approving through Noting.


Refit Monitoring Module (RMM)

Version: V1.14.33
Release Date: 2025-10-30

Division: Vizag and Mumbai

Overview
This release introduces key usability improvements and visual enhancements in the Refit Plan screen. The update includes better task dependency visualization, UI adjustments for improved readability, and bug fixes that enhance overall performance and stability.

Enhancements
Screen: Refit Plan

Issue: When modifying a task timeline—either by dragging the bar in the Gantt chart or through other editing features—the preceding or succeeding dependent tasks were not visually distinguished, making it difficult to identify timeline impacts or mismatches.

Resolution: The system now highlights dependent tasks whose timelines are affected by modifications, similar to the functionality in Microsoft Project. This enhancement helps users easily identify scheduling conflicts or dependencies at a glance.

New requirement
Screen: Refit Plan

Issue: In the “View” tab, opening a plan caused the screen to freeze in view-only mode.

Resolution: A provision has been added to allow users to access data in read-only mode.

Bug Fix
Screen: Refit Plan

Issue: Column width needed adjustment, left alignment was inconsistent, and the calendar code required revision.

Resolution: Column lengths have been increased, text has been left-aligned for better readability, and the calendar code has been reviewed and updated in Git.

Screen: Refit Plan

Issue: Title text did not wrap properly without increasing the Gantt bar size.

Resolution: Title text wrapping has been implemented without altering the Gantt bar dimensions, improving visibility and layout consistency.


Module: Budget Management System (BMS)

Version: V1.14.33
Release Date: 2025-10-30
Division: Vizag

Overview
This release introduces two new functional screens within the Budget Management System — DPE Extension and Completion Date — enhancing user capability to update and manage Work Order timelines directly.

Enhancements
Screen Name: DPE Extension

Issue: A new screen was required for DPE Extension to allow users to update the Work Order Date.

Resolution: A new DPE Extension screen has been developed. Users can now update and manage Work Order dates directly through this interface.

Screen Name: Completion Date

Issue: A new screen was required to enable users to update the Work Order Completion Date.

Resolution: A new Completion Date screen has been introduced. Users can now enter and update Work Order completion information efficiently within the BMS module.


Personnel 

Version: V1.14.34
Release Date: 2025-10-30

Screen Name: Employee Master
Enabled four accordian employee detail, appointment details, previous expreience, VII CPC on screen.


SWM – PAY

Version: V1.14.33
Release Date: 2025-10-30

Division: Vizag

Overview:
This release introduces enhancements to the Earning & Deduction and Payroll Report screens in the SWM – PAY module, improving data alignment, report clarity, and usability for payroll management.

Enhancements
Screen Name: Earning & Deduction

Issue: The Excel sheet header names did not align with the data mapping requirements.

Resolution: The Excel sheet headers have been updated and standardized to match the defined data mapping structure, ensuring consistency and clarity in exported reports.

Screen Name: Payroll Report

Issue: In the Payroll Report screen (NSP Schedule – Regular Paybill Report PDF), the corresponding pay bill number and year were not displayed alongside the file number.

Resolution: The report layout has been enhanced to display the pay bill number and year details next to the file number, improving data visibility and reference accuracy.

Refit Planning (RPP)

Version: V1.14.35
Release Date: 2025-10-31
Division: Mumbai

Screen Name: Work Order - Refit

Issue: To enable the edit option, the page had to be refreshed multiple times for A/DGM(P) and GM(R) user logins.
Resolution: The issue has been fixed. The edit option now works correctly without requiring multiple page refreshes.

Screen Name: Work Order Refit

Issue: The costing total amount was not being displayed for the next updater roles — MPLS, AGML, and GMR.
Resolution: The issue has been fixed. The costing total amount is now correctly displayed for the MPLS, AGML, and GMR roles.

Screen Name: PRM Remarks

Enhancement:
In Quick Update, a new column "Proposed QC Level" has been added to display the level proposed by the center to PRM.

Bug Fixes
Issue: PRM should not be able to propose an EMD that exceeds the matrix unit specified at the time of creating the WO.
Resolution: The issue has been fixed by implementing a validation to restrict PRM from proposing an EMD value beyond the defined matrix unit.

Screen Name: Work Instruction
Issue: In the Remarks History, the Proposed QC Level column was appearing blank.
Resolution: The issue has been fixed. The Remarks History now displays the Proposed QC Level value.

Screen Name: P1 Raise
Enhancement
Enhancement: The QC Level field is disabled, preventing the center from proposing a QC level at this stage.

Screen Name: DL Finalization
Enhancement:
In the detailed view, the field Cmd. HQ Remarks Remarsk has been renamed to Cmd. HQ Remarks.


Shop Floor Managment (SFM)

Version: V1.14.35
Release Date: 2025-10-31
Division: Mumbai

Screen Name: CRF Request

Issue: In the CRF printout, the revised values of PCD, PSD, and EMD were not being updated.
Resolution: The issue has been fixed. The CRF printout now correctly displays the updated values for PCD, PSD, and EMD.

Time Keeping (TKS)

Version: V1.14.35
Release Date: 2025-10-31
Division: Mumbai

Screen Name: Time Card Report
Issue: The shift field value in the Time Card Report was not displaying correctly based on the Assigned Shift reference value from the Shift Master.
Resolution: The issue has been fixed by updating the report logic to correctly fetch and display the shift field value according to the Assigned Shift reference from the Shift Master.

BTMS 


Version: V1.14.35
Release Date: 2025-10-31

Division: Vizag
Screen Name: Movement Plan/Order
Enhancement
In the position drop-down field added functionality of turn around.

Division: Vizag
Screen Name: Jetty Overview
Issue: The issue related to the jetty position has been fixed. Earlier, the system was taking the position from the Movement Plan; it now correctly takes the position assigned in the Movement Order.
Resolution: The issue has been addressed by updating the logic to fetch the jetty position from the Movement Order instead of the Movement Plan.

Division: Mumbai
Screen Name: Jetty Overview
Issue: Ships were not being displayed on the Jetty Overview map.
Resolution: The issue has been fixed by logic to ensure ships appear properly on the Jetty Overview screen.



Dry Dock

Version: V1.14.35
Release Date: 2025-10-31

Screen Name: Dry Dock Plan

Issue: The Dry Dock Plan Work Order was not functioning correctly.
Resolution: The issue has been fixed, and the functionality is now working as expected.


Yard Utility System (YUS)

Version: V1.14.35
Release Date: October 31, 2025
Division: Vizag and Mumbai

Overview

This release includes multiple corrections and functional improvements within the Yard Utility System (YUS) module. The updates focus on improving data accuracy, interface consistency, and filter functionality across various screens, including Service Requisition, R-Feedback Report, and Service Type Master.

Bug Fixes and Enhancements
Screen Name: Service Requisition

Issue: In the Service Requisition Transaction screen, the Save as Draft and View grid displayed the Request Date in an incorrect format (YYYY-MM-DD) and showed Start Time and End Time values in milliseconds instead of standard time format.

Resolution: Corrected the date format to align with the system’s standard (DD-MM-YYYY) and updated the time display to reflect standard time units instead of milliseconds.

Screen Name: R-Feedback Report

Issue: In the R-Feedback Report screen, the filters for Request No. and Request Date columns were not functioning as expected when selecting values from the Request No. dropdown list.

Resolution: Enhanced the filter logic to ensure that both Request No. and Request Date filters perform accurately and dynamically based on user selection.

Screen Name: Service Type Master

Issue: In Update Mode, the active/inactive functionality is not working correctly. Additionally, The selected record’s active/inactive status should work properly otherwise function directly, similar to the functionality in the Service Group Master or Service/Utility Master screens.

Resolution: Fixed the issue to ensure that the Active/Inactive toggle works properly in Update Mode. The functionality now operates consistently with other master screens.



SWM - TAX

Version: V1.14.35
Release Date: October 31, 2025
Divisions: Vizag and Mumbai

Bug Fix
Screen Name: Voluntary Tax

Issue: On the Voluntary Tax Transaction Dashboard screen, the filters in all grids such as Save as Draft and Views were not functioning correctly.

Resolution: The filter functionality has been corrected. Users can now apply and use filters in all grids, including Save as Draft and Views, as expected.

SWM - PAY

Version: V1.14.35
Release Date: October 31, 2025
Divisions: Mumbai

Bug Fix
Screen Name: Amend Pay Process

Issue: In Update Mode, when saving data, the system displayed the message “Data saved successfully.” The correct message should be “Data updated successfully.”

Resolution: The system message has been updated to correctly display “Data updated successfully.” when a record is modified in Update Mode.

Budget Management System (BMS)

Version: V1.14.35
Release Date: October 31, 2025
Division: Vizag

Enhancement

Screen Name: Code Head, Minor Head, and Major Head Master

Issue:
The PDF and Excel export icons were updated in the Code Head, Minor Head, and Major Head Master screens. (Note: Filtration functionality is pending implementation.)

Resolution:
Updated the UI elements for PDF and Excel icons to align with the latest design standards.

Note: Filtration functionality will be addressed in a Next release.


Financial Management System (FMS)

Version: V1.14.35
Release Date: October 31, 2025
Divisions: Vizag and Mumbai

Overview

This release introduces functional enhancements and bug fixes across the Financial Management System (FMS) module. The update focuses on improving proposal management and ensuring better reliability in transaction processing. Key improvements include enabling the Freeze Proposal feature, resolving saving issues in the Initiate Proposal screen, and correcting missing file number details in the Transaction Dashboard.

Enhancement
Division: Vizag

Screen Name: Financial Activities

Issue: Implemented and enabled the Freeze Proposal functionality. (Note: The Draft View implementation is pending.)

Resolution: The Freeze Proposal feature has been successfully integrated to allow users to finalize proposals.

Note: The Draft View functionality will be included in a next release.

Bug Fixes
Division: Mumbai

Screen Name: Initiate Proposal

Issue: Previously, the system did not save proposals on the first attempt and displayed an error message.

Resolution: The issue has been resolved. Users can now save proposals successfully on the first attempt without encountering errors.

Division: Mumbai
Screen Name: Transaction Dashboard

Issue: The File Number was not appearing in the Draft List of the Transaction Dashboard.

Resolution: The defect has been corrected. File numbers now display properly in the Draft List.


Refit Monitoring Module (RMM)
Division: Vizag

Enhancement

Screen Name: Refit Plan

Issue: As part of the CRF impact implementation, the Actual PCD and Revised PCD values were not being displayed in the WIL List (Work Item List).

Resolution: Modified the Refit Plan screen to display both Actual PCD and Revised PCD in the WIL List, ensuring alignment with CRF-driven updates and improving data transparency.


Budget Management System

Version: V1.14.36
Release Date: 2025-11-02
Division: Vizag

Overview

This release includes various enhancements and the development of new screens within the BMS module to improve functionality and user experience.

Enhancement Details

Screen Name: Carry Forward Liabilities

The Carry Forward Liabilities transaction functionality has been completed.

Note: The amount entered in the liabilities screen is not displayed in the FAC report. The update to the FAC report is pending due to related impacts.

Screen Name: Milestone

The Create Milestone functionality has been completed. This feature is provided under the Financial Case screen, allowing users to set milestones against a financial case.

Screen Name: Cancel Work Order

A provision has been added to allow users to cancel a work order transaction.

Screen Name: BC Report

The BC Report functionality has been completed. This report provides detailed information about the Budget Centre and allows users to download the data in Excel format.

Screen Name: Pending Milestone Report

The Pending Milestone Report functionality displays detailed information about pending milestones for the Milestone screen.

Note: The user interface has been created, but backend integration is still pending.

Screen Name: Fund Commitment

A new transaction, Fund Commitment, has been added within the BMS module.


Financial Management System (FMS)

Version: V1.14.36
Release Date: 2025-11-02
Division: Vizag

Overview

This release introduces usability enhancements to key screens within the Financial Management System (FMS). The updates aim to improve user control and transparency in managing work orders and bill booking activities. New interface elements have been added to provide clear status visibility and streamline data entry workflows.

Enhancements

Screen Name: Work Order
Issue: A “Cancel WO” radio button has been added to the Work Order screen to indicate when a work order is canceled.
Resolution: The new radio button allows users to easily mark and identify canceled work orders, improving clarity and record management in the FMS Work Order module.

Screen Name: Bill Booking
Issue: A Milestone dropdown has been added to the Bill Booking screen.
Resolution: The new Milestone dropdown enables users to select relevant milestones during bill booking, ensuring better linkage between billing and project progress tracking.


Refit Monitoring (RMM)

Version: V1.14.36
Release Date: November 2025-11-02
Division: Vizag

Overview

This release focuses on enhancing the usability and accuracy of the Refit Planning and Scheduling features within the Refit Monitoring Module (RMM). Key improvements include new feature development, interface refinements, and several bug fixes to improve data consistency and user experience in the Gantt chart and activity scheduling views.

Enhancements

Screen Name: Refit Plan
Issue: Duration input box size increased for better visibility and ease of data entry.
Resolution: The duration input field has been resized to improve user accessibility and readability during activity planning.

New Requirement
Screen Name: Refit Plan
Issue: When hovering the mouse over the Gantt chart, the system should display the exact MPB (Manpower Balance) booking percentage.Added a new feature to display the MPB (Manpower Balance Percentage) when users hover over activities in the Gantt chart.

Bug Fixes

Screen Name: Refit Plan
Issue: When an activity’s start date matched its parent activity’s start date, the system incorrectly created and displayed a predecessor relationship between the two activities in the Gantt chart.
Resolution: Logic corrected to ensure predecessor relationships are only displayed when explicitly defined by the user.

Screen Name: Refit Plan
Issue: When dates were modified using the drag bar in the Gantt chart, the activity sequence changed unexpectedly.
Resolution: Bug fixed to maintain correct activity sequence after date adjustments using drag functionality.

New Feature

Screen Name: Refit Activity Schedule
Issue: Refit Activity Schedule screen has been developed.
Resolution: A new Refit Activity Schedule screen has been introduced to streamline activity tracking and scheduling within the module.

BTMS

Version: V1.14.37
Release Date: November 2025-11-03
Division: Vizag

Overview
This release improves the alignment of the ship on the Jetty Overview screen. 

Enhancement

Screen Name: Jetty Overview

Alignment of the ship on the screen has been corrected to match according the jetty position.

Dry Dock

Version: V1.14.37
Release Date: November 2025-11-03
Division: Vizag

Overview
This release enhances the screen functionality by adding a new field, Dry Dock Position, which enables users to view the position details.

Enhancement

Screen Name: Dry Dock Undock

Added a new field named Dry Dock Position (Disabled), allowing users to view the entered details of the dry dock position in the Dry Dock Plan.

Refit Planning Program (RPP)

Version: V1.14.37
Release Date: 2025-11-03
Division: Mumbai

Screen Name: Work Order
Issue 1: When a planner created a work order and forwarded it to MPLS or AGM(PL) to add costing details, if the MPLS or AGM(PL) added an additional costing, the data was not being saved.
Resolution: The issue has been resolved. The system now allows MPLS and AGM(PL) users to add multiple costing entries, and the data is saved successfully.

Issue 2: The Edit option was disabled for users A/DGM(P) and GM(R), preventing them from editing the Work Order.
Resolution: The Edit option is now enabled for users A/DGM(P) and GM(R) in the Pending Action – Work Order Transaction dashboard.

Shop Floor Management

Version: V1.14.37
Release Date: 2025-11-03
Division: Mumbai

Reverified: Functionality was already intact; no issues found.
Data is displaying correctly in the Reason column.

Budget Management (BMS)

Version: V1.14.37
Release Date: 03-11-2025
Division: Vizag and Mumbai

Overview

This release (V1.14.37) introduces multiple updates and fixes in the Budget Management System (BMS) module to improve data accuracy, enhance report clarity, and strengthen input validation.
Key changes include updates to the FAC Certificate, Code Head Master, and Pending Milestone Report screens across Vizag and Mumbai divisions.

Bug Fixes
Screen Name: FAC Certificate
Issue: The FAC Certificate screen displayed unnecessary labels (B-C and D-C), which were not required in the certificate layout.
Resolution: The labels (B-C and D-C) have been removed from the FAC Certificate screen as per BA requirement.

Screen Name: Code Head Master
Issue: The Code Head Master screen allowed entry of special characters in code fields, leading to potential data inconsistency.
Resolution: Input validation has been implemented to enter the special characters, ensuring data integrity and consistency across the system.

Screen Name: Pending Milestone Report
Issue: The Pending Milestone Report did not clearly indicate which milestones were pending for completion.
Resolution: The Pending Milestone column now correctly displays only the milestones that are pending, improving clarity and report usefulness.

Enhancement
Screen Name: FAC Certificate
Issue: The Carry Forward Liability value was not properly displayed in the FAC Certificate.
Resolution: The Carry Forward Liability value is now displayed correctly in the third row of the FAC Certificate for better visibility.

Screen Name: FAC Certificate
Issue: The Code Head details were not visible on the FAC Certificate screen.
Resolution: The Code Head is now displayed in the FAC Certificate to ensure comprehensive information representation.

Financial Management (FMS)

Division: Vizag and Mumbai
Version: V1.14.37
Release Date: 03-11-2025


Enhancement
Screen Name: New Proposal
Description: The label for Minor Head Description on the New Proposal screen required correction for both Vizag and Mumbai divisions to maintain uniform terminology.
Resolution: The code head description replaced with Minor Head Description label has been updated on the New Proposal screen.

YAMS

Version: V1.14.38
Release Date: 04-11-2025
Division: Vizag

Overview
This release introduces a Delete option that allows users to remove unnecessary data from the grid.
Screen Name: Pre Dispatch Inspection
Issue: On the Pre-Dispatch Inspection screen, when users added item details in the grid, the Delete button was disabled, preventing them from removing items.
Resolution: The Delete icon is now enabled, allowing users to remove selected items.

Screen Name: Inward Gate Entry
Issue: On the Inward Gate Entry screen, when users added item details in the grid, the Delete button was disabled, preventing them from removing items.
Resolution: The Delete icon is now enabled, allowing users to remove selected items.

Screen Name: Pre-Inspection
Issue: On the Pre-Inspection screen, when users added item details in the grid, the Delete button was disabled, preventing them from removing items.
Resolution: The Delete icon is now enabled, allowing users to remove selected items.

Screen Name: Commissioning Report
Issue: On the Commissioning Report screen, when users added item details in the grid, the Delete button was disabled, preventing them from removing items.
Resolution: The Delete icon is now enabled, allowing users to remove selected items.

Time Keeping (TKS)

Version: V1.14.38
Release Date: 04-11-2025
Division: Vizag

Overview
This release addresses multiple bug fixes across the Daily Freeze and Frozen Report screens. A pop-up has been added to the Daily Freeze screen, and the issue with incorrect duration hours in the Frozen Report has been resolved.

Screen Name: Daily Freeze Screen
Issue: When the user froze a particular date, and then tried to select the same or a previous date, and save the transaction no pop-up message appeared to indicate that the date was already frozen.
Resolution: A pop-up message has now been provided to notify the user when the selected date is already frozen.

Screen Name: Frozen Report
Issue: The generated report was not displaying which date is freezed and which date is not freezed.
Resolution: The report logic has been corrected. It now properly displays frezzed and unfreezed date ensuring in the Frozen report.

Screen Name: Daily Attendance
Screen Name: Daily Attendance
Issue: The employee numbers should be in ascending order.
Resolution: The update has been done. Employee numbers are now in ascending order.

Refit Planning (RPP)

Version: V1.14.38
Release Date: 04-11-2025
Division: Mumbai

Overview

Screen Name: DL Upload

Enhancement

A new column labeled Remark has been added to the grid on the DL Upload screen. This column displays the return remarks provided by the planner.

The CMMS_SDTRS_Ref column value from the database has now been implemented as the Ship Code for all ships in the Excel file.


BMS 

Version: V1.14.37
Release Date: 04-11-2025
Division: Vizag and Mumbai

Enhancment

Screen Name: Minor Head Master
The validation for the Minor Head field has been updated. Only alphanumeric and special characters are now allowed during Minor Head creation.

Screen Name: Code Head Master
For the Code Head field, only special characters and numbers are now allowed.

Bug Fixes

Screen Name: Approve FAC by MFS
Issue: When the user clicked the Create button from the right-side toolbar without selecting any grid data, the transaction was still opening.
Resolution: The issue has been fixed. The transaction will now open only after selecting the required grid data.

Screen Name: Make FAC for BC
Issue: When the user clicked the Create button from the right-side toolbar without selecting any grid data, the transaction was still opening.
Resolution: The issue has been fixed. The transaction will now open only after selecting the required grid data.

FMS

Version: V1.14.37
Release Date: 04-11-2025
Division: Vizag and Mumbai

Bug Fixes

Screen Name: Document Viewer
Issue: In the viewer, documents uploaded under Notings were appearing against the documents of Activities.
Resolution: The mapping issue has been fixed. Documents uploaded under Notings now appear correctly in their respective section and are no longer displayed under Activities.

Screen Name: Fund Commitment
Only data related to financial files that have been routed will now be fetched and displayed on the screen.

BTMS

Version: V1.14.37
Release Date: 03-11-2025

Screen Name: Jetty Overview
Issue: After a movement order was created, the ships were not visible on the Jetty Overview map.
Resolution: The issue has been fixed. Ships now appear correctly on the map after a movement order is created.


SWM – PAY

Version: V1.14.38
Release Date: 04-11-2025
Division: Vizag

Overview

This release introduces a new Hold Pay Process feature and addresses key issues identified in the Non-Industrial Pay Summary screen.

Bug Fix

Screen Name: Non-Industrial Pay Summary
Issue: In the Retired Paybill Report (PDF) generated from the Non-Industrial Pay Summary screen:
The report heading incorrectly displayed the month as “01-Sep-2025” instead of “Sep-2025.”
The retirement count was not being reflected in the report output.

Resolution: The heading format has been corrected to display the month as “Sep-2025.” The issue with the missing retirement count has been fixed

New Feature
Screen Name: Hold Pay Process
Description: A new Hold Pay Process screen has been developed to allow users to generate records in Insert Mode, enabling better control over pay hold operations.
Resolution: Implemented the new screen with insert functionality to support the creation of hold pay records.


Yard Utility (YUS)
Version: V1.14.38
Release Date: 04-11-2025
Division: Vizag

Bug Fix

Screen Name: Service Allocation
Description: In the Service Allocation Transaction screen, the following issues were identified:
The Request Date column on the landing page was displaying an incorrect date or using an invalid format (YYYY-MM-DD).
The From Time and To Time fields were displayed in milliseconds instead of the proper time format.

Resolution: The Request Date column now displays the date in the correct and standardized format.
The From Time and To Time fields have been updated to display accurate time values in the appropriate format.


YAM 
Version: V1.14.39
Release Date: 05-11-2025
Division: Vizag

Overview

This release address bug fixes, including an issue where transactions were not being saved correctly on certain screens.

Screen Name: Pre Dispatch Inspection

Issue: The system displayed a “None Type” error, preventing the transaction from being saved successfully during the pre-dispatch inspection process.
Resolution: The error handling has been corrected, and transactions now save properly without triggering the “None Type” error.

Update:
UI Change – When the user clicks the Add button, the text now displays as "Add Details".

Refit Planning (RPP)

Version: V1.14.39
Release Date: 05-11-2025
Division: Mumbai

Overview

This release includes two bug fixes across the PRM Remarks and Work Order – Refit screens, resolving issues with disabled buttons in the PRM Remarks grid view and displaying the pending status from user correctly in the Work Order – Refit grid view

Screen Name: PRM Remarks”

Issue: In the grid view, the ‘Add Remarks’ button remained active even after the DL was finalized. Only the ‘Quick Update’ button was correctly disabled.
Resolution: Updated the functionality so that both buttons are disabled once the DL is finalized.

Screen Name: Work Order - Refit
Issue: In the planner login, the Work Order (WO) Pending Status and Pending From details were not displayed in the WO view grid.
Resolution: The issue has been fixed. The Pending Status of Pending From details are now displayed correctly in the WO view grid for the respective planner login.

Personnel

Version: V1.14.39
Release Date: 05-11-2025
Division: Mumbai

Screen Name: Civil Establishment Order

Issue: Data for the CE Type drop-down was not fetched dynamically for the option "Fresh Appointment with Dockyard".
Resolution: The issue has been resolved data now loads correctly for this option.

Yard Utility (YUS)

Version: V1.14.39
Release Date: 05-11-2025
Divisions: Vizag and Mumbai

Overview

This release focuses on resolving multiple issues identified in the Service Allocation and Service Requisition screens within the Yard Utility (YUS) module.
The fixes ensure accurate data population, proper display of dropdown values, and correct rendering of transaction details in the dashboard.

Bug Fix
Screen Name: Service Allocation

Issue: The WI Number field was not being populated in update mode and remained blank.

Resolution: Updated the backend logic to ensure the WI Number field auto-populates correctly during update operations.

Screen Name: Service Requisition

Issue: The Ship field dropdown appeared blank and did not display the list of available ships.

Resolution: Fixed the data-binding logic for the dropdown list to ensure all available ships are now displayed correctly.

Enhancement
Screen Name: Service Requisition

Issue: When clicking the Sub Transaction grid on the dashboard, the Service Request Feedback option appeared, but the Transaction Date was displayed incorrectly.

Resolution: Corrected the date-mapping function to ensure the Transaction Date now displays in the proper format and reflects accurate values.

SWM – PAY

Version: V1.14.39
Release Date: 05-11-2025
Divisions: Vizag and Mumbai

Bug Fix
Screen Name: Earnings Deductions

Issue: In the Earnings Deductions transaction, the data calculation was incorrect in update mode. Additionally, the toggle label Official Recovery was misspelled as Offical Recovery.

Resolution: The calculation logic has been corrected to ensure accurate computation during update operations. The toggle label has been updated to display the correct spelling Official Recovery.

Financial Management System (FMS)

Version: V1.14.39
Release Date: 06-11-2025
Division: Mumbai

Bug Fix
Screen Name: Initiate Proposal Screen

Issue: After refreshing the screen, the Refit Type field was not visible to users.

Resolution: The refresh logic has been corrected to ensure that the Refit Type field is consistently displayed after the page reloads.


Manpower Booking (MPB)

Version: V1.14.40
Release Date: 06-11-2025
Division: Vizag

Screen Name: OT Booking
Issue: Issue: In multi-selection drop-down, the employee type Civilian Officer should not appear.
Resolution: The logic has been corrected to ensure that Civilian Officer no longer appears in the multi-selection list.

YAM

Version: V1.14.40
Release Date: 06-11-2025
Division: Vizag

Screen Name: Inward Gate Entry

Update:
UI Change – When the user clicks the Add button, the text now displays as "Add Details".

Screen Name: Pre-Inspection

Update:
UI Change – When the user clicks the Add button, the text now displays as "Add Details".

OPRA

Version: V1.14.40
Release Date: 06-11-2025
Division: Mumbai

Screen Name: PRM Remarks

Enhancement
Update 1: In Quick Update, the field “Proposed COSM Remarks” has been replaced with “Proposed MPC Remarks.”

Update 2: In Quick Update, the field “HNQC” has been replaced with “Cmd. HQ Remarks.”

Refit Planning (RPP)

Version: V1.14.40
Release Date: 06-11-2025
Division: Mumbai

New feature Requiremnt
Screen Name: Work Instruction 
Update: The system has been updated to display the latest approved EMD, PSD, and PCD values in the Work Instruction, based on the most recent approved CRF request.

Screen Name: PRM Remark
Issue: Users were able to delete records even after PRM or Center remarks were provided, which should not have been allowed.
Resolution: The system has been updated to restrict deletion once PRM or Center remarks are entered.

Shop Floor Management (SFM)

Version: V1.14.40
Release Date: 06-11-2025
Division: Mumbai

New Feature Requirement
Screen Name: CRF Request 
The The system has been updated to ensure that the latest Revised EMD, Date Proposed, and Reason values are now displayed in grid view column.

Financial Managment (FMS)

Version: V1.14.40
Release Date: 06-11-2025
Division: Vizag

Screen Name: Financial Activities
The functionality of file recall has been provided allow user to recall the cancelled file.

Screen Name:  Financial Activities
The functionality of file freeze has been proivded allow user to view in view mode restrict the further activity.


Budget Managment (BMS)

Version: V1.14.40
Release Date: 06-11-2025
Division: Vizag

Screen Name: Pending Milestone Report
Update: The export functionality has been provided on the screen to enable users to download the report excel format for further analysis.

RMM 

Version: V1.14.40
Release Date: 06-11-2025
Division: Vizag

Screen Name: Refit Repair Mointoring
Issue: The system was not automatically updating parent and root parent activity dates when the date of a child activity was modified. As a result, related successor activities were not adjusting based on the revised parent dates.
Resolution: The logic has been updated to ensure that when a child activity date is modified, the corresponding parent, root parent, and related successor activities are automatically updated to reflect the change.

SWM – PAY

Version: V1.14.40
Release Date: 06-11-2025
Divisions: Vizag, Mumbai

Overview

This release includes functional enhancements, user interface corrections, and report accuracy improvements across multiple screens in the SWM – PAY module. The updates address user experience issues, data display inconsistencies, and introduce new API integrations for optimized performance and data management.

Enhancement

Divisions: Vizag and Mumbai
Screen Name: Pay Process
Issue: The “Created Date” field displayed both date and time.
Resolution: Updated the field configuration to display only the date.

Screen Name: Earnings Deductions
Issue: Implemented new API integrations and added server-side pagination to improve performance and data handling in the Earnings Deductions Transaction screen.
Resolution: The system now uses optimized API endpoints and supports server-side pagination to enhance data retrieval efficiency.

Division: Vizag

Screen Name: DA Master
Issue: Users were able to save records for dates that were already saved without receiving a warning.
Resolution: A popup message now appears to notify users when they attempt to save a record for a date that already exists.

Screen Name: Group-wise Pay OT Report
Issue: The grid displayed correct data, but the PDF print and detailed PDF report contained incorrect data.
Resolution: The PDF reports now accurately reflect the data displayed in the grid.

Screen Name: Payroll Report

Issue 1: Additional heads in the Paybill were not included in the total of the page-wise details.
Resolution: Updated the report logic to include all salary heads in the total calculation.

Issue 2: The NPS_Govt credit entry appeared twice, with one instance showing correctly below the HRA amount.
Resolution: Removed the duplicate entry so that only the correct NPS_Govt amount is displayed.

Issue 3: The NPS_Govt entry was missing from the debit side of the report.
Resolution: The missing NPS_Govt entry is now displayed correctly under the debit section.

Issue 4: Missing paybill number and year details in front of the File No. field.
Resolution: The report now includes Paybill Number and Year details next to the File No. field.

Issue 5: Required additional columns were missing from the report.
Resolution: Added the following columns to the report:

Matrix Level

Amt Adv

Refund No.

Govt Cont NPS

Yard Utility (YUS)

Version: V1.14.40
Release Date: 06-11-2025
Divisions: Vizag and Mumbai

Enhancement
Screen Name: Service Requisition
Issue: The calendar-clock icon was unresponsive when users attempted to select it for date and time input.
Resolution: The issue has been resolved. The calendar-clock icon is now fully functional and responds correctly when selected, allowing users to choose date and time values without error.


Refit Mointoring (RMM)

Version: V1.14.41
Release Date: 07-11-2025
Divisions: Vizag

Screen Name: Refit Repair Mointoring
Issue: The system was not automatically updating parent and root parent activity dates when the date of a child activity was modified. As a result, related successor activities were not adjusting based on the revised parent dates.
Resolution: The logic has been updated to ensure that when a child activity date is modified, the corresponding parent, root parent, and related successor activities are automatically updated to reflect the change.

BTMS

Version: V1.14.41
Release Date: 07-11-2025
Divisions: Vizag

Enhancements

Screen Name: Movement Plan

A new field, Bollard, has been added to the screen.

Screen Name: Movement Order

A new field, Bollard, has been added to the screen.

The value entered in the Bollard field in the Movement Plan screen is now fetched into the Movement Order screen.

Screen Name: Movement Status Report

A new PDF button has been added to the screen to allow users to download report data.

Screen Name: Movement Order

The field label Actual Name has been renamed to Movement Commence Time.

Dry Dock 

Version: V1.14.41
Release Date: 07-11-2025
Divisions: Vizag

Screen Name: Dry Dock planning
Issue: The system was displaying inactive ships and those without Refit or Operational orders under the Ship/Submarine options.
Resolution: The logic has been updated to ensure that only active ships with Refit or Operational orders are displayed under the Ship/Submarine options.

e-Seva

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Vizag


Screen Name: Bio-Data

Update: The system has been enhanced to allow users to enter future dates in the Due Date field.

Screen Name: Report Nominal Roll

Update: The Rank field has been updated with multi-selection functionality, enabling users to select multiple ranks simultaneously.


QCMS

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Mumbai

Screen Name: QC Level

Enhancement:

A new provision has been introduced for the QC Level and Raise QC Request screens.
Previously, Work Instructions (WI) were linked and redirected for QC based on the Defect Class.
This enhancement modifies the linking process to be based on the Center, improving accuracy and routing efficiency.

Enhancement Details:

Provision added to link DL Class to Center.

Based on the Center–DL Class linkage, the Work Instruction (WI) will now be forwarded to the respective QC Manager.

Once a WI is assigned to a QC Manager based on Center–Class linkage, the subsequent routing process to other defect classes will continue as per the existing process.

The same functionality applies when raising a QC Request against a WI.

Screen Name: Raise QC Request

Enhancement:

A new provision has been introduced for the Raise QC Request screen, aligning it with the QC Level functionality.
Previously, WI routing was handled based on the Defect Class; it is now handled based on the Center.

Enhancement Details:

Provision added to link DL Class to Center.

Based on the Center–DL Class linkage, the Work Instruction (WI) will be forwarded to the respective QC Manager.

Once WI is assigned to the QC Manager based on Center–Class linkage, the further routing to other defect classes remains as per the existing process.

This functionality also applies when raising a QC Request against a WI.


Shop Floor Management

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Mumbai

Screen Name: P1/O2 Received

Issue: In the Assistance WI tab, only Approved data was being displayed. The Pending data was not visible.
Resolution: The issue has been resolved. The Assistance WI tab now displays both Approved and Pending data.

Screen Name: P1 Raise

Update: Two new fields — Request Start Date and Request End Date — have been added. Additionally, the PSD and PCD fields from the parent WI are now displayed as disabled (read-only) fields for reference.


QAM

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Vizag

Screen Name: Lead Author Course
Update: The Type of Course dropdown has been updated to display data based on the selected Internal and External Audit Type.

Budget Management (BMS)

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Vizag

Screen Name: Budget Estimation

Update: Integration between the BMS (Budget Management System) and FMS (Financial Management System) modules has been completed to enable seamless data exchange and process alignment.

Financial Management (FMS)

Version: V1.14.42
Release Date: 10-11-2025
Divisions: Vizag and Mumbai

Issue: The Non-Ship field was not being auto-selected under the Ship Name dropdown when NON-SHIP was selected as the Ship Type.	
Resolution: The system now ensures that the Non-Ship field is not auto-selected when the Ship Type is set to NON-SHIP.
	
The database mapping has been updated. The Minor Head Description field is linked to its corresponding Code Head Long Name column in the database.


OPDEF

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Mumbai

This release includes enhancements and issue resolutions across multiple WI screens. The MC No. and WC No. fields now display full names instead of location codes. A confirmation pop-up has been introduced during WI Closure actions to improve user validation. Additionally, Release WI and Released WI tabs have been added to the OPDEF Release WI screen for better navigation and consistency with the RA-WI Release screen.

Screen Name: OPDEF Release WI

Issue:
The MC No. and WC No. fields on the screen displayed location codes instead of full names. The same issue was also present in the WI History tab.

Resolution:
The fields now display full names instead of location codes, including in the WI History tab.

Enhancement:
Two tabs "Release WI" and "Released WI" have been added to the grid OPDEF Release WI screen, similar to the tabs available in the RA-WI Release screen.

Screen Name: OPDEF WI Closure

Issue:
The MC No. and WC No. fields on the screen displayed location codes instead of full names.

Resolution:
The fields now display full names instead of location codes.

Update:
A confirmation pop-up has been added after clicking the WI Closure button.

Screen Name: RA WI Closure

Issue:
The MC No. and WC No. fields on the screen displayed location codes instead of full names.

Resolution:
The fields now display full names instead of location codes.

Update:
A confirmation pop-up has been added after clicking the WI Closure button.

TY Duty

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Mumbai

Overview

This release resolves multiple issues across TY Duty screens where data in the Select Proposal pop-up was not displaying. The pop-up now functions as expected across all affected modules, and proposal data retrieval issues have been fixed in the Request for Advance screen.

Screen Name: Request for Advance

Issue: Data was not displaying in the Select Proposal pop-up.
Resolution: The Select Proposal pop-up now displays data correctly.

Issue: The selected proposal data was not being fetched.
Resolution: The issue has been fixed; the selected proposal data is now fetched correctly.

Screen Name: MRO TY Duty

Issue: Data was not displaying in the Select Proposal pop-up.
Resolution: The Select Proposal pop-up now displays data correctly.

Screen Name: TY Duty Claim Application

Issue: Data was not displaying in the Select Proposal pop-up.
Resolution: The Select Proposal pop-up now displays data correctly.

Screen Name: TY Duty Status

Issue: Data was not displaying in the Select Proposal pop-up.
Resolution: The Select Proposal pop-up now displays data correctly.

Screen Name: Advance CDA Approval

Issue: Data was not displaying in the Select Proposal pop-up.
Resolution: The Select Proposal pop-up now displays data correctly.

Leave

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Mumbai

Overview
This update resolves an issue on the Apply Leave dashboard where transaction data was not displaying. The dashboard now correctly shows all relevant transaction details.

Screen Name: Apply Leave

Issue: Transaction data was not displaying on the Apply Leave dashboard.
Resolution: The issue has been resolved, and transaction data now displays correctly.


BTMS

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Mumbai

Overview:
This release includes an enhancement in the Movement Order screen to improve data capture and tracking.

Screen Name: Movement Order

Enhancement:
Two new fields — Movement Completion Time and Ship Pendant No. — have been added for user input.

Quartering

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Mumbai

Overview:
This update includes changes to the Accommodation Preference drop-down values across relevant Quartering screens for improved accuracy and consistency.

Screen Name: New Quarter Application

Update:
The Accommodation Preference drop-down values have been updated.

Screen Name: Application for Change

Update:
The Accommodation Preference drop-down values have been updated.

Financial Management (FMS)

Version: V1.14.44
Release Date: 12-11-2025
Divisions: Vizag and Mumbai

Overview

This release introduces functional enhancements and issue resolutions across the Financial Management module for the Vizag and Mumbai divisions. The update focuses on improving visibility, user accessibility, and operational efficiency within the Financial Activities, Sanction, and Work Order screens.

Division: Mumbai
Bug Fix
Screen Name: Financial Activities
Issue: File details were not displaying in View mode.
Resolution: The issue has been corrected, and file details now display accurately in View mode.

Enhancement
Division: Vizag
Screen Name: Sanction
Issue: Provision for Sanction Amendment was not available.
Resolution: A new Sanction Amendment provision has been introduced to enable updates and modifications to existing sanctions.

Enhancement
Division: Vizag
Screen Name: Work Order

Issue: Provision for Work Order Amendment was not available.
Resolution: A new Work Order Amendment provision has been implemented to allow modifications to issued work orders.

SWM – PAY

Version: V1.14.44
Release Date: 12-11-2025
Division: Vizag

Overview

This release focuses on improving the functionality and stability of the SWM – PAY module. Enhancements include improved data visibility and download features in the Supplementary Salary Process screen.
Bug fixes address issues related to button behavior and calculation accuracy in the Amend Pay Process and Payroll Report screens.

Enhancements
Screen Name: Supplementary Salary Process

Issue: A new “Add” button was required in the Supplementary screen to facilitate monthly Excel sheet uploads and downloads.

Details: The Excel sheet can now be added on a monthly basis, and the download functionality is operational.

Downloaded data will include:
Employees whose Basic VII CPC is not active for the selected month.
Employees whose Pay Group is not mapped for the selected month in VII CPC (OP_ID – 7830).

Resolution: A new “Add” button and download functionality have been successfully implemented, providing accurate employee data based on VII CPC mapping and activity.

Bug Fixes
Screen Name: Amend Pay Process

Issue: When data was opened in the Dashboard View Grid, all action buttons were expected to be disabled. However, the Save button remained enabled and functional.

Resolution: The issue has been fixed. The Save button is now correctly disabled when data is viewed in the dashboard grid.

Screen Name: Payroll Report (Page Debit Total Report PDF)
Issue: The Net Pay calculation was not visible in the Page Debit Total Report PDF.

Resolution: The Net Pay field has been restored and now displays correctly in the report.

Screen Name: Payroll Report (Paybill Report PDF)

Issue: The total amount column was displaying a value of 0.0 instead of the sum of all page-wise values.

Resolution: The total amount calculation logic has been corrected. The report now displays accurate column totals across all pages.

Screen Name: Payroll Report (GPF Schedule Report PDF)

Issue: The following columns were added but their corresponding values were not displayed:

Matrix Level

Amt Adv

Govt Cont NPS

Resolution: Data mapping for the above columns has been corrected. The corresponding values now display properly in the GPF Schedule Report PDF.

Screen Name: Raise OPDEF

Update (New Requirement):
Previously, the Center Name drop-down displayed values based on the center details. It has now been updated to display the Center Name based on the selected department.







e-Seva

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Vizag

Overview
This release includes key fixes and enhancements across the Bio Data and Bio Data Report screens. The Status filter and footer count issues in the Bio Data screen have been resolved, ensuring accurate record display.
Additionally, the Bio Data Report has been improved with the inclusion of the Nominal Roll Name column in the Excel output.

Screen Name: Bio Data
Issue: 
The Status filter was not functioning as expected.
The footer count was not displaying accurately.
Resolution: The Status filter has been corrected and is now fully functional.
The footer count has been updated to display the accurate number of records based on the applied filters.

Screen Name: Bio Data Report
Update:
The Nominal Roll Name column has been added to the Excel report.


TY Duty

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Mumbai

Overview
This release include an improved Employee ID pop-up with pagination in Request for Advance, and non-editable Start Date and Time fields after approval in TY Duty Proposal.

Screen Name: Request for Advance
Update:
The Employee ID pop-up has been updated, and pagination has been added.

Screen Name: TY Duty Proposal
Update:
After approval, the Start Date and Time fields at the bottom of the grid have been updated to be non-editable.

Leave

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Mumbai

Overview
This release includes bug fixes across the Apply Leave screen, including corrections to the actual leave count and handling of cases where no leaves are assigned.

Bug fixes

Screen Name: Apply Leave
Issue 1: The actual count of applied leaves was not displaying correctly.
Resolution: The issue has been fixed, and the applied leave count now displays correctly.

Issue 2: When no leaves were assigned to the user, the Balance field still displayed a value of 1.
Resolution: The issue has been fixed, and the Balance now correctly shows 0 when no leaves are assigned.

Refit Planning (RRP)

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Mumbai

Overview

This release includes enhancements to the Work Order creation process, ensuring PSD and PCD values are correctly saved to revised fields. Additionally, a backend issue related to storing COSM role and employee details has been resolved.

Enhancment

Screen Name: Work Order

Update:
When creating a WI, the selected PSD and PCD values are now saved to the WI Revised Start Date and Revised PCD fields in the backend.

Bug Fixes
Screen Name: Work Order

Issue:
While creating a Work Order (WO), selecting COSM did not save the corresponding COSM_Role_cd and COSM_emp_code in the WO_HRD table in the backend.

Resolution:
The issue has been fixed, and the correct COSM role and employee code are now stored in the backend as expected

Financial Management (FMS)

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Vizag

Overview

This release includes bug fixes and functional improvements across Document Viewer, Transaction Dashboard, and Work Order modules.

Bug Fix
Screen Name: Document Viewer

Issue: Incorrect document hyperlinks and sequence were displayed in the Document Viewer.
Resolution: Corrected the hyperlink mapping and restored the proper document sequence.

Screen Name: Transaction Dashboard

Issue: Files saved for new proposals were not appearing under the Draft tab.
Resolution: Updated the save logic to ensure all newly saved proposal files correctly display in the Draft tab.

Enhancement
Screen Name: Work Order

Issue: No message was displayed when a user attempted to save a Work Order without saving the Sanction Order.
Resolution: Added a validation message prompting users to save the Sanction Order before proceeding work order.

SWM – PAY

Version: V1.14.45
Release Date: 13-11-2025
Divisions: Vizag

Overview

This release introduces UI enhancements and improved data filtering capabilities within the Earnings Deductions module.

Enhancement
Screen Name: Earnings Deductions

Issue: Replaced the existing Type dropdown with a combogrid to improve selection efficiency and search capability.
Resolution: Integrated the combogrid component and updated the UI to support advanced search and selection.

Screen Name: Earnings Deductions

Issue: Implemented an Effective Month filter in the Get Employee API to fetch employee data based on the selected month.
Resolution: Updated the API logic to apply the Effective Month filter and return accurate month-wise employee data.





QCMS 

Version: V1.14.46
Release Date: 14-11-2025
Division: Mumbai

Screen Name: IIR
Issue: When the current stage is not equal to total inspection stage, screen must not allow to take 'QC cleared and Job completed'.
Resolution: A validation has been added to prevent users from selecting “QC Cleared” and “Job Completed” when the current stage does not match the total inspection stage.


Personnel

Version: V1.14.46
Release Date: 14-11-2025
Division: Mumbai

Enhancement

Screen Name: Annual Increment

Issue:
When a transaction is approved, the data should be reflected in the VII CPC accordion of the Employee Master.

Resolution:
The approved Annual Increment data now correctly reflects in the VII CPC accordion of the Employee Master.

Yard Utility (YUS)

Version: V1.14.46
Release Date: 14-11-2025
Divisions: Vizag and Mumbai

Overview

This release includes usability improvements and data-consistency corrections in the Service Requisition and Service Allocation screens to ensure accurate default values and standardized status labels across dashboards and UI components.

Enhancement
Screen Name: Service Requisition

Issue: The Ship Role linkage did not correctly default the Ship Name. The expected behavior is:

The Ship Name should default to the ship associated with the logged-in user.

If the query returns a single ship, that value should be set as default but remain editable.

If no data is returned, the Ship Name should default to Non_Ship, also remaining editable.

Resolution

The default Ship Name logic has been corrected to follow the above rules, ensuring consistent and accurate pre-population of values while preserving user editability.

Screen Name: Service Allocation

Issue: The status values displayed in the Dashboard cards, Transaction Stage dropdown (Confirmation Pop-Up), and Status dropdown (Service Allocation UI) were inconsistent with the Status list in the Service Request Export UI.
All components should follow this standardized set of statuses:

New

Available

Allocation Completed

Will be Planned

Rescheduled

Under Maintenance

Not Available

Additionally, Transaction Dashboard (Tran Dash) cards must use the same labels for consistency.

Resolution

All dropdowns and dashboard cards have been updated to use the unified status list, ensuring consistent terminology across the Service Allocation workflow.

Financial Management (FMS)

Version: V1.14.46
Release Date: 14-11-2025
Divisions: Vizag and Mumbai

Division: Vizag
Screen Name: Routing

Enhancement
Issue: A confirmation message was required to inform the user about the role to which the routing action was forwarded.
Example: “File routed successfully to ‘MCOR’.”

Resolution: A user-facing pop-up message has been implemented to clearly display the target role whenever a routing action is completed.

Bug Fix
Division: Mumbai
Screen Name: Routing

Issue: The routing feature in the Document Viewer page under the Noting section was nonfunctional, resulting in users in the Mumbai division being unable to save data.

Resolution: The routing functionality in the Document Viewer page within the Noting section has been fixed. Users in the Mumbai division can now save data without errors.

SWM – PAY

Version: V1.14.46
Release Date: 14-11-2025
Divisions: Vizag and Mumbai

Bug Fixes

1. Screen Name: Hold Pay Process

Issue:

The record is being saved/approved even when mandatory fields are left blank.

The Employee Type mandatory field is not being validated, allowing the record to be saved without a selected value.

Resolution:

Mandatory-field validation logic has been corrected.

The system will now prevent saving/approving a record if any mandatory field, including Employee Type, is left blank.

Appropriate error messages have been added to guide the user when mandatory data is missing.

2. Division: Vizag

Screen Name: NSO 94 Report

Issue:

The names for PC ADV and ALLCH are missing in the NSO 94 Report (INDUSTRIAL).

These names need to be added and mapped correctly.

Resolution:

Names for PC ADV and ALLCH have been added to the NSO 94 Report.

Data mapping has been corrected to ensure accurate display of both fields.

The report now retrieves and displays the information as expected.

Refit Planning (RPP)

Version: V1.14.46
Release Date: 14-11-2025
Division: Mumbai

Enhancement and Bug Fixes
Screen Name: PRM Remarks
Issue: The user (PRM) was able to give Per Center remarks from the detailed view but not from Quick Update.
Resolution: Per Center remarks can now be added from Quick Update as expected.

Screen Name: PRM Remarks
Issue: Once the DL has been finalized, changes in PRM or Center should not be allowed.
Resolution: A restriction has been implemented to prevent changes to PRM or Center after the DL is finalized.


QCMS 

Version: V1.14.46
Release Date: 14-11-2025
Division: Mumbai

Screen Name: IIR
Issue: When the current stage is not equal to total inspection stage, screen must not allow to take 'QC cleared and Job completed'.
Resolution: A validation has been added to prevent users from selecting “QC Cleared” and “Job Completed” when the current stage does not match the total inspection stage.

SWM - TAX

Version: V1.14.46
Release Date: 14-11-2025
Divisions: Vizag and Mumbai

Enhancement
Screen Name: Voluntary TAX

Issue:

After saving the record, the Transaction Date is not appearing.

Both Transaction ID and Transaction Date should be auto-generated, but this is currently not happening.

Resolution:

Logic has been updated to ensure that Transaction ID and Transaction Date are auto-generated upon saving the record.

The Transaction Date is now correctly displayed after the record is saved.

Backend validations and generation rules for these fields have been aligned with system requirements.


Screen Name: Financial Activities – Transaction Dashboard

UI Update: The column label “Active Y/N” in the grid has been updated to display “YES/NO”.

Screen Name: Financial Activities – Transaction Dashboard

Update: Only active files now appear in the Draft tab. The display logic has been updated to ensure that all relevant file statuses are shown correctly in the Draft tab.

Division: Vizag & Mumbai
Screen Name: New Proposal

Update: The “Type of Purchase” value “GOOD” has been changed to “GOODS".


Update: Only active files now appear in the Draft tab. The display logic has been updated to ensure that only active file statuses are shown in the Draft tab



Time Keeping (TKS)

Version: V1.14.48
Release Date: 14-11-2025
Divisions: Vizag and Mumbai

Screen Name: Allocation of Man power
Update: Manpower booking is allowed for past dates of the current month.

e-Seva


Version: V1.14.48
Release Date: 18-11-2025
Division: Vizag

Enhancement
Screen Name: Bio- Data Report
Enhancement
Screen Name: Bio-Data Report

Company Code and Division Code have been removed.
Rank Code has been replaced with Rank Name.
Employee Code has been replaced with Employee ID


Personnel

Version: V1.14.48
Release Date: 18-11-2025
Division: Vizag/Mumbai

Bug Fix

Issue: If an Employee Date of Birth is 1st of any month then His / Her Date of Retirement should previous month Last Date.
Resolution: The system logic has been updated to ensure that employees born on the 1st of any month now have their retirement date set to the last day of the previous month.

Enhancement

Update: Field Names

In Appointment Details, the field name “Recruited by SRC” has been changed to “Recruited by SRO.”

In Appointment Details, the field name “Ref. Auth Date” has been changed to “Authority Date.”

In Appointment Details, the field name “Ref. Auth No” has been changed to “Authority No.”


Financial Management (FMS)

Version: V1.14.48
Release Date: 18-11-2025
Divisions: Vizag and Mumbai

Overview
This release includes vendor-filter correction in the Sanction Order screen for Vizag Division and server-side pagination enhancements in the Transaction Dashboard for Mumbai Division.

Enhancements & Fixes
Division: Vizag

Screen Name: Sanction Order
Issue: The vendor filter incorrectly included all registered vendors. It has now been corrected to fetch only vendors with the status “Approved.”

Resolution: Updated filtration logic to ensure that only Approved vendors are displayed.

Division: Mumbai

Screen Name: Transaction Dashboard

Issue: Server-side pagination was required for improved performance in the Draft and View tabs.

Resolution: Implemented server-side pagination to optimize loading and navigation across the relevant tabs.


Yard Utility (YUS)

Version: V1.14.48
Release Date: 18-11-2025
Divisions: Vizag

Enhancement
Screen Name: Service Requisition

Issue: The requisition mode–based dynamic fields were not functioning because the required database records were not being generated. As a result:

When Signal was selected, the system did not display the text box for entering the Signal DTG number.

When Fax was selected, the system did not prompt the user to upload fax details.

When General was selected, the system incorrectly expected additional input.

Resolution: Corrected the underlying data creation process and updated the UI logic to ensure that:

The Signal DTG input box appears when the Signal mode is selected.

The Fax upload prompt is displayed when Fax mode is selected.

No additional fields appear when General mode is selected.

SWM - PAY

Version: V1.14.48
Release Date: 18-11-2025
Divisions: Vizag

Enhancement
Screen Name: Non-Industrial Pay Summary Report

Issue: Table alignment displayed incorrectly before downloading or viewing records. The data appeared outside the defined table boundaries, causing layout distortion.

Resolution: Corrected the table layout and alignment logic to ensure that all records render properly within table boundaries prior to download or on-screen viewing.

QCMS

Version: V1.14.49
Release Date: 19-11-2025
Divisions: Mumbai

Overview
In this release, we have made a few improvements to enhance the user experience. The Route To option is now disabled when a QC Level is assigned. In the Instant Inspection Report, the field name “Supplied By” has been updated to “Spare Supplied By” for clearer information. Also, the Assign QC Inspector pop-up will now show 50 records by default.

Screen Name: QC Level

Issue: When the QC Level was assigned to the work instruction, the Route To option was still enabled.
Resolution: The issue has been fixed. The Route To option is now disabled when a QC Level is assigned.

Screen Name: Instant Inspection Report

The field name "Supplied By" has been replaced with "Spare Supplied By", allowing the user to view details of the spare supplied.

Screen Name: Assign QC Inspector

Issue: The Assign Inspector pop-up did not display 50 records by default.
Resolution: The pop-up now displays 50 records by default.

Issue: The Assign Inspector pop-up was displaying 10 records by default; it should display 50 records by default.
Resolution: The pop-up now displays 50 records by default when opened.

Financial Management (FMS)

Version: V1.14.49
Release Date: 19-11-2025 
Divisions: Mumbai

Overview

This release introduces usability improvements in the Financial Activities screen and resolves an unnecessary error message displayed during activity saving.

Enhancements
Screen: Financial Activities

Issue: Saved activities were not previously marked as completed, making it difficult for users to identify which tasks were already done.

Resolution: Activities that have been saved are now automatically tick-marked in the activity list, providing clear visual confirmation of completed tasks.

Bug Fixes
Screen: Financial Activities

Issue: An unnecessary error message was displayed when saving activities.
Resolution: The incorrect error has been removed, and the save operation now works without interruptions.

Vendor Management System (VMS)

Version: V1.14.49
Release Date: 19-11-2025 
Divisions: Vizag

Overview

This release includes functional validation of the Vendor Performance Rating workflow and fixes an issue where data was incorrectly displayed after selecting a Work Order.

New Requirement
Screen Name: Vendor Performance Rating

Update: The Create VRF and Generated VRF workflow tabs have been added, and data visibility across both tabs has been reviewed and corrected.
Note: To learn more about creating and generating a VRF, refer to ticket OP_ID–7503.

Bug Fixes
Screen Name: Vendor Performance Rating

Issue: After selecting the WO No., the related data in the Create VRF and Generated VRF tabs did not appear in the grid, and an error message stating “Data not found” was displayed.

Resolution: The “Data not found” issue has been resolved. Data now loads correctly after selecting the Work Order and is properly displayed in the grid.

SWM - PAY
Version: V1.14.49
Release Date: 19-11-2025
Divisions: Vizag

Bug Fixes
Screen: Payroll Report

Issue: The department name was not displayed in the Paybill Report PDF. The corresponding field appeared blank in the generated report.

Resolution: The issue has been corrected. The department name now displays properly in the Paybill Report PDF.

QAM 

Version: V1.14.50
Release Date: 20-11-2025
Division: Mumbai

Overview
This release addresses a bug in the DL Upload feature where password-protected sheets caused an incorrect error. The issue has been fixed, and the correct message now appears.

Bug Fixes

Screen Name: DL Upload
Issue: After uploading the Access DB file, a pop-up error appears "the DL upload was not working for password-protected sheets". It should display error "Invalid Data Sheet Uploaded" instead.
Resolution: The issue has now been fixed, and the system correctly shows the “Invalid Data Sheet Uploaded” erro message when a password-protected sheet is uploaded.



MPB - Allocation of Manpower
MPB - Over Time Booking Industrial Transaction 
MPB - Amend OT Industrial
TKS - OT Finalization
MPB - Over Time Booking Non Industrial



Ajay@7743816300




Yard Utility (YUS)

Version: V1.14.50
Release Date: 20-11-2025
Divisions: Vizag and Mumbai

Overview

This release includes functional fixes and enhancements across the Service Requisition and Service Allocation modules. Updates address data-fetch issues, introduce new file upload capabilities and improve record handling during update operations.

Bug Fix
Screen Name: Service Requisition

Issue: In update mode, the Nature of Work dropdown values were not updating correctly and appeared blank.
Resolution: Corrected the update logic to ensure the Nature of Work field loads the appropriate values during record updates.

Screen Name: Service Requisition

Issue: The Ship Status, Actual Start Time and Actual End Time fields were displaying blank values. After status changes (e.g., “Will be planned – maintenance”), the fields were not fetching data correctly.
Resolution: Updated data retrieval logic to ensure these fields populate accurately after status modification.

Enhancement
Screen Name: Service Requisition & Service Allocation

Issue: A new requirement was introduced to support file upload functionality in both Service Requisition and Service Allocation screens. In the Service Allocation screen, a new action button was required to view the uploaded file name.
Resolution: Added file upload capability to both screens. Implemented a new button in the Service Allocation screen to display the requested file name.

SWM - PAY

Version: V1.14.50
Release Date: 20-11-2025
Divisions: Vizag and Mumbai

Overview

This release includes new feature enhancements and multiple defect fixes across Payroll Reporting, Hold Employee Details and Unhold Pay Process screens to improve data accuracy, usability and API-based list management.

New Requirement
Division: Vizag

Screen Name: Payroll Report

Issue: A need was identified for a dedicated screen to generate UPS Schedule Reports in a structured format.
Resolution: Introduced a new UPS Schedule Report screen that enables users to generate structured PDF reports.

Division: Mumbai
Enhancement

Screen Name:Hold Employee Details Report

Issue: The Employee list displayed on the report screen required API-based handling to ensure accurate data retrieval.
Resolution: Implemented API-driven Employee list management to maintain data consistency.

Screen Name: Unhold Pay Process

Issue: The Employee ID dropdown list was not filtered based on the selected Month field.
Resolution: Applied filter to display only employees relevant to the selected month.

Bug Fix
Screen Name: Unhold Pay Process

Issue: Some data fields were not fetching correctly in view mode.
Resolution: Corrected data-binding issues to ensure accurate information retrieval.

Screen Name: Duplicate Employee Records

Issue: The Employee ID dropdown was showing duplicate employee entries.
Resolution: Removed duplication by applying unique employee validation logic.


QCMS 

Version: V1.14.51
Release Date: 21-11-2025
Divisions: Mumbai

Overview

This release delivers fixes to improve accuracy in Offload status, Work Location display, department-based inspector filtering, and approval status handling.

Bug Fixes and Enhancement

Screen Name: Assign QC Inspector
Issue: 
1. In the Assign QC Inspector grid view, the Offload column displays “Yes” for all WIs by default, even though user set Offload to disabled when creating the WI.
Resolution:  
The Offload column logic has been corrected to reflect the actual Offload status configured during WI creation. It will now display “Yes” or “No” based on the saved WI settings.

Enhancement
Issue: In the Work Location column, display the work location name instead of the number.

Resolution:
The Work Location column mapping has been updated to display the work location name instead of the location number.

Screen Name: Assign QC Inspector
Issue: Display only those QC Inspectors who belong to the same department. For example, the QC Manager of the Hull department should see only the inspectors assigned to the Hull department.
Resolution: Department-based filtering has been applied so QC Managers now see only the inspectors from their own department.

Screen Name: Instant Inspection Report Approve
Issue: In the grid view, display 'Pending for Approval' in the Status column. Currently, it shows 'Approved' even though it has not been approved by the SMQC.
Resolution: The Status column logic has been corrected to reflect the actual approval state. It will now display “Pending for Approval” until the SMQC provides approval.

SWM - PAY
Version: V1.14.51
Release Date: 21-11-2025
Divisions: Vizag and Mumbai

Overview

This release includes UI updates, dropdown corrections, and data improvements across Employee, Loan, and Earnings/Deductions screens to improve accuracy and usability.

Enhancements

Screen Name: New Loan

Issue: The New Loan screen includes additional fields Rate of Interest and Remarks. (OP_ID: 8036)

Resolution: Added the new fields to support detailed loan data entry.

Screen Name: Earnings Deductions

Issue: Updated dropdown values required for Earning/Deduction.

Current: 1. Earning, 2. Deduction

Required:

Official Recoveries

Table Recoveries

Type dropdown in Official and Table Recoveries requires correct data patching. (OP_ID: 8037)

Resolution:

Updated Earning/Deduction dropdown values as specified.

Patched Type dropdown for both Official and Table Recoveries.

Bug Fixes

Screen Name: Hold Employee Details Report

Issue: Employee list in the Employee ID dropdown was not filtered based on the selected Employee Type.

Resolution: Applied filter logic to display only employees matching the chosen Employee Type.

Screen Name: Earnings Deductions

Issue: Certain fields under the Official Recovery toggle switch required removal.

Resolution: Removed the fields as per the updated functional requirement.

Yard Utility (YUS)
Version: V1.14.51
Release Date: 21-11-2025
Divisions: Vizag and Mumbai

Bug Fix

Screen Name: YUS – R: Feedback Report

Issue: The dropdown filters for Ship, Service Group, Request, and Type fields were not functioning as expected.

Resolution: Corrected the filter logic to ensure all dropdown fields return accurate and expected results.

Refit Planning (RPP)

Version: V1.14.52
Release Date: 22-11-2025
Division: Mumbai

Overview
This release of refit planning includes several bug fixes and improvements across DL and Work Order modules. Key updates enhance remark visibility, fix dropdown and validation issues, and improve overall user experience

Bug Fixes

Screen Name: DL – Finalization
Issue: The pagination option on the “View Remarks” screen is not user-friendly. By default, only 5 to 10 remarks are displayed on the screen.
Resolution: The pagination on the “View Remarks” screen has been updated to allow a maximum possible view of approximately 25 count of remarks.

Screen Name: WO – Amendment
Issue: The planner COSM drop-down value display random roles of the COSM.
Resolution: The planner COSM dropdown has been updated to display the complete list of COSM roles.

Enhancment

Screen Name: DL - Center Remarks
Issue: In Quick Update mode the COSM remarks does not display the additional remarks.
Resolution: The issue has been fixed, and additional COSM remarks now display correctly in Quick Update mode.

Screen Name: DL - Center Remarks
Issue: In Quick Update mode Cmd HQ remarks does not display the additional remarks.
Resolution: The issue has been fixed, and additional Cmd HQ. remarks now display correctly in Quick Update mode.

Screen Name: DL - Center Remarks
Issue: In the DL – Center Remarks transaction, the Center column in the grid view displays incorrect values, and the Center, PRM, PRM name to be removed.
Resolution: The Center, PRM and PRM name column has been removed from the grid view.

Issue: The PRM remarks entered for the center are visible in the Add Remarks screen but not visible in Quick Update.
Resolution: The issue has been fixed, and PRM remarks for the center now displays in Quick Update.

Screen Name: DL - Upload
Issue: When a user enters the same defect description for the same equip_sys, they should still be able to upload a DL. Therefore, the unique defect description validation needs to be removed.
Resolution: The unique defect description validation has been removed, allowing users to upload a DL even when the same defect description is entered for the same equip_sys.

Screen Name: Work Order - Costing Tab
Update: The “Total” option has been removed from the selection list in the Work Order – Costing tab, as the system performs the total calculation automatically.

Screen Name: DL - Finalization
Update: The "View Remarks" button has been added to the detailed view of DL – Finalization, allowing users to view the remarks in detailed mode as well.


Screen Name: DL – Assign PRM
Update: The provision to update the COSM remarks for the overall DL disabled in Quick Update is now enabled.

Screen Name: DL - Assign PRM
Update: In Quick Update, the COSM remarks in the DL Assign header disabled, and now it can allow user to edit unless the DL–Assign is finalized.

PIMS

Version: V1.14.53
Release Date: 25-11-2025
Division: Mumbai

Overview

This release updates the Leave Balance Amendment screen by adding a validation rule to the Earned Leave (EL) field.

Screen Name: Leave Balance Ammendment 
Feature: A validation rule has been introduced for the Earned Leave (EL) field. Users can no longer enter a value greater than 330 if a user enters a value above 330, an error message error message is displayed. This ensures data accuracy and compliance with leave policy limits.

Refit Planning (RPP)

Version: V1.14.53
Release Date: 25-11-2025
Division: Mumbai

Overview
This release includes a fix to ensure that remarks marked as “Other” are displayed correctly along with their additional details.

Bug Fixes

Screen Name: DL - Assign PRM
Issue: The grid view displays Other as the provided remark. Any additional remarks associated with Other should also be shown.
Resolution: The grid view has been updated to show Other remark along with the related in additional remark column.

SWM - PAY

Version: V1.14.53
Release Date: 25-11-2025
Divisions: Vizag and Mumbai

Bug Fix
Screen Name: Salary Head Master

Issue: The column-header filters were not functioning correctly in the Salary Head Master screen. Reference: OP_ID – 6830

Resolution: The filter functionality for all column headers has been corrected. Users can now apply filters as expected without errors or unexpected behavior.




BTMS

Version: V1.14.53
Release Date: 26-11-2025
Divisions: Mumbai

Overview
This release updates dashboard column positions, adds edit restrictions in Movement Plan, and fixes planned date visibility issues.

Enhancement

Screen Name: Every transaction dashboard
New Upgrade:
The column positions for the Date and Time fields have been updated in the Pending, View, and Draft tabs on the Transaction Dashboard.

Screen Name: Movement plan
New Feature:
When a Movement Plan transaction is saved, the ‘From Location’ field is disabled for Vizag in edit mode but remains enabled for Mumbai location in edit mode.

Bug Fixes
Screen Name: Movement Status
Issue: The planned date selected on the Movement Status screen was not visible in the grid.
Resolution: The issue has been resolved, and the selected planned date is now displayed correctly in the grid. 

Screen Name: Status COY
Issue: The planned date selected on the Status COY screen was not displaying in the grid.
Resolution: The issue has been fixed, and the planned date is now visible in the grid.

SWM - PAY

Version: V1.14.53
Release Date: 26-11-2025
Divisions: Vizag

Bug Fixes
Screen Name: Add Employees to DV

Issue:
In the Add Emp to DV screen, the Balance column was not calculating correctly. The system was not subtracting the required deduction fields—MRO Amount, ITax Rec, Cess Rec, Prof Tax, GPF/CPF—from the Amount entered for each employee.
As a result, the Balance DV Amount displayed incorrect values (e.g., Amount = 10,000 and Prof Tax = 1,000 should result in Balance = 0, but the system showed 1,000).
Resolution:
Updated the calculation logic to ensure all deduction fields (MRO Amount, ITax Rec, Cess Rec, Prof Tax, GPF/CPF) are correctly subtracted from the Amount column. The Balance DV Amount now reflects the accurate computed value.

Revoke Access, Transfer Ownership, Replicate Permissions, Replace Users 
download: 


TY Duty

Version: V1.14.55
Release Date: 27-11-2025
Divisions: Mumbai

Enhancements

Screen Name: TY Duty Claim Application

After forwarding the claim application to the user, the system now allows generating the print report at the first stage of the approval flow.

Added the employee’s pay level to the Employee Details section of the print report for claims related to temporary duty movement; however, the data is not appearing.

Added a new Vehicle Number field in the local table of the print report and in the Local Journey Details section of the TY Duty Claim Application.

Added a new Kilometer field in the local table of the print report and in the Local Journey Details section of the TY Duty Claim Application.

The Number field and Rate field have been removed from the Food Details section of the TY Duty Claim Application.

Dropdown values have been added for the Journey Mode field. The available values are: Bus, Personal Vehicle, Auto, Other in the Outstation Journey Details grid


Leave

Version: V1.14.55
Release Date: 27-11-2025
Division: Mumbai

Enhancement

Screen Name: Apply Leave

The Leave Type dropdown has been updated to include Compensatory Off, enabling users to apply for compensatory off leave.


Refit Planning (RPP)

Version: V1.14.55
Release Date: 27-11-2025
Division: Mumbai

Screen Name: Work Order

The Work Order flow (Return and Forward) has been checked.

Screen Name: DL – Upload

New validations have been implemented:

DART Number is now enforced to be unique ship-wise.

Defect Number is now enforced to be unique work-order-wise.

The validations for Defect Description and Equipment Code have been removed during defect list upload.

The system now automatically updates the value to “NA” if the Equipment System does not match the Equipment System Master while uploading the defect list.

Similarly, the system now updates the value to “NA” if the Location does not match the Location Master while uploading the defect list.

QCMS

Version: V1.14.55
Release Date: 27-11-2025
Division: Mumbai

Screen Name: Manage QC

Issue:
The Offloading Flow toggle switch for QC WI was not working.

Resolution:
The functionality of the Offloading Flow toggle switch for QC WI has been corrected and is now working as intended

SWM - TAX

Version: V1.14.55
Release Date: 27-11-2025
Divisions: Vizag

Overview

This release includes enhancements and corrections to the Amend Tax Regime screen and API. Updates focus on introducing new financial-year handling, improving employee regime selection logic, modifying database structure, and fixing filter issues.

Enhancements & Fixes
Screen Name: Amend Tax Regime

Issue: Add the new column rgm_fin_yr to erp_swm.amend_tax_regime. Update employee query to reflect the new column structure.

Resolution: Database schema updated with the new column rgm_fin_yr. Employee data retrieval logic modified to correctly use the updated field.

Screen Name: Amend Tax Regime

Issues: Employee list must be fetched from the IT Declaration table if the employee selected the OLD Regime for the chosen financial year (per C/D).

Remove the column tax_UNID from the API.

Restrict employees to one amendment per financial year.

Rename existing column fin_yr to rgm_fin_yr.

Introduce a new column fin_yr to store the session financial year for future reference.

Listing page filters are not functioning.

Resolution:

Employee population logic updated to pull data from IT Declaration based on OLD regime selection.

API modified to exclude the deprecated tax_UNID field.

Validation implemented to prevent more than one amendment within the same financial year.

Column fin_yr renamed to rgm_fin_yr, and a new fin_yr column added for session-year tracking.

Listing page filter defects corrected and fully functional.


Leave

Version: V1.14.56
Release Date: 28-11-2025
Divisions: Vizag


Overview

This release focuses on resolving multiple issues across Leave Management modules. Key improvements include correcting missing employee information in pop-ups, enforcing mandatory document uploads for specific leave types, and ensuring weekly-off logic correctly adapts to shift changes.

Fixes & Enhancements
1. Screen Name: Leave Detail

Bug Fixes

Issue: When the user clicked the Employee ID field to add employee details in the Employee ID pop-up, only the Employee ID appeared—employee information was not displayed.

Resolution: The logic fetching employee details has been corrected. The pop-up now retrieves and displays full employee information as expected.

2. Screen Name: Employee Leave Detail

Bug Fixes

Issue: When the user clicked the Employee ID field in the Employee ID pop-up, only the Employee ID appeared without corresponding employee details.

Resolution: The data-binding issue in the Employee ID pop-up has been fixed. Complete employee information is now loaded and displayed properly.

3. Screen Name: Leave Apply

Bug Fixes

Issue: Sick certificate upload needed to be mandatory for COML leave, and the upload option was not available.

Resolution: The system now enforces mandatory sick-certificate upload for COML leave. The upload field has been enabled and is now visible and functional.

4. Screen Name: Leave Apply

Bug Fixes

Issue: For employees whose weekly off is Monday, CL should accept Monday. However, if the employee’s shift changes, the weekly off should update accordingly—this was not working.

Resolution: Weekly-off validation has been updated to dynamically adapt to shift changes. The system now considers the employee’s current shift to determine the correct weekly off day, while retaining default rules for all other employees.

MHMS

Version: V1.14.56
Release Date: 28-11-2025
Divisions: Vizag

Screen Name: Hospital Master
Bug Fixes

Issue: When adding a new address in the Hospital Master, duplicate address records were being created.

Resolution: The duplicate data creation issue has been resolved by correcting the address-save logic. The system now validates existing entries properly and ensures only a single record is created when adding a new address. 



Dry Dock

Version: V1.14.56
Release Date: 28-11-2025
Divisions: Mumbai and Vizag

Overview 

This release resolves UI alignment issues in the Dry Dock module, ensuring stable and consistent screens when users select multiple ship classes.

Screen Name: Dock Master
Bug Fixes

Issue: When the user selected all options in the Class of Ship dropdown, the UI behaved incorrectly and the screen alignment became distorted.

Resolution: The screen now maintains proper alignment regardless of the number of selected options, ensuring consistent and stable UI behavior



BTMS

Overview 

This release includes improvements to enhance system stability and user experience within BTMS, ensuring smoother operations and more reliable functionality across key workflows.

Version: V1.14.56
Release Date: 28-11-2025
Divisions: Mumbai and Vizag

Screen Name: Jetty Mapping
Bug Fixes

Issue: When the user selected all options in the Class of Ship dropdown, the UI behaved incorrectly, causing screen misalignment.

Resolution: The UI layout handling for the Class of Ship dropdown has been fixed. The screen now remains properly aligned even when all options are selected, ensuring stable and consistent display. 

Syllabus Work Order (SWO) Module


Refit Planning (RPP)

Version: V1.14.57
Release Date: 03-12-2025
Divisions: Vizag

Overview

This release adds Reject and Return options to the Work Order – Refit screen for MPLS, A/DGM(PL), and GM(R) during the Work Order save process.

Enhancement

Screen Name: Work Order – Refit

1. Added “Reject” Option

Enable a Reject action while saving the Work Order at the following user levels login:

MPLS

A/DGM(PL)

GM(R)

2. Added “Return” Option

Enable a Return action while saving the Work Order at the following user levels login:

MPLS

A/DGM(PL)

GM(R)

Syllabus Work Order (SWO)

Version: V1.14.57
Release Date: 03-12-2025
Divisions: Vizag

Overview

Enhancement
Screen Name: SWO – Raise Request Assistance

1. This screen allows Center Users of any department to raise an assistance request to other PRM centers

2. Enables the Center User to view all requests raised by the center under the Pending section, which displays all pending data..

3. Enable the Center User to view all requests raised by the center under the Remarks Given section, which displays the requests for which remarks have been provided by the center.
Note: When remarks are given against a pending request, it moves to the Remarks Given status.

4. Enable the transaction to move to the next transaction screen if the remarks given are DAN or DOSSR; otherwise, it does not proceed to the next flow.

Enhancment 

Screen Name: Finalized Assistance

1. In this screen, finalization of assistance is implemented, and the flow works such that if the remarks are DAN or DOSSR, the transaction comes to this screen in Pending status

2. In this transaction screen, clicking the hyperlink copies the provided remarks into the Final MRR Remarks column.

3. After the user enters the remarks, the transaction moves to the Finalized status filter.


TY Duty

Version: V1.14.57
Release Date: 03-12-2025
Divisions: Mumbai

Overview

This release addresses bug fixes in the TY Duty Proposal and TY Duty Claim Application screens.

Bug Fixes
Screen Name: TY Duty Proposal

Issue: The "Advance and Claim of the TY Duty" link was not visible and remained stuck on the Proposal Page.

Resolution: The issue has been fixed, and the link is now visible and accessible.

Screen Name: TY Duty Claim Application

Issue: The "Advance and Claim of the TY Duty" link was not visible and remained stuck on the Proposal Page.

Resolution: The issue has been fixed, and the link is now visible and accessible.

Enhancement

In the TY Duty Claim application, the selected Journey Date from the “From” field is now displayed in the grid. Previously, this date was set to the Reporting Date. 

Bug Fixes

Screen Name: Request for Advance

Issue: The selection in the "Request for Advance" link was incorrect. Employees should be selected individually, and the amount should be generated accordingly.

Resolution: The selection logic has been corrected to allow individual employee selection, and the amounts are now generated correctly.

Personnel

Version: V1.14.59
Release Date: 11-12-2025
Divisions: Mumbai and Vizag

Overview
This release delivers key enhancements to the Personnel module, introducing a new Employee Deputation Outside screen to manage deputation records with insert, update, and view capabilities. This release also includes several improvements to the Employee Master screen, adding new data fields, refining self-employment logic within family details, and upgrading interface elements for better accuracy and usability.

Screen Name: Employee Deputation Outside
Divisions: Mumbai & Vizag

A new Employee Deputation Outside screen has been introduced in the Personnel module.
This screen provides the following functionalities:

Insert – Add new employee deputation records.

Update – Modify existing deputation details.

View – Retrieve and display deputation information.

Screen Name: Employee Master

Updates & Enhancements

1. Added new field: Yard Join Date Included in the Employee Details section.

2. Added new fields: Self Employed and Joint Declaration in family details section.

Screen Name: Employee Master Report

Added new report.

Screen Name: CEO Transaction
Bug fix
Issue: The CE Type was not being fetched in Update and View modes.
Resolution: The issue has been resolved, and CE Type now loads correctly in both Update and View modes.

Retirement

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai and Vizag

Overview

This release introduces enhancements to the Datasheet screen within the Retirement module. Two new fields Aadhaar Number and Date of Birth (DOB) have been added to the Family grid, enabling users to record and maintain essential personal details more accurately

Screen Name: Datasheet

In the family grid two field with name aadhar number and date of birth (DOB) so, user is able to add the his personnel details.


Leave

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai and Vizag

Overview

This release includes enhancements and bug fixes across multiple leave-related screens, improving usability, data entry flexibility, and reporting accuracy.

Enhancements and Bug Fixes
Screen Name: Leave Card Report 
1. Employee id field is non-mandatory now.

Issue: The year filter option was not appearing on a yearly basis.
Resolution: The issue has been resolved, and the year filter now appears correctly for yearly selection.

Screen Name: Employee Leave Report

1. Emp Id and Emp type, is non-mandatory now.

Bug Fixes

Issue: Employee leave data was not appearing in the report.
Resolution: The issue has been resolved, and the employee leave data now displays correctly in the report.

Screen Name: Apply Leave

1. A validation rule has been added for CCL, requiring a minimum of 5 days.

2. A Reject option has been added to the transaction stage in the confirmation dialog, allowing users to reject the leave application while saving the transaction. 

LTC

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai and Vizag

Overview

This release of the LTC module introduces a print report feature in the LTC Advance Proposal screen, enabling users to generate and print proposals directly from the system.

Screen Name: LTC Advance Proposal 
A print report has been added to the LTC Advance Proposal screen.

TY Duty

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai and Vizag

Overview

This release addresses a bug in the Claim Application screen to improve selection accuracy and prevent multiple proposals from being selected simultaneously.

Bug Fixes
Screen Name: Claim Application

Issue: Two proposals were getting selected at the same time.
Resolution: The selection logic has been corrected to ensure that only one proposal can be selected at a time.

BTMS

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai and Vizag

Overview

This release of the BTMS module corrects the placeholder label for Ship Pennant Number in the Movement Order screen, ensuring accurate and consistent data entry.

Screen Name: Movement Order
The placeholder label for Ship Pennant Number has been corrected. Previously, it was incorrectly displayed as Ship Pendent Number.


OPRA

Version: V1.14.59
Release Date: 10-12-2025
Division: Mumbai

Overview

This release hides the Proposed EMD and QC Level fields in the PRM Remarks and RA Center Remarks screens, and adds a Quick update option in the RA Assign PRM screen for entering additional remarks.

Enhacnments

Screen Name: OPRA – PRM Remarks 
The Proposed EMD and QC Level fields are now hidden.

Screen Name: RA Center Remarks 
The Proposed EMD and QC Level fields are now hidden.

screen Name: RA Assign PRM 
A Quick update option has been added to allow users to enter additional remarks.


OPDEF

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai

Enhancement

Screen Name: OPDEF PRM Remarks 
The Proposed EMD and QC Level fields are now hidden.

Screen Name: OPDEF Center Remarks
The Proposed EMD and QC Level fields are now hidden.

Screen Name: OPDEF Center Remarks
An Updated has been introduced to allow users to view center-wise remarks. With this update, one center can now see the remarks entered by other centers.

Refit Planning (RPP)

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai

Screen Name: PRM Remarks
The Proposed EMD and QC Level fields are now hidden.

Screen Name: Center Remarks 
The Proposed EMD and QC Level fields are now hidden.

Screen Name: Work Order 

Bug FixeThe alignment of the printed Work Order copy has been improved, as the previous print alignment was not proper.

2. A Reject option has been introduced for rejecting WO requisitions, along with a field to capture the reason for the rejection.


QCMS 

Version: V1.14.59
Release Date: 10-12-2025
Divisions: Mumbai

Screen Name: Assign QC Inspector L3

A complete process setup has been introduced for assigning a QC Inspector (L3), and the corresponding workflow has been created.


Leave

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai & Vizag

New Requirement: Validation

Screen Name: Leave Card
A validation has been added for the Employee Type field. The Employee ID must be selected before generating the Employee ID PDF; otherwise, the PDF will not be generated for the selected employee to view the report.

Screen Name: Leave Cancellation
Added 
Personnel

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai & Vizag

Overview

New Requirment

Screen Name: Employee Master
Print functionality is enabled for employee Master in the edit, view and create mode.

Bug Fixes
Screen Name: Employee Deputation order
Issue: Transaction is not getting saved after forwarding for approval, save as draft.
Resolution: The issue has been fixed.

Retirement

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai & Vizag

Bug Fixes
Screen Name: Retirement Reports
Issue:
In the Leave, CGEGIS, and Sparsh tabs of the Retirement Reports, the date format (DD/MM/YYYY) was not applied across all reports.

Resolution:
This issue has been fixed. The date format (DD/MM/YYYY) is now applied across all reports under the Leave, CGEGIS, and Sparsh tabs.

Manpower Booking (MPB)

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai

Screen Name: Unfreeze Screen
Bug Fixes 
Issue:
In the Unfreeze transaction, the approval flow should be as follows:

0–3 months: CC → SM → ADGM

3–6 months: CC → SM → ADGM → GM

6 months and above: CC → SM → ADGM → GM → ASD

Currently, this workflow was not functioning correctly. When the transaction was forwarded to the next role, the system showed an error upon clicking Approve.

Resolution:

The workflow configuration was updated to ensure transactions are routed according to the correct approval chain based on the duration.

Validation logic was corrected to prevent errors when forwarding transactions to higher roles (GM and ASD).

End-to-end testing was performed for all duration ranges (0–3, 3–6, 6+ months) to confirm that approvals and unfreeze transactions now process smoothly without errors.

Screen Name: Allocation of Manpower
Issue: Time card data is not matching with the allocation screen, causing discrepancies in manpower tracking and reporting.
Resolution: Fixed the data mapping so that time card entries now correctly reflect on the allocation screen.

Issue: System allows booking for more than 8 hours.
Resolution: Restricted the system to allow a maximum of 8 hours per booking.

Issue: Unknown Employee 52792A of CNO 48 found in CNO 73 MPB.
Resolution: Corrected the employee mapping to ensure employees appear only under their respective CNOs.

Issue: Actual working hours of an individual are not displayed for booking.
Resolution: Updated the system to show actual working hours during booking for accurate tracking.

Issue: Job details of the selected WI are not displayed.
Resolution: Implemented display of job details for the selected WI during booking.

Issue: Attendance for Holiday and Week Off is available inappropriately.
Resolution: Updated the logic to correctly handle attendance for Holidays and Week Offs.

Issue: WI manpower is deducted in booking of Non-Industrial but not in OT.
Resolution: Corrected the deduction logic to include WI manpower in OT bookings for Non-Industrial employees.

Issue: All WIs are displayed; ship-wise WIs are not filtered. A filter is required for Refit and OPS Cycle.
Resolution: Added filters to display WIs ship-wise and provide options for Refit and OPS Cycle selection.

Screen Name: Sub Transaction
Issue: Hours deducted in booking remain unchanged after amendment.
Resolution: Fixed the amendment process to ensure manhours for Non-Industrial employees are properly updated after changes.

Screen Name: Overtime Booking Industrial 
Issue: For Sunday bookings, users want the provision to select WI for Industrial. Currently, OT booking validation for more than 4 hours on WI is not working.

For OT Booking Non-Industrial, the system shows an error "Add Remarks" and is unable to save data. Remarks should only be required if OT exceeds 4 hours; OT under 4 hours should not require remarks.

Resolution: Implemented validation for Industrial OT bookings to allow WI selection and enforce the 4-hour limit correctly.

Corrected Non-Industrial OT logic to require remarks only for bookings exceeding 4 hours and allow saving for OT under 4 hours.

Time Keeping (TKS)

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai

Bug Fixes 
Screen Name: TKS Assign shift
Issue: Holidays were not being assigned correctly. They should be assigned based on the PIMS Holiday Master for the specific date.

Resolution: Updated the system to ensure holidays are assigned according to the PIMS Holiday Master for the relevant date.

Screen Name: Time Card Report 
Issue: Proper data was not being fetched for General Duty, Ministerial Duty, Shift Duty, Sunday/Holiday, Docking/Undocking, and Night Duty OT rules, so the report could not be viewed correctly.

Resolution: Implemented the OT and duty rules in the report logic to ensure correct data is fetched and displayed for all selected fields.

Screen Name: Time Card
Issue: When an employee has punch-out data but no punch-in for a specific date, the Work Hours column should show 0. Currently, it incorrectly shows 8 in the PDR Report.

Resolution: Updated the logic so that Work Hours show 0 when there is no punch-in data for the day.

Issue: Single punch records for present employees were not appearing in the Corrections screen.

Resolution: Updated the system to display single punch records for present employees in the Corrections screen.

Issue: The report is ready, but previous month calculations, 1-minute differences in working hours, and late/early calculations were not accurate.

Resolution: Corrected the calculation logic to ensure accurate previous month totals, working hours, and late/early computations in the report.

Issue: Employees marked present without completing the required shift working hours.

Resolution: Updated the system to accurately reflect shift completion, ensuring only employees who complete their shift hours are marked as present.

Issue: Employees marked late after 09:00 hours are not having their shift start time corrected to 08:00 hours as per shift timings; only the status changes to XX, ONE.

Resolution: Updated the logic to adjust the shift start time to 08:00 hours for late entries while correctly updating the status.

Issue: Early out proposals were not appearing in the Corrections screen.

Resolution: Updated the system to display early out proposals correctly in the Corrections screen.

Issue: After deactivating the logout punch, the system still marks the employee as Present (XX). A provision is required for handling Hurt Leave.

Resolution: Updated the system to prevent marking Present (XX) after deactivating logout punch and added handling for Hurt Leave cases.

Issue: Backdated processing for promotional or revoked employees is not available. For example, if the DEC list is published in the current month but the Date of Assumption is from a previous month, backdated reprocessing cannot be performed.

Resolution: Enhanced the system to allow backdated processing for promotional and revoked employees, ensuring correct updates even if the Date of Assumption is from a previous month.

Issue: Weekly total, date sorting, format, and font adjustments were not correctly applied.

Resolution: Implemented corrections for weekly totals, proper date sorting, and adjusted format and font for consistency.

Screen Name: Monthly Wages
Issue: The format is not matching the legacy TKS; the time should be displayed in HH:MM format.

Resolution: Updated the system to display time in HH:MM format as per the legacy TKS standard.

Issue: Working hours are showing minius values.

Resolution: Corrected the calculation logic to prevent minius values in working hours.

Screen Name: Attendance report - Sub Transaction 
Issue: Validation is required for PSD and PCD fields.

Resolution: Added validation checks to ensure PSD and PCD fields are correctly validated before submission.

Screen Name: Assign Shift
Issue: Duplicate entries found while assigning shifts. For example, when shifts 02, 04, 06 are assigned for an employee for 1 week, the Time Card report shows some shifts as blank and some as 01 instead of the assigned 02, 04, 06.
Resolution: Corrected the shift assignment logic to ensure all assigned shifts reflect correctly in the Time Card report for the full week.

Screen Name: Assign Shift
Issue: Ministerial Shift – 07 Shift is only applicable for Ministerial staff.
Resolution: Updated the system to restrict assignment of Shift 07 only to Ministerial staff.

Screen Name: Amendment Shift / Amend Attendance Punches
Issue: Civilian category is missing for amendment of attendance.
Resolution: Added the Civilian category in the amendment functionality to allow proper attendance corrections.

Screen Name: De-Assign
Issue: After assigning shifts (02, 04, 06), some shifts in the Time Card report are showing as blank.
Resolution: Fixed the de-assign logic to ensure that the Time Card report accurately reflects assigned and de-assigned shifts.

Screen Name: De-Assign Shift
Issue: Assign Shift done but some shifts appear as blank in the Time Card for shifts 02, 04, 06.
Resolution: Corrected the reporting logic to display all assigned shifts correctly after de-assignment.

Screen Name: De-Assign Shift
Issue: De-Assign shift updates should reflect correctly as per daily, weekly, and monthly views.
Resolution: Updated the system to apply de-assignments consistently across daily, weekly, and monthly reports.

Screen Name: Amendment Shift / Amend Attendance Punches
Issue: Civilian category is missing for amendment of attendance.
Resolution: Added the Civilian category to the amendment module to enable accurate attendance corrections.

Leave

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai & Vizag

Enhancement

Screen Name: Leave Cancellation
Implemented edit, view and update mode in  flow of Leave cancellation screen.

Refit Planning (RPP)

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai

Enhacnments
Screen Name: WI Closure
1. Validation has been added for Work Instructions (WI) with QC Levels L1, L2, and L3, preventing WI closure without the required QC clearance.
For QC Level L4, no validation is applied, and the WI can be closed without QC clearance.

2. Validation was checked for IIR, and the stage status is displayed as “QC Clear and Job Completed".

3. A new column, “QC Level,” has been added to the WI Closure grid.

Bug Fixes
Screen Name: Work Order Ammendment

Issue: After an MU amendment is completed and saved, the system does not automatically calculate or update the costing.

Resolution:
This issue has been fixed. The system now recalculates the costing automatically after an MU amendment.

Bug Fixes
Screen Name: DL Upload
Issue:
After creating a work order with the refit type selected as NR, the system allowed users to upload a DL with a different refit type.

Resolution:
This issue has been fixed. The system now prevents users from uploading a DL with a refit type different from the one selected in the work order.

Screen Name: DL Upload

Issue:
While uploading the DL, the system allowed uploading a DL with a different DL type.

Resolution:
This has been fixed by implementing DL variants (DL I and DL II) under the DL Type field during DL upload, ensuring only the correct DL type can be selected.

OPRA 

Version: V1.14.60
Release Date: 15-12-2025
Division: Mumbai

Enhancements
Screen Name: RA upload

Enhancements

Screen Name: RA Upload

Added validation to prevent duplicate RA numbers per Work Order and duplicate Defect Numbers per RA.

Added OPS-type-wise validation during RA upload. The system now validates the Work Order based on OPS type (Normal / AMP / SMP) before allowing the upload.

Bug Fixes

Screen Name: RA – RA Center Remarks

Issue:
Dropdown remarks entered by MPC were not visible in the detailed view. Remarks provided by MPC and PRM were also not consistently visible in both detailed and quick views.

Resolution:
Updated the remarks display logic to ensure all remarks entered by MPC and PRM are visible in both detailed and quick views.

Bug Fixes

Screen Name: RA – RA Center Remarks

Issue:
Proposed MPC remarks were not visible in the Quick Update view.

Resolution:
Fixed the Quick Update view to display proposed MPC remarks correctly.



Leave 

Version: V1.14.61
Release Date: 20-12-2025
Divisions: Mumbai/Vizag

Overview

This release includes enhancements and bug fixes to improve report accuracy and data presentation within the Leave Management module.

New Requirement: Enhacnments
Screen Name: Leave Card Report

When the Report Type is selected as Center-wise, the Employee ID field is automatically disabled on the screen. 
This ensures accurate report generation based on the selected report type.

Screen Name: LLDL Wages Report

The Company Code and Division Code columns are no longer included in the LLDL Wages Excel export.

Screen Name: LLDL Wages
A new Center No column has been added to the LLDL Wages Excel export file.

Bug Fixes
Screen Name: Employee Leave Report

Issue:
Employee report details were not displayed, and the date format was incorrect.

Resolution:
The issue with employee report data display has been resolved, and the date format has been updated to DD/MM/YYYY.


Refit Planning (RPP)

Version: V1.14.61
Release Date: 20-12-2025
Divisions: Mumbai

Bug Fixes and Enhancement

Screen Name: Work Order
Issue: In the Work Order print, the Start Date and End Date were not visible.

Resolution: Updated the Work Order print layout to display the Start Date and End Date.

Screen Name: Workinstruction/DL Finaliasation

Issue: The View Remarks tab displays the Proposed QC Level, even though the planner does not have the provision to update the proposed QC remark. Additionally, DL Finalization is hidden.

Resolution: Updated the View Remarks logic to hide the Proposed QC Level for planners and align the display based on user role and available actions.

Screen Name: DL - Upload services

A provision has been added for users to upload Service DLs and Service WIs.

Screen Name: Workorder Closure

Issue:
Not all work orders are visible for Work Order closure.

Both Ref Component and Non-Ref Component work orders are not appearing for closure.

Work orders without Ref Component and Work Instruction (WI) are not released.

Resolution:
Updated the Work Order Closure logic to display all work orders (both Ref Component and Non-Ref Component) for closure and ensured that work orders without Ref Component and WI are released appropriately

OPRA

Version: V1.14.61
Release Date: 20-12-2025
Divisions: Mumbai

Enhancement
PRM Remarks
Screen Name: RA PRM Remarks
Updated the RA PRM Remarks screen to remove the display of Proposed EMD and QC Level, as they are no longer required.

Screen Name: Work Instruction/DL Finaliasation
Issue:
The View Remarks tab displays the Proposed QC Level, even though the planner does not have the provision to update the proposed QC remark. Additionally, DL Finalization is hidden.

Resolution:
Updated the View Remarks configuration to hide the Proposed QC Level for planners and aligned the display based on user permissions and DL Finalization availability.

OPDEF

Version: V1.14.61
Release Date: 20-12-2025
Divisions: Mumbai

Screen Name: OPDEF - PRM Remarks
Updated the OPDEF PRM Remarks screen to remove the display of Proposed EMD and QC Level, as they are no longer required.

Screen Name: Work Instruction/DL Finaliasation
Issue:
The View Remarks tab displays the Proposed QC Level, even though the planner does not have the provision to update the proposed QC remark. Additionally, DL Finalization is hidden.

Resolution:
Updated the View Remarks configuration to hide the Proposed QC Level for planners and aligned the display based on user permissions and DL Finalization availability.

eSeva

Version: V1.14.61
Release Date: 20-12-2025
Divisions: Mumbai

Overview 

The Bio Data Master module has been enhanced to capture additional officer and dependent details and to improve data entry flexibility.

Enhancements Included:

Added GX Details (GX Number and GX Date) for In/Out Officers.

Added Appointment Letter Number and Appointment Letter Date for In/Out Officers.

Added Contact Number field in the Dependents section.

Added Date of Issue field for I-Card Number.

Made Date of Commission a mandatory field.

Added PAN Card and Voter ID fields.

Added IMSC and WNC Membership Number fields.

Added Dependent Pass Number field.

Updated Address fields (District, Taluka, City) to be non-mandatory.

SWM - PAY

Version: V1.14.62
Release Date: 29-12-2025
Divisions: Vizag

Overview 

Bug Fixes
Screen Name: Monthly Punches
Issue:
The monthly punch date was displayed for both single and multiple employees when selected from the field. It should display the monthly punch only for the selected single employee.

Resolution:
The system has been corrected to display the monthly punch details only for the selected single employee.

Screen Name: NSO 94 Report
Issue:
In the PAY BILL, the GPF subscription is 6%; however, it was incorrectly displayed as 10%.

Resolution:
The GPF subscription percentage has been corrected to display 6% as per the actual configuration.

Screen Name: NSO 94 Report
Issue:
As per the existing report format, the columns GP, MISCR, and MISCDB4 were missing.

Resolution:
The missing columns (GP, MISCR, and MISCDB4) have been added to the report as per the existing format.


Screen Name: NSO 94 Report
Issue:
The Total Amount of OT was not displayed on the last page in the employee-wise and pay group-wise formats.

Resolution:
The Total Amount of OT is now correctly displayed on the last page for both employee-wise and pay group-wise formats.

Screen Name: Employee Income Tax Summary
Issue:
In the Employee Income Tax Summary (Monthly Details), the gross salary was not reflected for the period March 2025 to February 2026.

Resolution:
The system has been updated to correctly display the gross salary for the specified period.

Screen Name: Table Recovery
Issue:
In Table Recovery, data was not populating for the recovery type Failed Recoveries.

Resolution:
The issue has been fixed, and data now populates correctly for the Failed Recoveries recovery type. 

Screen Name: Employee Paybill
Issue: Non-Industrial employees were incorrectly displayed in the Industrial employee login.

Resolution: The system has been corrected to display only Industrial employees in the Industrial employee login.

Screen Name: Employee Leave and Basic Details
Issue: The effective date was not reflected in the Basic Details section.

Resolution: The effective date is now correctly displayed in the Basic Details section.

New Requirment: ReportS

Screen Name: Emp Muster and OT Details Report

A new Emp Muster and OT Details Report screen has been introduced in the Reports section of SWM. This report enables users to generate structured employee muster and overtime records.

Screen Name: Deducted Rent / Total Rent Details Report

A new Deducted Rent / Total Rent Details Report screen has been introduced in the Reports section of SWM. This report enables users to generate structured records of deducted rent and total rent details.

Screen Name: Employeewise Bank Details
Employeewise Bank Details have been implemented in the SWM PAY module as per the user requirement NEFT module.

Financial Management (FMS)

Version: V1.14.62
Release Date: 29-12-2025
Divisions: Vizag

Overview

This release addresses bug fixes and enhancements related to the BQ Criteria and Noting screen of FMS.

Screen Name: BQ Criteria

Issue:
An error occurred while adding or importing BQ criteria.

Resolution:
The issue has been fixed, and BQ criteria can now be added or imported successfully without errors.

Screen Name: Noting 

Issue 1:
When adding a statement in the Noting editor and clicking Approve or Forward, an error message “Please save one noting as activity” was displayed due to an issue in saving the noting.

Resolution:
The issue has been fixed, and users can now successfully approve or forward the noting after adding and saving the statement.

Issue 2: Noting download was not working.

Resolution:
The issue has been fixed, and noting files can now be downloaded successfully.

Issue 3:
In the initial proposal activity, enclosures were displayed in the noting but were not shown in the enclosure list after saving.

Resolution:
The issue has been fixed, and enclosures are now correctly displayed in the enclosure list after saving.

Issue 4:
The Noting view and download options were not available or not working when attempting to view the entire file noting at a single place.

Resolution:
The issue has been fixed, and the Noting view and download options now work correctly to display and download the entire file noting at a single place.

Issue 5:
When adding a noting activity, the text data was saved successfully but was not displayed.

Resolution:
The issue has been fixed, and the saved text data is now correctly displayed after adding the noting activity.

Screen Name: POEV (Professional Officers Evaluation)

The least BQ rate and vendor response amount are now auto-fetched in the POEV screen. When a vendor is preferred based on the least bid amount, the corresponding values are automatically displayed for selection criteria.

Leave 

Version: V1.14.62
Release Date: 29-12-2025
Divisions: Mumbai

Overview

This release addresses bug fixes and enhancements related to the Employee Leave Report.

Screen Name: Employee Leave Report

Bug Fixes 
Issue:
The leave details of the selected employee were not displayed in the grid.

Resolution:
The issue has been fixed, and the leave details of the selected employee are now correctly displayed in the grid.

Enhancement

Casual Leave (CL) has been added to the employee card grid.

Personnel 

Version: V1.14.62
Release Date: 29-12-2025
Division: Mumbai 

Overview

This release includes an enhancement to improve clarity while selecting Civilian Establishment (CE) types.

Enhancement

Screen Name: Civilian Establishment Order

When a user selects a CE Type from the drop-down list, the corresponding CE type description is now automatically displayed. Descriptions have been added for all available CE type options to improve usability and clarity.

TY Duty 

Version: V1.14.62
Release Date: 29-12-2025
Divisions: Mumbai

Overview

Screen Name: TY Duty Claim Application

Issue:
The TY Duty claim application data was not saved during the transaction.

Resolution:
The issue has been fixed, and the TY Duty claim application data is now saved successfully during the transaction.

Screen Name: TY Duty Proposal

The Sanction Letter – Temporary Duty is generated in the report when the sanctioned amount is zero or non-zero. 

Leave

Version: V1.14.63
Release Date: 14-01-2026
Division: Mumbai

Overview 

Bug Fixes

Screen Name: Leave Entry
Issue: Leave balance is comming negative.
Resolution: 

Issue: Balance leave of employee is coming as 0, for any number of days coming.
Resolution:  

New Feature

Screen Name: Leave Accrual
Create view mode as well for leave accrual.


Leave  

Version: V1.14.63
Release Date: 14-01-2026
Division: Mumbai

Overview

This release focuses on fixing leave balance calculation issues and introducing an enhancement to the Leave Accrual screen to improve visibility and usability.

Bug Fixes

Screen Name: Leave Entry

Issue: Leave balance was displaying as a negative value for employees.

Resolution: Leave balance calculation logic has been corrected to prevent negative values and ensure accurate balance display based on leave balance of employee.

Screen Name: Leave Entry

Issue: Employee leave balance was shown as 0 regardless of the number of available leave days.

Resolution: Fixed an issue in the balance retrieval logic to correctly fetch and display the actual available leave balance for the employee.

New Feature

Screen Name: Leave Accrual

Enhancement: Introduced a View Mode for Leave Accrual, allowing users to view leave accrual details without enabling edit functionality. This improves data visibility while maintaining control over modifications.


Personnel 

Version: V1.14.63
Release Date: 14-01-2026
Division: Mumbai

Screen Name: CEO Report 

Issue: Duplicate CEO no. was coming.
Resolution: 

Screen Name: CEO Transaction

Issue: CEO Transaction - When CEO transaction is approved, the data is not getting updated according to that.
Resolution: 

Issue: History and CEO order no. are not coming.
Resolution: 

Screen Name: CEO Report

Issue: CEO Report print not showing correct name. 
Resolution: 

Enhancement
Screen Name: Service Movement Document

Added new field - Document Name in the service.

Screen Name: Employee Master

Issue: Employee Master - Spelling are incorrect for Experience.
Resolution: 

Screen Name: CEO Transaction

Issue: CEO Transaction - When CEO transaction is approved, the data is not getting updated according to that.
Resolution: 

Personnel Module

Version: V1.14.63
Release Date: 14-01-2026
Division: Mumbai

Overview

This release addresses multiple issues in CEO-related screens, improves data accuracy in reports and transactions, and includes minor enhancements and corrections in master and service-related screens.

Bug Fixes

Screen Name: CEO Report

Issue: Duplicate CEO numbers were being displayed.

Resolution: Fixed the CEO number generation logic to ensure uniqueness and prevent duplicate CEO numbers in reports.

Screen Name: CEO Transaction

Issue: After approving a CEO transaction, the corresponding data was not updating correctly in the system.

Resolution: Corrected the approval workflow to ensure that CEO transaction data is updated accurately upon approval.

Screen Name: CEO Transaction

Issue: CEO transaction history and CEO order number were not displayed.

Resolution: Fixed data retrieval logic to correctly fetch and display CEO transaction history and order numbers.

Screen Name: CEO Report

Issue: Printed CEO reports were not showing the correct employee name.

Resolution: Corrected the mapping of employee name fields to ensure accurate data is displayed in printed reports.

Screen Name: Employee Master

Issue: Incorrect spelling was displayed for the Experience field.

Resolution: Corrected spelling errors to ensure proper labeling in the Employee Master screen.

Enhancements

Screen Name: Service Movement Document

Enhancement: Added a new field Document Name to capture and display document details associated with service movements.

TY Duty 

Version: V1.14.63
Release Date: 15-01-2026
Division: Mumbai

Bug Fixes 

Screen Name: Request for Advance 

Issue: Travelling was not getting calculated.
Resolution: 

Screen Name: TY Duty Proposal

Issue: Journey date is coming as 1 day prior after forwarding or approval in view and edit mode.
Resolution: 

Screen Name: TY Duty Claim Application

Issue: Start date and end date is not coming.
Resolution: 

Issue: TY Duty claimed data not able to save the transaction.
Resolution: 



TY Duty Module

Version: V1.14.63
Release Date: 15-01-2026
Division: Mumbai

Overview

This release resolves calculation, date handling, and transaction-saving issues across TY Duty request, proposal, and claim screens to ensure accurate data processing and smooth workflow execution.

Bug Fixes

Screen Name: Request for Advance

Issue: Travelling days amount was not being calculated during advance request creation.

Resolution: Fixed the travelling days calculation logic to correctly compute and display the travelling amount based on entered journey details.

Screen Name: TY Duty Proposal

Issue: Journey date was displayed as one day earlier after forwarding or approval in view and edit modes.

Resolution: Corrected date handling and timezone conversion logic to ensure journey dates remain consistent across all workflow stages.

Screen Name: TY Duty Claim Application

Issue: Start date and end date were not displayed in the claim application screen.

Resolution: Fixed data binding to correctly fetch and display start and end dates in the TY Duty claim application.

Screen Name: TY Duty Claim Application

Issue: Claimed TY Duty data could not be saved during transaction submission.

Resolution: Resolved validation and transaction persistence issues to ensure TY Duty claim data is successfully saved.

Leave

Version: V1.14.64
Release Date: 20-01-2026
Division: Mumbai

Overview

This release focuses on resolving issues related to leave calculation, holiday inclusion, balance display, and transaction handling across multiple leave-related screens.

Bug Fixes
Issue 1

Description: While applying Earned Leave (EL), holidays were getting excluded.
Resolution: The leave calculation logic for Earned Leave has been corrected to ensure that applicable holidays are included as per the configured EL rules.

Issue 2

Description: Leave type “Dies Non” was excluding holidays and week-offs.
Resolution: The exclusion logic has been updated so that holidays and week-offs are handled correctly for the “Dies Non” leave type based on defined business rules.

Issue 3

Description: Leave balance for all leave types was displaying as 0, even after amendment.
Resolution: The issue in balance recalculation after leave amendment has been fixed, and amended leave balances are now displayed accurately.

Screen Name: Holiday Master

Issue: Entered occasion details were not appearing in the table.
Resolution: The data save and refresh issue has been resolved, and occasion details are now correctly displayed in the Holiday Master table after entry.

Screen Name: Leave Balance Amendment

Issue: While forwarding the transaction, saved amendment details were throwing an error.
Resolution: The transaction validation issue has been fixed, allowing amendment details to be forwarded successfully without errors.

Personnel

Version: V1.14.64
Release Date: 20-01-2026
Division: Mumbai

Overview

This release includes bug fixes and new features across Employee Master and Civilian Establishment Order (CEO) screens to improve data accuracy, workflow handling, and usability.

Screen Name: Employee Master
Bug Fixes

Issue 1:
Transfer Out Dockyard – In the field “Probation lifted iro of employee”, the value “No” was displayed instead of “Not Applicable”.
Resolution:
The dropdown logic has been updated to display “Not Applicable” for applicable employees.

Issue 2:
In fresh appointment CEO type, the record was showing a confirmation popup but not forwarding to the next updater / higher authority.
Resolution:
The workflow forwarding issue has been fixed, and records now correctly move to the next level after confirmation.

Issue 3:
The Date of Leaving was incorrect and should reflect the Superannuation Date.
Resolution:
The system now correctly populates the Date of Leaving based on the employee’s superannuation date.

Screen Name: Civilian Establishment Order
New Features

CEO – Declaration of Schedule Caste

Dropdown values restricted to GEN, OBC, and ST only.

CEO Preview Print

Preview and Print functionality enabled at Save as Draft stage.

Transfer Out Dockyard

Added new dropdown value “Not Applicable” in the field “Probation lifted iro of the employee”.

Employee Master – Promotion within Dockyard

In Promotion & MACP section, the field “Promoted to Post” now displays the post name instead of numeric values.

CEO Description

Relevant field details are now auto-fetched into the CEO description section.

Bug Fixes

Issue 1:
In History and CEO tabs, updated data for changed fields was not displaying correctly.
Resolution:
The issue has been resolved, and all modified field values now appear correctly in both History and CEO tabs.

Issue 2:
In CEO – Lifting of Probation and Confirmation, the Date of Appointment was hard-coded as 20-08-2001 in the description.
Resolution:
The hard-coded value has been removed, and the actual Date of Appointment is now dynamically populated.

TY Duty

Version: V1.14.64
Release Date: 20-01-2026
Division: Mumbai

Overview

This release addresses critical issues related to employee selection, data persistence, and grid handling in TY Duty workflows to ensure smooth transaction processing.

Bug Fixes
Screen Name: Request for Advance

Issue:
In the employee list pop-up, sorting based on filters and date was not working.

Resolution:
The sorting functionality has been fixed, and employees can now be correctly sorted using filters and date parameters.

Screen Name: TY Duty Proposal

Issue 1:
When adding a new employee to the grid for the second time, previously added employee records were not getting saved.

Resolution:
The grid data handling logic has been corrected to ensure that all previously added employee records are retained and saved properly.

Issue 2:
After saving the transaction, grid data was not being saved.

Resolution:
The save operation has been fixed to ensure that all grid entries are persisted successfully after transaction submission.

Module Name: SWM - PAY
Version: V1.14.64
Release Date: 20-01-2025
Divisions: Vizag and Mumbai

Overview:
This release includes functional enhancements, defect fixes, new requirement and cosmetic updates across payroll-related screens to improve reporting accuracy, system stability,
and user experience.

New Feature 
Screen Name: Pay Slip

As per the new requirement, a non-mandatory Center column has been added to the Payslip Report to support additional reference information.

Bug Fixes
Screen Name: Change Statement

Issue: The Change Statement Report Excel file fails to open.
Resolution: The issue preventing the Excel file from opening has been resolved.

Enhancment
Screen Name: Payroll Report
Cosmetic changes have been implemented across all payroll reports as per the approved requirements to enhance layout and readability.

Module Name: SWM - NEFT
Version: V1.14.64
Release Date: 20-01-2025
Divisions: Vizag and Mumbai

Bug Fixes
Scrreen Name: Payments to Banks

Issue: The loader continues to run indefinitely without displaying any loading message.
Resolution: The loader behavior has been corrected to ensure proper loading indication and completion.


Module Name: Yard Utility (YUS)
Version: V1.14.64
Release Date: 20-01-2025
Divisions: Vizag and Mumbai

Overview
This release addresses functional improvements and defect fixes in the Service Requisition screen to enhance listing controls and ensure proper display of feedback details in the Yard Utility system.

Enhancements
Screen Name: Service Requisition

Issue: WI listing controls and related provisions were required in the YUS module.
Resolution: WI listing controls and the associated provisions have been implemented in the Service Requisition screen as per requirements.

bugs
Screen Name: Service Requisition

Issue: In YUS feedback, Item, Batch, and other related details were not displayed.

Resolution: The issue has been fixed, and all relevant item, batch, and associated details are now displayed correctly in the YUS feedback section.

Refit Planning (RPP)

Version: V1.14.64
Release Date: 20-01-2025
Divisions: Mumbai

Overview

This release includes multiple bug fixes to improve stability and workflow continuity, along with functional and UI enhancements across RPP and OPS modules.

Bug Fixes
Screen Name: Work Instruction

Issue 1:
The OPRA No. was incorrectly mapped. It was displayed as “Defect No.” inside the Work Instruction screen, and “Equipment Name” was incorrectly displayed outside the screen.

Resolution:
Corrected the mapping so that OPRA No. and Equipment Name are displayed accurately in their respective locations.

Issue 2:
DL finalization PRM remarks, MPC remarks, and other remarks were not being saved to the database.

Resolution:
Fixed the issue to ensure all remarks are saved correctly during DL finalization.

Issue 3:
An error was displayed when using the WI-Count grid filter to filter work instructions.

Resolution:
Resolved the error and enabled proper filtering using the WI-Count grid filter.

Issue 4:
RPP Work Instruction was throwing an error during processing.

Resolution:
Issue fixed to ensure smooth creation and processing of Work Instructions.

Screen Name: Work Order

Issue:
In RPP Work Orders, only approved data was visible in the View screen. Newly created work orders were not visible in View or Pending for the next approver, causing a workflow blocker.

Impact:
This issue blocked workflow progression and required manual intervention.

Resolution:
Fixed the visibility issue to ensure newly created work orders are correctly displayed in View and Pending stages for the next approver.

Screen Name: Examine & Repair

Issue:
E&R data was visible to PRM/CC users even when the Work Instruction (WI) was not released.

Expected Behavior:
E&R DL/RA data should be visible to PRM/CC users only after the Work Instruction is released.

Resolution:
Updated the logic to display E&R DL/RA data to PRM/CC users only after the Work Instruction is released.

Enhancements

Provision to Add Reason and Remarks for P1/O2 Requests
Added functionality to capture reasons and remarks while raising P1/O2 requests.

Ship Name is now displayed on the Transaction Dashboard for selection across the following transactions, for both RPP and OPS Work Orders:

OPS Work Order Approval

Work Order Amendment

OPS Work Order Amendment

Work Order Closure

OPS Work Order Closure

UI Enhancement – API Method Update
Updated RPP and its sub-modules to use POST instead of GET for improved security and performance.

Defect List

Version: V1.14.64
Release Date: 20-01-2025
Division: Mumbai

Bug Fixes
Screen Name: DL Upload

Issue 1:
DL validation during upload was based on DART No. instead of Defect No. within a single refit cycle.

Resolution:
Updated the validation logic to ensure DL uploads are validated based on Defect No. within the same refit cycle.

Issue 2:
DL upload was restricted when Ship Remarks did not match the Remarks Master.

Resolution:
Enabled DL upload even when Ship Remarks do not match the Remarks Master.

Issue 3:
DL/RA work orders that were already closed or not yet approved were visible in Ship Staff login for uploading RA (Operational).

Resolution:
Corrected the visibility logic to ensure only valid and eligible DL/RA work orders are displayed for RA upload in Ship Staff login.

Enhancements
Flexible Equipment Code Handling During DL Upload

Added a new entry in Equipment Master:

Equipment Name: OTHER

Equipment Code: 00000

During DL upload:

If the uploaded Equipment Code does not match any value in the Equipment Master, the system will automatically set the Equipment Code to 00000.

Added a new column in DL Header:

CMMS_EQ_DESC

The equipment description received from CMMS or file upload will be saved in CMMS_EQ_DESC for both matched and unmatched equipment codes.

Displayed the CMMS_EQ_DESC column across all relevant screens (DL, WI, etc.) in the following format:

Equipment Code – Equipment Description

Shop Floor Management

Version: V1.14.64
Release Date: 20-01-2025
Division: Mumbai

Bug Fixes
Screen Name: WI Progress

Issue:
Work Instruction (WI) details were not displayed in the WI Progress screen due to data access control issues. Additionally, WIs were not visible based on PRM login and Center Location login (e.g., CRF and P1/O2).

Resolution:
Fixed the data visibility and access control logic to ensure:

WI details are displayed correctly in the WI Progress screen.

WIs are visible based on PRM login and Center Location login, similar to CRF and P1/O2 workflows.


Request Assistance (RA)

Version: V1.14.64
Release Date: 20-01-2025
Division: Mumbai

Bug Fixes
Screen Name: Examine & Repair

Issue:
Examine & Repair (E&R) data was visible to PRM/CC users even when the Work Instruction (WI) was not released.

Expected Behavior:
E&R DL/RA data should be visible to PRM/CC users only after the Work Instruction is released.

Resolution:
Updated the logic to ensure that E&R DL/RA data is displayed to PRM/CC users only after the Work Instruction is released.

Enhancements
Provision to Add Reason and Remarks for P1/O2 Requests
Added functionality to capture reasons and remarks while raising P1/O2 requests.




Enter the shift timing details in the grid below:

• First In: Select the time from the drop-down list.
• First Out: Select the time from the drop-down list.
• Break Time: Enter the break duration.
• Second Out: Select the time from the drop-down list.
• Work Hours: Displays the total working hours.


1.	On the left side toolbar, click HR. 
2.	From the Modules list, click the Time Keeping System (TKS) module, and then click Assign Shift under transactions.

Assign shift present date and future date.


The grid displays the following employee and shift-related information:

Employee Information

Employee ID: Displays the employee ID.

Employee Name: Displays the employee name.

Department: Displays the department name.

Center No.: Displays the center number.

Shift Information

From Date: Displays the shift assignment start date.

To Date: Displays the shift assignment end date.

Weekly Off: Provides checkboxes to select the weekly off day(s) for assigning the shift to a particular day.

Alt Sat Off: Based on the selected shift, this toggle switch is enabled or disabled. The data is fetched from the Shift Master.

Additional Details

Remarks: Allows entry of remarks, if any.


Note: Employee Id, Shift and Reason fields are non mandatory field for de-assignment of shift 

Employees shift assignment punch in out , punch out late in , late out how much time is employee 
Using this screen employee amend the shift of previous date of current month. 


Forward to the  manager and manager will approve from pending action. 

Approve 



The Amend Attendance Punches transaction allows authorized users and administrators to modify employee attendance punch details based on shift assignments. This transaction is used to correct or update punch-in and punch-out records for employees.

Through this transaction, users can amend attendance data such as punch-in time, punch-out time, late-in, and shift of employee.

The system provides two program codes for attendance amendment:

Amend Attendance – Shift: Allows amendments based on the employee’s assigned shift.

Amend Attendance – All: Allows amendments across all attendance records irrespective of shift assignment.

Both users and administrators with appropriate access rights can perform attendance punch amendments to ensure correctness of employee attendance recor

Allows amendments based on the employee’s assigned shift.


12346X


Centre No.*: Select the centre number for which the weekly or monthly freeze needs to be reversed.

Unfreeze From Date*: Select the start date from which the data should be unfrozen.

Unfreeze To Date*: Select the end date up to which the data should be unfrozen.

Fields marked with an asterisk () are mandatory.

If sunday selected on weekly off or wherever holiday there if users select the punch in and punch out is displayed.


Note: Maximum allowed OT Daily is 24, weekly , and Quarterly 14.







MIS 

Version: V1.14.65
Release Date: 24-01-2025
Division: Mumbai

Overview

This release includes a usability enhancement to the Service Request screen, where the Date field now defaults to the current date to streamline request creation.

Screen Name: Service Request

Enhancements

The Date field on the Service Request screen now defaults to the current date, eliminating the need for manual date selection.

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes bug fixes in the Manpower Booking (MPB) module to ensure compliance with overtime (OT) limits and to improve the visibility of Work Instructions (WI). These fixes enhance system validation and ensure accurate data availability during OT booking.

Bug Fixes
Issue 1

Issue: In OT Booking, the Non-Industrial system was accepting OT bookings exceeding 24 hours, which should not be allowed.

Resolution:
The system has been enhanced to restrict OT booking to a maximum of 24 hours. Any attempt to book OT beyond this limit is now prevented with appropriate validation.

Issue 2

Issue: Standing Work Instructions (WI) were not displayed in the Manpower Booking screen.

Resolution:
The system has been fixed to correctly fetch and display Standing Work Instructions in the Manpower Booking module.

Time Keeping (TKS)

Version: V1.14.65
Release Date: 24-01-2025
Division: Mumbai

Overview

This release includes critical bug fixes and functional enhancements in the Time Keeping (TKS) module. The changes ensure accurate employee data filtering, correct attendance amendment behavior in reports, and improved handling of overtime and compensatory off scenarios.

Bug Fixes
Screen Name: Overtime Booking – Industrial

Issue:
When clicking Show Data in Industrial OT Booking, the system was displaying both Industrial and Non-Industrial employee data.

Resolution:
The system now fetches and displays only Industrial employee data when the Industrial option is selected, ensuring correct data segregation.

Screen Name: Amend Attendance
Issue 1

Scenario: Punch In = 0, Punch Out = 0
After amending attendance as Absent, the Timecard Report incorrectly showed Punch In and Punch Out as Shift In and Shift Out time.

Resolution:
The system now correctly processes amended attendance records based on punch conditions, ensuring accurate Timecard reporting.

Issue 2

Scenario: Punch In = 08:30, Punch Out = 01:30 (Out punch less than Shift Out time)
After amending attendance as Absent, the Timecard Report displayed incorrect Punch In and Punch Out times.

Resolution:
The system has been corrected to handle out-punch values less than shift out time accurately in the Timecard Report.

Issue 3

Scenario: Punch In = 08:30, Punch Out = 19:00 (Out punch greater than Shift Out time)
Expected behavior: Punch In = Shift In Time, Punch Out = 19:00
Previously, the report incorrectly showed Shift In and Shift Out times.

Resolution:
The system now retains the actual out punch time when it exceeds shift out time, ensuring correct reporting.

Issue 4

Scenario: Punch In = Null, Punch Out = 19:00 (Out punch greater than Shift Out time)
Expected behavior: Punch In = Shift In Time, Punch Out = 19:00
Previously, the report showed Shift In and Shift Out times incorrectly.

Resolution:
The system now correctly reflects the actual out punch time in the Timecard Report.

Screen Name: Wages Export Report (CSV Download)

Issue:
Although the grid displayed only Industrial employee data after applying the filter, the downloaded Excel file contained all employee types.

Resolution:
The Excel export functionality has been fixed to download only the filtered data displayed in the grid.

Enhancements
Screen Name: Excess Hours OT – Compensatory Off

Enhancement Details:
Employees can avail Compensatory Off only if marked Absent for the selected day.

System Impact after Save:

Login and Logout times are updated to Shift In and Shift Out times.

Work Hours are calculated based on shift work hours.

Quarterly and Weekly OT balances are deducted by -4 hours (Comp Off = 4 OT hours).

Timecard, PDR, and Attendance Details reports reflect the above changes.

Screen Name: Excess Hours OT – Compensatory Off + OT

Enhancement Details:
Employees can avail Compensatory Off + OT only if marked Absent for the selected day.

System Impact after Save:

Login Time is set to Shift In Time.

Logout Time is set to Shift Out Time + OT consumed (e.g., 19:00).

Work Hours are calculated as shift work hours.

OT column displays consumed OT (e.g., 2 hours).

Quarterly and Weekly OT balances are deducted by -6 hours
(Comp Off = 4 hours + OT = 2 hours).

Changes are reflected in Timecard, PDR, and Attendance Details reports.


Refit Planning (RPP)

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release introduces an enhancement in the Refit Planning (RPP) module to improve vendor selection consistency across transactions by enabling vendor master data selection through a drop-down list.

Enhancements
Vendor Selection Enhancement

A provision has been added to fetch vendor details from the Vendor Master in the Vendor Name field as a drop-down list for the following transactions:

Only Registered and Temporary Registered vendors are displayed in the drop-down list.

Previously, the vendor drop-down was available only on the Work Instruction screen (applicable to both RPP and RA modules).

This enhancement now extends the same vendor selection functionality to the Raise QC Request screen, ensuring consistent vendor selection across transactions.

Request Assistance (RA)

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release introduces functional enhancements in the Request Assistance (RA) module to strengthen role-based controls, improve Work Instruction (WI) handling for offloaded jobs, and standardize vendor selection across related transactions.

Enhancements
Screen Name: PRM WI (Operational)

PRMs are now restricted from generating Work Instructions (WI) for other PRMs.

Each PRM can generate WI only for their own assignments, ensuring role-based accountability and control.

Screen Name: RPP WI, RA WI, PQ/O2 WI, OPDEF WI

For offloaded jobs, the Mandays value is enforced as 0.

The Mandays field is disabled for Offload WI transactions.

This restriction is applicable only for the Mumbai division.

Screen Name: WI / Release WI & Raise QC Request
Vendor Selection Enhancement

A provision has been added to fetch vendor details from the Vendor Master in the Vendor Name field as a drop-down list.

Only Registered and Temporary Registered vendors are displayed in the drop-down.

Previously, this vendor drop-down was available only on the Work Instruction screen (for both RPP and RA modules).

This enhancement now extends the same vendor selection functionality to the Raise QC Request screen, ensuring consistency across transactions.


OPDEF

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes bug fixes in the OPDEF module to ensure correct display and visibility of P1/O2 request and receipt data associated with OPDEF Work Instructions (WI).

Bug Fixes
Screen Name: P1/O2 Received
Issue 1

Issue:
In the P1/O2 Received screen, the details view was displayed as blank for OPDEF WI.

Resolution:
The system has been fixed to correctly fetch and display the P1/O2 received details for OPDEF Work Instructions.

Issue 2

Issue:
P1/O2 requests raised for OPDEF WI were not appearing in the P1/O2 Received grid.

Resolution:
The system has been corrected to ensure that P1/O2 requests raised for OPDEF WI are properly displayed in the P1/O2 Received grid.

Shop Floor Management (SFM)

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes a bug fix in the Shop Floor Management (SFM) module to ensure proper visibility and approval flow of CRF requests raised against OPDEF Work Instructions.

Bug Fixes
Issue

CRF requests raised by the Center against OPDEF WI were not visible in the PRM login for further forwarding and approval.

Resolution

The system has been fixed to ensure that CRF requests raised against OPDEF WI are correctly displayed in the PRM login, enabling proper forwarding and approval actions.

OPRA

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes a bug fix in the OPRA module to ensure correct visibility of OPS Work Orders (WO) during the closure process.

Bug Fixes
Issue

In OPS WO Closure, all work orders were visible, including those that were only initiated and not approved.

Resolution

The system has been corrected to display only approved OPS Work Orders in the OPS WO Closure screen. Initiated or unapproved work orders are now excluded.

Leave

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes multiple bug fixes in the Leave module to ensure correct leave calculation logic, accurate balance display, proper holiday handling, and seamless report generation. These fixes improve leave processing accuracy and system reliability.

Bug Fixes
Screen Name: Leave Entry
Issue 1

When applying Earned Leave (EL), holidays from the Holiday Master were being excluded, whereas they should be included.
For Casual Leave (CL), holidays should be excluded.
Testing could not be completed on the NUD system due to zero leave balance for all leave types.

Resolution:
The system has been fixed to:

Include holidays and weekly offs for Earned Leave (EL).

Exclude holidays and weekly offs for Casual Leave (CL).
Leave calculation logic has been corrected as per leave type rules.

Issue 2

For CL, holidays and weekly offs were not consistently excluded, while other leave types were expected to include them.
Additionally, Dies Non leave was incorrectly excluding holidays and weekly offs.

Resolution:
The system now correctly applies leave rules as follows:

CL excludes holidays and weekly offs.

All other leave types, including Dies Non, include holidays and weekly offs in leave calculation.

Issue 3

While applying leave, the leave balance for all leave types was displayed as zero, even after amendments.

Resolution:
The leave balance calculation has been fixed to correctly display available balances for all leave types, including amended balances.

Screen Name: Holiday Master
Issue

The Occasion field was not displayed in the Holiday Master table.

Resolution:
The system has been corrected to properly display the Occasion column in the Holiday Master grid.

Screen Name: Leave Balance Amendment
Issue

An error was encountered while forwarding the Leave Balance Amendment transaction.

Resolution:
The forwarding process has been fixed, allowing Leave Balance Amendment transactions to be forwarded successfully without errors.

Screen Name: Absent Leave Report
Issue

Data was not fetching in the Absent Leave Report.

Resolution:
The report generation logic has been corrected to fetch and display Absent Leave data accurately.

Personnel

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes bug fixes and enhancements in the Personnel module to improve data accuracy, ensure correct history tracking, enhance report generation, and introduce additional fields to support promotion and transfer processes.

Bug Fixes
Screen Name: Employee Master
Issue 1

In the History and CEO tabs, data for all changed fields was not being displayed.

Resolution:
The system has been fixed to display all modified field values correctly in both the History and CEO tabs.

Issue 2

When updating employee information, the Department field was getting cleared.

Resolution:
The system has been corrected to retain the Department value during employee master updates.

Issue 3

The Date of Leaving was not aligned with the employee’s Superannuation Date.

Resolution:
The Date of Leaving is now correctly set based on the Superannuation Date, as per business rules.

Screen Name: CEO Report
Issue

After clicking the Print button in the CEO Report:

Center and Department fields were blank.

Designation was generated correctly.

(BA Remark: Currently, only the Center field is blank.)

Resolution:
The report generation logic has been fixed to correctly populate Center, Department, and Designation fields in the printed CEO Report.

Screen Name: Annual Increment
Issue

Upon saving the transaction, the Serial Number was not generated.

Resolution:
The system has been fixed to automatically generate the Serial Number upon successful save of the Annual Increment transaction.

Enhancements
Promotion – Within Dockyard (CEO)

A new field “Promoted to Post” has been added.

The field is provided as a drop-down list populated with Designation values.

Upon selection, the employee’s Designation is automatically updated in the Employee Master.

CEO – Transfer Out Dockyard

In the Probation Lifted field, the drop-down value “NO” has been replaced with “Not Applicable” for better clarity and accuracy.

TY Duty

Version: V1.14.65
Release Date: 24-01-2026
Division: Mumbai

Overview

This release includes multiple bug fixes in the TY Duty module to improve calculation accuracy, data saving reliability, and filter/sorting functionality across TY Duty screens.

Bug Fixes
Screen Name: MRO TY Duty
Issue 1

Issue:
The MRO Amount was not calculating automatically when the Interest Rate was changed. Additionally, after selecting the Proposal Code and clicking the Go button, the system was displaying an error, preventing testing.

Resolution:
The system has been fixed to:

Automatically recalculate the MRO Amount when the Interest Rate is modified.

Correct the error occurring after selecting the Proposal Code and clicking Go, enabling proper data retrieval and testing.

Issue 2

Issue:
The employee filter pop-up was throwing an error.

Resolution:
The employee filter pop-up functionality has been fixed and now works correctly without errors.

Screen Name: TY Duty Proposal
Issue 3

Issue:
Sorting and date filters were not functioning as expected.

Resolution:
Sorting and date filter functionality has been corrected and now works properly.

Issue 4

Issue:
When adding employees to the grid a second time, the employees added during the first attempt were not getting saved.

Resolution:
The system has been fixed to ensure that all added employee records are retained and saved correctly, even when employees are added multiple times.

Issue 5

Issue:
After saving the transaction, the grid data was not being saved.

Resolution:
The save logic has been corrected to ensure that all grid data is saved successfully upon transaction completion.

Issue 6

Issue:
Filter and sorting functionality was not working consistently across TY Duty screens.

Resolution:
Filter and sorting functionality has been standardized and fixed across all TY Duty screens.

QCMS

Version: V1.14.65
Release Date: 24-01-2025
Division: Mumbai

Overview

This release introduces functional enhancements and bug fixes in the QCMS module to improve Work Instruction (WI) visibility, QC request handling, IIR tracking, and validation of approved work orders. These changes enhance usability, data accuracy, and role-based access.

Enhancements
Screen Name: WI Add Equipment

A provision has been added to list Work Instructions (WI) in the WI Add Equipment transaction based on:

PRM

Center (Location) login

Only Released WIs that are not closed are displayed.

WI visibility is restricted as follows:

If MFAB is logged in, only MFAB-related released WIs are displayed.

If a Center (Main / WC) is logged in, only center-related released WIs are displayed.

Screen Name: Raise QC Request

A provision has been added to view both Pending and Created IIRs, similar to the existing functionality in the Raise QC Request screen.

The Reject column displayed in the grid view has been hidden for better clarity.

Screen Name: IIR

A filter option has been added to allow users to view Pending and Created IIRs.

Screen Name: Raise QC Request (Enhancement)

In the Inspection Type field, the following values have been added to the drop-down list:

Installation

Visual

Functional

Bug Fixes
Screen Name: QC Level
Issue

In the WO drop-down, all operational work orders were displayed, including those that were not approved.

Resolution

The system has been fixed to display only approved Work Orders in the WO drop-down list.

SWM PAY

Version: V1.14.65
Release Date: 24-01-2026
Division: Vizag

Overview

This release includes bug fixes and multiple enhancements in the SWM PAY module to improve report segregation, payslip accuracy, payroll report naming consistency with the legacy system, employee visibility logic, and payroll reporting details.

Bug Fixes
Screen Name: Sanction Report

Issue:
Six different reports are generated from the Sanction Report screen; however, they were not split based on user login roles.

Resolution:

Report access has been segregated based on login role.

For CLERK (GPS/PS) role, the report is generated as per the attached specified format.

Remaining reports are now accessible only to the CONTROL CELL role.

Enhancements
Screen Name: Printed Payslip – Credit/Debit Remarks

Enhancement Details:

The Credit and Debit remarks, which were not updating in the printed payslip, have been fixed and now reflect correctly.

Pre-Printed Payslip – Column Changes

The following column mappings have been updated:

ITax = ITax + Edu Cess

GPF_CPF = GPF_SUB + NPS_GOV_D

GPF_ADV = GPF_ADV

CPP/ARR = NPS_IND

Screen Name: SWM Pay Certificate

Enhancement Details:

The Employee List API has been updated.

If a logged-in user is linked to both Industrial and Non-Industrial employees, both are displayed.

Otherwise, only the specific employee(s) linked to the user are shown.

Screen Name: Payroll Reports
Downloaded Report Naming Convention (As per Legacy System)

Downloaded PDF reports are now named using the following logic:

Report Name + Month + Pay Bill Number

The naming of reports has been aligned with the legacy system, as detailed below:

Payroll Reports
Report Name	Downloaded File Name Format
Payroll	Paybill December 2025 52A
Credit Summary	PageCreditTotal_December 2025_52A
Debit Summary	PageDebitTotal_December 2025_52A
GPF Subscription	GpfSchedule_December 2025_52A
PRAN / NPS Recovery	PRANSchedule_December 2025_52A
CGEGIS	GISCGISRecoverySchedule_December 2025_52A
CGHS Recovery	CGHSRecoverySchedule_December 2025_52A
MES / Navy Recovery	MES_Recovery_ScheduleDecember 2025_52A
CPWD / Estate Manager Recovery	Estate_Manager_RecoveryDecember 2025_52A
House Building Advance	HOUSEBUILDINGADVANCESchedule_December 2025_99A
Computer Advance	Computer Advance_Schedule_December 2025_52A
Vehicle Advance	Vehicle Advance_Schedule_December 2025_52A
Festival Advance	Festival Advance_Schedule_December 2025_52A
Income Tax Recovery	IncomeTaxReSchedule_December 2025_52A
Leave Recovery	LeaveRecovSchedule_December 2025_52A
PLI Schedule	PLISchedule_November 2025_28
UPS Recovery	UPS_Recovery_Schedule_December 2025_52A
OT Print Reports – Legacy Naming
Report Name	Downloaded File Name
OT Summary	OT_Summary_December 2025_2A
OT Bill (Pay Group)	OT_Allowance_Bill_December 2025_2A
Muster Report	DEC_OT_Muster_2A
Screen Name: Employee Basic Details Report

Enhancement Details:

New columns have been added:

Old Basic

New Basic

Grade Pay

Next Increment Date

Existing columns are repurposed as follows:

From Date → Next Increment Date

To Date → Effective Date

The report format has been updated as per the attached specification.

SWM GPF

Version: V1.14.65
Release Date: 24-01-2026
Division: Vizag

Screen Name: Increase / Decrease – Staff Minute Sheet
Enhancements
Field Changes

The existing “Amount” column has been renamed to “Revised Amount”.

A new field “Existing Amount” has been added.

This field is read-only.

The Existing Amount is auto-fetched by the system based on current records.

Print Format Enhancement

The Staff Minute Sheet (SMS) print format has been modified as per the attached format. The updated print behavior is as follows:

Dynamic Fields

All markings and changes made in the Staff Minute Sheet are dynamically fetched from the system and reflected in the print.

Static Fields

Fields where no changes are marked remain static in the printed output.

Layout & Formatting Improvements

The following layout changes have been implemented in the print format:

Added proper spacing in the report title “STAFF MINUTE SHEET”.

Added spacing before “Officer’s Name & Designation” to allow proper placement of e-signature / physical signature.

Updated the text “TO: SM (Pers)” for correct formatting.

Fixed page margins on both left and right sides for improved alignment and readability.

Financial Managment (FMS)

Version: V1.14.65
Release Date: 24-01-2025
Division: Vizag/Mumbai

Overview

This release includes an enhancement in the Financial Management (FMS) module to improve accuracy of employee details displayed in the workflow timeline dashboard.

Enhancement

The Timeline Dashboard has been enhanced to display the correct routed employee name. Previously, when a file was initiated by JMCOM and routed to MCOM, an incorrect employee name was shown in the timeline. This issue has now been corrected to ensure accurate workflow visibility.



Refit Planning (RPP)

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

Bug Fixes

Screen Name: Work Instruction

Issue: The system fails to retain applied filters on the “WI Create” screen after a WI is created and the user returns to the screen, causing unnecessary repetitive actions and impacting user productivity.
Resolution: 

Screen Name: Assign PRM, RA Assing PRM

Issue: Modification of PRM should be allowed by the planner. At present system does not allow change of PRM

Currently if all prm are removed from 'detailed view' then its working but incase of Multiple PRM Are there , if single prm removed then its not working. Removed or deleted prm is till visible. 

In 'Quick update' if multiple PRMs are assigned then if the user wants to remove one or all the PRM then the system does not allow to save the data unless and untill any new PRM is selected.

Add remove prm functionality should work in both Quick and Details view.

This case is applicable for both RPP & OPS. 

Note :

1. PRM removed should be allowed till prm is not given any remarks or Prm has not assing any center further.

2.  COSM can add prm  till DL is not finalized

Resolution: 


Screen Name: Work Order Closure

Issue: Ship is showing in transaction dashboard, but not showing inside screen header filter while closing RPP WO.
Resolution: 

Screen Name: DL Finalization

Issue: If we open finalize screen and click on quick update screen the authorized center field is showing as center code instead of center name; it should reflect as (011) HULL FABRICATION.
Resolution: 

Screen Name: Assistant WI (P1/O2-Received)

Issue: The WO filter is not working — the specific work order does not appear in the Operation Work Order list, but when the filter is cleared, the transaction becomes visible.
Resolution: 

Screen Name: DL Upload

Issue: DL Upload : After uploading DL OR RA, Equipment name showing NA for ALL DL.
Resolution:

Screen Name: P1/O2 Receive

Issue: Work Instruction number is generating wrong.
Resolution: 

Screen Name: Approve CRF RPP/RA/OPDEF

Issue: Show WI no. for which crf is raised in detail view left side panel.
Resolution: 

Issue: Approve crf Header filter for All (When filter is blank) its showing CRF for approval which is already approved, it should list of Approve crf  in disable mode, currently it is allowing reaaprove the crf which is already approved.
Resolution: 

Enhancement

Screen Name: Work Order Closure

All the workorders not visible for workorder closing { 1.All wo refcomp + not refComp should come for wo Close 2.without refComp and wi is not released }.

Screen Name: Work Order

Work order - Transaction dashboard-Closed WO to be visible along with the status 'WO Closed' in status column.

OPRA

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

Screen Name: Work Instruction

Enhancement

Show tab create wi and generated.

Bug Fixes

Screen Name: WO Closure

Issue: Even after closing the OPS WO, the closed WO is still visible in OPS WO closure screen. Also new OPS wo is automatically created and displayed even though the WO is not approved yet.

Show only Normal WO Which are approved
Once Normal WO is closed then closed subsequently related other 4 WO of (Ops, amp, smp, dry dock).

Resolution: 

Screen Name: Assistant WI (P1/O2 - Received)

Issue: The WO filter is not working — the specific work order does not appear in the Operation Work Order list, but when the filter is cleared, the transaction becomes visible.
Resolution: 

Screen Name: OPS WO Closure

Issue: Even though the WO created is new and no DL/WI is given against that workorder. It is still displaying the warning message 'WI open for the WO'.
Resolution: 

Screen Name: CRF Approve

Issue: Employee name is not displayed in Transaction stage. Earlier also the data flow was correct but in transaction stage it was displayed that it is being forwarded to Admin. Right now the role type shown is correct but no employee name is displayed.
Resolution: 

Screen Name: DL Upload OPRA

Issue: After uploading DL OR RA, Equipment name showing NA for all defect list.
Resolution: 

Screen Name: P1 O2 Receive

Issue: P1O2 RECEIVE : wi no is generating wrong.
Resolution: 

Screen Name: RA Approve CRF REQUEST

Issue: Not able approve Crf request for WI which created by PRM
Resolution: 

Screen Name: Approve CRF 

Issue:

1. Show WI no. for which crf is raised in detail view left side panel.
2. Approve crf Header filter for All (When filter is blank) its showing CRF for approval which is already approved, it should list of Approve crf  in disable mode, currently it is allowing reaaprove the crf which is already approved

Resolution: 

Screen Name: SFM - CRF Request

Issue: In case of offload, no EMD is given. But right now the system allows to amend EMD when CRF request is raised.
Resolution: 

Screen Name: OPRA Work Instruction

Issue: After the WI is created, when clicked on 'View WI' button from the generated WI tab. All the fields of the WI is not displayed.
Resolution: 

Enhancement

Screen Name: CRF Approval

The CRF requests once approved by MPC is not displayed in MPC login

Add filter at header level same as Rpp CRF Approve screen
WO order filter
Status : Pending, Reject, Approved, Blank filter for selected wo and Ship show All crf with status.

OPDEF

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

Bug Fixes

Screen Name: Opdef PRM Remarks Raise OPDEF

Issue: 
Only Approved Work order should display in left pannel while raising Opdef. 

Note : Also show only approved work order for below mentioned transaction.

Resolution: 


Screen Name: Opdef Center Remarks

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution:

Screen Name: Opdef Finalization

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 


Opdef WI

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

Opdef WI Release

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

Opdef Correspondence

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

Opdef Progress

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

AST/OST 

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

AMP/SMP

Issue: Only Approved Work order should display in left pannel while raising Opdef.

Note : Also show only approved work order for below mentioned transaction.

Resolution: 

Screen Name: Opdef Release WI

Issue: Opdef Release WI - IN DETAIL VIEW  EQUIPMENT NAME AND DESC SHOWING BLANK.

Resolution: 

Screen Name: CRF Request and Approve CRF request

Issue: OPDEF : IN Update tab data not showing for created CRF.

Resolution: 

Screen Name: Approve CRF Request

Issue: 

1. Show WI no. for which crf is raised in detail view left side panel.
2. Approve crf Header filter for All (When filter is blank) its showing CRF for approval which is already approved, it should list of Approve crf  in disable mode, currently it is allowing reaaprove the crf which is already approved.

Resolution: 


Other

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview


Screen Name: SWO - Standing WI

Enhancement 

1. The OPN must be incremental for every next quarter. Example, current OPN is 501, then from next Quarter (1-Jan-2026 to 31-Mar-2026) the OPN will become 601, THEN 701 AND SO ON.

After 901, the next quarter will again have OPN 101.

For every Q1, the Item number can take 2 digits of current year, i.e, 25 of 2025, 26 of 2026 etc. Item no. will be 261001 for Q1 of 2026. Therefore, WI no. will be like 01200-261001-701.

Consider Q1 = Jan-Mar, Q2 = Apr-Jun, Q3 = Jul-Sep, Q4 = Oct-Dec.

2. Following requirements are needed to be developed for fully functioning of Standing Work Instructions - 

Only Current Quarter must be auto-selected to Process/Show Data of WI list. Prohibit the Issue of WI for previous, next Quarter.
OPN No. must be processed as per procedure on 'Show Data' button to validate before Issuing WI on grid itself.
Add columns in grid for - EMD, Job Head, Job Summary, Job Description.
All date forms shown in grid to be in DD-MM-YYYY format. Ex: 25-01-2026
Quarter 1 should be Jan-Mar, Quarter 2 = Apr-Jun, Quarter 3 = Jul-Sep, Quarter 4 - Oct-Dec ----- This is for Division: Mumbai only.
Rename 'Process' button with 'Show Data'.
Show Centre Name in grid instead of loc_cd for column name 'Centre No.'
Show Already issued Work Instructions with 'Released Date' as per past Quarter selection. Keep the columns same in both Pending & Issued grid.

3. Standing WI quarter dropdown

For user testing, open all the quarters in the dropdown and allow the user to select and process past, present and upcoming quarters. Let this happen for both, Release WI and Released WI tabs.

Later for production, provide 2 header filters - Year [2025, 2026, 2027...] and Quarter [261001, 261002, 261003, 261004] selection. Then allow user to select or process only-
 1.  Current quarter and upcoming quarters of the same year - Release WI tab
 2.  Only those quarters for which past workinstructions were issued - Released WI tab




Screen Name: Work Instruction

Duplication of workinstructions in standing wo module.  Quarterly opn no should automatically change.


Bug Fixes


Issue:

Standing Work instruction  = Throwing an error on click of issue Work Instruction.

400 Bad Request

{
   "div_cd": 1,
   "item_no": "261001"
}

"user_message": "Database Integrity error: Missing required field: 'tran_no'.",
Vizag issue

Resolution: 

Issue: 


Following columns are showing wrong data in grid view of  -

1. PSD = Showing 1 year later date.
 2. PCD = Showing 1 year later date
 3. Total WI records fetched are 246 out of 448
 4. Date format should be in DD-MM-YYYY. Ex: 14-01-2026

Following columns are not passing data from wi_mst table to wi_hdr table -

1. MC no.
 2. WC no.
 3. Defect Description is hardcoded.
 4. EMD is hardcoded.

Also pass Release Date in wi_hdr table as 'Issued date' from Standing Work Instruction screen.

Resolution: 

Issue: New Data processing issues on frontend

Following columns are showing wrong data in grid view of  -

1. PSD = Showing 1 year later date.
 2. PCD = Showing 1 year later date
 3. Total WI records fetched are 246 out of 448
 4. Date format should be in DD-MM-YYYY. Ex: 14-01-2026

Following columns are not passing data from wi_mst table to wi_hdr table -

1. MC no.
 2. WC no.
 3. Defect Description is hardcoded.
 4. EMD is hardcoded.

Also pass Release Date in wi_hdr table as 'Issued date' from Standing Work Instruction screen.

Resolution: 

Shop Floor Management (SFM)

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

Enhancments

Screen Name: P1 O2 Recived : Access controls

Provision to view list of  wi as per work center wise
Once request is accepted then update Requested center as WC IN WI , and Keep Main center as Main center column.



Defect List (DL)

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Screen Name: RA upload 

Issue: QC dl class code showing blank
Resolution: 


Leave

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai + Vizag

Overview

This release includes bug fixes and enhancements to improve leave validation logic, balance calculation, reporting accuracy, and overall system stability.

Bug Fixes
Screen Name: Covering Leave

Issue 1:
For Casual Leave (CL), the system restricts leave application to the calendar year only (1 year). However, for other leave types, users can apply for past leaves without any year restriction (e.g., applying leave for 2008).

Resolution:
Year validation has been standardized. Leave applications are now restricted as per defined business rules for all leave types.

Issue 2:
While selecting Earned Leave (EL), holidays and weekly offs are incorrectly excluded from leave calculation.

Resolution:
EL leave calculation now correctly includes holidays and weekly offs as per policy.

Issue 3:
When a covering leave transaction is created, the number of leave days is incorrectly added back to the leave balance.

Resolution:
Leave balance calculation has been corrected to prevent incorrect balance adjustments.

Screen Name: Leave Conversion

Issue 1:
After applying for leave conversion and forwarding it to the next updater role, the system displays the error:
“Applied leave days exceed leave balance.”

Resolution:
Leave balance validation during conversion has been corrected.

Issue 2:
The leave selection pop-up displays past and already converted leaves.

Resolution:
Only future leaves are now displayed, and already converted leaves are excluded from the pop-up.

Screen Name: Apply Leave

Issue 1:
Leave balance is deducted at the updater edit stage instead of approval stage, causing an error during approval:
“Applied leave exceeds the balance days.”

Resolution:
Leave balance is now deducted only after final approval, preventing validation errors.

Issue 2:
Users are unable to apply for leave due to the error:
“Failed to get employee data.”

Resolution:
Employee data retrieval has been fixed.

Issue 3:
Calendar freezing rules are inconsistent across leave types.

Future calendar is frozen for Commuted Leave (already implemented).

Medical Extra Ordinary Leave does not follow the same rule.

Resolution:
Future calendar freezing has now been applied to Medical Extra Ordinary Leave as well.

Screen Name: Leave Accrual

Issue:
After selecting mandatory fields and clicking Show Data, filtering within the grid does not work.

Resolution:
Grid filter functionality has been fixed.

Screen Name: Employee Leave Report

Issue:
Data patching issues cause incorrect or incomplete report data.

Resolution:
Data patching has been corrected to ensure accurate report generation.

Screen Name: LLDL Report

Issue:
The Center No. is displayed as 0 for all centers instead of the actual center numbers.

Resolution:
Center numbers are now correctly populated in the report.

Screen Name: Absent Details

Issue:
The loader is missing, and the screen takes excessive time to load.

Resolution:
A loader has been added and performance optimized.

Screen Name: Leave Entry

Issue:
Commuted Leave is not saved, and the transaction stage is not generated after clicking Save.

Resolution:
Commuted Leave saving logic and transaction stage generation have been fixed.

Screen Name: Leave Details / Leave Card / Leave Order / Employee Leave Report

Issue:
Reports fail to open and display the error:
“An API error occurs while fetching.”

Resolution:
API integration issues have been resolved, and reports now load correctly.

Screen Name: Delay Leave Report

Issue:
Report data is not fetched. Financial year handling is unclear.

Resolution:
Data fetching issues have been fixed. Financial year selection is now handled automatically as per system configuration.

Screen Name: Leave – Absent Detail

Issue:
Incorrect data is displayed.

Resolution:
Absent detail data accuracy has been corrected.

Enhancements
Screen Name: Apply Leave

Enhancement:

Extra Ordinary Leave (Medical) and Commuted Leave now allow only past calendar dates.

Future dates are frozen for these leave types.

Screen Name: Leave Conversion

Enhancement:
After clicking Select Leaves, only EL and HPL leaves for the selected employee are displayed in the dialog box.

Screen Name: LLDL Wages Report

Enhancement:
The exported Excel file is now renamed automatically based on the generated month and year of the report.


LTC 

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Screen Name: MRO LTC

Issue: List of employees and Application Details are not showing the recently created transactions employees and application in the list of dropdowns of LTC MRO Transaction screen

BA Remark- Unable to test as it is not showing Employee list in Employee Id also in screen MRO date field is not correctly displayed.

Resolution: 

Screen Name: LTC Advance Proposal

Issue: Entitle Year and LTC By Which Travel is proposed, and Place of Visit is getting Blank After Forwarding to next updater Role and Next Updater is opened it in Edit Mode
Resolution: 

Screen Name:  LTC Advance Proposal

Issue: In LTC Advance Proposal if selected Self and Family from "LTC For" then in Add Family Members all family members details are reflecting if I'm selecting only 2 out of 5 family members then after forwarding to next updater role and next updater role is opened that transaction in edit mode then Add Family Members is still editable and all the family members is getting selected automatically instead out selected only 2 members while initiating the form.
Resolution: 

Screen Name: LTC Advance Proposal

In DB - Terminal ID, Nearest railway station, To station are passing data as a string

while doing a save as a draft then in Transaction doc_no. , GPF Pran no., Family details, Active yn value is 0 for all, Mode of travel is blank

Resolution: 

Screen Name: LTC Claim Application

Issue: Terminal_id, GPF pran no., app_by, app_dt, active_yn, and add LTC_proposal id (reference of LTC Advance proposal table primary key)
Resolution: 

Screen Name: LTC Leave Encashment

Issue: ltc_leave_encashment, terminal_id, app_by, active_yn, data is N/A and add column ltc_proposal_id reference of ltc_advance_proposal
Resolution: 

Screen Name: LTC Advance Proposal

Issue: Unable to run the flow as after filling all the details and forwarding to next updater role it is showing an error of "aaa" which is related to invalid family Id.
Resolution: 

Screen Name: LTC Advance Proposal

Issue: Date of Retirement data is not available.
Resolution: 

Screen Name: LTC Advance Proposal

Issue: The transaction is not getting saved.
Resolution: 

Screen Name: LTC Advance Proposal 

Issue: Duplicate employees and transactions are coming for one employee.
Resolution: 

MIS

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

This release includes a bug fix to restore proper functionality of the Service Request feedback feature.

Bug Fixes
Screen Name: Service Request Feedback

Issue:
The Service Request feedback functionality does not work correctly. When users enter feedback details and hover over the Add Feedback button, the required parameters are not displayed. On clicking Save, the system throws an error.

Resolution:
The feedback screen now correctly displays all required parameters, and feedback can be saved successfully without errors.


Personnel

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

This release includes a bug fix and an enhancement to improve data accuracy and access control in the Personnel module.

Bug Fixes
Screen Name: Employee Master

Issue:
In the Add Previous dialog box, the spelling for Experience is incorrect.

Resolution:
The spelling error has been corrected.

Enhancements
Screen Name: Employee Master

Enhancement:
CEO Preview Print access has been enabled in Save as Draft mode.



BTMS

Version: V1.14.65
Release Date: 31-01-2026
Division: Mumbai

Overview

This release introduces a new reporting requirement in the BTMS module.

New Requirement
Report Name: Movement Order Report

Requirement:
A new report titled Movement Order Report is to be developed to support tracking and reporting of movement order detail.


Module Name: Yard Utility (YUS)
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Enhancement
Screen Name: Service Requisition

Issue: The WI (Work Instruction) listing behavior in Yard Utility does not clearly differentiate between Ship and Non-Ship scenarios, leading to inconsistent
For Ship-based operations:
Display Work Instructions only for the selected Ship and Center.
Filter Work Instructions based on centers mapped to the logged-in user.
Use the Work Center field in the WI master for filtering logic.

For Non-Ship operations:
Display only Standing Work Instructions.
Ensure Standing Work Instructions support and adhere to the Center concept.

Resolution: WI listing has been enhanced to handle Ship and Non-Ship scenarios distinctly. The system now enforces center-based filtering aligned with user
mappings and ensures Standing Work Instructions are correctly associated with centers for Non-Ship operations.


Module Name: SWM - PAY
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Overview: This release introduces enhancements and fixes in the SWM – PAY module to improve Industrial payroll data upload, salary reporting accuracy, and
certificate generation. The changes focus on better data validation, standardized processing, and correction of calculation and reporting inconsistencies for
the Mumbai division.

Division: Mumbai
New Requirement
Screen Name: Industrial Salary Upload

New Update: There was no standardized mechanism to upload Industrial payroll data received from CDA, resulting in potential data inconsistency and lack of validation
during salary processing.

Provision added to upload Industrial Pay Excel (CDA format) into Navyojana.
File upload is supported in a single shot for all Industrial employees.
Employee Type is defaulted to INDUSTRIAL during upload.
Salary Month is mandatory before initiating upload.

Validation rules implemented:
Salary for the same month cannot be uploaded multiple times.
Employees are validated against the Employee Master.
If any record fails validation, the entire file upload is blocked.
System prevents salary month selection from the UI if salary is already uploaded for that month.

Division Vizag and Mumbai
Bug Fix
Screen Name: Last Pay Certificate / Income Statement

Issue: Income Statement and Last Pay Certificate reports displayed data inconsistencies such as incorrect month order, improper signature rendering, duplicate employee count, and invalid bank details.

Resolution: Corrected month sequencing in Income Statement.
Fixed signature data rendering issues.
Resolved duplicate employee count in Last Pay Certificate.
Corrected bank particulars data mapping.
Last Pay Certificate issues are now fully closed.

Bug Fix
Screen Name: Pay Certificate

Issue: Salary component calculations in the Pay Certificate were not matching payroll data.

Resolution: Pay Certificate calculation logic has been corrected to align with payroll computations, ensuring accurate salary figures.


Module Name: SWM - GPF
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Enhancement
Screen Name: Update GPF Closing Balance

Issue: The GPF Closing Balance update screen was displaying employee records beyond the scope of the logged-in user’s Control Cell, leading to incorrect
employee visibility.

Control Cell location is now mapped to the corresponding system location.
The Employee ID dropdown is restricted to display only employees belonging to the logged-in user’s Control Cell.

Resolution: Employee visibility in the GPF Closing Balance update screen has been restricted based on the logged-in Control Cell location, ensuring accurate
and secure data access.

Amit Patil (TW): Module Name: SWM - TAX
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Enhancement
Screen Name: IT Declaration

Issue: When an IT Declaration was approved directly, the approved amount fields were not being populated automatically, leading to incomplete approval data.

On direct approval of an IT Declaration, all applicable amounts are now automatically populated as Approved Amounts.

Resolution: The approval workflow has been enhanced to default all amounts to approved values when a transaction is approved directly.

Quality Check Management (QCMS)
Version: V1.14.65
Release Date: 31-01-2026
Divisions: Vizag and Mumbai

Overview:
This release enhances the Quality Check Management System (QCMS) by improving equipment management, QC request visibility, role-based access control, status
tracking, and inspector-specific access. The changes streamline PRM and Control Cell workflows, improve data accuracy, and address performance and validation issues across QC operations for Vizag and Mumbai divisions.

Enhancement
Screen Name: Add Equipment

Issue: In the WI Add Equipment transaction, the equipment name field was incorrectly rendered, preventing PRMs from adding equipment details against a released Work Instruction.
Provision added to enter Equipment Name correctly in the grid.
PRM can now add multiple equipment against a single Work Instruction.
Added provision to select these equipment while raising a QC request.
The Equipment dropdown in the Raise QC Request screen now lists all equipment added against the selected WI, allowing single or multiple selection.

Resolution: Equipment management has been enhanced to support multiple equipment mapping per WI and enable seamless selection during QC request creation.

Bug Fix
Screen Name: Assign QC Inspector

Issue: The center name displayed in the Assign QC Inspector grid did not match the work center selected during Work Instruction creation.
Column Location renamed to Main Center.
Column Center No. renamed to Work Center.
Main Center and Work Center now display values as defined during WI creation.

Resolution: Center details are now consistently displayed, improving clarity during QC Inspector assignment.

Enhancement
Screen Name: Raise QC Request
Issue: The Raised QC Request tab displayed only the Approved status, providing limited visibility into request progress.

The following statuses are now displayed with pending responsibility visibility:
Pending for Assigning Inspector – Inspector not assigned
Pending for IIR – Inspector assigned, IIR not generated
IIR In Progress – IIR generated but not completed
IIR Completed – Final remarks marked as QC Cleared and Job Completed
VRF Pending – IIR completed, VRF not generated (Offloaded QC)
I-Note Pending – VRF generated, I-Note not generated (Offloaded QC)

Resolution: QC request status tracking has been enhanced to provide clear, actionable visibility across all stages.

Enhancement
Screen Name: Raise QC Request
Issue: L2 Work Instructions were visible to Control Cell users during QC request creation, leading to unauthorized access.

For Control Cell Login:
Display only released WIs that are not closed.
Display WIs mapped to the logged-in Main Center or Work Center.
Display only WIs with QC Level L3.

For PRM Login:
Display only WIs assigned to the logged-in PRM.
Display only released WIs that are not closed.
Display WIs with QC Levels L1 and L2 only.

Resolution: QC request access has been restricted based on role, center, and QC level, ensuring controlled and compliant processing.

Enhancement
Screen Name: Raise QC Request

Issue: Users were unable to view details of the raised QC request in downstream screens.
Provision added to view raised QC request details in:
Assign QC Inspector screen
Instant Inspection Report (IIR) screen

Resolution: QC request details are now accessible across related screens for better traceability.

Bug Fix
Screen Name: Raise QC Request

Issue: QC requests could not be saved when Offload was set to No due to vendor field validation issues.

Resolution: Vendor field validation has been corrected, allowing successful QC request submission when Offload is set to No.

Screen Name: Raise QC Request

Issue: The Raise QC Request form experienced excessive load times for L3 cases under Control Cell login.

Resolution: Data loading logic has been optimized to reduce screen load time and improve performance.

Bug Fix
Screen Name: QC Level

Issue: Operational Work Instructions were not visible for QC level assignment in QC Manager and Senior Manager screens.

Resolution: Operational WIs are now correctly displayed for QC level assignment.

Enhancement
Screen Name: IIR (Inspection & Inspection Report)
Issue: QC requests were visible to all inspectors, even when assigned to a specific inspector.

Resolution: QC requests now appear only in the login of the inspector assigned to that QC request.


TY Duty

Version: V1.14.66
Release Date: 03-02-2026
Divisions: Mumbai

Overview

This release includes a bug fix to improve usability in the Advance CDA Approval workflow.

Bug Fixes
Screen Name: Advance CDA Approval

Issue:
Filters and pagination are not working correctly in the Advance CDA Approval screen.

Resolution:
Filter and pagination functionality has been fixed and now works correctly in the Advance CDA Approval screen.


Leave

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Bug Fixes
Screen Name: Leave Absence Report

Issue:
Data is not fetched in the Leave Absence Report.

Resolution:
Data fetching logic has been fixed, and the Leave Absence Report now displays data correctly.


LTC 

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Bug Fixes
Screen Name: LTC Leave Encashment

Issue:
In the LTC Leave Encashment screen, the EL Current Balance field is displayed as N/A while applying for encashment. As a result:

EL balance is not reflected correctly for eligible employees.

Validation rules related to EL balance and encashment are not enforced consistently.

Previously applied EL encashment details are not displayed correctly.

EL balance may change at incorrect workflow stages.

Expected Functional Behavior:

All employees who have applied for LTC should appear in the Employee ID dropdown.

Corresponding LTC applications should populate based on the selected employee.

EL Current Balance should display the employee’s available EL balance.

EL balance should be deducted only after final approval, not during forward stages.

Approved encashments should not reappear in the LTC Application dropdown.

Previously applied EL encashments should be displayed at the bottom of the form.

Business Rules:

EL balance must be greater than 40.

Employee must have applied Leave with LTC for the block year.

Maximum 10 EL can be encashed per request.

Maximum 6 encashments allowed.

Encashment can be claimed twice within a block of 4 calendar years.

If EL balance is 40 or below, encashment should not be allowed.

Resolution:

EL Current Balance is now correctly fetched and displayed for the selected employee.

All LTC-applied employees and related applications are populated correctly.

EL balance deduction now occurs only after final approval, as per the approval hierarchy.

Validation rules for EL balance, encashment limits, and block-year eligibility have been enforced.

Approved encashment applications are excluded from the LTC Application dropdown.

Previously applied EL encashments are now displayed correctly in the form.

Personnel 

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview


Bug Fixes

Screen Name: Annual Increment

Issue 1: When the transaction is saved, the save button is not getting disabled neither the grid.
Resolution: 

Issue 2: Data is not correctly updating. When some users are deleted.
Resolution: 

UI Enhancement

1. Required new Dropdown value in Transfer out of Dockyard in field "Probation lifted iro of the employee- "Not Applicable".

Screen Name: CEO Transaction
1. CEO Type- In Fresh Appointment field name "Group of the Post" require dropdown as - A, B-NG, B-G, C".
2. In CEO- Lifting of Probation and Confirmation- in field "Probation Period for the Post as per SRO (in Years)" required only till 1,2,3,4 Dropdown value instead of 1 to 7.
3. In Ceo - Declaration of Schedule CASTE only keep- GEN, OBC AND ST.



Personnel

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview

This release includes bug fixes and UI enhancements to improve data integrity, control behavior, and dropdown standardization in Personnel transactions.

Bug Fixes
Screen Name: Annual Increment

Issue 1:
After saving the transaction, the Save button and grid remain enabled.

Resolution:
The Save button and grid are now disabled after a successful save.

Issue 2:
When some users are deleted, the data in the grid is not updated correctly.

Resolution:
Data refresh and update logic has been fixed to ensure accurate grid updates after user deletion.

UI Enhancements
Screen Name: Transfer Out of Dockyard

Enhancement:
A new dropdown value “Not Applicable” has been added to the field:
“Probation lifted in respect of the employee.”

Screen Name: CEO Transaction

Enhancement 1:
In Fresh Appointment, the field “Group of the Post” is now provided as a dropdown with the following values:

A

B-NG

B-G

C

Enhancement 2:
In Lifting of Probation and Confirmation, the field
“Probation Period for the Post as per SRO (in Years)” now allows only the following dropdown values:

1

2

3

4

Enhancement 3:
In Declaration of Schedule Caste, the available dropdown values are now restricted to:

GEN

OBC

ST

Refit Planning (RPP)

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview

This release introduces UI enhancements to improve data control and clarity in RPP transactions, along with a bug fix related to refit type data fetching.

UI Enhancements
Screen Name: P1/O2 Raise

Enhancement:

Assistant PRM is now a mandatory field.

Screen Name: RPP – WO Amendment Date

Enhancement 1:

A new field “WO Amend Date” has been added.

The field is auto-populated with the current date on form load and remains editable.

This date represents the effective amendment date of the RPP work order.

Enhancement 2:

The WO Date field is now disabled for editing.

WO Date represents the date when the work order was first created as Draft.

A new display-only field “WO Approved Date” has been added to show the date on which the work order was finally approved by GM(R).

Enhancement 3:

Selection of Refcomp Date and DTG has been disabled in this transaction under the Refcomp tab.

Bug Fixes
Screen Name: RPP – WO Amendment Date

Issue:
The Refit Type is not fetched correctly in this transaction. For work orders with ra_flag, the refit type value retrieved from the database is mismatched (e.g., R is incorrectly fetched as O).

Resolution:
The refit type fetching logic has been corrected to align with the approved work order, ensuring accurate refit type values are displayed during WO amendment.
 
OPDEF

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview

This release introduces UI enhancements to improve data control.

UI Enhancements
Screen Name: P1/O2 Raise

Enhancement:

Assistant PRM is now a mandatory field. 

OPRA 

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview

This release introduces UI enhancements to improve data control.

UI Enhancements
Screen Name: P1/O2 Raise

Enhancement:

Assistant PRM is now a mandatory field.


Time Keeping (TKS)

Version: V1.14.66
Release Date: 03-02-2026
Division: Mumbai

Overview

UI Enhancement
Screen Name: Deassign Screen
Enhancement:
A task confirmation popup has been introduced for the Deassign screen to displays the employee proper. 


SWM - GPF
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Enhancement

Screen Name: GPF Increase Decrease

Issue: Centre list was not restricted based on the logged-in user role.

Resolution: Updated the system to display centres based on the logged-in user’s role.

SWM - PAY
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Enhancement
Screen Name: DA Master

Issue: Applicable_From_Date added in DA Master table. This impacts DA Arrears processing.

Resolution: Applied patch to control DA arrears calculation based on Applicable_From_Date.

Quality Control Management (QCMS)
Version: V1.14.66
Release Date: 03-02-2026
Divisions: Vizag and Mumbai

Overview:
QCMS is a system used to manage and monitor quality control activities for work instructions. It helps in assigning QC inspectors, raising QC requests, tracking inspection progress, and maintaining quality compliance. The system ensures proper workflow management, role-based access, and accurate recording of inspection results, improving overall quality assurance and operational efficiency.

Enhancement
Screen Name: Assign QC Inspector

Issue 1: Incorrect center name displayed in grid view. Column naming was unclear.
Resolution: Updated grid to display Main Center and Work Center as per Work Instruction.
Renamed columns:
Location → Main Center
Center No. → Work Center

Screen Name: Raise QC Request
Issue: Status column displayed only Approved status. Pending status and workflow visibility were not available.

Resolution: Enhanced status display with workflow tracking:
Pending for Assigning Inspector
Pending for IIR
IIR In Progress
IIR Completed
VRF Pending (Offloaded QC)
I-Note Pending (Offloaded QC)

Enhancement
Screen Name: Add Equipment

Issue: Equipment name could not be added properly while adding equipment against Work Instruction. Equipment selection was not available during QC request.
Resolution: Enabled equipment name entry while adding equipment.
Allowed multiple equipment entries against a single Work Instruction.
Updated Raise QC Request screen to allow selection of added equipment.

Bug Fix
Screen Name: IIR

Issue: QC requests were visible to all inspectors instead of only the assigned inspector.
Resolution: Updated system to display QC requests only to the assigned inspector.

Screen Name: WI Add Equipment
Issue: Work Instructions (WI) were not filtered based on QC level and user role.
All WIs were visible to PRM role even for Level L3.
Control Cell users were unable to view WIs or add equipment.

Resolution: Implemented role-based WI visibility.
L1 & L2 WIs are visible to assigned PRM.
L3 WIs are visible to respective Control Cell centers for request raising and equipment addition.

Screen Name: WI Add Equipment

Issue: System displayed errors “No Ship Found” and “No Records Found” after selecting ship and clicking Show Data (Control Cell login).
Resolution: Fixed data loading issue to display correct records after ship selection.

Screen Name: QC Level

Issue: QC Level Date column remained blank after assigning QC level for WIs (RPP, RA, OPDEF).

Resolution: Updated system to display QC Level assignment date in the QC Level Date column.

Issue:
In the transaction dashboard, the Ship is available for selection, but it is not displayed inside the WO Amendment transaction screen.

Details:

OPS WO Amendment:

The WO is available for amendment, but the Ship name is not displayed in the header filter.

Refit WO Amendment:

The Ship name is not displayed in the header filter.

The WO is also not appearing for amendment.

Resolution:
The ship and work order fetching logic has been corrected. The Ship name now appears correctly in the header filter, and eligible work orders are displayed properly for both OPS and Refit WO Amendment transactions.


Screen Name: SFM – CRF Request

Issue:
Once a CRF request is approved, the name of the approving employee is not displayed.

Resolution:
The approving employee’s name is now correctly displayed after CRF approval.


LTC

Version: V1.14.66
Release Date: 04-02-2026
Divisions: Mumbai

Overview

Screen Name: LTC Advance Proposal
Issue: Once transaction of LTC advance proposal saved the application number is not getting generated after approval.
Resolution: 

Screen Name: LTC claim Application
Issue: Data not Forward/ Approve.
Resolution: 

Manpower Booking (MPB)

Version: V1.14.66
Release Date: 04-02-2026
Divisions: Mumbai

Overview

This release includes enhancements and fixes to improve overtime booking screens and ensure accurate reporting of employee allocations.

UI Enhancements
Screen Name: Overtime Booking – Industrial / Non-Industrial (Including Amendment Screens)

Enhancement:
Dropdown values have been removed from the OT Booking (Industrial and Non-Industrial) screens and their respective Amendment screens, as per updated business requirements.

Screen Name: Allocation Report

Issue 1:
Although there are two allocation transactions, only one transaction is displayed in the Allocation Report.

Issue 2:
If a single employee is allocated multiple times, the report displays the employee only once instead of showing each allocation separately.

Expected Behavior:
Each allocation transaction for an employee should be displayed as a separate entry in the report.

Resolution:
The Allocation Report logic has been corrected to display all allocation transactions, ensuring that multiple allocations for the same employee are shown as separate records.


Personnel

Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Overview

This release includes a new requirement and a UI enhancement to improve data visibility and usability in Personnel transactions.

New Requirement
Screen Name: Civilian Establishment Order

Issue:
The CEO Type data is not displayed in the Civilian Establishment Order transaction dashboard grid coloumn.

Resolution:
CEO Type data is now fetched and displayed in the transaction dashboard grid coloumn.

UI Enhancements
Screen Name: Technical Resignation from Service

Enhancement:
A new field “Date of Application” has been added to the Technical Resignation from Service screen.

Time Keeping (TKS)

Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Overview

This release includes bug fixes to ensure correct attendance, time card, and reporting behavior, along with enhancements to improve OT finalization logic and balance adjustments.

Bug Fixes
Screen Name: Amend Attendance Punches

Issue:
When users amend attendance punches (such as changing shift, in-time, or out-time) and click Save, the updated entries do not reflect in the Time Card and other related TKS reports.

Resolution:
Attendance amendment logic has been fixed. All changes made through Amend Attendance Punches now correctly reflect in the Time Card and all dependent reports.

Screen Name: Time Card

Issue 1:
After OT Finalization, the Time Card and other TKS reports incorrectly display Late In, Early Out, and Work Hours for Sundays, Holidays, and Weekly Off days.

Resolution:
The Time Card and reports now correctly suppress Late In, Early Out, and Work Hours for Sundays, Holidays, and Weekly Off days after OT Finalization.

Issue 2:
Before OT Finalization, the status is shown as XX. However, after OT Finalization:

Weekly Off days should show status XW

Holidays should show status XH

Currently, the system continues to show XX, which is incorrect.

Resolution:
Post OT Finalization, status codes are now updated correctly:

XW for Weekly Off

XH for Holiday

Screen Name: Amend Attendance

Issue:
The dropdown option “Boat/Train/Bus Late – 1 Session” is available for all shifts without proper validation.

Expected Behavior:

This option should be selectable only if punch-in time is between shift start time and up to 2 hours after shift start.

If punch-in exceeds 2 hours, the system should restrict selection and display an error message.

When selected within the valid window:

Punch-in time should be automatically updated to the shift start time.

The option should be allowed only twice per month, as per TKS rules.

Resolution:
Validation logic has been implemented to enforce time limits, automatic punch-in correction, monthly usage limits, and error handling as per TKS rules.

Enhancements
Screen Name: OT Finalization – Night & Server Duty OT and WI Balance

Enhancement:
OT balance adjustment logic has been enhanced to correctly handle Night Duty, Server Duty, Quarterly OT, Weekly OT, and WI balances.

Updated Behavior:

Booked OT = 10.5, Actual OT = 10.5, Final OT = 4 / 3.5 (01 / 02 shift)
→ Excess OT (6.5 / 7) is reverted back to Quarterly and Weekly OT balances.

Booked OT = 10.5, Actual OT = 3, Final OT = 3
→ Remaining 7.5 OT is reverted back to Quarterly, Weekly, and selected WI balances.

Booked OT = 10.5, Actual OT = 7, Final OT = 4 / 3.5
→ Excess OT is distributed correctly between Quarterly OT, Weekly OT, and selected WI balance based on shift type.

Actual OT is now restricted to not exceed Booked OT.


Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Overview



SWM - TAX
Version: V1.14.66
Release Date: 05-02-2026
Divisions: Vizag and Mumbai

Overview
This release includes corrections in TDS calculation, reporting accuracy, and data display standardization. The update ensures compliance with payroll taxation
rules, improves validation controls, and resolves inconsistencies in employee tax reports.

Enhancements
Screen Name: Rejected IT Declaration

Issue 1: HRA amount was displayed on an annual basis instead of a monthly basis.
Resolution: Updated the HRA display logic to show the amount on a monthly basis as per taxation declaration standards.

Screen Name: Month-wise TDS

Issue 2: Tax and cess amounts were calculated incorrectly, though total tax was correct.
Resolution: Corrected the tax and cess calculation logic to ensure accurate component-wise values.

Issue3: Pay Month field was not mandatory.
Resolution: Implemented mandatory validation for the Pay Month field.

Issue 4: Absent late recovery amounts were incorrectly included in gross values for TDS calculation.
Resolution: Updated logic to exclude absent late recovery from gross TDS calculations.

Issue 5: Employee count in the report was inconsistent.
Resolution: Corrected report generation logic to ensure accurate employee count.


Other – SWO 

Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Overview

This release includes enhancements to the quarter selection logic for Standing Work Instructions (SWO) to ensure controlled WI release and improved data visibility.

Enhancements
Screen Name: SWO – Standing Work Instruction

Enhancement Details:

Release WI Tab

Only the current quarter is visible and selectable during the active quarter date range.

Work Instructions for the next quarter can be released only in the respective quarter.

The Year filter is not required for this tab, as only the current quarter is shown at all times.

Released WI Tab

All quarters for which Work Instructions have already been issued are displayed.

Users can filter records using the Year and Quarter options in the header.

The existing deployed behavior remains unchanged and continues to work as expected.



Defect List (DL)

Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Bug Fixes

Issue:
After uploading the RA, the OPRA No. column is displayed as blank.

Resolution:
The OPRA number is now correctly populated and displayed after RA upload.

OPDEF

Version: V1.14.66
Release Date: 04-02-2026
Division: Mumbai

Bug Fixes / Requirement
Screen Name: OPDEF Remark

Issue:
PRM remarks cannot be entered because the WO No. field displays multiple duplicate entries for the same work order. Selecting any one of these entries results in the error “No Data Found.”

Resolution:
Duplicate work order entries have been removed, and the WO selection logic has been fixed. PRM remarks can now be entered successfully without errors.


Refit Planning (RPP)

Version: V1.14.66
Release Date: 07-02-2026
Division: Mumbai

Overview

Bug Fixes

Screen Name: P1/O2 Release WI
Issue 1: In grid view, show Request center , assistance center name instead of number. Also 'Item number' column remains blank.
Request center and assistance center displayed is wrong 

Resolution:

Issue 2: P1/02 Release :Main center field,QC Level field remains blank.
Resolution: 

Screen Name: DL – Assign PRM
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Assing PRM.
Resolution: 

Screen Name: DL - AA Remark(HQ)

Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
AA Remarks.
Remarks: 

Screen Name: RPP-PRM Remarks
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Prm Remarks.
Resolution: 

Screen Name: Ship Staff Remarks
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Ship Remarks.
Resolution: 

Screen Name: DL-Center Remarks
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Center Remarks.
Resolution: 

Screen Name: DL- Finalization
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
DL Finalization.
Resolution: 

Screen Name: Work Instruction
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
WI Creation.
Resolution: 

Screen Name: Release WI
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
WI Release.
Resolution: 

Screen Name: Approve CRF Request 
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Approve CRF.
Resolution: 

Screen Name: COMCOS Remarks
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
COMCOS Remarks.
Resolution: 

Screen Name: WI Amendment
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
WI Amendment.
Resolution: 

Screen Name: E&R Job Status
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
E & R Job status.
Resolution: 

Screen Name: WI Closure
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
WI Closure.
Resolution: 

Screen Name: Refit Completion
Issue: Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Refit Completion.
Resolution: 

Screen Name: CRF Request
Issue: RPP -Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
CRF Request.
Resolution: 

Screen Name: ASSISTANT WI P1/O2 Raise
Issue: RPP - Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Assistant WI - P1O2 Raised.
Resolution: 

Screen Name: ASSISTANT WI P1/O2 Receive
Issue: RPP - Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Assistant WI - Recived.
Resolution:

Screen Name: Part Landing Intimation
Issue: RPP- Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Part Landing Intimation.
Resolution: 

Screen Name: Receipt and Dispatch
Issue: RPP - Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
Reciept and Dispatched.
Resolution: 

Screen Name: RPP - Only Approved WORK Order to be shown in header filter for Mentioned Transaction.
WI Progress.
Resolution: 

Enhancement
Screen Name: Ship Staff Remarks

Provision to validate the WO DCD OR Revise DCD while uploading DL Or RA

1. Check dcd or revise dcd of wo is less than or equal to current date then do not allowed to upload. Show warning msg " Revise WO end date".

Screen Name: DL Upload RPP 
1. If it is greater than to current date then allowed to upload.


Refit Planning (RPP)

Version: V1.14.66
Release Date: 07-02-2026
Division: Mumbai

Overview

This release focuses on bug fixes across multiple RPP screens to ensure that only Approved Work Orders are available for transaction processing. Additionally, validation enhancements have been implemented during document uploads to prevent incorrect WO end dates.

Bug Fixes
Screen Name: P1/O2 Release WI

Issue 1:

In Grid View, Request Center and Assistance Center names were displayed as numbers.

Item Number column remained blank.

Incorrect Request Center and Assistance Center were displayed.

Resolution:

Request Center and Assistance Center names are now displayed correctly instead of numeric codes.

Item Number column is now populated correctly.

Correct mapping of Request Center and Assistance Center ensured.

Issue 2:

Main Center field and QC Level field remained blank in P1/O2 Release.

Resolution:

Main Center and QC Level fields are now populated correctly based on the selected Work Order.

Approved Work Order Filter Fix (Common Across Screens)

Issue:
For the mentioned transactions, non-approved Work Orders were appearing in the header filter.

Resolution:

Only Approved Work Orders are now displayed in the header filter for the following screens:


Enhancements
Screen Name: Ship Staff Remarks

Enhancement:
Validation added for WO DCD / Revised DCD during DL or RA upload.

Logic Implemented:

If WO DCD or Revised DCD is less than or equal to the current date, upload is not allowed.

System displays warning message:
“Revise WO end date.”

Screen Name: DL Upload – RPP

Enhancement:

If WO DCD or Revised DCD is greater than the current date, DL upload is allowed.





Module Name: SWM - PAY
Version: V1.14.66
Release Date: 09-02-2026
Divisions: Vizag and Mumbai

Overview
This release focuses on improvements in Supplementary Salary processing and Pay Slip reporting accuracy. The update resolves data inconsistency issues,
enhances employee visibility in salary-related workflows, and introduces additional reporting flexibility as per revised business requirements. The
enhancements ensure improved payroll data reliability and user accessibility.

Division: Mumbai
Screen Name: Supplementary Salary Entry

Issue: After selecting the month, the system downloads an Excel file but does not display accurate employee data.
The report should include:
Employees who joined the dockyard during the selected month.
Employees whose salary is on hold during the selected month.
Employee selection popup displays limited employee records based only on the Excel data.
Employee popup should display all eligible employees irrespective of Excel data filtering.

Resolution: Corrected logic for Excel data generation to include:
Employees joining the dockyard in the selected month.
Employees with salary hold status for the selected month.
Modified employee popup to display complete employee master data instead of filtered Excel data.
Improved data fetching logic to ensure consistency between popup data and backend employee records.

Screen Name: Pay Slip
Division: Vizag

Issue: Certain payroll components were not updated in the Preprinted Pay Slip report:
OTA
GPF & CPF Subscription
PCA Advance
Requirement to include an optional Center column in the Pay Slip report.

Resolution: Updated report data mapping to ensure correct display of OTA, GPF, CPF subscription, and PCA Advance values.
Added Center column as a non-mandatory field in the Pay Slip report template.
Ensured backward compatibility with existing report configurations.


TKS
Version: V1.14.66
Release Date: 09-02-2026
Divisions: Mumbai

Overview

This release includes corrections in attendance processing, overtime calculations, reporting accuracy, and format standardization across TKS reports. The
update resolves calculation discrepancies, improves leave status visibility, corrects update functionality, and aligns report output formats with business
requirements.

Bug Fix
Screen Name: Wages Export Report
Issue: Time values in report columns were displayed using “:” format (Example: 08:00) instead of required format (Example: 0800).

Resolution: Updated report formatting logic to display time values without colon separators as per export report standard.

Enhancement
Screen NAme: Time Card
Issue: Overtime (OT) column total was calculated using numeric summation instead of interval-based time calculation, resulting in incorrect totals.

Resolution: Modified OT calculation logic to compute total overtime using time interval aggregation.

Screen Name: Time Card / Reports
Issue: Employees applying for leave were displayed with status “LL” in reports. As per requirement, status should be displayed as “AA”.

Resolution: Updated leave status mapping across TKS reports to display employee status as “AA” for applicable leave scenarios.

Bug Fix
Screen Name: Amend Attendance Punches

Issue: When Punch Out time was updated earlier than Shift Out time:
Reports incorrectly displayed employee status as “XX”.
Early Out duration was not calculated.

Resolution: Corrected attendance evaluation logic to:
Display employee status as “AA”.
Calculate Early Out duration after considering grace period.

Screen Name: Amend Attendance Punches

Issue: Update functionality failed due to incorrect date value passed during update mode.

Resolution: Corrected date parameter handling in update mode to ensure proper transaction updates.

Screen Name: Excess OT Hours

Issue: When shift was amended for an absent employee:
Time Card reflected correct attendance.
Excess OT Hours screen showed incorrect attendance error.
Comp Off booking was blocked due to incorrect validation.

Resolution: Aligned attendance validation logic in Excess OT Hours screen with Time Card processing to ensure accurate attendance status and allow Comp Off booking.

OPDEF

Version: V1.14.66
Release Date: 07-02-2026
Division: Mumbai

Overview

This release addresses critical display and validation issues in OPDEF Work Instruction processing and strengthens finalization checks across RPP, OPRA, and OPDEF workflows.

Bug Fixes
Screen Name: OPDEF – WI Release

Issue:

In OPDEF Release WI, WO Number column remained blank in the grid view.

Resolution:

WO Number is now displayed correctly in the grid view during OPDEF WI Release.

Screen Name: Work Instruction

Issue:

While creating a Work Instruction, the PRM field remained blank even though PRM had already been finalized in the corresponding DL.

Resolution:

PRM details are now fetched correctly from the finalized DL and populated in the Work Instruction screen.

Enhancements / Validations
Finalization Validation (RPP / OPRA / OPDEF)

Applicable Screens:

DL Finalization

RA Finalization

OPDEF Finalization

Issue:

System allowed finalization even when no final COSMOS remarks were provided for at least one PRM.

Resolution / Enhancement:

A validation has been added during finalization.

If DL / RA / OPDEF status is set to Finalized and final COSMOS remarks are missing for any PRM, the system will block the action and display the message:

“Please provide final COSMOS remarks for PRM.”

Shop Floor Management (SFM)

Version: V1.14.66
Release Date: 07-02-2026
Division: Mumbai

Overview

This release includes bug fixes to improve label accuracy and data consistency in P1/O2-related transactions across SFM screens.

Bug Fixes
Screen Name: P1/O2 Received

Issue:

Left panel was incorrectly displaying OPDEF No. label for RA defects.

Resolution:

Label in the left panel has been corrected to display the appropriate RA defect reference instead of OPDEF No.

Screen Name: Assistant WI – P1/O2 Raise

Issue:

For RPP / OPRA / OPDEF transactions under P1/O2 Status, MC No. and WC No. were displayed as the same status.

Resolution:

MC No. and WC No. are now displayed correctly with their respective status.

OPRA

Version: V1.14.67
Release Date: 09-02-2026
Division: Mumbai

Overview

This release focuses on resolving issues related to PRM deletion functionality, approval workflow visibility for specific roles, incorrect item number generation in WI Release, and missing item number display in the P1O2 Release screen.

Bug Fixes

Screen: RA Assign PRM

Issue:
The user was unable to remove the PRM from the Detail View, as there was no delete option available in Detail View mode.

Resolution:
The delete option is provide in the Detail View mode, allowing the user to remove the PRM successfully.

Screen Name: OPS WO Approval

Issue:
The Approve option was missing from the Transaction Stage drop-down for the G(MR) role.

Resolution:
The issue has been resolved, and the Approve option is now available in the Transaction Stage drop-down for the G(MR) role.

Screen Name: RA WI Release

Issue: The RPP-02 or second WI item number was generated incorrectly and displayed wrongly in the WI History and WI Display screens.

Resolution: The item number generation logic was corrected. The WI History and WI Display screens now reflect the correct RPP-02 item number.

Screen Name: RA P1O2 Release

Issue: The Item Number field appeared blank in the P1O2 Release screen.

Resolution: The issue has been resolved, and the Item Number is now correctly displayed in the P1O2 Release screen.

Admin 

Version: V1.14.67
Release Date: 09-02-2026
Division: Mumbai

Overview

Enhancement

Screen Name: Ship Master

When a new ship is created, it must be auto linked to all the roles except Role Type having Ship staff and COSM. COSM will be linked in the Ship Master itself.

Shop Floor Management

Version: V1.14.67
Release Date: 09-02-2026
Division: Mumbai

Overview

This release update ensures better tracking of request statuses and enhances communication between involved departments.

Enhancement

Screen Name: ASSISTANT WI P1/O2 Raise

After a P1 is raised, the status of the raised request is now displayed to the respective center. This enhancement improves visibility and allows the concerned center to track the progress of the request in real time..

Other

Version: V1.14.67
Release Date: 09-02-2026
Division: Mumbai

Overview

This release ensure correct data display across environments and streamline the SWO process flow for the Mumbai Division.

Bug Fixes

Issue:
In the NUD environment, the Raise Request Assistance grid was incorrectly displaying the Requesting Centre’s PRM and Centre Name under the Assistant PRM and Assistant Centre fields.

This issue was not observed in the UAT server.

Resolution:
The data mapping issue in the NUD environment has been corrected. The Assistant PRM and Assistant Centre fields now display the appropriate values as per the workflow.

Enhancements
Screen Name: SWO – IDWR Process Flow

The updated workflow for IDWR is as follows:

Raise Assistance by Centre 1 → Accept Assistance by PRM 2 (on behalf of Centre 2) → Generate WI by Planner (MPLS/MYCS)

Note:
The program “Finalized Assistance” in SWO is not applicable to the Mumbai Division.

Screen Name: SWO – Generate WI

The following enhancements have been implemented:

The SWO dropdown now displays the WO Description exactly as shown in the Raise Request Assistance screen of SWO.

The following fields have been removed as they are not relevant:

QC Level

Authority

Job Location

The PRM field located at the top-right of the screen has been disabled.

Refit Planning (RPP)

Version: V1.14.67
Release Date: 12-02-2026
Division: Mumbai

Overview

This release includes enhancements in the WO Amendment and RPP Dashboard screens to improve system logic accuracy and user control over data retrieval.

Enhancement Details
Screen Name: WO Amendment

Enhancement Description:

The existing query was checking a hardcoded value 'NORMAL' on the column refit_type_name.

This has been modified to use the column rf_type_unid = 'NORMAL' instead.

Screen Name: RPP – Dashboard

Enhancement Description:

The onload data call has been removed.

A Show Data button has been added to manually fetch data.


Others

Version: V1.14.67
Release Date: 12-02-2026
Division: Mumbai

Overview

Enhancement

Screen Name: Raise Request Assistance 



RPP

Version: V1.14.68
Release Date: 12-02-2026
Division: Mumbai

Bug Fixes

Screen Name: Release WI / P1O2 Release

Release WI – Edit Form (Offload Toggle Behaviour)

Issue:

While editing the WI details, the user was able to enable and disable the Offload Flag.

When a WI with QC Level (for example, L3) was enabled for the Offload Flag, the QC Level correctly changed to L1.

However, when the Offload Flag was disabled again, the QC Level became blank, whereas it should have reverted back to the original level (L3).

Resolution:

The logic has been corrected to ensure that when the Offload Flag is disabled, the QC Level reverts to its original value instead of becoming blank.

Screen Name: P1O2 Release
Issue:

The PRM data was not being properly patched in the P1O2 Release screen.

Resolution:

The issue has been resolved, and the PRM data is now correctly patched and displayed in the P1O2 Release screen.

Screen Name: CRF Request
Enhancement Details:

The PSD and PCD fields were appearing blank in CRF Request and CRF Approve screens.

The system now displays the PSD and PCD values that were originally entered during WI creation.

The Revised PCD field will now automatically reflect the original PCD value (similar to Revised PSD & Revised EMD).

Users may modify the date if required.

By default, PSD, PCD, and EMD values will reflect in Revised PSD, Revised PCD, and Revised EMD fields.

Importance:

Without Revised PCD, the WI was not displayed in MPB for booking because no updated PCD date was available. This enhancement ensures proper booking visibility.

Screen Name: Release WI
Issue:

An error occurred while updating WI through RA Release WI.

Resolution:

The issue has been resolved, and WI updates now function correctly without system errors.

OPRA

Version: V1.14.68
Release Date: 12-02-2026
Division: Mumbai

Overview

This release includes multiple bug fixes and functional enhancements across OPS WO Approval, WI Release, P1/O2 Release, Reporting, CRF Request, and PRM Remarks modules. 
These updates improve validation logic, data consistency, reporting accuracy, and workflow efficiency.

Bug Fixes
Screen Name: OPS WO Approval
Issue:

When the user forwards the transaction for the first time (data fetched from WO), the system displays a “Please fill all required data” error even though all mandatory fields are completed.

However, if the user manually edits the Authority Letter No. field and saves again, the transaction is successfully forwarded.

Impact:

This caused false validation errors and prevented smooth forwarding on the first attempt.

Resolution:

The validation logic for the Authority Letter No. field has been corrected. The system now properly recognizes the field as filled during the initial forward action, eliminating the need for manual re-entry.

Screen Name: Release WI
Module: Edit Form (Offload Toggle Behaviour)
Issue:

While editing the WI details:

When the Offload Flag was enabled for a WI with QC Level (e.g., L3), the QC Level correctly changed to L1.

When the Offload Flag was disabled again, the QC Level became blank instead of reverting to the original level (L3).

Resolution:

The logic has been corrected to ensure that when the Offload Flag is disabled, the QC Level reverts to its original value instead of becoming blank.

Screen Name: P1/O2 Release
Module: Edit Form (Offload Toggle Behaviour)
Issue:

The same Offload Toggle issue was observed in the P1/O2 Release screen.

Resolution:

The QC Level restoration logic has been corrected to ensure proper reversion when the Offload Flag is disabled.

Screen Name: Report – WI Release For The Day
Issues:

MPC was unable to view WIs issued till date for a work order.

The WO filter did not display any work order even after selecting the ship.

Resolution:

The reporting logic and filter functionality have been corrected. WIs are now properly displayed based on selected filters.

Screen Name: P1O2 Release
Issue:

PRM data was not being properly patched in the P1O2 Release screen.

Resolution:

The issue has been resolved. PRM data is now correctly patched and displayed.

Screen Name: Release WI
Issue:

An error occurred while updating WI through RA Release WI.

Resolution:

The issue has been resolved, and WI updates now function correctly without system errors.

Enhancement
Screen Name: CRF Request & CRF Approve
Enhancement Details:

The PSD and PCD fields were appearing blank in CRF Request and CRF Approve screens.

The system now displays the PSD and PCD values that were originally entered during WI creation.

The Revised PCD field will now automatically reflect the original PCD value (similar to Revised PSD & Revised EMD).

Users may modify the date if required.

By default, PSD, PCD, and EMD values will reflect in Revised PSD, Revised PCD, and Revised EMD fields.

Importance:

Without Revised PCD, the WI was not displayed in MPB for booking because no updated PCD date was available. This enhancement ensures proper booking visibility.

Screen Name: RA – PRM Remarks
Issue:

FMU Remarks were not visible on the PRM screen.

Resolution:

FMU Remarks are now correctly displayed on the PRM screen.


OPDEF

Version: V1.14.68
Release Date: 12-02-2026
Division: Mumbai

Overview

This release includes an enhancement to the OPDEF module specific to the Mumbai Division.

Enhancement
Work Order Number Format Update

For the Mumbai Division, OPDEF work order numbers ending with ‘5’ have been introduced.




Personnel

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai

Overview

Enhancements have been implemented in the CEO Transaction screen and Employee Master mapping related to CE Type options and Employee Status updates.

Screen Name: CEO Transaction 

Enhancements

1. Reporting to Dockyard on Transfer

The corresponding Employee Status effect is auto-fetched and reflected in the Employee Status field of the Employee Master.

2. Transfer Out of Dockyard

Struck Off Strength (SOS) details have been incorporated into the Description field.

The SOS field has been mapped accordingly.

The corresponding Employee Status effect is automatically reflected in the Employee Master.

3. Change of Name

When the “Change of Name” option is selected, the status effect is displayed as “Changed Name.”

The same is auto-fetched and mapped to the Employee Status field in the Employee Master.

4. Deemed Suspension CE Type 

The Remark field has been removed for the “Deemed Suspension” option under the CE Type field.

5. Pay Fixation on MACP – Description & Print Format Added

PAY FIXATION ON MACP (OPTION–I)
                                                                                            
PAY FIXATION ON MACP (OPTION–I)                                                                         
 i) Pay fixed on grant of macp to __________                                                        
 ii) Date of next increment __________ @ Rs. __________ w.e.f. __________ in the Pay Scale / Grade Pay / Pay Matrix Level before fixation   
 iii) Last Basic & Grade Pay / Pay Matrix Level before fixation __________PAY FIXATION ON MACP (OPTION–II)                                                                      
 i) Pay notionally fixed on grant of macp to __________ @ Rs. __________ w.e.f. __________ to __________ in the revised Pay Scale / Grade Pay   
 ii) Pay to be fixed @ Rs. __________ in the __________ w.e.f. __________              
 iii) Date of Next Increment __________                                                                 
 iv) Last Basic & Grade Pay / Pay Matrix Level before fixation __________
 

6. Death of Employee

The “Death of Employee” option selected under CE Type is mapped to the corresponding status and reflected in the Employee Status field of the Employee Master.

7. Sports Increment – Description & Print Format Added

The Individual has been granted Sports Increment with effect from (1st APR 2025). 
The Increment will be the form of PERSONAL PAY equal to one increment i.e Rs. 480/- p.m in the PML - 01 (18000-59000) (GP 18000) at the same rate till retireemt for participating in KHO KHO Tournament organised by Centrak service matter pay fixation on promotion. Retirement Benefits or DA/CCA etc. and remains fixed during the entire service.

8. Pay Fixation on Appointment – Description & Print Format Added

PAY FIXATION ON APPOINTMENT
                                                                        
  (i)Consequent on appointment to tmm (Payscale -18000-59000), level -01), Pay Fixed @18000/- in the PML-01, cell-02 wef 01/12/25                 
    (ii) Date of next increment due on 01/01/26
	
9. Employee Status Mapping (EMP Master)	

The mapping of “Employee Status” has been added to the EMP Master based on the selected CE Type option from the dropdown of CEO transaction. The same is reflected in the Employee Master screen as below:

Transfer Within Dockyard – Employee Status Effect: Transferred

Reporting to Dockyard on Transfer – Employee Status Effect: Transferred

Transfer Out of Dockyard – Employee Status Effect: Transferred

Declaration to Other Backward Class – Employee Status Effect: Backward Class

Declaration to Scheduled Caste – Employee Status Effect: Scheduled Caste

Declaration to Scheduled Tribe – Employee Status Effect: Scheduled Tribe

Conversion to Buddhist Religion – Employee Status Effect: Buddhist

Resignation from Service – Employee Status Effect: Resignation from Service

Medically Unfit – Employee Status Effect: Medically Unfit

Death of Employee – Employee Status Effect: Death

Missing Employee – Employee Status Effect: Missing

Voluntary Retirement – Employee Status Effect: Voluntary Retirement

Termination from Service During Probation Period – Employee Status Effect: Terminated

Technical Resignation from Service – Employee Status Effect: Technical Resignation

Pay Fixation on Appointment – Employee Status Effect: Transferred

Pay Fixation on MACPS – Employee Status Effect: Probation

Deemed Suspension – Employee Status Effect: Suspension

Retired Employee – Employee Status Effect: Retired

Joining Dockyard on Promotion – Employee Status Effect: Transferred

Corrigendum – Employee Status Effect: Corrigendum

Miscellaneous – Employee Status Effect: Miscellaneous

Reinstatement in Service – Employee Status Effect: Transferred

Marriage Declaration – Employee Status Effect: Marriage Declaration

Transfer on Promotion – Employee Status Effect: Transferred

Dismissal from Service – Employee Status Effect: Dismissal from Service

Compulsory Retirement from Service – Employee Status Effect: Compulsory Retirement

Suspension Revoked – Employee Status Effect: Revoked Suspension


Refit Planning (RPP)

Version: V1.14.68
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes enhancements and bug fixes in the Refit Planning (RPP) module to improve validation, usability, 
and job status functionality.

Enhancements
Screen Name: Release Work Instruction

Released Work Instructions (WI) are now disabled in editable mode under the Released tab.

Screen Name: Work Instruction

The EMD field validation has been implemented while saving the Work Instruction (WI).

Bug Fixes
Screen Name: RPP WI Release

Issue: In the Detail View, Refit Type and Equipment Location were displayed as blank.

Resolution: The issue has been resolved. Refit Type and Equipment Location are now correctly displayed in the Detail View.

Screen Name: E&R Job Status

Issue: The E&R report submission was previously restricted to Control Cell login and was disabled for Center login.

Resolution: The functionality has now been enabled for Center login.


OPDEF

Version: V1.14.68
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes enhancements and bug fixes in the OPDEF module to improve Work Instruction visibility and finalization workflow.

Enhancements
Screen Name: OPDEF Work Instruction

The list of PRMs finalized under the selected OPDEF is now displayed in disabled mode on the Work Instruction screen.

This enhancement enables users to view which PRMs have already been finalized while creating a Work Instruction (WI).

During WI creation, users can select the finalized PRMs as required.

Bug Fixes
Screen Name: OPDEF Finalization

Issue: The Work Order was not appearing on the screen.

Resolution: The issue has been resolved, and the Work Order is now displayed correctly during OPDEF Finalization.

OPRA

Version: V1.14.68
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes enhancements and bug fixes in the OPRA module to improve data visibility, filtering, approval display logic, and Work Order (WO) print functionality.

Enhancements
Screen Name: RA Center Remarks (Grid View)

The Center Name is now displayed instead of the Center Number.

The “PRM” column has been removed from the grid view.

The Ship Remarks column is now correctly displaying data.

Screen Name: E&R Job Status

Two filters have been added in the header: “Operational” and “Opdef.”

The defect list is displayed based on the selected filter.

All other functionalities remain unchanged.

Screen Name: OPS WO Approval

A provision has been added to view the status of the Work Order (WO).

Screen Name: WO Amendment

When a WO is approved, GM(R) is displayed as the approving authority. The same will now be displayed even if the WO is amended.

In case of PSD & PCD amendments, no approval flow is required. After amendment, only the name of GM(R) will be displayed in the WO print.

In case of Costing amendments, approval flow is required, and the final approving authority is A/DGM (PL). However, in the WO print, only the name of GM(R) will be displayed.

The name and designation of the latest/current GM(R) available in the system will be fetched dynamically and displayed in all relevant print formats.

The above logic applies to the following print formats:

RPP WO Print

RA WO Print

RPP WO Amendment Print

RA WO Amendment Print

Bug Fixes
Screen Name: WI Release

Issue 1: In the Detail View, OPRA No., Period of Refit, PRM Name, Subsystem, and Main CNO were showing blank.

Resolution: The issue has been resolved. All fields are now displayed correctly in the Detail View.

Issue 2: In the Grid View, Estimated Mandays were showing blank.

Resolution: The issue has been resolved. Estimated Mandays are now displayed correctly in the Grid View.

Shop Floor Management (SFM)

Version: V1.14.68
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes enhancements in the Shop Floor Management (SFM) module to improve P1 transaction visibility and tracking.

Enhancements
Screen Name: Assistant WI P1/O2 Receive

The P1 Reason and Remarks columns have been added to:

The “Raised P1” grid view

The “Received P1” screen

The P1 Reason and Remarks details are now auto-fetched and displayed in both the Raised P1 and Received P1 grid views.

A provision has been implemented to allow users to select and open past transactions in view mode.


Personnel 

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai

Overview 

Enhancement

Screen Name: CEO Transaction

1. Added new field in CEO Transaction and Employee master "Marriage Date".

2. Added Category field with dropdown value of Other Backward class.

3. Added Date of Resignation in Description in Removal From Service.

4. 42_MISCELLANEOUS FIELDS REQUIRED: Remove remark field.

5. MAJOR PUNLISHMENT DISMISSAL FROM SERVICE Remove Remark Field and Add Employee Status field with Defalult value of Dismissal from service.

6. DISMISSAL FROM SERVICE Remove Remark Field and add Employee Status with Defaut status of Dismissal from service.

7. 52_COMPLETION OF PROBATION ON PROMOTION Remove remark field.

8. 23_DEPARTMENTAL QUALIFYING EXAMINATION FOR PROMOTION Remove remark field.

9. TERMINATION FROM SERVICE ON PROBATION PERIOD FIELDS REQUIRED: 
Employee status default value should be TERMINATED 
MAPPING/ AUTOFETCH: Map with Employee Status in Employee Status

10. MEDICALLY UNFIT FIELDS REQUIRED: Employee status default value should be MADICALLY UNFIT and effect in Employee status.

MAPPING/ AUTOFETCH: Map Date of Unfit with decription Date of Unfit.

11. 49_ONE TIME VII CPC FIXATION Remove remark field.

Personnel 

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai

Overview

Enhancements
Screen Name: CEO Transaction

A new field “Marriage Date” has been added in both the CEO Transaction and Employee Master screens.

A Category field has been added with a dropdown value including Other Backward Class (OBC).

Date of Resignation has been added in the Description section under the Removal from Service option.

For Miscellaneous, the Remark field has been removed.

For Major Punishment – Dismissal from Service:

The Remark field has been removed.

An Employee Status field has been added with the default value “Dismissal from Service.”

For Dismissal from Service:

The Remark field has been removed.

The Employee Status field has been added with the default status “Dismissal from Service.”

For Completion of Probation on Promotion, the Remark field has been removed.

For Departmental Qualifying Examination for Promotion, the Remark field has been removed.

For Termination from Service on Probation Period:

The Employee Status default value is set to “Terminated.”

The status is mapped and reflected in the Employee Status field of the Employee Master.

For Medically Unfit:

The Employee Status default value is set to “Medically Unfit.”

The status effect is reflected in the Employee Status field.

The Date of Unfit is mapped to the Description field.

For One Time VII CPC Fixation, the Remark field has been removed.


OPDEF

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes bug fixes and enhancements in the OPDEF module to improve Work Instruction (WI) behavior, PRM control, and data consistency.

Bug Fixes
Screen Name: OPDEF WI Release

Issue:
When the “WI” button was clicked in the OPDEF WI Release screen to view OPDEF WI details, 
the Job Summary was incorrectly replaced with Job Details. The originally entered Job Summary (captured during WI creation) was not displayed.

Resolution:
The issue has been resolved. The originally entered Job Summary is now displayed when viewing OPDEF WI details.

Enhancements
Screen Name: OPDEF – PRM Remarks

OpDef PRM Remarks are now disabled for PRMs once they are finalized from MPC.

Only Work Orders (WOs) with Refit Type = OPS are now displayed in:

OpDef Finalization Grid Header

OPDEF WI

OPDEF Release WI

Finalized PRMs are now pre-selected in the Generate WI form of OPDEF.

The selected PRM is now correctly displayed in the form.

OPRA

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai

Overview

This release includes a bug fix in the RA Work Instruction screen to restore WI generation functionality.

Bug Fixes
Screen Name: RA Work Instruction

Issue:
The PCD Calendar was disabled, preventing users from generating the Work Instruction (WI).

Resolution:
The issue has been resolved. The PCD Calendar is now enabled, and Work Instructions can be generated successfully.


TKS

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai & Vizag

Overview

This release includes an enhancement in the TKS module to improve validation and employee selection logic in the Excess OT process.

Enhancements
Screen Name: Excess OT

In the Bio Data Master, if an employee is marked under Excess OT Hours, 
that employee will no longer appear in the employee selection list on the Excess OT HR screen.

Screen Name: Time Card

Enhancements
1. General Rule (Applicable to Listed Permissions)

For the following permissions:

Half Day Leave

Hospital Permission

Pay Day Permission

Late Condone

TY Duty

Courses

Deputation

The following changes have been implemented:

The In-Time is recorded as the actual punch-in time.

The system does not manipulate, round off, auto-adjust, or align the In-Time.

The Time Card report displays original punch timings.

2. Late & Hospital Permission

In-Time is recorded as the actual punch-in time.

No shift alignment or correction is applied.

Late minutes are calculated from the actual punch-in time.

OT is calculated as:

Shift Duration + Late Minutes + Booked OT (if applicable)

3. Pay Day Permission & Half Day Casual Leave

In-Time is recorded as the actual punch-in time.

Out-Time is set to the official shift end time.

OT calculation starts only from the official shift OT start time.

4. TY Duty, Courses & Deputation

Punch-In and Punch-Out are recorded as actual punch timings.

No change has been made to the existing logic for these permissions.

Impact

Ensures accurate attendance processing.

Prevents manipulation of punch data.

Aligns OT calculation with company policy.


Refit Planning (RPP)

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai 

Overview

This release addresses bug fixes across the multiple screen of Refit Planning (RPP) module. Issues such as "Record not found", data fetching problems, and system assignment errors have been resolved.

Bug Fixes

Screen Name: Work Instruction

Issue: The “Record not found” error was displayed on the Work Instruction transaction dashboard screen while attempting to create a new Work Instruction in the system.

Resolution: The issue has been resolved. Users are now able to create new Work Instructions in the system successfully.   

Screen Name: RPP-PRM Remarks

Issue: Multiple PRMs were assigned against single DL from User. 
When the user opened the pending PRM remark from the transaction dashboard, the system did not allow the user to assign center for the same defect list (DL).
To assign the center, the user had to navigate to transaction panel of the same screen.

Resolution: The issue has been resolved. The system allows user to assign the center for same DL directly from the pending PRM remarks without navigating to the transaction.

Screen Name: Approve CRF request

Issue: The reason selected on the raise CRF screen was not reflected on the approve CRF screen.
Resolution: The issue has been resolved. The selected reason is now displayed on the approve CRF screen.

Issue: The reason selected on the Raise CRF screen was not reflected on the Approve CRF screen.
Resolution: The issue has been resolved. The selected reason is now correctly displayed on the Approve CRF screen.


OPDEF 

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai 

Overview

This release resolves an issue where the Job Summary and Job Details field were interchange on the OPDEF Release Work Instrcution.

Bug Fixes

Screen Name: OPDEF Release WI

Issue: When the user clicks a WI in the OPDEF WI to view the details of OPDEF work instruction, the job summary and job details field data were interchanged. The job details were displayed in the job summary field, and for newly created WIs, the job summary was not displayed.  
created WI the job summary is not displayed.
Resolution: The issue has been fixed. The system now correctly displays the Job Summary and Job Details in their respective field in the screen.

OPRA

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai 

Overview

This release addresses bug fixes and enhancements across the RA – PRM Remarks screen.

Screen Name: RA - PRM Remarks

Issue: Multiple PRMs were assigned against single DL from User. 
When the user opened the pending PRM remark from the transaction dashboard, the system did not allow the user to assign center for the same defect list (DL).
To assign the center, the user had to navigate to transaction panel of the same screen.

Resolution: The issue has been resolved. The system allows user to assign the center for same DL directly from the pending PRM remarks without navigating to the transaction.

Enhancements

Screen Name: RA - PRM Remarks
Imporved the layout of defect details section for better readability. The defect no. is displayed below the defect description and equipment name is displayed below the defect number preventing the overlaps and improving clarity.


Other - Standing Work Order (SWO)

Version: V1.14.69
Release Date: 16-02-2026
Division: Mumbai 

Overview

This release addresses bug fixes related to information population on the screen and includes enhancements of pending tab and filter option value. 

Screen Name: Generate WI

Enhancements

1. The generated work instrcution has been removed from create Work Instruction, only pending information is displayed.

2. The fresh WI value has been set for filter when it is selected the system displays all work instruction in grid whose WI Count = o.

Bug Fixes

Issue: When a request was raised in the Raise Request Assistance screen, the rasied request was not popuplated on the Accept Request Assitance screen.
Resolution: The issue has been resolved. The raised request information is now displayed on the accept request assistance screen.



TKS

Version: V1.14.69
Release Date: 18-02-2026
Division: 

Overview

This release includes enhancements and bug fixes related to the Attendance module.

Screen Name: Amend Attendance
Enhancement

Added a Return option in the Transaction Stage drop-down within the confirmation message.

Bug Fixes
Screen Name: Amend Attendance

Issue: When an attendance amendment request was forwarded to the next approver, the request appeared in the next role’s pending list but remained visible in the previous role’s pending list as well.

Resolution: The issue has been resolved. Once the request is forwarded, it is now removed from the previous role’s pending list and displayed only in the appropriate next role’s pending list.

Screen Name: Amend Attendance / Amend Attendance Punches

Issue: When the entire month was frozen using Monthly Freeze, the Amend Attendance and Amend Attendance Punches screens still allowed data to be saved. These screens should not allow any changes unless the month is unfrozen.

Resolution: The issue has been resolved. The system now restricts saving attendance data when the month is frozen. Users must unfreeze the month before making any amendments.

Screen Name: Attendance Report

Issue: The attendance report PDF was not generated.

Resolution: The issue has been resolved. The attendance report PDF is now generated successfully.



SWM - NEFT

Version: V1.14.69
Release Date: 18-02-2026
Division: Vizag

Bugs
Screen Name: Employeewise Bank Details Report
Issue: Duplicate records were displayed in the Employeewise Bank Details Report screen, causing data redundancy and confusion in report validation..
Resolution: The duplication logic has been corrected. The report now fetches and displays unique employee bank records without repetition.

Screen Name: Payments to Banks Report
Issue: Duplicate entries were appearing in the Payments to Banks Report, leading to incorrect reporting output.
Resolution: This issue has been fixed from backend. The report now generates accurate, non-repetitive transaction data.

SWM - PAY

Version: V1.14.69
Release Date: 18-02-2026
Division: Vizag

Bugs
Screen Name: Bonus Report
Issue: Incorrect data was reflected in the Bonus Report, and bonus calculations were inconsistent.
Resolution: Bonus data is now accurately computed and displayed as per defined business rules.

Screen Name: TAACS Un-Freeze Details
Issue: Records were displayed without populated center attendance details in the TAACS Un-Freeze Details screen.
Resolution: Center attendance information is now correctly fetched and displayed along with the related records.
 

Jay#@20267456


QCMS/VMS

Version: V1.14.70
Release Date: 19-02-2026
Division: Mumbai

Overview

This release addresses improvement in transaction stage functionality in Quality Management (QCMS) and Vendor Management (VMS).

Screen Name: Vendor Rating Performance

Enhancements

Previously, the generated VRF form was forwarded to the admin, With this saved update, now the transaction stage has been modified to the SMQC user instead of the admin.

Personnel

Version: V1.14.70
Release Date: 19-02-2026
Division: Mumbai

Overview

This release addresses bug fixes and enhancements related to improved information fetching and the mapping of fields across the CEO Transaction and Employee Master.

Enhancement

Screen Name: CEO Transaction

1. For the option CASTE VALIDITY, the CE type field is now mapped with Date of Validity and following description:
"The verification of the caste validity wrt 19-02-2026 above individual has been successfully.

This description is also visible in the print format.

2. For the option TECHNICAL RESIGNATION FROM SERVICE, the CE Type field is now mapped Date of Technical Resignation with description field date of Technical Resignation is properly displayed in the field of "Date of Technical Resignation" on the screen.

3. For the option DEPARTMENTAL QUALIFYING EXAMINATION FOR PROMOTION option, the CE Type field has been enhanced to map and display the selected Category, Resolution Availed, Qualified Post, Qualified Trade, and Remarks in the description field. Furthermore, the selected employee information with description is now properly reflected in the Category field of the Employee Master screen.

4. For the option SUPERNNUATION, the CE Type field is now mapped with the following description:

“The individual will be placed on pension establishment upon attaining the age of superannuation (60 years) w.e.f. 28-02-2055.”

5. For the option QUALIFYING FOR CERTIFICATE OF COMPLETENCY option, the CE Type field has been enhanced to map and display the selected Category, Resolution Availed, Qualified Post, Qualified Trade, and Remarks in the description field.

6. For the option RETIRED EMPLOYEE option, the CE Type field now properly fetches the entered GPF No. and Trade from the Employee Master in the CEO Transaction. Additionally, the Employee Status field is automatically set to “Retired” by default, and the modified description information is displayed in the print report.

7. The Remark field has been removed from the Employee Details accordion and added the PRAN No. field in the Employee Master. The entered PRAN No. value is now properly fetched in the CEO Transaction.

8. For the option GRANT OF FAMILY PLANNING ALLOWANCE, the CE Type field the remark field has been removed.

9. For the option MISSING OF EMPLOYEE, the CE Type field is now mapped Date of Missing and remark field has been removed.

10. For the option Termination From Service on Probation Period, the CE Type field employee status label has been removed from description.

11. For the option ALLOCATION OF PRAN NO., the CE Type field is now mapped to the PRAN No. in the description field, and the same is reflected in the PRAN No. field of the Employee Master.

12. For the option QUALIFYING FOR CERTIFICATE OF COMPETENCY, the CE Type field is now properly mapped to the Category field in the Employee Master, and the selected Category is displayed in the description field

Bug Fixes

Screen Name: Employee Master

Issue: For the option PAY FIXATION MACPS, the CE type field description blanks gap was not to edittable.
Resolution: The issue has been resolved. Users are now able to edit the blank gap in the description field.

Screen Name: CEO Transaction

Issue: In the Grant of Financial Upgradation option, the CE Type field description had a spacing issue in the label, and the mapped description was not properly displayed in the description field.

Resolution: The issue has been fixed. The spacing in the label “Grant of Financial Upgradation” has been corrected, and the description is now properly mapped and displayed in the description field.
 
SWM - PAY 

Version: V1.14.70
Release Date: 19-02-2026
Division: Mumbai

Overview:
This release addresses a bug related to incorrect placeholder names in the field labels.

Screen Name: SWO_PAY – NSO 94

Issue:
Incorrect placeholder names were displayed for two fields.

For the “Pay Group” field, the placeholder was shown as “Select Center”.

For the “Employee ID Selection” field, the placeholder was shown as “Select”.

Resolution:
The issue has been fixed. The placeholder names now correctly correspond to their respective field labels on the screen.



QCMS 

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai

Overview

This release introduces enhancements to the QC Level screen to improve information visibility, add new columns, enhance system functionality, and arrange information sequentially.

Enhancements

Screen Name: QC Level

1. Improved grid data visibility; the Job Details column has been shifted to the left for better viewing.

2. Added columns for Finalized Remarks and PRM Remarks on the screen for individual WI.

3. A provision has been added for users to either accept or return option the routed WI. The system now maintains the routing history.

4. The system has been updated to allow users to modify the QC Level against the assigned WI.

Screen Name: Raise QC Request

1. In the Work Field, the data is now displayed sequentially as:

Onboard

Inside Yard

Outside Yard

Outstation Works

2. In the Inspection Type dropdown, the options are now displayed sequentially as:

Defectation

New Spare Inspection

CFA

Assembly/Fitment

Trials/Functional Checks

Screen Name: Assign QC Inspector

1. Added a Time Slot column to the grid.

Screen Name: Instant Inspection Report

1. The total count is now displayed on the screen.

OPDEF

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai and Vizag

Overview

This release addresses bug fixes and enhancements in the OPDEF WI screen to improve information visibility and WI generation logic.

Bug Fixes
Screen Name: OPDEF WI

Issue:
For newly created WIs in the Create WI tab, the created WI information was not displayed in the Generated WI tab when users clicked the WI button.

Resolution:
The issue has been fixed. The created Work Instruction information is now correctly displayed in the Generated WI tab.

Enhancements
Screen Name: OPDEF WI

Implemented WI generation logic for the Mumbai Division: 

opdef -  {WO +ITEMNO(Sys code+sub sys code+DL NO) + OPN}

2. Implemented WI generation logic for the Vizag Division:

opdef - {WO +ITEMNO(Sys code+sub sys code+ship loc code) + OPN}

Refit Planning (RPP)

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai and Vizag

Enhancements
Screen Name: Work Instruction 

Implemented WI generation logic for the Mumbai Division: 

RPP - {WO +ITEMNO(Sys code+sub sys code+DL NO) + OPN}

2. Implemented WI generation logic for the Vizag Division:

RPP - {WO +ITEMNO(Sys code+sub sys code+DL NO) + OPN}


OPRA 

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai and Vizag

Enhancements

Screen Name: RA Work Instrcution 
 
Implemented WI generation logic for the Mumbai Division: 

RA - {WO +ITEMNO(Sys code+sub sys code+DL NO) + OPN}

2. Implemented WI generation logic for the Vizag Division:

RA - {WO +ITEMNO(Sys code+sub sys code+DL NO) + OPN}

Shop Floor Management (SFM)

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai

Overview 

This release introduces enhancements to the CRF Request and Raise CRF Request screens.

Enhancement 

Screen Name: CRF Request 

A status column has been implemented with name to display the CRF Request status and the authority with whom the request is currently pending. This information is now visible to the user who has raised the request.

1. Pending with PRM- When CRF is created and forwarded to PRM, and the PRM has not forwarded it further.
2. Pending with Planner/MPC- When the CRF is Forwarded by PRM and is pending approval from Planner/MPC.

Screen Name: Raise CRF Request

A status column has been implemented with name to display the raised CRF Request status and the authority with whom the request is currently pending. This information is now visible to the user who has raised the request.

1. Pending with PRM- When the CRF is raised and forwarded to PRM, and the PRM has not forwarded it further.
2. Pending with Planner/MPC - When the rasied CRF is forwarded by PRM and is pending approval from Planner/MPC.

SWM PAY

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai

Overview 

This release includes enhancements and bug fixes in the SWM PAY module to improve functionality and reporting.

Enhancement 

Screen Name: GRP Change Request

Two dropdown values, Industrial and Non-Industrial, have been added to the Employee Type field.

The Employee Type field has now been made mandatory.

Bug Fixes
Screen Name: DV Wise Details Report

Issue:
The DV Wise Details Report was not functioning properly.

Resolution:
The issue has been fixed. The report is now displayed on the screen and can be generated successfully.

Screen Name: Payments to Bank

Issue:
The Payments to Bank report was not functioning properly.

Resolution:
The issue has been fixed. The report is now displayed on the screen and can be generated successfully.

Personnel 

Version: V1.14.70
Release Date: 21-02-2026
Division: Mumbai

Overview 

This release includes bug fixes and enhancements in the personel module to improve data saving and field mapping functionality.

Screen Name: CEO Transaction

Bug Fixes 

Issue: For the option Voluntary Retirement Service, the CE Type field was not being saved.
Resolution: The issue has been resovled. The system now allows users to save the information.

Enhancements

For the option REMOVE FROM SERVICE, the CE Type - Date of Removal is now mapped with Description and Date of Removal fields on the screen.

Admin -01

Version: V1.14.71
Release Date: 21-02-2026
Division: Mumbai

Overview 

This release includes enhancements to the Ship Master screen.

Enhancments

Screen Name: Ship Master 

The Yard Craft and Establishment radio buttons have been intoduced for the Ship option of Ship/Submarine field, the user can select either one or both options.
When the user selects the Ship option from the Ship/Submarine dropdown field, these two radio buttons are displayed on the screen. These radio buttons are non-mandatory and can be selected based on user preference.


YSM - 01

Version: V1.14.71
Release Date: 21-02-2026
Division: Vizag

Overview

This release includes enhancements to all screens with the implementation of an approval workflow.

Screen Name

YSM – All Screens

Enhancements

Implemented approval workflow for all screens in the YSM module.


Manpower Booking (MPB) -03

Version: V1.14.71
Release Date: 21-02-2026
Division: Mumbai

Overview 

Bug Fixes 

Screen Name: Overtime Booking Industrial 

Issue 1: When user tries to open an already created record in the view mode, the frozen pop-up message is displayed. Since the record is only being viewed and not edited, this message should not be displayed.
Resolution: The issue has been fixed. The message will no longer be displayed when opening a record in view mode.

Issue 2:
In the view mode of the Overtime Booking (Industrial), the quarterly balance was missing.

Resolution:
The issue has been resolved. The quarterly balance now appears correctly in view mode.

Issue 3:
When an overtime booking record is forwarded to the next role, the user in the next role opens the record and attempts to save it. During saving, the system displays a validation message stating “Select WI,” even though the Work Item (WI) is already selected. The user is required to re-select the WI to proceed.

Resolution:
The issue has been resolved. The validation message no longer appears while saving or forwarding the transaction.

Enhancment 

The approval flow has been implemented as per the requirement and is functioning successfully.

For OT Booking from 1 to 2.5 hours, the approval flow is:
CC → SMMS

For OT Booking from 3 to 3.5 hours, the approval flow is:
CC → SMMS → A/DGM MS

For OT Booking from 4 hours and above, the approval flow is:
CC → SMMS → A/DGM MS → GMT
Personnel -06

Version: V1.14.71
Release Date: 21-02-2026
Division: Mumbai

Overview 

This release includes enhancements to the CEO Transaction screen in the Personnel module.

Enhancement 

Screen Name: CEO Transaction 

1. Added dropdown values “Yes” and “No” for the Upgradation Granted field.

2. Configured the Present Scale dropdown to display numbers as per the defined level.

3. Added a dropdown list of pay scales for the Upgradation to the Pay Scale field.

4. Implemented a calendar control for the Date of Effect field.

5. For the option “Conversion to be Buddhist Religion,” the CE Type field now defaults to “Buddhist.” The value is automatically displayed in the Buddhist Religion field and mapped to the Employee Master Category field.

6. The Handicapped % field is mapped with the corresponding field in the Employee Master, and the Employee Status Effect field updates the Employee Status field in the Employee Master.

LTC -01

Version: V1.14.71
Release Date: 21-02-2026
Division: Vizag

Bug Fixes 

Screen Name: LTC Advance Proposal

Issue:
In the History Details section, the fields LTC Type, Place of Visit, and LTC For are displayed in blue. These fields should be displayed in black.

Resolution:
The issue has been resolved. The fields LTC Type, Place of Visit, and LTC For are now displayed in black as required.

Leave -01

Version: V1.14.71
Release Date: 21-02-2026
Division: Vizag

Enhancement

Screen Name: Covering Leave

Enabled the “To Date” field to allow selection of future dates through the calendar control.

BTMS -01

Version: V1.14.71
Release Date: 21-02-2026
Division: Vizag

Screen Name: Jetty Overview
Enhancement

Implemented mapping of all ships and jetty alignments for the Vizag division, including proper handling of positions.


Refit Planning (RPP) - 01

Version: V1.14.71
Release Date: 21-02-2026
Division: Vizag

Screen Name: Work Instruction 

Issue:
No data was displayed in the WI Count grid for the respective WO No., resulting in the number of work instructions not being shown.

Resolution:
The issue has been resolved. The WI Count grid now correctly displays the number of work instructions against the respective WO No.


Personnel
Version: V1.14.77
Release Date: 07-03-2026
Divisions: Mumbai

Overview

This release includes updates to the Civilian Establishment Order screen to improve data accuracy and enforce proper category selection. The changes include field modifications in the Major Punishment (CRS) section and validation updates in the Declaration of Schedule Tribe category dropdown.

Enhancements

Screen Name: Civilian Establishment Order
Issue: In the Major Punishment – CRS section, the Effective Date field was previously used, which did not align with the required business process.

Resolution: The Effective Date field has been removed and replaced with a new field Date of CRS. The Date of CRS is now mapped with the Date of Superannuation in the Employee Master to ensure accurate data alignment.

Bug Fixes
Screen Name: Civilian Establishment Order
Issue: In the CEO – Declaration of Schedule Tribe section, the Category dropdown displayed incorrect or additional values.

Resolution:
The Category dropdown has been restricted to the following valid options: GEN, OBC, and SC, ensuring correct category selection and compliance with the required configuration.


Module Name: SWM - PAY
Version: V1.14.77
Release Date: 07-03-2026
Divisions: Vizag

Overview

This release introduces improvements to the Pay Process management and adds a new reporting capability. The update enhances user control by enabling record deletion in the Amend Pay Process screen and introduces a newly developed Night Duty Report screen for operational reporting.

Screen Name: Amend Pay Process

Enhancement:
A provision to delete records has been implemented. Users can now remove the required records directly from the screen.

New Requirement
Night Duty Report

Update:
The Night Duty Report screen UI has been developed and made available for user access.


RPP/RA

Version: V1.14.77
Release Date: 07-03-2026
Divisions: Mumbai and Vizag

Overview

This release addresses a bug fix in the Work Instruction screen.

Bug Fixes

Issue:
After creating a WI, when navigating back to the main Work Instruction screen, the system redirects to the Generated WI tab and does not retain the previously applied filters or pagination settings.

Resolution:
The issue has been resolved. Now, when users return to the main Work Instruction screen after creating a WI, the system retains the previously applied filters and pagination settings.


BTMS
Version: V1.14.77
Release Date: 07-03-2026
Divisions: Vizag

New Requirement
Screen Name: Movement Plan

Update:
A role-based workflow for Movement Planning has been implemented. User Departments (MPLAS, MPC, Dock Master, FNO, COMCOS(E) – SOO, DOPO, SO (OPS)) are configured as Requesters with access to limited fields such as Ship/Submarine, From Location, To Location, Date, Position, and Movement to initiate requests. Submitted requests are forwarded to COY Department (COY Ops) with status “Pending COY Approval.” COY Ops is configured as the Approver with full access to planning fields to review jetty availability, plan movements, and approve or reject requests. Unauthorized roles are restricted from performing approval actions.



Other - SWO 

Version: V1.14.78
Release Date: 09-03-2026
Divisions: Vizag 

Enhancement

Screen Name: Generate WI 

1. The Work Instruction (WI) numbering logic in the SWO module has been enhanced as described below.

2. The first 5 digits represent the standard Work Order number of the SWO module.

The next 6 digits represent the Item Number:

The first 2 digits indicate the financial year (e.g., 25, 26).

3. The next 4 digits are an incremental number, starting from 0001.

The next 3 digits represent the Operation Number, which is an incremental number starting from 901.

5. When a new request is raised against a Work Order (WO):

The Item Number will start from 260001.

The Operation Number will be 901.

For subsequent requests against the same WO, the Item Number will increment (e.g., 260002, 260003, etc.), while the Operation Number will remain 901.

This sequence represents how many Assistant Work Instructions (Asst. WI) have been generated against a single WO.

5. If multiple O2 records are created using the Add button in the WI screen:

The Item Number will remain the same.

The Operation Number will increment sequentially (901, 902, 903, etc.).

This sequence represents how many O2 WIs have been generated for one WI.

6. When the calendar year changes, the first two digits of the Item Number (financial year) should automatically update accordingly.

7. A provision has been implemented to allow users to raise O2 in the WI screen. When the user clicks the Add button on the WI screen, the system will allow the creation of a new WI for O2 (similar to the existing Refit process).
A screen design has been attached in the reference files.

The Add button has been enabled in the WI screen. After clicking the Add button, the following behavior will apply:

8. WI Number Handling
The WI Number field will be disabled and will display the operation number as an incremental value from the previous one.
Example: If the previous operation number is 901, the new WI will display 902.

9. Assistance Center Selection
The Assistance Center field will be enabled, allowing the user to select a new center for O2.
The dropdown list will display the center names.

10. Field Data Replication
The data present in the following fields before clicking the Add button will be automatically replicated after clicking the Add button:

PSD

PCD

EMD

QC Level

Authority

Job Location

Job Summary

Job Details

OPDEF 

Version: V1.14.78
Release Date: 09-03-2026
Division: Vizag

Bug Fixes 

Screen Name: OPDEF PRM Remarks 

Issue: PRM remarks are not being saved, the work order displayed is incorrect, and the status filters are not functioning properly.
Resolution: The issue has been fixed, and the PRM remarks are now saving correctly. The correct work order is displayed, and the status filters are functioning as expected.

Issue: The work order filters are not functioning properly.
Resolution: The issue has been fixed, and the work order filters are now functioning properly.

Refit Planning (RPP)

Version: V1.14.78
Release Date: 09-03-2026
Division: Vizag

Bug Fixes

Screen Name: RPP - COMCOS Remarks

Issue: Information was not appearing on the COMCOS Remarks screen.
Resolution: The issue has been fixed, and the information is now displayed correctly on the COMCOS Remarks screen.

Shop Floor Management (SFM)

Version: V1.14.78
Release Date: 09-03-2026
Division: Mumbai

Enhancements

Screen Name: CRF Request – Raise / Update Grid

Description:
Previously, when a user navigated to a specific page (e.g., Page 3) of the Raise or Update CRF grid and applied filters to narrow down records, then opened the CRF Request detail screen to view or create a CRF, the grid would reset to Page 1 and all applied filters were cleared upon returning to the list screen. This required users to manually reapply filters and navigate back to the desired page, which was repetitive and time-consuming, especially when working with large datasets.

Enhancement:
The system now persists the pagination state (current page and rows per page) and header filter state (Ship, WO, Refit, Operational, OpDef Switch) for both the Raise and Update tab grids independently. When the user navigates back to the CRF Request list screen, the grid automatically restores to the previously selected page and applied filters.


SWM - PAY
Version: V1.14.78
Release Date: 09-03-2026
Divisions: Vizag

Overview

This release includes minor functional fixes and UI data-display improvements in the SWM–PAY module. The update focuses on improving data visibility and sorting consistency in employee records and hold pay processing screens.

Enhancement
Screen Name: Employee Leave and Basic Details

Issue: The From Date field in the employee leave records was not consistently ordered in the grid view and Excel export.
Resolution: Updated the sorting logic so that From Date is displayed in descending order in both the application grid and Excel export, ensuring consistency and easier access to the latest records.

Bug Fix
Screen Name: Hold Pay Process

Issue: After selecting employees and saving the record, the system displayed a successful save confirmation, but the selected employees were not visible in the grid.
Resolution: Fixed the grid refresh and data retrieval logic so that selected employees are correctly displayed in the grid after saving.


pk0409	



Replace the damaged wiring harness and source all connectors to prevent recurring electrical bulbs 

Inspected the wiring, identified burn makes near the connector, removed damaged harness, and prepared replacement installation.




OPRA

Version: V1.14.79
Release Date: 10-03-2026
Divisions: Mumbai

Overview 

This release includes enhancements to improve usability and visibility across multiple OPRA modules. A new DART No. column has been added to the Work Instruction (WI) grids in the OPRA, RA, OPDEF, and RPP modules to provide better reference and tracking of work instructions.

Enhancements

Screen Name: OPRA / RA / OPDEF / RPP Work Instruction

A new column with the field label DART No. has been added to both the Create WI and Generated WI grids.

Screen Name: RA Assign PRM

In the RA Assign PRM grid, the assigned PRMs are displayed in green. 
When the Quick Update window is opened, the previously assigned PRMs (green checkbox selections) now appears at the top of the list, making it easier to identify the PRMs that were selected earlier.


Request Assistance (RA)

Version: V1.14.79
Release Date: 10-03-2026
Divisions: Mumbai

Overview

This release includes enhancements to the RA – WO Amendment screen to improve tracking of work order amendments and maintain data consistency. It also includes a bug fix related to the fetching of the Refit Type in the transaction.

Enhancements
Screen Name: RA – WO Amendment

1. A new field named WO Amend Date has been added. This field automatically populates with the current date when the form opens and can be modified if required. This date will be used to identify the RPP – WO Amendment date.

The WO Date field has been disabled for editing in this transaction. The WO Date represents the date when the Work Order was first created as Draft.

Another field named WO Approved Date has been added to the WO form. This date represents the date when the Work Order is finally approved by GM(R).

2. The selection of Refcomp Date and DTG has been disabled in this transaction under the Refcomp tab.

Bug Fixes

Issue: Refit Type was not being fetched in this transaction. It should be fetched based on the same approved WO.

Resolution: The issue has been fixed, and the Refit Type is now fetched correctly based on the approved WO.


SWM - PAY
Version: V1.14.79
Release Date: 10-03-2026
Divisions: Vizag

New Requirement
Sceeen Name: Role Employee Type Link
Update: Implemented a dedicated master screen that enables users to create, manage, and maintain role and employee type linkages, improving data organization and consistency in employee master records.
 
 

Shop Floor Management (SFM)

Version: V1.14.80
Release Date: 11-03-2026
Divisions: Mumbai

Overview

This release includes bug fixes in the Assistant WI (P1/02 Raise) screen to improve data accuracy and prevent unintended multiple submissions during save operations.

Screen Name: Assistant WI P1/02 Raise
Bug Fixes

Issue 1: The work order number displayed in the Transaction Panel of SFM – Assistant WI (P1/02 Raise) appears incorrect.
Resolution: The issue has been fixed, and the correct work order number is now displayed.

Issue 2: The screen displays DL No. instead of OpDef No.
Resolution: The issue has been fixed, and the field now correctly displays OpDef No.

Issue 3: PSD and PCD fields were disabled, preventing the selection of the PCD date.
Resolution: The issue has been fixed, and the PCD date can now be selected.

Issue 4: After clicking Save, the form remains enabled, allowing users to click Save multiple times.
Resolution: The issue has been fixed. The form is now disabled after clicking Save to prevent multiple submissions.

OPDEF

Version: V1.14.80
Release Date: 11-03-2026
Divisions: Mumbai

Overview

This release includes an enhancement in the PRM Remarks screen to prevent duplicate center selection for the same Work Instruction (WI). It also includes a bug fix in the Raise OPDEF Transaction Dashboard to correct issues with the smart search filter.

Enhancements
Screen Name: OPDEF – PRM Remarks

The system previously allowed users to select the same center multiple times for the same Work Instruction (WI), resulting in duplicate entries being displayed on the screen. Additionally, when attempting to delete a center, selecting one center would automatically select all duplicate centers.

This behavior has been improved to prevent duplicate center selection for the same WI and to ensure that center selection and deletion work correctly.

Bug Fixes

Issue: In Raise OPDEF – Transaction Dashboard, the Smart Search filter was not working properly. When searching in one column, the text entered in that column's search field was automatically copied into all other column search fields.

Resolution: The issue has been fixed, and the Smart Search filter now works correctly for individual columns.

Request Assistance (RA)

Version: V1.14.80
Release Date: 11-03-2026
Divisions: Mumbai

Overview

This release includes a bug fix in the CRF Approve screen to ensure that the Work Order (WO) list is correctly filtered based on the selected ship.

Bug Fixes
Screen Name: CRF Approve

Issue: The Work Order (WO) should be displayed based on the selected Ship. Currently, when the Ship and WO are selected from the Transaction Dashboard, the correct data is displayed. However, if the Ship is changed within the screen, the WO list is not filtered according to the newly selected Ship.

Resolution: The issue has been fixed, and the WO list is now correctly filtered based on the selected Ship.


Stock Report 

The stock report allow you to view the avaiable stock of article with equipment details grid stock report, material in register, material out register.

Stock Report

The Stock Report allows you to view the available stock of articles along with equipment details in the following sections: Equipment Details Grid, Stock Report, Material In Register, and Material Out Register.



RPP 

Version: V1.14.81
Release Date: 12-03-2026
Divisions: Vizag

Enhancement

Screen Name: PRM Remarks

In the Quick Update and Detailed views of RPP – PRM Remarks, when adding PRM Remarks and Proposed EMD/QC Remarks against a Work Instruction, the Assign Center field has now been made mandatory while saving the transaction. The system will not allow the transaction to be saved unless the Assign Center field is selected.


Request Assistance 

Version: V1.14.81
Release Date: 12-03-2026
Divisions: Vizag

Enhancement 

Screen Name: OPRA - PRM Remarks

1. In the Quick Update and Detailed views of RPP – PRM Remarks, when adding PRM Remarks and Proposed EMD/QC Remarks against a Work Instruction, the Assign Center field has now been made mandatory while saving the transaction. The system will not allow the transaction to be saved unless the Assign Center field is selected.

2. In RA Defect, if the PRM is FMU and the Final MPC Remarks type is FMU OWC Remarks, the system will now allow the creation of a Work Instruction (WI).


Defect List (DL) (3)

Version: V1.14.84
Release Date: 17-03-2026
Divisions: Vizag

Overview

This release includes enhancements to improve grid structure, data visibility, and usability within the Defect List module.

Enhancements

Screen Name: Approve DL Defects

The following columns have been hidden:

Create Date

DART No.

DL Type

The grid column sequence has been updated to improve readability and logical flow:
Defect Class → Equipment → Sub-Equipment → Description

Screen Name: Approve ADD Defect

The Work Order Number is now automatically fetched by default to reduce manual input and improve efficiency.


Refit Planning – 7

Version: V1.14.84
Release Date: 17-03-2026
Divisions: Vizag and Mumbai

Overview

This release includes enhancements to improve usability and consistency, along with bug fixes to enforce proper field restrictions across multiple screens.

Enhancements

Screen Name: RPP COMCOS Remarks

The Detail View column has been removed from the grid to simplify the user interface.

Screen Name: Approve ADD Defect

The Work Order Number is now automatically fetched by default to improve efficiency and reduce manual input.

Screen Name: Work Instruction

In the WI Generate Grid, the label has been updated from “Propose COMCOS Remarks” to “Final Remarks” for better clarity and standardization.

Bug Fixes

Screen Name: P1/O2 Release / Work Instruction / Release WI / Approve CRF Request

Issue: Job number field was editable.

Resolution: The Job Number field has been restricted to non-editable mode and is now consistently disabled across all applicable screens.

 
OPRA (3)

Version: V1.14.84
Release Date: 17-03-2026
Divisions: Vizag and Mumbai

Overview

This release includes enhancements to improve user interface clarity and bug fixes to enforce field-level restrictions across multiple screens.

Enhancements

Screen Name: RA – COMCOS Remarks / RA SMU Remarks / RA FMU Remarks

The Detail View column has been removed from the grid to simplify the interface and improve usability.

Screen Name: RA Work Instruction

In the WI Generate Grid, the label has been updated from “Propose COMCOS Remarks” to “Final Remarks” for better clarity and standardization.

Bug Fixes

Screen Name: P1O2-Release / RA Work Instruction / RA Release WI / Approve CRF Request

Issue: Job number field was editable.

Resolution: The Job Number field has been restricted to non-editable mode and is now consistently disabled across all applicable screens.

Shop Floor Management - 9

Version: V1.14.84
Release Date: 17-03-2026
Division: Mumbai

Overview

This release addresses issues related to the Job Number field editability, ensuring consistent behavior across all relevant modules and screens.

Bug Fixes

Screen Name: ASSISTANT WI P1/O2 Receive

Module: RPP - P1/O2 Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: OPRA - P1/O2 Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: OPDEF - P1/O2 Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: RPP - CRF Request Raise
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Screen Name: Raise CRF Request

Module: RPP - CRF Request Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: OPRA - CRF Request Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: OPDEF - CRF Request Raise
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Screen Name: CRF Request

Module: OPRA - CRF Request Raise
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Module: OPDEF - CRF Request Receive
Issue: Job number field should not be editable.
Resolution: The Job Number field has been restricted to non-editable mode and is now permanently disabled.

Refit Planning (RPP)

Version: V1.14.85
Release Date: 18-03-2026
Division: Vizag

Overview

This release includes enhancements to improve user experience and performance, along with bug fixes to address system delays and optimize screen responsiveness.

Enhancements

Screen Name: Release WI

Feature	Description: Auto Route to Grid

The system now automatically redirects users to the grid view with the previously selected filters applied when changes are made during Work Item (WI) release.

Bug Fixes

Screen Name: DL Finalization

Issue: The DL -Finalization : screen is taking too much time to load when the Go button is clicked.
Resolution: Performance of the DL Finalization screen has been improved by optimizing data retrieval and backend processing. The loading time upon clicking the Go button has been significantly reduced, ensuring faster response and smoother user experience.

OPRA 

Version: V1.14.85
Release Date: 18-03-2026
Division: Vizag

Enhancements

Screen Name: RA Release WI

Feature	Description: Auto Route to Grid

The system now automatically redirects users to the grid view with the previously selected filters applied when changes are made during Work Item (WI) release.

Screen Name: RA SMU Remarks

Issue: The Shankul ship is not being fetched in the SMU Remarks screen even though it is already linked properly in the admin screen.
Resolution: The issue has been resolved by correcting the data mapping and ensuring proper synchronization between the admin configuration and the SMU Remarks screen. 
The system now correctly fetches and displays the linked Shankul ship as expected.



OPRA (17)

Version: V1.14.86
Release Date: 19-03-2026
Division: Vizag

Overview

This release includes enhancements across multiple screens, including RA Assign PRM, RA – Finalization, MPC Remarks Report, RA FMU Remarks, RA – COMCOS Remarks, and RA – SMU Remarks.

Enhancement

Screen Name: RA Assign PRM 

1. The dropdown option in the Status field “Pending from FMU” has been replaced with “Pending from Unit.

2. In the case of a ship, when the user selects the “Pending from Unit” option in the Status field, the system displays a list of RA/DL for which FMU Remarks are blank in the grid.

3. In the case of a submarine, when the user selects the “Pending from Unit” option in the Status field, the system displays a list of RA/DL for which FMU Remarks are blank in the grid.

4. When the user selects the “Pending to Assign” option, the grid displays a list of request assistance records with FMU remarks, which the remarks are dockyard remarks and are not assigned from PRM.

5. For the a submarine, when the user selects the "Pending to Assign" option in status field, the grid displays list of RA/DL for which COMCOS and SMU both remarks are blank and remark type are dockyard remarks and SMU remark.

Screen Name: RA - Finalization

1. Validation has been added for RA finalization. If a Work Instruction is released with any RA in “Finalized” status, the user can amend DL details and finalize the status.

Screen Name: MPC Remarks Report

1. Added header filter as Work Order.

2. Report is now displayed based on ship selection.

3. On show data show list Ra for selected ship and Work Order.

4. Additionaly add New column before Defect No. Column name is "Opra Number".

Screen Name: RA FMU Remarks

During the DL upload process, the FMU DL code (fmu_dl_cd) is generated by concatenating the ship_code, defect_type_name, refit_type_name, and LST_RTN_DT, separated by underscores, following the format {ship_code}_{defect_type_name}_{refit_type_name}_{LST_RTN_DT}. For example, in the code 102_MR_ONE_1705202309_4809, 102 represents the ship code, MR indicates the defect type name, ONE refers to the refit type name, and 1705202309_4809 corresponds to the last return date.

Filter Changes and Data Display

The following filter changes have been implemented for the respective screens:

Screen Name: RA – COMCOS Remarks

1. Remarks Given (Assigned) option

Displays a list of RA/DL records where COMCOS Remarks are not null.

2. Pending for Remarks option

Displays a list of RA/DL records where COMCOS Remarks are null.

3. All option

Displays all RA/DL records for the selected ship and Work Order (WO).

Screen Name: RA – SMU Remarks

1. Remarks Given (Assigned) option

Displays a list of RA/DL records where SMU Remarks are not blank.

2. Pending for Remarks option

Displays a list of RA/DL records where SMU Remarks are blank.

3. All option

Displays all RA/DL records for the selected ship and Work Order (WO).



Refit Planning (RPP) (5)

Version: V1.14.86
Release Date: 19-03-2026
Division: Vizag

Overview

Enhancements

Screen Name: DL - Finalization 

1. Validation has been added for DL finalization. If a Work Instruction is released with any RA in “Finalized” status, the user can amend DL details and finalize the status.

2. This validation is not applicable in E&R and tentative cases where the Work Instruction (WI) is generated and released. It is applicable only when the status is “Finalized” and the WI is released.

Filter Changes and Data Display

The following filter changes have been implemented for the COMCOS screen:

Screen Name: COMCOS Remarks 

1. Remarks Given (Assigned) option

Displays a list of RA/DL records where COMCOS Remarks are not null.

2. Pending for Remarks option

Displays a list of RA/DL records where COMCOS Remarks are null.

3. All option

Displays all RA/DL records for the selected ship and Work Order (WO).

Refit Planning (RPP) (4)

Version: V1.14.87
Release Date: 21-03-2026
Division: Vizag


Enhancements
1. Screen Name: Work Instruction
Added a new filter for Fresh WI in the WI Generation transaction to streamline the creation and identification of new Work Instructions.

Screen Name: DL Finalization

2. Introduced a new Status Filter in DL/RA Finalization to allow better tracking and segregation of records.
Enhanced defect visibility:

3. Now displays a list of defects where all assigned PRMs have provided remarks, ensuring only fully-reviewed defects are shown for action.

Screen Name: Work Order

4. Implemented WO Costing Functionality:
Enables costing at the Work Order level for improved financial tracking and analysis.


OPRA (3)

Version: V1.14.87
Release Date: 21-03-2026
Division: Vizag

Enhancements

Screen Name: RA Work Instruction

1. Added a new filter for Fresh WI in the WI Generation transaction to streamline the creation and identification of new Work Instructions.

2. Introduced a new Status Filter in DL/RA Finalization to allow better tracking and segregation of records.

Enhanced defect visibility:

3. Now displays a list of defects where all assigned PRMs have provided remarks, ensuring only fully-reviewed defects are shown for action.

OPDEF 

Version: V1.14.87
Release Date: 21-03-2026
Division: Vizag

Screen Name: OPDEF Work Instruction

1. Added a new filter for Fresh WI in the WI Generation transaction to streamline the creation and identification of new Work Instructions.


Equipment Name	
OEM Details	
Equipment Make	
Equipment Cost
Equipment / Item to be Indigenised	
Components within Equipment	
Total in System / No of systems in Navy	
Basic Functionality	
Project Cost	
Project Date	
Steering Agency	
Trial Status and Date	
Incatting Status	
Indigenising Agency	
BLR / BER Qty	
Follow on Order	
Original Item Cost	
Savings to E-chequer	
PAC for Indigenisation Agency	

UAT Sat - Unsatisfactory testing outcome of Article.

Sat - Satisfactory testing outcome of Article.


In case of Submarine hide cosm remarks from quick update and 
show COMCOSE Remarks and SMU Remarks in quick update for below transaction.


Refit Planning (RPP) (6)

Version: V1.14.88
Release Date: 24-03-2026
Division: Vizag

Overview 

This release addresses the bug fixes and enhancment across multiple screen of Refit Planning (RPP) module.

Enhancments 

Screen Name: DL - Assign PRM 

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed.

Screen Name: PRM Remarks

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed.

Screen Name: DL-Center Remarks

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed..

Screen Name: DL - Finalization

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed..

Screen Name: Release WI

Upon making any changes during WI release, the system automatically redirects to the grid with the selected filter applied.

Bug Fixes

Screen Name: DL -Finalization 
Issue: The screen takes too much time to load when the ‘Go’ button is clicked.

Resolution:  The issue has been resolved, and the screen now loads as expected.

OPRA  (6)

Version: V1.14.88
Release Date: 24-03-2026
Division: Vizag

Overview 

This release addresses the bug fixes and enhancment across multiple screen of OPRA module.

Enhancments

Screen Name: RA - Assign PRM

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed...

Screen Name: RA - PRM Remarks

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed...

Screen Name: RA - Center Remarks

The Quick Update and Detail mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed....

Screen Name: RA - Finalization

The Quick Update mode has been enhanced. In the case of a submarine, two remarks—COMCOS Remarks and SMU Remarks—are displayed....

Screen Name: RA Release WI

Upon making any changes during WI release, the system automatically redirects to the grid with the selected filter applied.

Bug Fixes 

Screen Name: RA SMU Remarks

Issue: The ship ‘Shankul’ was not being fetched in the SMU Remarks screen, despite being correctly linked in the Admin screen.
Resolution: Resolution: The issue has been resolved. The ‘Shankul’ ship is now correctly fetched and displayed in the SMU Remarks screen as expected.

Refit Planning (RPP)

Version: V1.14.92
Release Date: 26-03-2026
Division: Mumbai

Overview

This release includes enhancements and bug fixes aimed at improving system accuracy and workflow efficiency in the Refit Planning (RPP) module.

Enhancements 

In the DL Finalization screen, when the status is set to 'Tentative', the selected is now moved from 'PRM Remarks Given' to 'In Progress'. Previously, it was visible in both statuses.

Bug Fixes 

Issue:
When a WI is selected and released, it is still displayed in the 'Release WI' tab. It should be removed from the 'Release WI' tab and displayed in the 'Released' tab once the 'Release WI' button is clicked.

Resolution: The issue where a Work Item (WI) remained visible in the 'Release WI' tab even after being released has been resolved.

Now, once a WI is selected and the 'Release WI' action is performed:

It is removed from the 'Release WI' tab.
It is correctly displayed in the 'Released' tab.

This ensures proper tracking and eliminates duplicate visibility.


OPRA 

Version: V1.14.92
Release Date: 26-03-2026
Division: Mumbai


Overview


Bug Fixes 

Screen Name: OPS WO Closure

Issue 1: The system is taking current date by default in the following fields

Dockyard start date (DSD).

Resolution: The issue has been fixed.


Issue 2: RA-OPS WO closure- The system is taking current date by default in the following fields

Dockyard Completion date (DCD)

Resolution: The issue has been fixed.

Issue 3: RA-OPS WO closure- The system is taking current date by default in the following fields

Likely Start date (LSD)

Resolution: The isssue has been fixed.

Issue 4: RA-OPS WO closure- The system is taking current date by default in the following fields

Likely completion date (LCD).

Resolution: The issue has been fixed.


Issue 5: RA-OPS WO closure- The system is taking current date by default in the following fields

WO Date.

Resolution: The issue has been fixed.

Screen Name: RA Release WI

Issue 1: RA Release WI - Edited WI details are not shown correctly to Multiple screen

Resolution: The issue has been fixed.

Issue 2: "RA Release WI - Edited WI details are not shown correctly to Multiple screen

WI Release for the day.

Resolution: The issue has been fixed.

Issue 3: "RA Release WI - Edited WI details are not shown correctly to Multiple screen

CRF request screen.

Resolution: The issue has been fixed.

Issue 4: RA Release WI - Edited WI details are not shown correctly to Multiple screen


Raise P1 screen.

Resolution: The issue has been fixed.

Screen Name: PRM Remarks

Issue 1: RA - PRM Remarks - If DL is finalised by COSM it should be removed from PRM remarks,Currently it is showing with disabled quick update option."

Resolution: The issue has been fixed.

Issue 2: RA - PRM Remarks - If DL is finalised by COSM it should be removed from center remarks screen; Currently it is showing with disabled quick update option."

Resolution: The issue has been fixed.


Refit Planning (RPP)

Version: V1.14.92
Release Date: 26-03-2026
Division: Vizag 

Refit Planning (RPP)

Version: V1.14.92
Release Date: 26-03-2026
Division: Vizag

Overview
Screen Name: RPP - PRM Remarks

Issue:
If a DL is finalized by COSM/MPC, it should be removed from the PRM Remarks and Center Remarks screens.
Currently, it is still visible with the quick update option disabled.

Changes:

Removed from PRM Remarks tabs:

Pending Assign Center
Pending PRM Remarks
PRM Remarks Given

Kept only in:

All tab

Removed from Center Remarks tabs:

Pending for Remarks
Remarks Given

Kept only in:

All filter

Resolution:
The issue has been fixed.

Screen Name: DL - Center Remarks

Issue:
If a DL is finalized by COSM/MPC, it should be removed from the PRM Remarks and Center Remarks screens.
Currently, it is still visible with the quick update option disabled.

Changes:

Removed from PRM Remarks tabs:

Pending Assign Center
Pending PRM Remarks
PRM Remarks Given

Kept only in:

All tab

Removed from Center Remarks tabs:

Pending for Remarks
Remarks Given

Kept only in:

All filter

Resolution:
The issue has been fixed.

Enhancements
Screen Name: RPP - WI Amendment
The grid view must include the Job Description field.
This screen is primarily used to link RMM activities to the WI; therefore, the Job Description is mandatory.


Screen Name: Work Instruction

Issue:
When a new WI is created with fresh PSD and PCD, the PSD date is incorrectly displayed as 1970 in the WI History tab of the DL, even though the correct PSD (e.g., 2026) was provided during creation.

Resolution:
The issue was caused by incorrect handling of the PSD value while fetching data for the WI History tab. This has been corrected, and the system now displays the actual PSD entered during WI creation instead of the default date (1970). 


Defect List (DL)

Version: V1.14.93
Release Date: 29-03-2026
Divisions: Mumbai and Vizag

Overview 

Bug Fixes

Screen Name: DL Upload RPP/OPRA 

Issue: Not able to upload RA through accdb file. Shows error 'Duplicate DLno.'
Multiple DL can be uploaded against one OPRA no. so the system must take the combination of OPRA NO. and DL.
Currently the system is only taking the DL no. validation and if the same DL no. is used against a different OPRA no. the system is showing error.
Resolution: The issue has been fixed.

Enhancements 

Screen Name: Add DL Defects - RPP

1. System and Sub-System should be kept non- mandatory.
2. Details of defect field should be big and should be kept at the bottom of the screen- should cover full screen(from left- to right) and the field should have resizer also.- "reference can be taken from RPP- WI screen- Job head (field)".
3. Remove "state parameters/ limits" field from the screen.
4. Dart No. field (should be non- mandatory) is not showing mandatory in the front end but not allowing to save the data is not filled in field.
5. If assistance required is selected as Yes- it should enable new field as "Remarks"(Non. Mandatory, open text field). 


Refit Planning (RPP)

Version: V1.14.93
Release Date: 29-03-2026
Divisions: Vizag

Overview 

Bug Fixes 

Screen Name: RPP-PRM Remarks

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Screen Name: DL-Center Remarks

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Screen Name: Work Instruction 

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Enhancement

REMARKS : In all screen of RPP/OPRA/OPDEF, Remarks list should be show Dockyards Remark type at top.

Request Assistance (OPRA) 

Version: V1.14.93
Release Date: 29-03-2026
Divisions: Vizag

Overview 

Bug fixes 

Screen Name: RA PRM Remarks

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Screen Name: RA - Center Remarks

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Screen Name: RA - Work Instruction 

Issue: All EMD field must only accept numeric characters. If typing any alphabet system should give some error and should not allow user to save the data.
Resolution: The issue regarding the field EMD numberic character 

Screen Name: DL Upload RA

Issue: Not able to upload RA through accdb file. Shows error 'Duplicate DLno.'
Multiple DL can be uploaded against one OPRA no. so the system must take the combination of OPRA NO. and DL.
Currently the system is only taking the DL no. validation and if the same DL no. is used against a different OPRA no. the system is showing error.
Resolution: The issue has been fixed.

QCMS
Version: V1.14.93
Release Date: 29-03-2026
Divisions: Mumbai

Overview:
This release focuses on improving equipment handling and document management across QC workflows. Enhancements ensure better visibility, consistency, and usability for users interacting with QC requests, inspections, and approvals.

Bug
Screen Name: WI Add equipment
Issue: System allowed selection of multiple equipment; however, only the first selected equipment was displayed in the Raise QC Request screen. Users had to repeatedly reopen the screen to add additional equipment.
Resolution: Fixed the issue to ensure all selected equipment are saved and displayed correctly in the Raise QC Request grid view. Users can now add multiple equipment in a single action without repetition.

Enhancement
Screen Name: Raise QC request screen, Assign QC inspector screen and IIR Screen

Issue:
No provision to upload and view documents across QC workflow screens
Limited visibility of documents added at different stages by different roles (QC Manager, MQC, QC Inspector)
Documents not consistently available in Generated IIR and approval stages

Resolution:
Implemented file upload functionality across all relevant QC screens
Enabled centralized document visibility for each QC request
Users can now view all previously uploaded documents regardless of role or stage
Ensured documents are dynamically updated and accessible in:

QC Request lifecycle
Generated IIR tab (QC Inspector & QC Manager)
IIR Approval Screen for MQC review
Improved traceability and document continuity throughout the QC process.

Firing Trend Last 10 Years


My expert role is e.g. a highly competent technical writer. Your key characteristics include: Content Design and Visual Communication. I am a technical writer. Use your expertise to challenge my thinking and ensure my ideas are sound. Your advice should be clear, candid, and informative. Stay in character throughout the conversation.


Refit Planning (RPP)

Version: V1.14.94
Release Date: 30-03-2026
Division: Mumbai

Overview

This release includes a bug fix related to DL approval functionality.

Bug Fixes
Issue:
After adding DL, users were unable to approve it via the “Approve Add DL defect” screen.
Although a “Save successful” message was displayed, the data was not actually being saved.
Resolution:
The issue has been resolved. DL approvals now save and process correctly.
OPDEF

Version: V1.14.94
Release Date: 30-03-2026
Division: Mumbai

Overview

This release introduces a UI enhancement in the Create WI tab.

Enhancements
In the Create WI tab:
Removed the “Main center no.” column
Added a new “WI Count” column
The main center column shows the center code of database.



Module Name: Retirement
Version: V1.14.94
Release Date: 30-03-2026
Divisions: Vizag

Bug Fix
Screen Name: Data Sheet
Issue: Datasheet transactions were editable in view mode, leading to unintended modifications.

Resolution: Restricted edit functionality in view mode. Datasheet transactions are now read-only unless accessed in edit mode.

Module Name: SWM - PAY
Version: V1.14.94
Release Date: 30-03-2026
Divisions: Vizag

Bug Fix
Screen Name: Supplementry Salary Entry

Issue: While adding or deleting salary heads using the pop-up and grid:

Deleted records were auto-populating again after re-selection
Inconsistent behavior observed when selecting/deselecting salary heads
Resolution: Fixed synchronization between pop-up and grid:

Deleted records no longer reappear automatically
Proper handling implemented for add/remove actions
Ensured consistent data display based on user selection
Module Name: MPB
Version: V1.14.94
Release Date: 30-03-2026
Divisions: Vizag

Bug Fix
Screen Name: Department-wise Monthly Report Visible to Managers

Issue: Manager report displayed incorrect data:

Random OT hours mapped to incorrect designations
Resulted in data inconsistency and unreliable reporting
Resolution: Corrected data mapping logic:

Ensured accurate association of OT hours with respective designations
Restored report accuracy and consistency
Module Name: TAACS
Version: V1.14.94
Release Date: 30-03-2026
Divisions: Vizag

Bug Fix
Screen Name: OT Finalization
Issue: System allowed editing of Final OT even when it matched Booked OT, violating business rules and affecting Actual OT calculations.

Resolution:

Disabled editing of Final OT when it equals Booked OT
Ensured compliance with business rules
Corrected impact on Actual OT calculations




Defect List (DL) – RPP

Version: V1.14.95
Release Date: 30-03-2026
Division: Vizag

Overview

This document outlines the issues identified in the RPP DL – Upload screen and their respective resolutions.

Bug Fixes 

Screen Name: RPP DL – Upload

Issue 1: RPP DL Upload

While uploading the DL, the system throws an error in Excel stating “Invalid Ship Code Selected”, even though the selected ship code is correct.

Resolution:
The validation logic has been corrected to accurately recognize valid ship codes during upload.

Issue 2: RPP DL Upload

When uploading the second ship (Vela), the system throws an “Invalid Refit Type” error, even though the uploaded value is correct.

Resolution:
The refit type validation has been fixed to ensure correct values are accepted during upload.

Screen Name: Add DL Defects

Issue:
While saving data in the Add DL Defects screen (Defect 1 – DL), the system throws an error message “Error while saving data!”, and the network tab shows a “500 Internal Server Error.”

Resolution:
The issue has been resolved by fixing the server-side error that was causing the failure during data save operations.



Refit Planning (RPP)

Version: V1.14.95
Release Date: 30-03-2026
Division: Vizag

Overview

This document summarizes the bug fixes and enhancements implemented in the Refit Planning (RPP) module.

Bug Fixes
Screen Name: RPP – PRM Remarks

Issue:

The Quick Update option is disabled, When saving from Detailed Mode, the system does not save and remains stuck in a loading/buffering state.

Resolution:
The issues have been resolved by enabling the Quick Update functionality and fixing the save operation in Detailed Mode.

Enhancement
1. Performance Improvement

Issue:
The screen takes approximately 1 minute 10 seconds to load data for only 6 entries.

Resolution:
Performance optimization has been implemented to reduce the screen loading time.

Screen Name: P1/O2 Received

Issue:
Data visibility issue where requests should be displayed in P1/O2 Received based on Login PRM = Assistance PRM, but were not appearing correctly.

Resolution:
The data visibility logic has been corrected to ensure requests are displayed as per the defined PRM mapping.

Retirement
Version: V1.14.95
Release Date: 31-03-2026
Divisions: Vizag

Overview

This release enhances the accuracy and usability of the Retirement module by correcting report data logic and enabling flexibility in transaction fields. Users can now rely on precise spouse data in reports and make necessary edits to auto-populated details without restrictions.

Bug Fix
Screen Name: Retirement Details Report
Issue: Spouse details were not populated correctly. The report fetched other family relations instead.
Resolution: Updated logic to fetch only spouse details from Employee Master → Family Information.

Enhancement
Screen Name: Retirment Details
Issue: Name, Date of Birth, and Relation fields were non-editable despite being auto-populated.
Resolution: Fields are now editable while continuing to auto-populate from PIMS – Employee Master.

Personnel
Version: V1.14.95
Release Date: 31-03-2026
Divisions: Vizag

Overview
This release addresses critical data-saving and validation issues in the Personnel module, ensuring reliable transaction processing and proper data capture. Improvements also enhance system feedback and data integrity in employee records.

Bug Fix
Screen Name: Employee Master
Issue: Changes were not saved, and no validation/error message was displayed.
Resolution: Fixed save issue and added validation messages for better user guidance.

Screen Name: Employee Master
Issue: cgegis_cd was saved as null when adding a new row.
Resolution: Corrected logic to ensure proper generation and storage of cgegis_cd.


Defect List (DL)

Version: V1.14.96
Release Date: 01-04-2026
Division: Mumbai

Overview

We’ve improved the Defect List (DL) module to make it easier and faster to add defects for both refit and operational ships. You can now enter all required details from a single screen, reducing steps and improving data accuracy.

What’s new
Add DL Defect – Refit Ships

User can now add defect details for refit ships from a single screen. Enter or select the following fields:

Ship name
Refit type
DL type (select from dropdown)
DL class (select from dropdown)
Defect number (required)
Equipment code
Equipment name
Equipment system
Equipment location
Machine run hours
Dart number
Maintop number
Defect description

Note: Enter all fields manually except DL type and DL class.

Add DL Defect – Operational (RA) Ships

User can now add defect details for operational ships from a single screen. Enter or select the following fields:

Ship name
Operational number (use format: OPRA/147/__/_______)
Refit type
MYCM or ship remarks
Defect class (select from dropdown)
Defect description

Screen Name: OPRA DL Upload 

Screen Name: OPRA DL Upload
The screen allows uploading values that include a combination of integers and strings.


Refit Planning (RPP)

Version: V1.14.96
Release Date: 01-04-2026
Division: Mumbai and Vizag

Overview

We’ve enhanced the Work Instruction (WI) functionality in the Refit Planning (RPP) module. The system now supports automatic WI generation based on Dockyard remarks, improving workflow efficiency and ensuring better tracking of actions.

Enhancement

Screen Name: Work Instruction
The system generates a Work Instruction (WI) when the DL Finalize Remarks is set to Dockyard remarks.
You can add or configure remarks types, if required, for this process.


Request Assistance (OPRA)

Version: V1.14.96
Release Date: 01-04-2026
Division: Mumbai and Vizag

Overview

This release addresses bug fixed several issues and made improvements in the Request Assistance (OPRA) module to enhance data accuracy, system reliability, and user experience. These updates address errors in Work Instruction, OPDEF details, and status tracking, and improve clarity in OPS WO Approval.

Bug fixes
Screen Name: RA Work Instruction

Issue 1:
The Work Center dropdown does not display data.

Resolution:
issue. The Work Center dropdown now displays data correctly.

Issue 2:
When you click Save, a backend error occurs. The record is not saved, and no error message appears on the screen.

Resolution:
The issue has been fixed. You can now save records successfully, and the system handles errors correctly.

Screen Name: OPDEF Cancel/Progress
Details tab

Issue:
When you open the Details tab for an OPDEF record, some fields are blank or display incorrect data, including:

Date OPDEF Raise (blank)
Equipment Name (incorrect)
TO (blank)
Infor (blank)
Ship Remarks (blank)
Assign PRM (blank)
Main Center (incorrect)
Work Center (blank)
Assistant Required toggle shows enabled even when not selected
Assistant Department (incorrect)
STA toggle shows ON by default even when previously disabled

Resolution:
The issue has been fixed. All fields now display accurate and consistent data.

Status tab

Issue:

Repair Start Date field does not display any data
Duration field does not calculate automatically

Resolution:
The issus has been fixed:

The system now displays the Repair Start Date based on the OPDEF raised date
The Duration field is calculated automatically using the Repair Start Date and Repair End Date

Enhancements
Screen Name: OPRA OPS WO Approval
Renamed DSD Date to OPS Start Date
Renamed DCD Date to OPS End Date
The updated field names now also appear correctly in the print output.




Ajay@8888/%


Request Assistance (OPRA) (7)

Version: V1.14.98
Release Date: 04-04-2026
Division: Mumbai & Vizag

Overview

This release includes important bug fixes and improvements to enhance system accuracy and ensure mandatory fields are correctly reflected in work order outputs.

Bug Fixes

Screen Name: OPS WO Approval
Issue: The work order print did not display the DSD & DCD fields, even though they are mandatory when creating a new work order.
Resolution: The issue has been successfully fixed. The DSD & DCD fields are now correctly displayed in the work order print as expected.

Screen Name: P1/O2 Release

Issues:

The revised PSD & PCD entered during the P1/O2 Raise/Receive process were displayed incorrectly in the WI Details section due to a date format issue.
The Proposed QC Level field was unnecessarily visible in WI Details.
The Job No. field remained blank in the P1/O2 Raise and Receive screen.
The Job No. field was editable in WI Details, which should not be allowed.
The PRM field appeared empty in WI Details.

Resolution:
All the above issues have been resolved. Date formats are now displayed correctly, unnecessary fields have been removed, and relevant fields are properly populated and controlled as per system requirements.

Enhancements

Screen Name: RA - Assign PRM

The DL Number generated from the "DL Number Generation" screen after approval (via Approve Add DL Defects) is now automatically reflected in the OPRA No. field within the RA - Assign PRM screen.
Upon selecting the OPRA No., the system now displays all associated defects (added and approved against the respective DL Number) in the grid for better visibility and tracking.


Defect List (DL) (4)

Version: V1.14.98 
Release Date: 04-04-2026
Division: Mumbai & Vizag

Enhancement

Screen Name: Add Defect (DL) - RPP

1. The DL Number is now automatically generated based on the selected Work Order (WO), eliminating the need for manual entry.
2. Upon DL code selection, the following details are now auto-populated and displayed in read-only mode for improved accuracy and consistency:
Work Order
Ship Name
Refit Type
DL Type

Bug Fixes

Screen Name: Add DL Defect

Issue: While saving the transaction, the system threw a database error indicating an invalid date value for the DL Date field.
Resolution: The issue has been fixed. The system now correctly validates and saves the DL Date without errors.

Screen Name: Approve Add Defect

Issue: The DL Number was being entered manually by the user, whereas it should be auto-generated. Additionally, during approval (Add Defect), the DL Number was changing automatically and overriding the originally entered value.
Resolution: The issue has been fixed. The DL Number is now consistently auto-generated and remains unchanged during the approval process.


Refit Planning (RPP) (5)

Version: V1.14.98
Release Date: 04-04-2026
Division: Mumbai & Vizag

Screen Name: P1/O2 Release

Issues:

The revised PSD & PCD entered during the P1/O2 Raise/Receive process were displayed incorrectly in the WI Details section due to a date format issue.
The Proposed QC Level field was unnecessarily visible in WI Details.
The Job No. field remained blank in the P1/O2 Raise and Receive screen.
The Job No. field was editable in WI Details, which should not be allowed.
The PRM field appeared empty in WI Details.

Resolution:
All the above issues have been resolved. Date formats are now displayed correctly, unnecessary fields have been removed, and relevant fields are properly populated and controlled as per system requirements.

Module Name: Leave
Version: V1.14.99
Release Date: 04-04-2026
Divisions: Mumbai

Enhancement
Screen Name: Apply Leave , Covering Leave

Update:
Added a new column "Next Updator Role" in the View Tab for:
Apply Leave
Covering Leave
The column is displayed next to the Status column. If the transaction is Approved, the Next Updator Role field remains blank.


Request Assistance (OPRA)

Version: V1.14.101
Release Date: 07-04-2026
Division: Mumbai and Vizag

Overview

This release includes fixes to prevent incorrect data carry-forward in PRM assignment and enhancements to improve visibility and navigation in the RA PRM remarks workflow.

Bug Fixes

Screen Name: OPRA Assign PRM

Issue No. 2:
When a user assigns a PRM to one defect and saves it, then opens another defect and enters MPC Remarks and Additional Remarks without assigning a PRM, the transaction still gets saved.

Additionally, the previously assigned PRM is automatically copied to the new defect along with the same remarks, which is incorrect.

Resolution:
The system now enforces PRM assignment before saving a defect. It also ensures that no previously assigned PRM or remarks are carried forward to a new defect.

Enhancements

a. In RA PRM remarks screen, by default all options are required in OPS type, which will show all the RAs under WO (AMO, SMP, DD, Normal).

b. If routing through dashboard, it will open with the selected WO.
For example: From dashboard, if clicked on RA pending to assign center of Normal WO, the system will open RA Assign PRM remarks screen with status "Pending to assign center" and with Normal WO.

Refit Planning (RPP)

Version: V1.14.101
Release Date: 07-04-2026
Division: Mumbai

Overview

This release includes a fix to prevent incorrect PRM assignment and unintended data carry-forward between defects, ensuring accurate and consistent data entry.

Bug Fixes

Screen Name: RPP Assign PRM

Issue No. 1:
When a user assigns a PRM to one defect and saves it, then opens another defect and enters MPC Remarks and Additional Remarks without assigning a PRM, the transaction still gets saved, which should not happen.

Additionally, the previously assigned PRM is automatically copied to the new defect along with the same remarks, which is incorrect.

Resolution:
The system now enforces PRM assignment before saving a defect and prevents copying of PRM and remarks from previously accessed defects.



Leave
Version: V1.14.102
Release Date: 07-04-2026
Divisions: Mumbai

Overview
This release focuses on stability improvements and workflow corrections in Leave management. Key updates include:

Fixes in Leave Cancellation save issues.
Improvements in Bulk Leave Approval functionality and UI behavior.
Ensuring proper reflection of leave applications for approval.

Bug Fix
Screen Name: Leave Cancellation
Issue: Leave Cancellation in update mode was not saving and resulted in an Unprocessable Entity error.
Resolution: Fixed the validation and save logic to ensure successful update and submission of Leave Cancellation transactions.

Screen Name: Bulk Leave Approval
Issue: Leave applications were not reflecting in Bulk Leave Approval after being applied.
Resolution: Corrected data synchronization logic to ensure all applied leave transactions are visible for approval.

Enhancement
Screen Name: Leave Cancellation and Bulk Leave Approval

Issue:
Save option was incorrectly disabled in view mode.
Edit mode behavior required restriction to view-only where applicable.
Center dropdown remained editable even after approval.
Resolution:
Restricted Save/Edit options appropriately based on mode.
Enabled only View option where required.
Disabled center dropdown once the transaction is approved to prevent further modification.


Defect List

Version: V1.14.102
Release Date: 08-04-2026
Division: Mumbai

Overview

This release focuses on resolving critical issues in the Defect Management module, particularly in defect creation, approval workflows, and user interaction inconsistencies. Improvements ensure smoother navigation, accurate system behavior, and enhanced usability across screens.

Bug Fixes
Screen Name: Add DL Defect
Issue 1: A database error occurs on save.
Resolution: Fixed the database handling logic to prevent errors during record saving and ensure successful data persistence.
Issue 2: When the user activates the Assistance Required toggle button, the Next tab becomes disabled, whereas it should remain enabled.
Resolution: Updated the UI logic to ensure the Next tab remains enabled regardless of the toggle state.
Screen Name: Approve Add Defect - OPRA - RPP
Issue 1: Selecting multiple defects (including using Select All) does not work.
Resolution: Corrected the selection handling logic to support multi-select functionality, including Select All.
Issue 2: In OPRA Add Defect, the Save button is not clickable.
Resolution: Fixed the button state logic to ensure the Save option is enabled when required conditions are met.

Request Assistance (OPRA)

Version: V1.14.102
Release Date: 08-04-2026
Division: Mumbai

Overview

This release addresses issues in the Request Assistance module, focusing on improving report accuracy and filter functionality for better user experience and data reliability.

Bug Fixes
Screen Name: RA Status Report
Issue 1: The OPRA Number header filter is not working, and the count is inaccurate.
Resolution: Fixed the filtering logic and corrected count calculation to ensure accurate and consistent report data.




LTC 

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai

Overview 

This release includes enhancements in the LTC module related to printing functionality and report updates.

Enhancements 

Screen Name: LTC Advance Proposal 

1. The print option is now available directly on the Advance LTC Proposal screen and able to generate a print.

2. The transaction number is now included and properly fetched in the CEO report for printing.


Retirement (1)

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai

Overview 

This release includes bug fixes in the retirement module related to transaction forwarding and role visibilty.

Bug Fixes

Screen Name: Retirement Details - Forward Transaction Dialog.

Issue:  When name of employee was selected with filled all required details on retiement details screen while saving the information in confirmation message dialog transaction details of employee while forwarding that details the role name was not getthing reflected.
Resolution: The issue has been fixed role details in transaction stage is now reflected while for forwarding.

Dry Dock (2)

Version: V1.14.103
Release Date: 09-04-2026
Division: Vizag

Overview 

This release includes enhancements in the Dry Dock Module related to dock status management and maintenance tracking.

Enhancements 

1. The Dock Status can now be toggled to Maintenance, making the dock unavailable for booking and enabling maintenance time tracking.
2. Maintenance Start Date and Time are now reflected in the payload when the toggle button is enabled.


TY Duty (1)

Version: V1.14.103
Release Date: 09-04-2026
Division: Vizag

Overview

This release includes bug fixes in the TY Duty module to restore proper functionality of the amendment process.

Bug Fixes
Screen Name: TY Amendment
Issue: The complete TY Duty Amendment functionality screen was not working.
Resolution: The issue has been fixed, and the screen is now functioning as expected.


Defect List (3)

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai 

Overview 

This release includes bug fixes and enhancements in the Defect List module to resolve display errors, correct field details, and add new read-only fields.

Screen Name: Approve Add defect

Issue 1: Even though the Defect List is selected, the system displays error "Select at least one record."
Resolution: The issue has been fixed by correcting the selection validation logic to ensure selected defect records are properly recognized, preventing the erroneous message “Select at least one record.”


Issue 2: When transaction is opened, the fields "Refit Type, DSD & DCD" details are displayed blank, even though the work order contains dockyard start date and  dockyard completion date.
Resolution: The issue has been fixed by updating the data mapping logic to ensure Refit Type, DSD, and DCD fields are correctly populated from the work order, including dockyard start and completion dates..

Enhancement

Screen Name: Add DL Defects

1. Two new fields with labels DSD and DCD have been added to Add DL Defects screen read-only.


OPDEF 

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai 

Overview 
This release include enhancements in the OPDEF module related to Work Instruction (WI) screen updates and data display improvements.

Screen Name: OPDEF WI
 
In header of OPDEF Work Instruction "Create WI" tab the Main Center No. column has been removed and a new WI Count column has been added. Details of Main Center column are displayed using the center code colum from the database.

Request Assistance (OPRA) (6)

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai 

Overview

This release introduces an approval mechanism for OPS Work Orders to ensure proper validation and control for operational ships.

Enhancements
Screen Name: OPS Work Order
1. Provision for an approval mechanism has been implemented for OPS Work Orders.
2. Currently, multiple (5) OPS Work Orders are generated automatically. These Work Orders are now required to go through the approval process.
3. Normal Work Order can now be marked as the Primary Work Order.
4. OPS Work Orders are now included in the approval mechanism similar to Refit Work Orders.
5. The approval flow has been defined as:
MPLAS → A/DGM(PR) → GM(R)
6. Since multiple Work Orders are generated for operational ships, all Work Orders must be approved by GM(R).

Refit Planning (RPP) (1)

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai

Overview

This release includes a bug fix in the Refit Planning module to ensure correct filtering of DL Types in the DL Status Report.

Bug Fixes
Issue: In the DL Status Report, the DL Type dropdown displays incorrect values instead of showing only refit-related DL Types and defect types.
Resolution: The issue has been fixed by updating the filtering logic to display only refit-related DL Types and defect types in the DL Type dropdown.

Shop Floor Management (SFM) (1)

Version: V1.14.103
Release Date: 09-04-2026
Division: Mumbai

Overview

This release includes enhancements in the Shop Floor Management module to improve visibility of CRF request details.

Enhancements
Screen Name: Raise CRF Request
1. The additional Reason provided by the user at the time of raising a CRF request is now displayed in the grid view for Refit, OPS, and OPDEF.


Request Assistance (RA) (1)

Version: V1.14.104
Release Date: 10-04-2026
Division: Mumbai and Vizag 

Overview 

Bug Fixes

This release addresses a bug fix across the RA status report related to the defect type dropdown values.

Screen Name: RA Status report

Issue: Display only operational Defect Types in the dropdown on the RA status report screen.
Resolution: Updated the dropdown to display only operational defect types on the RA status report screen.

Refit Planning (RPP) (1)

Version: V1.14.104
Release Date: 10-04-2026
Division: Mumbai

Overview:
This release addresses a bug where data appeared before release (COSM). The flow has been updated to ensure data is displayed only after release.

Bug Fixes 

Screen Name: WI Release for the day

Issue: Data was appearing on the screen before release (COSM), which should not occur. The data should be displayed only after release.

Resolution: Fixed the issue by ensuring that data is displayed only after release.

Defect List (DL) (1)

Version: V1.14.104
Release Date: 10-04-2026
Division: Mumbai

Overview

This release addresses an issue where data was not displayed correctly in the Approve Add Defect List (RPP) screen. The issue has been resolved to ensure proper data visibility.

Bug Fixes

Screen Name: Approve Add Defect List (RPP)

Issue:
When opening the transaction screen, the Refit Type, DSD, and DCD fields remained blank even though the selected WO contained DSD and DCD values. The data was displayed only after selecting a different WO for the same ship.

Resolution:
Fixed the issue by ensuring that the Refit Type, DSD, and DCD fields are populated correctly when the transaction screen is opened.


OPDEF (1)

Version: V1.14.104
Release Date: 10-04-2026
Division: Mumbai

Overview

This release addresses an issue where information was not displayed correctly on the OPDEF WI Release screen.

Bug Fixes

Issue:
Data inconsistency was observed between the landing page and the detailed transaction screen, where incorrect data was displayed.

Resolution:
Fixed the issue to ensure consistent and accurate data is displayed across both the landing page and the detailed transaction screen.

 
Refit Planning (RPP)

Version: V1.14.105
Release Date: 13-04-2026
Division: Mumbai

Overview

This release introduces enhancements to the work order closure process in Refit Planning.

Enhancements
Renamed Refcom Completion to Work Order Closure.
Added a Work Order Closure link, aligned with the existing Refit Completion link.
On clicking the Work Order Closure link, the system opens the corresponding work order.
Introduced a new field in Refcom: Work Order Closure Date (Date and Time).
Added a new column Refcom Date before the Work Order Closure column.
On clicking the Work Order Closure details, the Work Order Closure screen opens.
Implemented validation during Work Order closure:
@All Work Instructions (WI) must be closed before closing the Work Order.
@If not, a warning message is displayed:
“<count of WI> WIs are open. Please close all WIs before Work Order Closure.”


SWO

Version: V1.14.105
Release Date: 13-04-2026
Division: Mumbai

Overview

This release addresses an issue encountered while generating Work Instructions (WI) in SWO.

Bug Fixes

Issue:
While generating WI in SWO, an error occurred during the save operation.

Resolution:
Fixed the issue to ensure that Work Instructions (WI) are saved successfully without errors.


Retirement
Version: V1.14.106
Release Date: 13-04-2026
Divisions: Vizag

Overview:
This release addresses key system issues in the Prepare CEO Retirement List screen, ensuring accurate data population and improving user interaction during
transaction confirmation. These fixes enhance reliability and provide a smoother user experience during retirement processing.

Bug
Screen Name: Prepare CEO Retirement List
Issue: CEO Number and CEO Date were not populating after saving the Prepare CEO transaction.
Resolution: Fixed the data population logic to ensure CEO Number and CEO Date are correctly displayed after saving.

Enhancement
Screen Name: Prepare CEO Retirement List
Issue: On saving after employee selection, closing the confirmation popup caused unclear system behavior.
Resolution: Improved confirmation popup handling to ensure consistent and predictable user interaction after saving.

Leave Travel Concession (LTC)
Version: V1.14.106
Release Date: 13-04-2026
Divisions: Mumbai

Overview
Enhancements have been made to the LTC Advance Proposal screen to improve the usability of historical proposal data. The update ensures that previously submitted proposals are now more meaningful and effectively usable within the workflow.

Enhancement
Screen Name: LTC Advance Proposal

Update: Enhanced functionality to make previous proposal selection meaningful and usable within the process.


WI	Work Instruction
SWO	(Project-specific – confirm full form, e.g., Shop Work Order / Service Work Order)
CEO	(Project-specific – confirm full form, e.g., Chief Executive Officer or system-specific term)
LTC	Leave Travel Concession


SWO – Other
Version: V1.14.107
Release Date: 14-Apr-2026
Division: Mumbai

Bug Fixes 

Issue 1: In the Raise Request Assistance module, the Work Order dropdown was not displaying any data and appeared blank.

Resolution: The issue has been resolved. The Work Order dropdown now correctly displays the available data.

Issue 2: In the Raise Request Assistance module, users were unable to save the transaction as the Save button was not functioning.

Resolution: The issue has been resolved. The Save button is now working correctly, allowing transactions to be completed successfully.


Retirement
Version: V1.14.107
Release Date: 14-04-2026
Divisions: Vizag

Overview
This release focuses on improving data accuracy, correcting relationship mappings, and restricting unintended user actions within retirement-related screens to ensure consistency and reliability.

Bug and Enhancement
Screen Name: Configure Benefits
Issue:
In EL tab, all fields were editable instead of auto-populated and non-editable.
Employee selection gets locked after first selection, requiring full page refresh to change employee.
Resolution:
Implemented auto-population of EL tab fields with read-only restriction.
Fixed employee selection behavior to allow reselection without page refresh.

Bug
Screen Name: Retirement Details
Issue:
Incorrect relation mapping displayed.
Data not loading correctly.
Resolution:
Corrected relationship mapping logic.
Fixed data retrieval issue to ensure accurate display.

Screen Name:Retired Employee Report
Issue:
Family details displaying incorrectly.
Relationship data missing or incorrect.
Resolution:
Fixed family details data mapping.
Ensured correct relationship display in reports.

Leave Travel Concession (LTC)
Version: V1.14.107
Release Date: 14-04-2026
Divisions: Mumbai

Overview:
This release addresses inconsistencies in LTC forms and reports, ensuring accurate employee-specific data rendering and resolving report generation issues.

Bug
Screen Name: LTC Advance Proposal
Issue:
"LTC Leave Advance Proposal" print shows same data for all employees.
"Requisition for Advance of LTC" – Basic Pay not reflecting.
Transaction number not appearing in CEO report; print error encountered.
Resolution:
Fixed employee-specific data rendering in LTC proposal print.
Enabled proper display of Basic Pay in requisition form.
Resolved transaction number mapping and fixed CEO report print error.


Dry Docking
Version: V1.14.108
Release Date: 15-04-2026
Divisions: Vizag

Overview
Enhancements have been implemented in the Dry Dock Master to support comprehensive maintenance tracking, including lifecycle management and historical data storage.

New Requirement
Screen Name: Dry Dock Master

Update:
Implemented APIs to capture and store maintenance start and end timestamps
System now calculates maintenance duration automatically
Enabled multiple maintenance cycles per dock
Maintenance records are persisted in Dock_Maintenance_Log for audit and tracking purposes

Leave Travel Concession (LTC)
Version: V1.14.108
Release Date: 15-04-2026
Divisions: Vizag

Overview
A defect impacting employee data visibility in the LTC Claim Application has been resolved to ensure accurate data display.

Bug Fix
Screen Name: LTC Claim Application

Issue: Employee data was not reflecting in the Application Details popup after selecting an application.

Resolution:
Fixed data binding issue in the Application Details popup
Employee information now loads correctly upon application selection


Refit Planning (RPP)

Version: V1.14.111
Release Date: 21-04-2026
Divisions: Mumbai

Overview 

This release of Refit Planning (RPP) introduces enhancements to improve control and visibility over EMD (Earnest Money Deposit) utilization against Work Orders (WO). The update ensures that users are notified when EMD usage approaches or exceeds defined thresholds and prevents the creation of Work Instructions (WI) when limits are exceeded.

Enhancements on Work Instruction screen

When the EMD against a Work Order (WO) exceeds 90%, the system displays a warning message while creating a Work Instruction (WI).
When the EMD exceeds 100% for a Work Order (WO), the system does not allow the creation of a Work Instruction (WI) against that WO.
When the EMD used reaches 100% for a Work Order (WO), the system displays a warning message while creating a Work Instruction (WI).


OPRA 

Version: V1.14.111
Release Date: 21-04-2026
Divisions: Mumbai

Overview 

This release of OPRA introduces enhancements to improve control and visibility over EMD (Earnest Money Deposit) utilization against Work Orders (WO). The update ensures that users are notified when EMD usage approaches or exceeds defined thresholds and prevents the creation of Work Instructions (WI) when limits are exceeded.

| **Screen Name**           | **Enhancement Details**                                                                                                             |
| ------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| OPRA Work Instruction     | When the EMD against a Work Order (WO) exceeds 90%, the system displays a warning message while creating a Work Instruction (WI).   |
| OPRA Work Instruction     | When the EMD exceeds 100% for a Work Order (WO), the system does not allow the creation of a Work Instruction (WI).                 |
| OPRA Work Instruction     | When the EMD used reaches 100% for a Work Order (WO), the system displays a warning message while creating a Work Instruction (WI). |
| RA Assign PRM             | Functionality implemented to mark *Signal RA* as not available in Quick Update.                                                     |
| OPS Work Order Generation | The Work Order start date is now updated in the *Actual Start Date* column.                                                         |


OPDEF 


Version: V1.14.111
Release Date: 21-04-2026
Divisions: Mumbai

This release of OPDEF introduces enhancements to improve control and visibility over EMD (Earnest Money Deposit) utilization against Work Orders (WO). The update ensures that users are notified when EMD usage approaches or exceeds defined thresholds and prevents the creation of Work Instructions (WI) when limits are exceeded.

Enhancements on RA Work Instruction

When the EMD against a Work Order (WO) exceeds 90%, the system displays a warning message while creating a Work Instruction (WI).
When the EMD exceeds 100% for a Work Order (WO), the system does not allow the creation of a Work Instruction (WI) against that WO.
When the EMD used reaches 100% for a Work Order (WO), the system displays a warning message while creating a Work Instruction (WI).



Module Name: Leave Travel Concession (LTC)
Version: V1.14.111
Release Date: 21-04-2026
Divisions: Mumbai

Overview:
Enhancements in this module ensure improved transaction control and prevent duplicate processing during approval workflows, thereby maintaining data integrity.

Bug
Screen Name: LTC Advance CDA Approval

Issue: CDA Approval transaction was being saved multiple times, leading to duplicate records.
Resolution: Added validation to restrict multiple submissions and ensured single transaction save.

Module Name: Retirement
Version: V1.14.111
Release Date: 21-04-2026
Divisions: Vizag

Overview
This update addresses data visibility issues to ensure accurate display of critical retirement-related information in benefit configuration.

Bug
Screen Name: Configure Benefits

Issue: Retirement Date was not displayed on the Configure Benefits page.
Resolution: Resolved data mapping issue to correctly display Retirement Date.

Module Name: Leave
Version: V1.14.111
Release Date: 21-04-2026
Divisions: Mumbai

Overiew:
This release improves usability, workflow continuity, and validation accuracy in leave management processes, ensuring smoother transaction handling and better user experience.

Bug
Screen Name: Leave Balance Amendment
Issue 1: Save button was disabled in Edit mode and required manual refresh.
Resolution: Fixed UI behavior to enable Save button without refresh.

Issue 2: Approval stage was not visible, and forwarding action resulted in an error.
Resolution: Corrected workflow configuration and resolved forwarding issue.

Enhancement
Screen Name: Bulk Leave Approval
Update: Added “Status” and “Next Updator Role” columns in View mode.

Bug
Issue 2: No records were displayed in View mode.
Resolution: Fixed data loading issue to display records correctly.

Enhancement
Screen Name: Covering Leave

Update: Validate leave application based on leave balance applicable to the specific period instead of current balance.



OPRA 

Version: V1.14.112
Release Date: 21-04-2026
Divisions: Mumbai

Overview 
This release enhances RA and OPS workflows by improving OPDEF detail visibility, enabling more flexible PRM remarks handling, and updating the RA Finalization screen with additional columns. It also fixes an issue where closed work orders were incorrectly shown in the Raise OPDEF screen.

Screen Name: RA Status Report 

Enhancements

1. Implemented display of OPDEF details when a WO is selected as an OPS work order.

Bug Fixes

Screen Name: OPS WO Closure

Issue: Even though the WO is closed it is still displayed in 'Raise OPDEF' screen for raising OPDEF.
Resolution: 

Enhancements

Screen Name: RA – PRM Remarks
The system currently prompts for assignment of at least one center.
The system now allows saving remarks without center assignment.

Screen Name: RA – Finalization
Added columns for “PRM Remarks” and “Status”, similar to the RPP DL Finalization screen.
Removed “SS Remarks” column, as it is available in the Quick Update pop-up.

Refit Planning (RPP)

Version: V1.14.112
Release Date: 21-04-2026
Divisions: Mumbai

Overview 

Screen Name: Add DL defects

Enhancements 

The DL number should be sequence automatically as:

"YYXXXX"

a. the first two digit will reflect Year as 26, 27 etc.

b. the next 4 digit number should incremental starting from 0001 for slected ship

For e.g. the first number for this year for any ship will be "260001"

c. After clicking on the save button if click on add  button the system should automatically generate a incremental number in the screen- allowing the user to add new defect against the same.

Refit Planning (RPP)

Version: V1.14.113
Release Date: 22-04-2026
Divisions: Mumbai

Overview
This release addresses two issues in the DL Status Report. The report logic has been updated and improved to meet the defined acceptance criteria.

Bug Fixes 

Screen Name: DL Status Report 

Issue 1: The report page displayed an incorrect count. It showed the PRM count instead of the actual count of approved DLs.Resolution:  
Resolution: Fixed the logic to count only approved DL records. The report page now displays the correct DL count.

Issue 2: Duplicate DL numbers were appearing when multiple PRMs were assigned to the same DL.

Acceptance Criteria: DL number should not repeat for a given WO.

Resolution: Updated the logic to ensure each DL number is displayed only once per WO, even when multiple PRMs are associated with the same DL.

patekarmilind7066@gmail.com