````md id="l11b50"
# QuickInvoice - Invoice Generator Web Application

QuickInvoice is a full-stack Invoice Generator Web Application developed using React.js, Spring Boot, and MongoDB. The application helps users create, manage, export, and share professional invoices digitally.

The system provides secure authentication using Clerk, PDF invoice generation, invoice storage using MongoDB, and email integration using Brevo (Sendinblue). It is designed for freelancers, startups, and small to medium-sized businesses to simplify billing operations and reduce manual work.

---

# Features

- Secure User Authentication using Clerk
- Create and Manage Professional Invoices
- Add Multiple Invoice Items
- Automatic Price and Total Calculation
- Generate Downloadable PDF Invoices
- Send Invoices through Email using Brevo
- Store Invoice Records in MongoDB
- Responsive and Interactive User Interface
- RESTful API Communication
- Secure and Scalable System

---

# Technologies Used

## Frontend
- React.js
- HTML
- CSS
- JavaScript
- Vite

## Backend
- Java
- Spring Boot
- Spring MVC
- REST APIs

## Database
- MongoDB

## Authentication
- Clerk

## Email Service
- Brevo (Sendinblue)

## PDF Generation
- iText / PDFBox

## Version Control
- Git & GitHub

````
---

# Usage

1. Register or Login using Clerk Authentication.
2. Create a new invoice.
3. Add customer details and invoice items.
4. Generate invoice PDF.
5. Download the invoice.
6. Send invoice through email.
7. View invoice history.
8. Edit or delete invoices anytime.

---

# API Endpoints

## Authentication APIs

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| POST   | /api/auth/login    | User Login        |
| POST   | /api/auth/register | User Registration |

## Invoice APIs

| Method | Endpoint           | Description       |
| ------ | ------------------ | ----------------- |
| GET    | /api/invoices      | Get All Invoices  |
| GET    | /api/invoices/{id} | Get Invoice By ID |
| POST   | /api/invoices      | Create Invoice    |
| PUT    | /api/invoices/{id} | Update Invoice    |
| DELETE | /api/invoices/{id} | Delete Invoice    |

---

# Problem Statement

Many freelancers and small businesses still use manual methods such as handwritten bills or spreadsheets for invoice creation. These methods are time-consuming, error-prone, and difficult to manage.

QuickInvoice solves these issues by providing:

* Automated invoice creation
* Centralized invoice storage
* PDF export functionality
* Email integration
* Secure user authentication
* Professional invoice formatting

---

# Objectives

* To develop a secure invoice generation system.
* To simplify invoice management.
* To generate professional PDF invoices.
* To provide automated email delivery.
* To reduce manual calculation errors.
* To build a scalable full-stack web application.

---

# System Modules

## Authentication Module

Handles secure login, signup, and session management using Clerk.

## Invoice Management Module

Allows users to create, edit, update, and delete invoices.

## PDF Generation Module

Converts invoice data into professional PDF documents.

## Email Integration Module

Sends invoices directly to customers using Brevo.

## Database Module

Stores invoice and user information securely in MongoDB.

---

# Database Collections

## User

Stores user account information.

## Invoice

Stores invoice details and customer information.

## Item

Stores invoice item details such as product name, quantity, and price.

---

# Advantages

* Reduces manual effort
* Saves time in billing
* Easy invoice management
* Secure authentication
* Professional invoice format
* Quick PDF generation
* Email sharing support
* Scalable and reliable system

---

# Future Enhancements

* Payment Gateway Integration
* GST and Tax Automation
* Multi-role Access
* Invoice Analytics Dashboard
* Cloud Deployment
* Mobile Application Support
* Dark Mode

---

# GitHub Repository

```
https://github.com/AnshikaBukhariya/QuickInvoice
```

```
```
