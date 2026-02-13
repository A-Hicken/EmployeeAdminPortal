# Employee Admin Portal

Employee Admin Portal is a backend-focused ASP.NET Core Web API designed to manage employee records through clean, structured endpoints. This project demonstrates CRUD operations, database integration using Entity Framework Core, and a scalable project structure suitable for real-world applications.

The goal of this project is to showcase practical backend development skills, including API design, data modeling, and database migrations.

---

## 🚀 Features

- Create, read, update, and delete employee records
- RESTful API endpoints
- Entity Framework Core with code-first migrations
- SQL Server database integration
- Clean separation of concerns (Controllers, Models, Data)
- Environment-based configuration

---

## 🛠 Tech Stack

- **ASP.NET Core**
- **C#**
- **Entity Framework Core**
- **SQL Server**
- **Visual Studio**

---

## 📂 Project Structure

- `Controllers/` – API endpoints
- `Models/` – Data models
- `Data/` – Database context
- `Migrations/` – EF Core migrations
- `Program.cs` – Application entry point and configuration

---

## ⚙️ Getting Started

### Prerequisites

Make sure you have the following installed:

- [.NET SDK](https://dotnet.microsoft.com/download) (compatible with ASP.NET Core)
- SQL Server (LocalDB or full instance)
- Visual Studio or VS Code

---

### 🧩 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/EmployeeAdminPortal.git
   
2. Open the solution

3. Open EmployeeAdminPortal.sln in Visual Studio

4. Configure the database

5. Update the connection string in appsettings.json if needed

6.Apply migrations

dotnet ef database update


7. Run the application

dotnet run

8. Test the API

Use Swagger (if enabled), Postman, or the included .http file

## 📡 API Overview (Example)

GET /api/employees – Get all employees

GET /api/employees/{id} – Get employee by ID

POST /api/employees – Add a new employee

PUT /api/employees/{id} – Update an employee

DELETE /api/employees/{id} – Remove an employee

## 📌 Purpose

This project was built as a learning-focused and portfolio-ready example of backend API development using ASP.NET Core. It emphasizes clean architecture, maintainability, and real-world backend patterns.

## 🧪 Future Improvements

Authentication & authorization

Frontend UI integration

Pagination and filtering

Input validation and error handling enhancements

👤 Author

Built by Amberlie Hicken
