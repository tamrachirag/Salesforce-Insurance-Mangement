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

### 📸 Screenshots

- [Classic Email Template](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/Classic%20EmailTemplate.png)
- [Email Edit Flow](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/EmailEditFlow.png)
- [Error Log Flow](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/ErrorLog%20Flow.png)
- [Flows Screenshot](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/Flows%20Screenshot.png)
- [Object](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/Object.png)
- [Object Record Page](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/ObjectRecordpage.png)
- [Page Layouts](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/PageLayouts.png)
- [Contact & Insurance Report](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/Report%20Of%20an%20Contact%26Insurance.png)
- [Validation Rule - Insurance](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/ValidationRule2Insurance.png)
- [Fields](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/fields2.png)
- [Fields and Object Insurance](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/fiels%20and%20object%20Insurance%281%29.png)
- [Validation Rule Error](https://raw.githubusercontent.com/tamrachirag/Salesforce-Insurance-Mangement/main/validationRuleError.png)


## 🧰 Tools & Technologies

- Salesforce CRM (Lightning Experience)
- Flow Builder
- Validation Rules
- Classic Email Templates
- Reports & Dashboards
- Permission Sets and Profiles



