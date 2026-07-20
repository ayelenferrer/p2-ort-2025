# ✈️ Flight Reservation System - ASP.NET MVC

This project is an academic prototype of an airline ticket sales system, developed using ASP.NET 8.0 MVC **without database persistence**. All data is managed in memory, simulating the real operation of the system.

## 🧭 Main Features

- User management for **administrators** and **customers** (premium and occasional).
- Simulated catalog of **aircraft** and their characteristics.
- Registration of **airports**, **routes**, and **flights**, with validations such as range and frequency.
- **Ticket issuance** with dynamic price calculation, taking into account:
  - Seat cost (distance, airport costs, and operational costs).
  - Customer type and luggage.
  - Departure and arrival fees.
  - Profit margin.
- Web interface built with ASP.NET 8.0 MVC and **role-based access control**.
- Complete simulation without the need for SQL Server or Entity Framework.

## 🔐 User Roles

- **Administrator**:
  - Can modify premium customers' points.
  - Can change gift eligibility for occasional customers.
  - Has access to protected administrative features.

- **Customer**:
  - Can view and purchase tickets.
  - Can access personal information and reservations.
  - Has different behavior depending on whether they are premium or occasional.

## ⚙️ Technologies Used

- ASP.NET 8.0 MVC
- C# .NET
- CSS
- JavaScript
- Bootstrap 5
- In-memory business logic (no SQL, no Entity Framework)
- Role-based authentication and authorization

## 🚀 How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/codewitheduardo/Obl-P2-mar25.git
   ```
2. Open the project in Visual Studio 2022 or later.
3. Run the application (F5 or dotnet run).
4. Sample users and data are loaded automatically from the code.
   
