# Invoice Payment Tracker

**Course:** COP5818 - Full Stack Development for FinTech  
**Student:** Zachary Armstrong  
**Team:** Group 6 - Individual Project

## Project Purpose

Invoice Payment Tracker is a small web application that helps a small-business owner record invoices, track payments, and see how much customers still owe. The application will use fictional financial data in U.S. dollars.

## Essential Features

1. Create invoices with a customer name, invoice number, invoice date, due date, and amount.
2. View invoices with their outstanding balances and calculated payment status: unpaid, partially paid, or paid.
3. Record simulated payments against an invoice and view its payment history.
4. View summary totals for invoice amounts, payments received, and outstanding balances.

## Main Workflow

The user creates an invoice, records a payment, and sees the updated balance and payment status.

For example, an invoice for $600.00 with a recorded payment of $200.00 will show an outstanding balance of $400.00 and a status of partially paid.

## Planned Technology

- Frontend: HTML, CSS, and JavaScript
- Backend: Node.js and Express
- Database: File-backed SQLite

The browser will communicate with the Express API, which will validate requests and read or write SQLite records. The database will contain related invoices and payments tables. Monetary amounts will be stored as integer cents, and balances will be calculated from saved records.

## Responsibilities and Development Workflow

As the sole member, I am responsible for planning, frontend development, backend development, database design, integration, testing, and documentation.

I will track tasks with GitHub Issues, pull the latest main branch before starting work, use short feature branches, make meaningful commits, and open pull requests. Before merging, I will review my changes and test the affected workflow.

## Testing Plan

Testing will check financial calculations, invalid inputs, the complete browser-API-database workflow, and persistence after restarting the application. Payments must be positive and cannot exceed the remaining invoice balance.

## Scope and Current Status

This repository is currently in the proposal stage. Application implementation has not started.

The project will run locally and will not process real payments. Bank connections, user authentication, multiple currencies, and public deployment are outside the planned scope.

Setup, run, and testing instructions, fictional sample data, source acknowledgments, and known limitations will be added as implementation progresses.

## Planning Sources and Assistance

The project plan follows the COP5818 P1 Project Proposal instructions and the course Expense Tracker materials. ChatGPT assisted with organizing the initial project scope and drafting this README. Any use of AI for submitted work must follow the course syllabus policy.
