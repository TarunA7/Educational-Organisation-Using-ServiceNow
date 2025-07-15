# 🎓 Educational Organisation Using ServiceNow

## 📘 Overview

This project is a **custom-built Educational Management System** developed using the **ServiceNow** platform. It automates the core academic processes including student admissions, academic tracking, and data management. It leverages ServiceNow features like **custom tables**, **form design**, **client scripts**, **process flows**, and **number maintenance** to deliver a scalable and low-code solution tailored for educational institutions.

## 🎯 Key Objectives

- ✅ Streamline student admission and academic record workflows.
- ✅ Automate field calculations and status updates.
- ✅ Enhance user experience with dynamic forms.
- ✅ Maintain centralized and secure student information.
- ✅ Provide lifecycle visibility using visual process flows.
- ✅ Enable scalability for future modules (fees, faculty, etc.).

## 🧰 Technologies Used

- [ServiceNow Developer Instance](https://developer.servicenow.com)
- ServiceNow Studio
- Form Designer
- Client Scripts (JavaScript)
- Process Flow Designer
- Number Maintenance
- Local Update Sets

## 🏗️ Modules Created

### 📌 Salesforce Table (Base Table)

Stores core student information:
- Admin Number (Auto-generated)
- Student Name, Grade
- Father & Mother Name, Contact Numbers
- Admission Date

> 🔹 Extensible table used as a parent for Admission and Progress tables.

### 📌 Admission Table

Handles all student enrollment activities:
- Admission Status (New, InProgress, Joined, etc.)
- Purpose of Joining
- School and Area Information
- Location Details (Auto-filled via Pincode)

> 🔹 Includes client scripts for field auto-population and status handling.

### 📌 Student Progress Table

Tracks academic performance:
- Marks in 6 subjects (Telugu, Hindi, English, Maths, Science, Social)
- Total Marks (auto-calculated)
- Percentage (auto-calculated)
- Result (Pass/Fail)

> 🔹 Client scripts handle calculations and field disabling for accuracy.

## 🧠 Client Scripts Implemented

- **Auto-populate Student Details**: Fetches Salesforce data into Admission form.
- **Pincode-Based Location Autofill**: Dynamically updates Mandal, City, District.
- **Total/Percentage/Result Calculation**: Based on subject marks.
- **Field Disabling**: Prevents manual entry of calculated fields.

## 🔄 Process Flow

> Created a visual flow for Admission Status:

```
New → InProgress → Joined → Rejected → Rejoined → Closed → Cancelled
```

## 🚀 Features

- 📌 Dynamic Forms with onChange logic
- 🛡️ Data Integrity via field disabling and validations
- 📊 Real-time Result Calculations
- 🔄 Status Lifecycle Management
- 🔢 Unique ID generation using Number Maintenance
- 📁 Modular Design with Update Set support

## 📈 Outcomes

- Reduced manual effort in admissions
- Zero calculation errors in student results
- Transparent admission status tracking
- Improved administrative efficiency
- Scalable for future use-cases like Fees, Exams, Faculty

## 🔮 Future Enhancements

- 📧 Email/SMS Notifications for Admission Updates
- 📱 Mobile Support for Students and Admins
- 📊 Dashboards for Real-Time Analytics
- 🧑‍🏫 Faculty & Class Module
- 💳 Fee Management System
- 🧾 Report Cards & Certifications
- 🔗 Integration with LMS platforms

## 📎 Project Setup Steps

1. Sign up at [developer.servicenow.com](https://developer.servicenow.com)
2. Request a **Personal Developer Instance**.
3. Log into the instance and open **Studio**.
4. Create custom tables: `Salesforce`, `Admission`, `Student Progress`.
5. Create and configure forms using **Form Designer**.
6. Add **Client Scripts**, **Process Flow**, and **Number Maintenance**.
7. Capture everything in a **Local Update Set**.
8. Test and validate workflows, field behavior, and UI layouts.

## 🧑‍💻 Author

**Akula Tarun Veerrajukumar**  
Final Year B.Tech (IT) Student  
Vishnu Institute of Technology  
Email: *[your email]*  
GitHub: [github.com/yourusername](https://github.com/yourusername)

## 📄 License

This project is intended for academic and educational purposes only.