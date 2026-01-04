# 🚇 Metro Ticket Generating System in ServiceNow

## 📌 Project Overview
The **Metro Ticket Generating System in ServiceNow** is a digital solution that automates metro ticket booking and smart card recharge using ServiceNow’s low-code platform.  
This project demonstrates how ServiceNow can be extended beyond traditional ITSM use cases to deliver real-world, service-based applications.

Users can:
- Recharge a metro smart card
- Book a metro tickets
- View real-time fare calculations
- Store transaction details securely in a custom database

---

## 🎯 Objectives
- Digitize metro ticket booking and recharge processes
- Reduce manual effort and eliminate paper-based tickets
- Enable real-time fare calculation and validation
- Improve commuter convenience through automation
- Store structured data for reporting and analytics

---

## 🧩 Key Features
- Service Catalog-based metro ticket booking
- Dynamic form behavior using UI Policies
- Automated fare calculation using Catalog Client Scripts
- Field-level input validation
- Automated data storage using Flow Designer
- Custom **Metro Database** table for tracking transactions

---

## 🛠️ Technologies Used
- **Platform:** ServiceNow
- **Modules & Components:**
  - Service Catalog
  - Catalog Client Scripts
  - UI Policies
  - Flow Designer
  - Custom Tables
- **UI Layer:** Service Portal
- **Automation Engine:** Flow Designer

---

## 🧪 Functional Flow
1. User selects **Book A Metro Ticket** from the Service Catalog
2. User chooses one option:
   - **Recharge Smart Card**, or  
   - **Book QR Ticket**
3. Relevant form fields appear dynamically based on selection
4. Fare is calculated automatically
5. Input validations are performed
6. User submits the request
7. Flow Designer captures catalog variables
8. Ticket details are stored in the **Metro Database** table

---

## 📊 Custom Table
**Table Name:** Metro Database  

The table stores:
- Mode of Payment
- Recharge Amount
- Smart Card Details
- Journey Type
- User Details
- and more
  
This ensures structured data storage and enables future reporting and analytics.

---

## 🎥 Demo Video
A complete walkthrough of the project, including catalog configuration, automation flow, and QR ticket logic, is available in the **Project Demo Video** file.

---

## 🏁 Conclusion
The **Metro Ticket Generating System in ServiceNow** modernizes metro ticket operations by centralizing data, automating workflows, and enhancing user experience.  
This project highlights ServiceNow’s capability to build scalable, data-driven, and non-IT enterprise applications using low-code tools.
