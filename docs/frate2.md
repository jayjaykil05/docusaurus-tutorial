---
id: frate2
title: FUNCTIONALITY
sidebar_label: Creating and Updating Employee Rates
---
# Creating and Updating Employee Rates 

## Files
these are the files that will be affected:

#### EmployerRates.cs
#### EmployerMaster.cs
#### ItemSearch3.cs
#### Database


## Process 

Clicking **Employee Rates** in the **Employee** button in the **Menu Strip** in the _Master.cs_ will open up the _Employee Rates_ form.

Clicking the **OK** button after checking **Checkboxes** that corresponds with the data the user wants to filter, it  will close the _ItemSearch3_ form and filter the **DataTable** in the **Employee Search** tab in _Employee Rates_ form then select an employee  in the **Datatable**.

Click the **Rates** tab to switch ti the rates tab

Clicking the **New** button will clear and enable the **Textboxes** in the **Rates** tab. 

Clicking the **Save** button will trigger the event `btnSave_Click`  that will save a new Employee rate for the selected employee and is added to the **Datatable** in the **Rates** tab.

Clicking the **Load** button will trigger the event `btnLoadRates_Click` that will load the current employee rate of the selected employee.

Clicking the **Edit** button will enable all the **Textboxes** to be edited on.

Clicking the **Update** buttong will trigger the event `btnSave_Click` update the current values of the **Textboxes** overwriting the old one.


## Terms

#### NFD Rate
Night-Differential rate is the employee's rate in Night shift.

#### OT Rate
Overtime rate is the employee's rate when an overtime is rendered.

#### Day-Off Rate
Day-Off rate is the employee's rate when the employee has rendered work time on the employee's Day-Off

#### Day-Off OT Rate
Day-Off rate is the employee's rate when the employee has rendered overtime on the employee's Day-Off

#### Salary Type
Type of Deduction of Salary the employee has; if it is Monthly, Semi-Monthly, Weekly, Daily

#### SSS Contribution
Contribution to SSS depending on which salary type the employee has

#### PH Contribution
Contribution to PhilHealth depending on which salary type the employee has

#### HDMF Contribution
Contribution to Pag-ibig depending on which salary type the employee has

#### W/Tax Type
If the employee has a Withholding Tax

#### Flexi Time
If the Employee is on Flexi Time

#### Arawan
If the employee is on "Arawan"