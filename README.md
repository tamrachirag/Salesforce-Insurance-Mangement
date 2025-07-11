# Salesforce-Insurance-Mangement
Developerd a salesforce-based insurance mangement system to handle customer and insurance details efficiently.
# Salesforce Insurance Management System

A Salesforce-based project to manage customer insurance policies, automate workflows, enforce business rules, and generate insightful reports.

## 🚀 Features

- **Custom Object: Insurance**
  - Fields: Insurance Type, Sub-Type, Start Date, Maturity Date, Yearly Premium, Insurance Value, Date of Surrender.
  - Formula Field to calculate Total Paid.
  - Dependent picklists for Type and Sub-Type.

- **Flow Automation**
  - Updates the surrender date automatically when status is changed.
  - Sends an email to the Insurance Manager on surrender.

- **Validation Rules**
  - Prevents editing of records once status is "Surrendered".
  - Restricts changes to important fields like Insurance Type after surrender.

- **Reports & Dashboards**
  - Funnel chart to show Insurance Value distributed by customers.

- **Permission Control**
  - Profiles and Permission Sets configured to restrict record editing based on surrender status.

- **UI Enhancements**
  - Custom tabs and page layout with roll-up view of total insurance records under contacts.

## 📸 Screenshots



### 📸 Screenshots

- [Classic Email Template](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/Classic%20EmailTemplate.png?raw=true)
- [Email Edit Flow](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/EmailEditFlow.png?raw=true)
- [Error Log Flow](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/ErrorLog%20Flow.png?raw=true)
- [Flows Screenshot](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/Flows%20Screenshot.png?raw=true)
- [Object](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/Object.png?raw=true)
- [Object Record Page](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/ObjectRecordpage.png?raw=true)
- [Page Layouts](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/PageLayouts.png?raw=true)
- [Contact & Insurance Report](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/Report%20Of%20an%20Contact%26Insurance.png?raw=true)
- [Validation Rule - Insurance](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/ValidationRule2Insurance.png?raw=true)
- [Fields](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/fields2.png?raw=true)
- [Fields and Object Insurance](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/fiels%20and%20object%20Insurance%281%29.png?raw=true)
- [Validation Rule Error](https://github.com/tamrachirag/Salesforce-Insurance-Mangement/blob/main/validationRuleError.png?raw=true)

## 🧰 Tools & Technologies

- Salesforce CRM (Lightning Experience)
- Flow Builder
- Validation Rules
- Classic Email Templates
- Reports & Dashboards
- Permission Sets and Profiles



