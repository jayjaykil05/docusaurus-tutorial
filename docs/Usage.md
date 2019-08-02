---
id: Usage
title: Usage
sidebar_label: Usage
---
In this section is where the configuration and usage of the project is listed.

## Opening the Projects

Inside the project there are two folders; *Service* and *System* Folder. The *Service* folder where the **API** of the project while the *System* folder is where the **Frontend/Application** is located.

To open the **Frontend/Application**: go to the *System* folder and open the `Manufacturing.sln` file.  
            
To open the **API**, go to the *Service* folder and open the `THM.sln` file.


**Note that for the Application to work the **API** is required.  

## Changing the Connection of the Database

This procedure is needed to connect the the database of the project.
To configure the connection of the database open the **Web.Config** file on the *Service* project folder. On the `appsettings` section replace the value property to the two `ConnectionStrings`; Myconnectionstring for the `Payroll Database` and Myconnectionstring2 for the `ESS Database`.