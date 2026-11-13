
# 🏨 HotelHup

### Hotel Property Management System

HotelHup is a web-based Hotel Property Management System (PMS) designed to help hotel teams manage their daily operations in one place.

It brings together property, room, guest, reservation, folio, payment, housekeeping, and reporting management, reducing the need to rely on disconnected tools and manual workflows.

---

## 🚀 Features

HotelHup covers the complete hotel guest journey, from reservation creation to check-out, billing, and reporting.

### 🛎️ 1. Reservations & Front Desk

- **Reservation lifecycle:** Create, modify, confirm, and cancel bookings, with availability search, booking details, and status-change history.
- **Guest stay operations:** Check-in, check-out, room assignment and release, checkout extension, and early checkout.
- **No-show handling:** Record and manage no-show reservations.
- **Room availability:** Search available rooms based on dates, occupancy, and room requirements.

**Screenshots:**

<p align="center">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094354.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094504.png" width="48%" />
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094751.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094840.png" width="48%" />
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094848.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094857.png" width="48%" />
  <img src="docs/images/Reservations%20%26%20Front%20Desk/Screenshot%202026-11-13%20094913.png" width="48%" />
</p>

---

### 💳 2. Billing, Payments & Reports

- **Folio management:** View folios and summaries, add charges, void items, and close or reopen folios.
- **Payments:** Record payments, view payment summaries, and process refunds.
- **Financial tracking:** Monitor financial transactions and billing activities.
- **Reports:** Occupancy, revenue, arrivals, departures, in-house guests, room status, payments, refunds, cancelled reservations, housekeeping, and expenses.

**Screenshots:**

<p align="center">
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095049.png" width="48%" />
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095056.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095139.png" width="48%" />
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095308.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Billing,%20Payments%20%26%20Reports/Screenshot%202026-11-13%20095330.png" width="48%" />
</p>

---

### 🏨 3. Properties, Rooms & Guests

- **Properties:** Create and update hotel details and settings, activate or deactivate properties, and manage property-level taxes and policies.
- **Rooms & room types:** Create, update, activate, or deactivate rooms and room types, with available-room search.
- **Guest profiles:** Add, update, and view guest profiles and booking history.
- **Guest privacy:** Deactivate guest profiles or anonymize personal data.

**Screenshots:**

<p align="center">
  <img src="docs/images/Properties,%20Rooms%20%26%20Guests/Screenshot%202026-11-13%20100029.png" width="48%" />
  <img src="docs/images/Properties,%20Rooms%20%26%20Guests/Screenshot%202026-11-13%20100054.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Properties,%20Rooms%20%26%20Guests/Screenshot%202026-11-13%20100126.png" width="48%" />
  <img src="docs/images/Properties,%20Rooms%20%26%20Guests/Screenshot%202026-11-13%20100225.png" width="48%" />
</p>

---

### 💰 4. Rates & Policies

- **Rate plans:** Manage rate plans and view their version history.
- **Taxes:** Configure and manage property-level tax settings.
- **Cancellation policies:** Create, update, and activate or deactivate cancellation policies.
- **Deposit policies:** Configure deposit requirements and payment conditions.
- **Policy snapshots:** Preserve policy details on reservations to maintain historical consistency.

**Screenshots:**

<p align="center">
  <img src="docs/images/Rates%20%26%20Policies/Screenshot%202026-11-13%20100326.png" width="48%" />
  <img src="docs/images/Rates%20%26%20Policies/Screenshot%202026-11-13%20100343.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Rates%20%26%20Policies/Screenshot%202026-11-13%20100432.png" width="48%" />
</p>

---

### 🧹 5. Hotel Operations

- **Housekeeping:** Create and assign housekeeping tasks.
- **Cleaning workflow:** Start and finish cleaning tasks and inspect rooms.
- **Room readiness:** Track room conditions and inspection status.
- **Services & expenses:** Manage hotel services and record, view, update, or cancel expenses.

**Screenshots:**

<p align="center">
  <img src="docs/images/Hotel%20Operations/Screenshot%202026-11-13%20100643.png" width="48%" />
  <img src="docs/images/Hotel%20Operations/Screenshot%202026-11-13%20100656.png" width="48%" />
</p>

---

### 🔐 6. Users & Access Management

- **User management:** Create and manage user accounts, activate or deactivate users.
- **Role management:** Manage roles and assign roles to users.
- **Authentication:** Login, access-token refresh, and logout.
- **Authorization:** Role- and permission-based access control.
- **Property-level access:** Restrict users to their assigned hotel properties.

**Screenshots:**

<p align="center">
  <img src="docs/images/Users%20%26%20Access/Screenshot%202026-11-13%20100910.png" width="70%" />
</p>

---

## 🖥️ Application UI

HotelHup provides a responsive web interface for managing hotel operations through a centralized dashboard.

**Screenshots:**

<p align="center">
  <img src="docs/images/Application%20UI/Screenshot%202026-11-13%20101105.png" width="48%" />
  <img src="docs/images/Application%20UI/Screenshot%202026-11-13%20101143.png" width="48%" />
</p>

<p align="center">
  <img src="docs/images/Application%20UI/Screenshot%202026-11-13%20101155.png" width="70%" />
</p>

 ## Architecture

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

## Authentication & Authorization
- JWT Bearer authentication.
- Refresh-token renewal with token rotation and revocation on logout.
- Role-Based Access Control (RBAC) using ASP.NET Identity roles.
- Permission-Based Authorization using application permissions and authorization policies.
- Property-scoped access checks for property-bound users, verified in reservation workflows.

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
