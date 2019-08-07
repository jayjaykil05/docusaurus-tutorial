---
id: frate1
title: FUNCTIONALITY
sidebar_label: Creating and Updating Employee Salary
---
# Creating and Updating Employee Salary

## Files
these are the files that will be affected:

#### Main.cs
#### EmployeeRates.cs
#### Database
#### ItemSearch3.cs

## Process

Clicking **Employee Rates** in the **Employee** button in the **Menu Strip** in the _Master.cs_ will open up the _Employee Rates_ form.

Clicking the **OK** button after checking **Checkboxes** that corresponds with the data the user wants to filter, it  will close the _ItemSearch3_ form and filter the **DataTable** in the **Employee Search** tab in _Employee Rates_ form then select an employee  in the **Datatable**.

Go to the **Salary** tab.

Clicking **Load** will load the salary history into the **datatable** of the selected employee.

Clicking the **New** button will enable all **textboxes** that will now be editable. Clicking the **Save** button will prompt a message box that will ask if the user wants to save the inputted data. If the user clicked **yes** the data will be saved and is reflected in the **datatable** in the **Salary** tab in _Employee Rates_ form.

For Updating Select from the datatable, this will provide the values of the selected row on to the **Textboxes**.

Clicking the **Edit** button will enable all **textboxes** that will now be editable with there current values in them. Clicking the **Save** button will prompt a message box that will ask if the user wants to save the inputted data. If the user clicked **yes** the data will be updated and is reflected in the **datatable** in the **Salary** tab in _Employee Rates_ form.

## Rules

#### Daily Rate
Rate of an Employee Daily
#### Monthly Rate 
Rate of an Employee Monthly. It is Computed as: 

Monthly = (DailyRate)(Number of Working Days)

#### Hourly Rate 
Rate of an Employee on an Hourly Basis

Hourly = Daily Rate/8
#### Salary Type
Types of Salary acquired:

Monthly for monthly basis

Semi-Monthly for twice a month basis

Weekly for a weekly basis

#### Status 
If the selected emnployee is stil active or inactive