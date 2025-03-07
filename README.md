E-commerce Invoice Portal
A React-based application for managing store invoices and products.

Features
Invoice Management
View and filter invoices by date range and store
Calculate item-wise totals with tax
Generate and download PDF invoices
Search invoices by order ID or store name
Product Management
Add, edit, and delete products
Filter products by store
Search products by name or description
Manage product prices (regular and deal prices)
Authentication
Store owner login system
Store-specific data access
Getting Started
Install dependencies:
npm install
Start the development server:
npm start
Open http://localhost:3000 to view the application
Dependencies
React
Redux Toolkit
Material-UI
React Router
jsPDF (for PDF generation)
Moment.js (for date handling)
Project Structure
src/
  ├── components/
  │   ├── auth/
  │   │   └── Login.js
  │   ├── common/
  │   │   └── Navbar.js
  │   ├── invoices/
  │   │   └── InvoiceList.js
  │   └── products/
  │       └── ProductManagement.js
  ├── store/
  │   ├── index.js
  │   └── slices/
  │       ├── authSlice.js
  │       ├── invoiceSlice.js
  │       └── productSlice.js
  └── App.js
Usage
Log in using store credentials
Navigate between Invoices and Products using the navigation bar
Use filters and search functionality to find specific items
Generate PDF invoices by clicking the "Download PDF" button
Manage products through the product management interface
