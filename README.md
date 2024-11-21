# Automated Data Extraction and Invoice Management

This project is a React-based application for automating the extraction, processing, and management of invoice data from various file formats. It organizes the extracted data into three main sections: Invoices, Products, and Customers. The app ensures that data is synchronized in real-time using Redux for consistent updates across the application.

## Features

1. **File Uploads, AI-Powered Data Extraction, and Organization**:

   - Accepts various input files such as:
     - **Excel Files**: Contains transaction details (serial number, net/total amount, customer info).
     - **PDF/Images**: Invoices with customer and item details, totals, tax, etc.
   - Implements a generic AI-based extraction solution to identify and organize relevant data into the appropriate tabs (Invoices, Products, Customers).

2. **React App Structure with Tabs**:

   - **Invoices Tab**: Displays a table with invoice data such as Serial Number, Customer Name, Product Name, Quantity, Tax, Total Amount, and Date.
   - **Products Tab**: Displays a table with details like Name, Quantity, Unit Price, Tax, Price with Tax.
   - **Customers Tab**: Displays a table with Customer Name, Phone Number, and Total Purchase Amount.

3. **Centralized State Management (Redux)**:

   - Synchronizes changes in real-time across all tabs.
   - Any updates made in the Products or Customers tabs are instantly reflected in the Invoices tab.

4. **Validation and Error Handling**:

   - Ensures data validation for completeness and accuracy.
   - Handles missing or incomplete fields, providing clear user feedback.
   - Supports different file types and gives feedback for unsupported formats.

5. **Code Quality and Documentation**:
   - Follows React/Redux best practices.
   - Includes documentation on AI-powered data extraction.
   - Provides test cases with screenshots/videos of working functionality.

## Installation

To get started with the project, clone the repository and install the necessary dependencies.

```bash
   git clone https://github.com/hzratali/invoice-management-swipe.git
   cd invoice-management-swipe
   npm install
```