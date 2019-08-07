---
id: frate3
title: FUNCTIONALITY
sidebar_label: Creating and Updating Employee Allowances
---
# Creating and Updating Employee Allowances 

## Files
these are the files that will be affected:

#### EmployerRates.cs
#### EmployerMaster.cs
#### ItemSearch3.cs
#### Database


## Process

Clicking the **New** button will clear and enable the **Textboxes** in the **Rates** tab.

Clicking the **Save** button will trigger the event `btnSaveAllow_Click`  and will save a new Employee rate for the selected employee and is added to the **Datatable** in the **Allowances** tab.

Clicking the **Load** button will trigger the event `btnLoadAllow_Click`and will load the current employee rate of the selected employee.

Clicking the **Edit** button will enable all the **Textboxes** to be edited on.

Clicking the **Update** buttong will trigger the event `btnUpdateAllow_Click` and will update the current values of the **Textboxes** overwriting the selected one.

## Terms


#### Allowance Amount
Amount of Allowance given to the employee

#### Type 
Type of Deduction of salary the employee has, if it is Monthly, Semi-Monthly, Weekly or Daily.

#### Description
Description of the task for the allowance.

#### Status
Status of the emplyoee if active or inactive.

#### Effective Date
Effectivity Date of the Allowance given.

#### Taxable
If the Allowance will be taxable or not.    

#### Is De Minimus
If the Allowance is a De minimis.

#### Applicable Only On
Where the Allowance is applicable on

#### Included to Premium
If the Allowance is included to Premium

#### Include to  SSS/Pag-ibig/PhilHealth
If the  Allowance to SSS/Pagibig/Philhealth