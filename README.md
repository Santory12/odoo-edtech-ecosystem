# Odoo Community: EdTech & Subscription Management

## 📌 Overview
This repository highlights a comprehensive ecosystem configuration built entirely on **Odoo 17 Community Edition** for an international language school managing over 30 instructors and 2,000+ students. 

This project demonstrates the power of "Out-Of-The-Box" (OOTB) Odoo Community configuration, proving that complex billing and e-learning workflows can be achieved with minimal custom coding through deep architectural knowledge.

## 🏢 Business Challenge
The language school required a unified platform to replace fragmented tools used for student billing, lesson tracking, and instructor payroll. Key challenges included:
- Tracking student prepaid balances (Subscriptions).
- Automating tutor payroll based on varying hourly rates.
- Providing a digital space (Portal) for students to take quizzes and track their progress.

## 💡 Solution & Configuration Strategy
We deployed a tightly integrated suite of standard Odoo Community modules (Sales, Invoicing, CRM, eLearning) and configured advanced business workflows:

### Key Implementations:
1. **Automated Balance Deduction:** Configured automated workflows where moving a lesson card to the "Completed" stage in the CRM/Project pipeline automatically deducts the specific lesson cost from the student's prepaid balance.
2. **Automated Tutor Payroll (Vendor Bills):** Set up a system where completed lessons automatically generate draft Vendor Bills (`in_invoice`) for the instructors, dynamically calculating payouts based on their individual hourly rates.
3. **Customized Student Portal:** Adapted the standard Odoo eLearning portal to match the brand's visual identity. Students can securely log in, view their remaining balance, access learning materials, and complete interactive quizzes.
4. **Multi-Currency Adaptation:** Fully localized the accounting and invoicing flows to support PLN (Polish Zloty) billing compliance.

## 🛠 Tech Stack & Modules Used
- **Platform:** Odoo 17 Community
- **Core Modules:** eLearning, Invoicing, Sales, CRM, Contacts
- **Concepts:** Automated Actions, Record Rules, Portal Customization, Financial Localization

> **Note:** *This repository serves as a portfolio showcase of Odoo configuration architecture. Client-specific data, proprietary course materials, and production databases have been strictly excluded under NDA.*