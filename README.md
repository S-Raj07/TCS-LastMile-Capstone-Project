# TCS-LastMile-Capstone-Project

Name: Sushanthi Raj

College: Dayananda Sagar College Of Engineering

Linkedin Profile: https://www.linkedin.com/in/sushanthi-raj-a43779262?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app

Batch : 5


🌍 Phase 1: Problem Understanding & Industry Analysis

📌 Project: GreenForce – Carbon Footprint & Sustainability Management Platform on Salesforce
1. Introduction

Sustainability has become a global priority. Businesses are under pressure from regulators, investors, and customers to reduce their environmental footprint and adopt transparent ESG (Environmental, Social, Governance) reporting.

The GreenForce platform, built on Salesforce, aims to provide a centralized sustainability management solution that helps organizations track, automate, and analyze their environmental impact effectively.

2. Problem Understanding

Businesses face several sustainability management challenges:

Scattered Data Sources → Emissions data spread across Excel, ERP, and supplier systems.

Complex ESG Reporting → Manual reporting methods are error-prone and time-consuming.

Low Stakeholder Engagement → Employees and suppliers lack visibility in sustainability efforts.

Compliance Risks → Non-compliance with standards (EU CSRD, SEC, UN SDGs) can cause penalties.

3. Industry Analysis
3.1 Market Trends

Increasing ESG regulations & government mandates.

Investors prefer sustainable businesses.

Growing demand for digital solutions in carbon tracking.

3.2 Existing Solutions

SAP Sustainability Control Tower → Powerful but expensive & complex.

Microsoft Cloud for Sustainability → Strong analytics but limited SME customization.

Standalone ESG Tools → Often siloed, no CRM integration.

3.3 Gap Identified

Existing tools are costly, siloed, or hard to adopt.

Lack of real-time engagement for employees & suppliers.

Need for a CRM-driven sustainability solution for mid-sized organizations.

4. Proposed Solution – GreenForce

GreenForce leverages Salesforce CRM to:

Centralize carbon, energy, waste, and travel data.

Automate carbon calculations and workflows.

Engage employees and suppliers via portals.

Deliver real-time dashboards and AI-driven insights.

5. Business Value

✅ Compliance – Easier ESG & carbon reporting.
✅ Cost Savings – Detect inefficiencies in energy, waste, and travel.
✅ Reputation – Strengthen brand image as a green business.
✅ Engagement – Motivate stakeholders to contribute to sustainability goals.

6. Deliverables of Phase 1

✔️ Business Problem Documented

✔️ Industry Research Completed

✔️ Competitor & Gap Analysis

✔️ Draft Problem Statement & Objectives

7. Conclusion

Phase 1 defined the problem, industry trends, and gaps in existing solutions. GreenForce is positioned to be a unique Salesforce-based sustainability management platform that empowers businesses to achieve compliance, transparency, and engagement in their sustainability journey.

🌍 Phase 2: Org Setup & Configuration

This phase focuses on setting up the Salesforce Developer Org and configuring the foundation for the GreenForce app.

Steps:

Create Developer Org

Sign up at Salesforce Developer
.

Activate and log in.

Company Branding

Setup → Company Information → Update company name/logo to GreenForce.

Setup → Apps → App Manager → New Lightning App → Name: GreenForce Sustainability Platform.

Users

Setup → Users → New User → Add Sustainability Manager, Analyst, Supplier, Employee.

Roles & Profiles

Setup → Roles → Define hierarchy:

Sustainability Manager

Analyst

Supplier

Employee

Clone Standard User Profile → Customize permissions.

Create Permission Sets for granular access (e.g., Supplier Read-Only).

🗂️ Phase 3: Data Modeling & Relationships

This phase defines the data architecture for GreenForce using Salesforce custom objects and relationships.

Custom Objects:

Initiatives → Sustainability projects and campaigns.

Carbon Emissions → Tracks Scope 1, 2, 3 emissions.

Energy Usage → Renewable & non-renewable energy.

