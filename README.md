---
title: "Smart Home Automation System"
output: github_document
---

# Smart Home Automation System  

## Introduction  
This GitHub repository contains the code for a **Smart Home Automation System**. The system is designed to **automate home management** and send **notifications based on events and predefined rules**. It is a **Database Management System (DBMS) project** that explores SQL queries, database design, table creation, data insertion, and query execution for data management and retrieval. The **SQL script** included in this repository provides detailed insights into the project.  

## Business Overview  
Our project aims to **simplify the management of smart home devices** by creating a **centralized platform** for control, automation, and monitoring. This system will improve **home convenience, energy efficiency, and security** through smart automation.  

## Problem Statement  
Managing multiple smart home devices can be **challenging** because there is **no single platform** to control them all efficiently. Current solutions **lack centralized control** for diverse smart home devices.  

## Proposed Solution  
We propose a **Smart Home Automation System** with the following features:  
- **User Management**: Users can register, create profiles, and manage their smart homes.  
- **Device Integration**: Supports various smart devices like lights, thermostats, cameras, and sensors.  
- **Device Control**: Users can control devices individually or in groups.  
- **Automation Rules**: Users can set custom automation rules based on triggers and actions.  
- **Event Notifications**: Real-time alerts for events (e.g., motion detection, door opening).  
- **Energy Efficiency Insights**: Helps users optimize energy consumption.  
- **User-Friendly Interface**: A simple and responsive web and mobile UI.  

## Target Users  
This system is designed for:  
- Homeowners and renters with smart home devices.  
- Individuals looking to improve energy efficiency and security.  
- Tech-savvy users interested in automation.  

## Data Requirements  
The system includes entities like **User, House, Room, Device, Automation Rule, Event Notification, and Event Type**, with attributes and relationships between them.  

## Conceptual and Logical Models  
- **Conceptual Model**: Shows system entities and their relationships.  

![](![Conceptual_diagram](https://github.com/user-attachments/assets/3589397f-54d9-4dd0-83ed-1e334e7f67ed)
)

- **Logical Model**: Defines **primary keys, foreign keys, and attributes** to structure the database properly.  

![]![Logical_diagram](https://github.com/user-attachments/assets/85193bd1-6044-4f0c-8574-d8629737351c)
 

## Database Schema  
The database consists of the following tables:  
- **Users**: Stores user details.  
- **Houses**: Contains property details.  
- **UserHouses**: Connects users to houses.  
- **DeviceTypes**: Lists types of smart devices.  
- **Devices**: Stores device details.  
- **DeviceStates**: Records device activity status.  
- **Rooms**: Represents rooms in each house.  
- **AutomationRules**: Defines rules for automation.  
- **UserAutomationRules**: Links users to automation rules.  
- **EventTypes**: Lists different event categories.  
- **EventNotifications**: Logs system notifications.  
- **UserEventNotifications**: Associates users with notifications.  


## SQL Queries  
The project includes various **SQL queries**, such as:  
- **Data Retrieval Queries**: Use `SELECT` to fetch data from tables.  
- **Data Modification Queries**: Insert, update, or delete records.  
- **Data Aggregation Queries**: Perform calculations like `COUNT`, `SUM`, `AVG`, etc.  
- **Data Manipulation Queries**: Transform and manipulate data as needed.  
- **Transaction Management**: Ensures **data consistency and integrity** using ACID properties.  
- **Stored Procedures & Functions**: Automates complex database operations.  
- **Views**: Creates virtual tables for simplified querying.  

These SQL queries help **retrieve user and house data, manage devices, handle automation rules, send event notifications, and ensure smooth transactions**.  

For more details, check the **SQL script** in this repository.
