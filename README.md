# BellaHair
BellaHair is a comprehensive, full-stack salon management system developed as a 2nd-semester exam project for the AP Computer Science program at UCL University College. 

The primary goal of the application is to streamline day-to-day hair salon operations by providing a unified, intuitive interface for handling complex booking rules, employee scheduling, customer loyalty, and automatic invoicing.

> ⚠️ **Portfolio Note:** This repository is an imported version of the original group project, showcased here as part of my personal professional portfolio.

## ✨ Key Features

#### 📅 Advanced Booking System
Manage salon appointments with intelligent built-in overlap prevention and real-time employee scheduling checks to ensure no double-bookings.

#### 👥 Customer & Employee Management
Keep track of private customers, their individual visit histories, and loyalty statuses. It also manages employee profiles, rosters, and the specific treatments they are qualified to offer.

#### 💇 Treatments & Products Catalog
Maintain a detailed catalog of salon treatments (including dynamic durations and pricing) as well as retail product inventory.

#### 💸 Dynamic Discount Engine
Automatically calculate and apply various discount types at checkout, including Loyalty Discounts, Campaign/Promotional Discounts, and Birthday Discounts.

#### 🧾 Invoicing & Receipt Generation
Automatically generate accurate, itemized, and professionally styled invoices and receipts for completed bookings.

## 🛠️ Tech Stack & Architecture
This project was built with a strong focus on modularity, scalability, and strict software engineering principles:

- **Frontend:** Interactive and responsive web UI built with Blazor, styled using MudBlazor and Radzen components.
- **Backend:** .NET 9 / C# supplying a robust enterprise foundation.
- **ORM & Database:** Entity Framework Core utilizing MSSQL for production and SQLite for development.
- **Architecture:** Clean Architecture and Domain-Driven Design (DDD) to separate concerns and ensure framework independence.
- **Design Patterns:** CQRS (Command Query Responsibility Segregation) pattern separating read and write operations for maximum testability.
- **Invoicing:** Document generation handled via QuestPDF for pixel-perfect PDF receipts.
- **Testing:** Comprehensive unit testing implemented using NUnit and FixtureBuilder to cover domain behavior and handlers.