Waste Management → Recycling, landfill, hazardous waste.

Travel & Commute → Business travel, employee commuting.

Stakeholder Engagement → Employee/supplier activity.

Example Relationships:

Carbon Emissions → Master-Detail with Initiatives.

Energy Usage → Lookup to Initiatives.

Travel & Commute → Lookup to Employee.

Stakeholder Engagement → Lookup to Employee/Supplier.

⚡ Phase 4: Process Automation (Admin)

This phase automates sustainability workflows using Salesforce automation tools.

Tools Used:

Flows (Record-Triggered, Scheduled, Screen Flows).

Approval Processes for initiatives.

Email Alerts & Notifications for compliance reminders.

Key Automations:

Carbon Data Submission Flow → Validates supplier data & notifies Analyst.

Sustainability Initiative Approval → Routed to Manager for approval/rejection.

Employee Engagement Automation → Awards points & recognition emails.

Scheduled Monthly Reports → Auto-generate emission reports for management.

Compliance Reminders → Notify suppliers 7 days before deadlines.

Business Value:

✅ Efficiency → Reduces manual work.

✅ Compliance → Meets ESG regulations.

✅ Engagement → Involves employees & suppliers.

✅ Accuracy → Prevents incomplete/incorrect submissions.



### Phase 5: Apex Programming (Developer)

**Objective:** Implement backend logic and automation using Apex. 

**Key Tasks:**  

- Create **Apex classes** for CRUD operations on `Emission_Record__c` and other custom objects.
  
- Implement **Triggers** for automated actions.
   
- Develop **Batch Apex jobs** for scheduled processing of large datasets.
   
- Write **Test Classes** to meet Salesforce deployment requirements.  

**Outcome:** Automated, reliable backend operations and custom business logic.

---


### Phase 6: User Interface Development

**Objective:** Design a user-friendly interface for internal users and external stakeholders.  

**Key Tasks:**  

- Customize **Lightning Pages** for Salesforce objects.
  
- Build **Lightning Web Components (LWC)** for interactive UI.
  
- Ensure mobile responsiveness and accessibility.
  
- Add **Validation Rules** to enforce data quality.  

**Outcome:** Intuitive and interactive UI for seamless data entry, review, and management.

---

### Phase 7: Integration & External Access

**Objective:** Enable secure interaction between Salesforce and external systems. 

**Key Tasks:**  

- Create **Connected Apps** for API access.
   
- Expose **REST APIs** for external apps and IoT devices.
  
- Set up **Platform Events** for real-time data updates.
  
- Provide **external portals** via Experience Cloud or Salesforce Sites.
  
- Implement **security measures** like OAuth, field-level permissions, and IP whitelisting.  

**Outcome:** External systems can securely send and receive data from Salesforce in real-time.

---

### Phase 8: Data Management & Deployment

**Objective:** Ensure data integrity, migration, and seamless deployment.  

**Key Tasks:**  

- Use **Data Loader / ETL tools** for historical data migration.
  
- Implement **Data Validation Rules** and duplicate management.
    
- Configure **Sandboxes** for testing before production.
  
- Deploy metadata using **Change Sets / Salesforce CLI**.  

**Outcome:** Clean, consistent data and reliable production deployment.

---

### Phase 9: Reporting, Dashboards & Security Review

**Objective:** Provide actionable insights and ensure platform security.  

**Key Tasks:**  

- Create **Custom Reports** for emissions trends and analysis.
  
- Build **Dashboards** with charts, tables, and KPIs.
   
- Conduct **Security Review** of profiles, permission sets, and sharing rules.
  
- Set up **Scheduled Reports** and notifications.  

**Outcome:** Data-driven insights with secure access for decision-makers.



---

### Phase 10: Final Presentation & Demo Day
**Objective:** Showcasing the fully functional GreenForce platform.  

DEMO VEDIO

https://drive.google.com/file/d/17KapdFgbxPyF3UzPI5iZVN8k6Ee_eyf6/view?usp=drive_link

