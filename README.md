# Power Apps Canvas App - Contoso Coffee Machine Ordering

## Overview

This is my **first Canvas App** built using Microsoft Power Apps. It is a beginner-level project where I created a coffee machine ordering system for Contoso Coffee. This app was developed as a learning project to explore the Power Platform, including Canvas Apps, Dataverse, Power Automate, and Model-driven Apps.

Through this project, I learned how to build a complete business application from scratch — from designing the UI in Canvas Apps to setting up data tables in Dataverse and creating automated approval workflows using Power Automate.

## Features

- Product catalog with multiple coffee machine categories
- Side-by-side comparison of machines
- Machine ordering with approval workflow
- Power Automate integration for automated approval requests
- Machine Procurement app for approvers (Model-driven app)
- Business Process Flow for order tracking
- Dataverse tables for storing machine and order data
- Responsive canvas app design

## Tech Stack

- Microsoft Power Apps (Canvas App)
- Microsoft Dataverse
- Power Automate (Cloud Flows)
- Model-driven App (Machine Procurement)
- Business Process Flow
- Microsoft Teams (Notifications)

## Screenshots

![App Screenshots](Screenshots/s1.jpg)

![Screenshot 2](Screenshots/s2.jpg)

![Screenshot 3](Screenshots/s3.jpg)

![Screenshot 4](Screenshots/s4.jpg)

![Screenshot 5](Screenshots/s5.jpg)

![Screenshot 6](Screenshots/s.jpg)

## Project Structure

```PowerApps-Contoso-Coffee-Machine-Ordering/

Solution/
  ContosoCoffeeApproval_1_0_0_1.zip

Screenshots/
  s1.jpg
  s2.jpg
  s3.jpg
  s4.jpg
  s5.jpg
  s.jpg

Docs/
  Importing Module 1.docx
  Importing Module 2.docx
  Importing Module 3.docx
  Complete Solution.docx
  README.md

.gitignore
README.md
```

## How to Use

1. **Download the solution file** from `Solution/ContosoCoffeeApproval_1_0_0_1.zip`
2. Go to the **Power Apps Maker Portal**
3. **Import the solution** using the Import option
4. Add necessary connections (Microsoft Teams, etc.) during import
5. **Publish All Customizations** after import
6. **Launch the Machine Ordering App**
7. Browse machines, compare, and submit an order
8. Check the **Machine Procurement App** for approval workflow

## Quick Start Commands (Git)

```bash
git clone https://github.com/grishmachawla/PowerApps-Contoso-Coffee-Machine-Ordering.git
cd PowerApps-Contoso-Coffee-Machine-Ordering
```

## App Components

- **Machine Ordering App** - Canvas app for browsing and ordering machines
- **Machine Procurement App** - Model-driven app for managing orders and approvals
- **Machine Order Table** - Dataverse table storing order records
- **New Machine Approval Request Flow** - Power Automate cloud flow for approvals
- **Business Process Flow** - Order lifecycle management

## Use Case

This application demonstrates a coffee machine ordering system built as a **learning project**. It covers:

- Customer-facing product catalog and ordering system
- Automated approval workflow using Power Automate
- Management dashboard for order processing
- Integration with Microsoft Teams for notifications

## Author

Grishma Chawla

## If you like this project

Give it a * on GitHub!

## My Learning Journey

This was my **first Canvas App** project and it was a great introduction to the Power Platform. Here is what I learned:

- Building a Canvas App from scratch using drag-and-drop components
- Creating and managing Dataverse tables and relationships
- Designing automated workflows using Power Automate cloud flows
- Building Model-driven apps for admin/procurement management
- Implementing approval workflows with Power Automate
- Configuring Business Process Flows for order tracking
- Connecting apps with Microsoft Teams for notifications
- Understanding the complete Power Platform ecosystem

## Challenges Faced

- Learning the Power Fx formula language for the first time
- Understanding Dataverse table relationships and lookups
- Debugging Power Automate flow errors
- Designing a clean and user-friendly app layout

## Future Improvements

- Add more validation and error handling
- Implement email notifications for order status
- Add analytics dashboard for order trends
- Expand the product catalog with more categories
