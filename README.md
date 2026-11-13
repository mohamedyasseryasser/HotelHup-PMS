
# 🏨 HotelHup

### Hotel Property Management System

HotelHup is a web-based Hotel Property Management System (PMS) designed to help hotel teams manage their daily operations in one place.

It brings together property, room, guest, reservation, folio, payment, housekeeping, and reporting management, reducing the need to rely on disconnected tools and manual workflows.

## 📌 Project Overview

HotelHup is designed for hotel owners and operational teams, including administrators, front-desk staff, and housekeeping staff.

The system provides a centralized platform for managing:

- **Multi-Property Management:** Manage operations across one or more hotel properties.
- **Reservations & Room Availability:** Search availability and manage guest reservations.
- **Guest Management:** Maintain guest profiles and reservation history.
- **Front Desk Operations:** Handle guest check-in, check-out, and room assignments.
- **Billing & Payments:** Manage guest folios, charges, payments, and refunds.
- **Housekeeping:** Create tasks, inspect rooms, and track cleaning progress.
- **Operational Reports:** Monitor occupancy, revenue, reservations, and daily hotel activities.

---

 

## ✨ Features

### 📅 1. Reservations & Front Desk
- Search room availability based on check-in and check-out dates.
- Create, update, confirm, and cancel reservations.
- View reservation details and status history.
- Record guest no-shows.
- Assign and release rooms.
- Process guest check-ins and check-outs.
- Handle early checkouts and checkout extensions.

### 🧾 2. Folios, Billing & Payments
- View guest folios and billing summaries.
- Add and void folio charges.
- Close and reopen folios.
- Record and review payments.
- View payment summaries.
- Record refunds.

### 🏨 3. Property Management
- Create and update hotel property records.
- Activate and deactivate properties.
- Configure property settings and taxes.

### 🛏️ 4. Room & Room Type Management
- Create and manage rooms and room types.
- Update room information and configurations.
- Activate and deactivate rooms and room types.

### 👤 5. Guest Management
- Create, view, and update guest profiles.
- Access guest reservation history.
- Deactivate guest profiles.
- Anonymize guest personal data.

### 💰 6. Rate Plans & Booking Policies
- Create and manage rate plans.
- View rate plan version history.
- Configure cancellation and deposit policies.
- Manage property tax configurations.
- Retain applicable policy snapshots with reservations.

### 🔐 7. User Management & Access Control
- User login, token refresh, and logout.
- Create and manage user accounts.
- Activate and deactivate users.
- Assign roles and enforce role-based and permission-based authorization.
- Restrict access based on assigned hotel properties.

### 🧹 8. Housekeeping Management
- Create and assign housekeeping tasks.
- Start and complete housekeeping tasks.
- Inspect rooms.
- Track and update room-cleaning progress.

### 📊 9. Reports & Dashboard
- Occupancy and revenue reports.
- Arrivals, departures, and current guest reports.
- Room status reports.
- Payment and refund reports.
- Reservation cancellation reports.
- Housekeeping and expense reports.

### ⚙️ 10. Hotel Services & Expenses
- Manage hotel services.
- Record, view, and update expenses.
- Void expenses when applicable.

---

## 📸 Application Screenshots

### 📅 Reservations & Front Desk

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094354.png" width="100%" alt="Reservations Screenshot 1" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094504.png" width="100%" alt="Reservations Screenshot 2" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094751.png" width="100%" alt="Reservations Screenshot 3" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094840.png" width="100%" alt="Reservations Screenshot 4" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094848.png" width="100%" alt="Reservations Screenshot 5" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094857.png" width="100%" alt="Reservations Screenshot 6" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094913.png" width="100%" alt="Reservations Screenshot 7" />
</p>

### 🧾 Billing & Payments

<p align="center" dir="ltr">
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095139.png" width="100%" alt="Billing and Payments Screenshot 1" />
</p>

<p align="center" dir="ltr">
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20171619.png" width="100%" alt="Billing and Payments Screenshot 2" />
</p>

---

## 🅰️ Angular Frontend Highlights

- **Standalone Components:** Modular application structure using standalone components.
- **Lazy Loading & Routing:** Feature-based navigation with lazy-loaded routes.
- **Route Guards:** Authentication, role-based, and permission-based route protection.
- **HTTP Interceptors:** JWT token attachment and centralized HTTP request handling.
- **Angular Services & Dependency Injection:** Reusable services for API communication and application logic.
- **Reactive Forms:** Dynamic forms with validation and error handling.
- **Angular Signals:** Reactive state management and efficient UI updates.
- **TypeScript Interfaces:** Strongly typed models and DTOs.
- **OnPush Change Detection:** Optimized component change detection.

---

## 🏗️ Architecture & Project Structure

### Backend
- **API Layer:** ASP.NET Core controllers expose the application endpoints.
- **Application Layer:** Application services, DTOs, repository/service interfaces, and permission definitions.
- **Core Layer:** Core entities and enums, including users, roles, permissions, properties, reservations, and refresh tokens.
- **Infrastructure Layer:** Repository implementations and data-access integrations.

