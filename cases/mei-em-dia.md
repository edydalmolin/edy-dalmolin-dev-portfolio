# MEI em Dia

**Business management app for Brazilian micro-entrepreneurs**

MEI em Dia is a Flutter application designed to help self-employed professionals and small business owners organize the most important parts of their daily operation in one place.

The product focuses on simplicity, clarity and practical business control.

## Product Overview

The application centralizes:

- Client management
- Income and expenses
- Accounts receivable
- Accounts payable
- Appointments and reminders
- Budgets and quotes
- Business overview
- MEI-specific information and financial guidance
- AI-assisted business interaction

## Tech Stack

- Flutter
- Dart
- Riverpod
- GoRouter
- Drift
- SQLite
- Material 3
- REST-ready architecture
- Android
- iOS
- Automated testing

## Architecture

The project follows a modular, feature-first architecture with clear separation between UI, business logic and data layers.

Each major feature is organized independently, with controllers, repositories, domain models and persistence responsibilities separated to improve maintainability and scalability.

The application uses Drift + SQLite for typed local persistence and Riverpod for state management.

Navigation is handled with GoRouter.

## Main Modules

### Clients

Full client management with:

- Create, edit and search
- Contact information
- Financial relationships
- Outstanding amounts
- Client history
- WhatsApp interaction
- Protection against deleting clients with linked records

### Financial Management

The financial module supports:

- Income
- Expenses
- Monthly filtering
- Cash-flow visibility
- Business result calculation
- Optional client association

### Receivables and Payables

The app includes:

- Pending receivables
- Pending payables
- Due dates
- Overdue tracking
- Status filtering
- Settlement workflow
- Automatic financial entry generation when a receivable is settled

### Agenda

Users can organize:

- Appointments
- Payment reminders
- Receivable reminders
- Completed and pending items
- Overdue tasks
- Client-linked events

### Budgets and Quotes

The budgeting flow supports:

- Draft creation
- Client association
- Status changes
- Sent and approved states
- Conversion of approved budgets into receivables

### Business Dashboard

The home screen consolidates:

- Monthly income
- Monthly expenses
- Financial result
- Receivables
- Payables
- Upcoming commitments
- Budget shortcuts
- Business assistant access

### MEI Management

The application includes a business-focused module for Brazilian MEIs with:

- Annual revenue visibility
- Revenue limit monitoring
- Working capital guidance
- Business obligations
- Configuration and business information

## Quality and Testing

The project includes automated tests for business logic, repositories, controllers and feature workflows.

The development process prioritizes maintainable code, modularization and regression protection.

## Product Development Focus

MEI em Dia was designed as a real commercial product rather than a technical demonstration.

The development process involved:

- Product definition
- Feature architecture
- Local data modeling
- Business rules
- Financial workflows
- User experience decisions
- Automated validation
- Android build preparation
- iOS-ready project structure

## My Role

I am responsible for the product direction, architecture decisions, implementation workflow, validation and continuous evolution of the application.

AI-assisted development tools are used to increase productivity, while architecture, product decisions, testing and final validation remain actively reviewed.

## Status

The application is under active development and release preparation.

The source code remains private because this is a commercial product.

---

[Back to portfolio](../README.md)
