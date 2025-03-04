# Mega Man Robots API

![Mega Man Robots API](./_docs/assets/icon.png)

## 🚀 Features

- Provides structured data on Mega Man series robots.
- RESTful API with clear and efficient endpoints.
- Built with .NET Core 3.1 and Entity Framework Core.
- Implements best practices for dependency injection and data management.

## 📥 Installation & Usage

### Prerequisites
- .NET Core 3.1 SDK
- SQL Server (or configured database provider)

### Clone the Repository
```sh
git clone https://github.com/felipeAguiarCode/MegaApiDotnetCore.git
cd MegaApiDotnetCore
```

### Install Dependencies
```sh
dotnet restore
```

### Run the Application
```sh
dotnet run
```

### API Documentation (Swagger UI)
After running, access:
```
http://localhost:5000/swagger
```

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|---------|-------------|
| **GET** | `/api/v1/robots` | Retrieves a list of all robots. |
| **GET** | `/api/v1/robots/{id}` | Fetches details of a specific robot by ID. |
| **POST** | `/api/v1/robots` | Creates a new robot entry. |

## 🛠️ Technologies Used

- **Entity Framework Core** - ORM for database interaction.
- **ASP.NET Core** - Web API framework.
- **Dependency Injection** - Improves modularity and testability.
- **Swagger UI** - Provides API documentation and testing.

## 📦 Dependencies

| Package | Version | Link |
|---------|---------|------|
| Microsoft.EntityFrameworkCore | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/3.1.8) |
| Microsoft.EntityFrameworkCore.Design | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.Design/3.1.8) |
| Microsoft.EntityFrameworkCore.SqlServer | 3.1.8 | [NuGet](https://www.nuget.org/packages/Microsoft.EntityFrameworkCore.SqlServer/3.1.8) |
| Newtonsoft.Json | 12.0.2 | [NuGet](https://www.nuget.org/packages/Newtonsoft.Json/12.0.2) |

## 📂 Project Structure

```bash
src/
├── 📂 Controllers      # Routes for API endpoints
├── 📂 Models           # Database models
├── 📂 Services         # Business logic layer
├── 📂 Middlewares      # Middleware functions for request processing
├── 📂 Database         # Database-related components
│   ├── 📂 DTOs             # Data Transfer Objects
│   ├── 📂 EntityFramework  # ORM Entity Framework setup
│   │     ├── 📂 Context         # Database context configuration
│   │     ├── 📂 Migrations      # Database migrations
│   ├── 📂 Repositories     # Repository pattern for data access
```

## 📜 License
This software is licensed under the terms of the [MIT License](LICENSE).

👨‍💻 Developed by **Arthur Vieira** - [GitHub](https://github.com/arthurvieira1986)
