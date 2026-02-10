# ROJ Office Supplies Dashboard (ERP System)

**Version:** 4.0 (YMK Intelligence)  
**Created By:** Yohannis Megos (YMK)

## 📖 Overview

The **ROJ Office Supplies Dashboard** is a comprehensive Enterprise Resource Planning (ERP) web application designed to manage the day-to-day operations of an office supplies business. It handles inventory tracking, point-of-sale (POS) transactions, financial reporting, supplier management, bid tracking, and payroll processing.

The system features a **Dual Inventory Architecture** (Physical Stock vs. Tax/Official Stock) to manage actual business operations alongside regulatory compliance. It also integrates **Google Gemini AI** to provide an intelligent assistant ("YMK AI") for querying business data using natural language.

---

## 🚀 Key Features

### 1. 📊 Executive Dashboard
*   **Real-time Metrics:** Displays today's revenue, net profit, and transaction counts.
*   **Alert System:** Visual notifications for **Low Stock** items and **Overdue Customer Debts** (>30 days).
*   **Quick Actions:** Shortcuts to essential modules.

### 2. 🏪 Store Management (POS)
The heart of the system for handling daily sales and stock.
*   **Point of Sale:** Record sales via Cash, Credit, CBE Transfer, or Telebirr.
*   **Dual Stock System:**
    *   **Physical Stock:** Tracks actual inventory quantity available in the warehouse.
    *   **Tax Stock:** Tracks inventory reported for tax purposes.
*   **Sales History:** View, edit, and void transactions.
*   **Audit Check:** Analyzes sales to identify "Unreported Sales" (Risk Analysis) by comparing physical vs. official records.

### 3. 📦 Inventory & Products
*   **CRUD Operations:** Add, Edit, and Delete products.
*   **Categorization:** Group items by category (Stationary, Electronics, Sanitary, etc.).
*   **Stock Levels:** Set reorder levels and view cost/selling prices.
*   **History:** Detailed transaction history (Sales vs. Restocking) per item.

### 4. 📜 Registered Bids
*   **Bid Tracking:** Manage tender participation status (**In Progress**, **Won**, **Lost**).
*   **Details:** Track reference numbers, organizations, bid bond amounts, and sample requirements.
*   **Filtering:** Weekly filters and status-based sorting.

### 5. 🚚 Suppliers
*   **Vendor Database:** Manage contact details, TIN numbers, and categories for distributors and manufacturers.
*   **Integration:** Linked to the Purchase Order system for seamless restocking.

### 6. 🛒 Order List (Procurement)
*   **Restocking Workflow:**
    1.  **Pending:** Create purchase orders for low-stock items.
    2.  **Received:** Convert orders to inventory stock upon delivery.
*   **Cost Updates:** Automatically updates `Cost Price` in inventory when new stock is received.
*   **Receipt Tracking:** Flag purchases as "Official" (with FS number) or Internal.

### 7. 💳 Credit Customers (Ledger)
*   **Debtor Management:** Track individual customer balances.
*   **Ledger System:** Chronological record of Debts (Sales) vs. Payments.
*   **Settlement:** Settle specific invoices or make lump-sum payments.
*   **Returns:** Process item returns which automatically adjusts inventory and customer balance.

### 8. 💸 Expenses & Payroll
*   **General Expenses:** Record operational costs (Rent, Utilities, Transport) categorized for reporting.
*   **Payroll System:**
    *   Employee database management.
    *   **Auto-Calculation:** Automatically calculates **Income Tax** (based on Ethiopian tax brackets), **Pension (7%)**, and **Company Pension (11%)**.
    *   Generates Net Pay and records total company expense.

### 9. 📈 Financial Summary Reports
*   **Income Statement:** Revenue, COGS, Gross Profit, Expenses, and Net Income.
*   **Balance Sheet:** Assets (Cash, Accounts Receivable, Inventory, Fixed Assets) vs. Liabilities (VAT, Pension) & Equity.
*   **Modes:**
    *   **Internal (All):** Shows the true financial health of the business.
    *   **Official (Tax):** Generates reports based strictly on transactions with official receipts.
*   **Drill-down:** Click on report lines to see specific transaction details.
*   **Export:** Generate PDF and Excel reports.

### 10. 🤖 YMK AI Chat
*   **AI Assistant:** A chat interface powered by **Google Gemini**.
*   **Capabilities:** Ask questions in **English or Amharic**.
    *   *"How much did we sell today?"*
    *   *"List items with low stock."*
    *   *"Who is the customer with the highest debt?"*

---

## 🛠 Tech Stack

### Frontend
*   **React (v18/19):** UI Component library.
*   **TypeScript:** Type safety and better developer experience.
*   **Tailwind CSS:** Utility-first styling.
*   **Vite:** Build tool and development server.
*   **Libraries:** `jspdf` (PDF generation), `xlsx` (Excel export), `@google/genai` (AI integration).

### Backend
*   **PHP:** Server-side logic and API endpoints.
*   **MySQL:** Relational database management.
*   **Architecture:** RESTful API communicating via JSON.

---

## 📂 Project Structure

---
*Created by Yohannis (YMK) - Full Stack Developer & System Architect.*
<img width="1335" height="627" alt="ymk 1" src="https://github.com/user-attachments/assets/44ef1746-e2d1-4a55-a036-90b44083164f" />
<img width="1360" height="646" alt="ymk 3" src="https://github.com/user-attachments/assets/2e61c393-0fd1-476e-afbb-ad9ed13afdda" />
<img width="1360" height="646" alt="ymk 2" src="https://github.com/user-attachments/assets/39d25168-57f6-4c85-9274-cf2d474774f6" />
