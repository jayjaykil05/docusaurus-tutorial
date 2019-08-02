---
id: doc8
title: FUNCTIONALITY
sidebar_label: Add New Employee
---
# Add New Employee

## Files
these are the files that will be affected:

#### -EmployeeMaster.cs
## Process
Clicking **New** button in the **General Inofrmation** tab in the _EmployerMaster_ form will trigger the event `btnNext_Click` that will **clear** and **enable** the **textboxes** in the tab.

Clicking **Next** button in the **General Inofrmation** tab in the _EmployerMaster_ form will trigger the event `btnNext_Click` that switches the tab to the **Others** tab and enable the the textboxes given the condition that the important details are filled up are met.

Clicking **Next** button in the **Others** tab in the _EmployerMaster_ form will trigger the event `btnNext2_Click` that switches the tab to the **Education/Work** tab.

Clicking the **Save** button will trigger the `btnSave_Click` event that shows a **Dialogbox** that will ask if the user wants to save the record, if the user clicks **yes**  it will save the all the Information the user provided into the _Database_ as long as the **Biometric ID** is not a duplicate.