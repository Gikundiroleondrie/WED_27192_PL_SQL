

## ⚡ Electricity Bill Database System ##
 ##Phase I##

👤 IDENTIFICATION

Name: Leondrie Gikundiro

ID: 27192

Course: Database Development with PL/SQL (INSY 8311)

Lecturer: Eric Maniraguha

Academic Year: 2024–2025

Group: E

---

## 📌 Overview ##

**Electricity billing in developing regions often faces challenges such as data inaccuracy, delayed billing, lack of monitoring, and revenue loss. Manual processes can also lead to customer dissatisfaction due to unexpected disconnections or billing disputes.

To address these challenges, the Electricity Bill Database System is designed using Oracle PL/SQL. It enables accurate billing, efficient customer account management, real-time monitoring of meter readings, and fast generation of reports for decision-makers.

---

**🎯 Project Objectives**

The main goals of this system are to:

⚙️ Automate electricity billing and meter reading entry.

📊 Provide real-time tracking of consumption and payment history.

🔍 Detect unpaid bills and generate system alerts.

🧾 Assist customers and utility staff in tracking bills, usage, and due dates.

📤 Provide summarized data for reporting to energy regulatory bodies.



---

**👥 Target Users**

Customers – track consumption and receive timely bills.

Billing Clerks – manage meter readings and generate bills.

Utility Managers – monitor revenue and detect usage patterns.

Government/Energy Boards – access MIS reports for policy decisions.



---

**🧱 Core Entities and Descriptions**

Entity	Description

-Customers	Stores customer details (name, address, contact, meter number).
-Meters	Information about meter types and installations.
-Readings	Monthly readings submitted by technicians.
-Bills	Calculated bills based on consumption and tariff.
-Payments	Payment transactions recorded per bill.
-Tariffs	Pricing structure based on consumption units.



---

🔗 Relationships

One customer → One meter

One meter → Many readings

One reading → One bill

One bill → One or many payments

One tariff → Many bills



---

**⚙️ Business Logic Features**

✅ Automatic bill calculation based on unit consumption and current tariff.

⏰ Flag unpaid bills after due date.

📈 Aggregate usage and payment history per customer.

💳 Track partial payments and update balance accordingly.

🔐 Enable admin role for managing tariff changes.



---

**🚀 Expected Outcomes**

⏱️ Faster and accurate bill generation.

⚖️ Transparent billing and better customer satisfaction.

💰 Improved revenue collection for the utility company.

📊 Stronger data support for tariff planning and energy usage forecasting.



---
## PHASE II ##
**🧠 MIS Reports and Insights**
![image](https://github.com/user-attachments/assets/e2476070-feed-4c7d-9193-830f20ed4668)

The system generates reports such as:

Monthly consumption per customer

Outstanding bills and overdue accounts

Peak usage areas or time periods

Revenue trends by district or tariff group



---

📦 Technical Phases

## Phase III – Logical Model Design ##

Includes entities, relationships, primary and foreign keys, and constraints.

![WhatsApp Image 2025-05-24 at 23 33 13](https://github.com/user-attachments/assets/14993c96-9765-435b-8397-2e400d4f47c8)


## Phase IV – Oracle Schema Setup ##

**User schema creation and Oracle DB environment configuration.**

![data pdb](https://github.com/user-attachments/assets/45ff9655-ef7e-4d28-b86e-819b4c114b2b)


## Phase V – Table Creation and Sample Data ##

**Tables created from logical model; sample data inserted to simulate real billing scenarios.**
![TABLES](https://github.com/user-attachments/assets/d1d8c717-d86a-4f77-9e8d-6ae597099518)
![insert code](https://github.com/user-attachments/assets/41f2fcc6-1564-4d4a-86a0-fdeb4593f2a4)
![select codes](https://github.com/user-attachments/assets/750a51b5-00c8-4ab7-9ba0-5716d8630bfe)
![tabl 01](https://github.com/user-attachments/assets/3adde59d-d6e6-4ca4-b2ce-28a2b2498848)
![tabl 02](https://github.com/user-attachments/assets/95e99450-d461-4db6-a2c6-0ecd8adf1a30)
![tabl 03](https://github.com/user-attachments/assets/58e4dc3e-2f57-46c5-b638-840f02a8af5d)
![tabl 04](https://github.com/user-attachments/assets/9dc573c7-e619-4411-8407-0cedb58fde38)
![tabl 05](https://github.com/user-attachments/assets/1ecf2a95-2715-46df-82c2-4447aa5fc0c1)
![tabl 06](https://github.com/user-attachments/assets/88ce6131-8cd5-4d57-a4f9-c1f3dada939f)
![tabl 07](https://github.com/user-attachments/assets/e22e24d8-d08e-4bd5-90dc-fcb3358193ee)





## Phase VI – PL/SQL Procedures & Queries ##

Includes:

**Procedures for inserting readings and generating bills**
![procedure test](https://github.com/user-attachments/assets/340f0fdc-ac98-448a-8695-135c4635d199)

**Functions for calculating outstanding balances**
![all funct](https://github.com/user-attachments/assets/d6a0f7e5-5b35-49cc-b77e-7bfe175780b8)

**Cursors to list top energy consumers**

**Triggers to prevent duplicate readings**
![trigers](https://github.com/user-attachments/assets/b8825f78-7d66-42f5-a18f-88cdd569688c)


## ✅ Final Reflection ##

This system proves that technology can be leveraged to improve service delivery, financial efficiency, and customer trust in the energy sector. With proper extensions, this system can integrate with mobile apps or prepaid meter APIs, bringing Rwanda closer to smart utility infrastructure.


---