### Frontend
- **Components:** Angular screens and UI components.
- **Models:** TypeScript models and API data contracts.
- **Services:** API communication, authentication, and permission-related services.
- **Guards:** Route protection for authentication, roles, and permissions.
- **Interceptors:** Attach Bearer access tokens to API requests and handle token refresh.

---

## 🔐 Authentication & Authorization

- JWT Bearer authentication.
- Refresh-token renewal with token rotation and revocation on logout.
- Role-Based Access Control (RBAC) using ASP.NET Identity roles.
- Permission-Based Authorization using application permissions and authorization policies.
- Property-scoped access checks for property-bound users, verified in reservation workflows.

---

## 💡 Key Technical Highlights

- **Layered Architecture:** Separates the API, Application, Core, and Infrastructure layers, with service and repository abstractions.
- **Authentication and Authorization:** Uses JWT bearer authentication, refresh-token rotation, and role- and permission-based access control with property-scoped authorization.
- **Reservation Data Integrity:** Uses SQL Server `RowVersion` tokens for optimistic concurrency checks and serializable transactions around key reservation workflows. Room-availability checks help prevent conflicting room assignments.
- **Versioned Rates and Policy Snapshots:** Supports versioned rate plans and stores applicable pricing and policy details with reservations to preserve the terms used at booking time.
- **Relational Data Management:** Uses Entity Framework Core with SQL Server and database migrations to manage persistence and schema changes.

 
---

## 🛠️ Technologies & Tools

### ⚙️ Backend
- 💻 C#
- 🚀 .NET 8
- 🌐 ASP.NET Core Web API
- 🗄️ Entity Framework Core 8
- 🛢️ Microsoft SQL Server
- 🔐 ASP.NET Core Identity
- 🔑 JWT Bearer Authentication
- 🛡️ Policy-Based Authorization
- ⏳ Hangfire 1.8
- 📚 Swagger / OpenAPI
- 💉 Dependency Injection
- 🔄 CancellationToken
- 🔒 RowVersion & Optimistic Concurrency

### 🎨 Frontend
- 🅰️ Angular 22
- 📘 TypeScript 6
- 📡 RxJS 7.8
- ⚡ Angular Signals
- 🧩 Standalone Components
- 🧭 Angular Router
- 📝 Angular Forms
- 🌐 Angular HttpClient
- 🎨 Bootstrap 5.3
- 💅 CSS3

### 🏗️ Architecture & Design Patterns
- 🏛️ Clean Architecture Style
- 📦 Repository Pattern
- ⚙️ Service Layer
- 📋 DTO Pattern
- 🔗 RESTful API
- 🗃️ Code First Approach
- 🔄 Database Migrations
- 💉 Dependency Injection
- 🔐 Role-Based & Policy-Based Authorization

### 🧪 Testing

**Backend:**
- 🧪 NUnit 5
- 🎭 Moq 4.21
- ⚙️ Microsoft.NET.Test.Sdk
- 🔌 NUnit3TestAdapter

**Frontend:**
- 🧪 Vitest 4
- 🌐 JSDOM
- 🅰️ Angular Testing APIs

### 🔧 Development Tools
- 💻 Visual Studio
- 📝 Visual Studio Code
- 📦 npm 11
- 🅰️ Angular CLI 22
- 🐙 Git & GitHub
- 🚀 Postman
- 📚 Swagger UI
- ✨ Prettier

### ☁️ Deployment & Hosting
- 🌐 MonsterASP
- 🛢️ SQL Server Hosting

---

## 🚀 How to Run

### 📋 Prerequisites

Make sure you have the following installed:

- 💻 .NET SDK 8
- 🛢️ SQL Server
- 🟢 Node.js (Compatible with Angular 22)
- 📦 npm 11.16.0
- 🅰️ Angular CLI 22.0.8
- 📝 Visual Studio 2022, JetBrains Rider, or VS Code

### ⚙️ 1. Backend Setup

**Restore Dependencies**

```bash
dotnet restore
```

**Build the Project**

```bash
dotnet build
```

**Run the Backend**

```bash
dotnet run --project HotelHup/HotelHup/HotelHup.API.csproj
```

**Swagger API Documentation**

Once the backend is running, access Swagger at:

```text
https://localhost:<port>/swagger
```

### 🎨 2. Frontend Setup

**Navigate to the Frontend Directory**

```bash
cd hotelhup_front
```

**Install Dependencies**

```bash
npm install
```

**Start the Angular Application**

```bash
npm start
```

Alternatively:

```bash
ng serve
```

The frontend will be available at:

```text
http://localhost:4200
```

### 🔧 3. Environment Configuration

Before running the application, configure the following:

**Backend Configuration:**
- SQL Server Connection String.
- JWT Secret Key.
- JWT Issuer.
- JWT Audience.
- Hangfire Settings.

**Frontend Configuration:**
- Configure the Backend API Base URL in the Angular Environment Files.

> ⚠️ Never commit sensitive configuration values or JWT secrets to GitHub.

### 🏗️ 4. Build & Testing

**Build Frontend for Production**

```bash
npm run build
```

**Run Frontend Tests**

```bash
npm test
```

```
