# 💸 Calculating Family Expenses Using ServiceNow

A guided project aimed at creating a structured, scalable, and user-friendly system to **track and manage family expenses** using the **ServiceNow** platform.

#**Demo Video**
https://drive.google.com/file/d/1mLZ7XdVAxOi7PIBJ4DrmJe6JUzgqEsPC/view?usp=drivesdk

---

## 🧾 Project Objective

The goal of this project is to build a comprehensive **Family Expense Calculation System** that empowers users to:

- Categorize and record expenses
- Set budgets and track them in real time
- Establish relationships between tables for better data organization
- Generate insightful financial reports

---

## 🛠️ Steps Followed

### 1️⃣ Setting Up ServiceNow Instance
Created a personal developer instance (PDI) from ServiceNow to start building and testing the application.

### 2️⃣ Creation of New Update Set
An update set was created to capture customizations and configurations during the project development.

### 3️⃣ Creation of Table (`Family Expenses`)
A new table was added to store core family expense details like category, amount, and date.

### 4️⃣ Creation of Table (`Daily Expenses`)
A related table was created to capture individual daily expense entries, linked to the main family record.

### 5️⃣ Creation of Relationship
Defined the relationship between the `Family Expenses` and `Daily Expenses` tables to enable hierarchical tracking.

### 6️⃣ Configuring Related List on Family Expenses
Set up a related list in the Family Expenses form to view all linked daily expenses for easy reference.

### 7️⃣ Creation of Business Rules
Implemented business logic using **Business Rules** to automate tasks like field validations, updates, or notifications.

### 8️⃣ Configure the Relationship
Used ServiceNow's dictionary settings to fine-tune the relationship (one-to-many) between the tables for accurate data linkage.

### 🔚 Conclusion
Tested the end-to-end application and confirmed that it allows for efficient recording, tracking, and management of family expenses, providing users with a real-time financial overview.

---

## 📊 Key Features

- ✅ Expense categorization and logging
- ✅ Real-time expense tracking
- ✅ Relationship-based data structure
- ✅ Budget tracking and financial insights
- ✅ Scalable and user-friendly UI

---

## 🧠 Tools & Technologies Used

- **ServiceNow Developer Instance**
- **Tables and Relationships**
- **Update Sets**
- **Business Rules**
- **UI Policies**
- **Flow Designer**

---
