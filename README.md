WebApiInMemoryDemo
📌 Overview

This project is a .NET 8 ASP.NET Core Web API demo application designed to showcase RESTful API development using:

HTTP verbs (GET, POST, PUT, DELETE)

Entity Framework Core In-Memory Database

Swagger UI (OpenAPI) for API documentation and testing

This project is intended as a technical demonstration for reqruiters to highlight backend API skills and best practices.

🚀 Features

RESTful API design

CRUD operations

In-memory database (no external DB required)

Swagger UI for API exploration and testing

Clean and simple project structure

.NET 8 (LTS)

🛠️ Technologies Used

.NET 8

ASP.NET Core Web API

Entity Framework Core (InMemory Provider)

Swashbuckle Swagger (OpenAPI)

C#

📂 Project Structure
WebApiInMemoryDemo
│
├── Controllers
│   └── ProductsController.cs
│
├── Data
│   └── AppDbContext.cs
│
├── Models
│   └── Product.cs
│
├── Program.cs
├── WebApiInMemoryDemo.csproj
└── README.md

🔄 API Endpoints
HTTP Verb	Endpoint	Description
GET	/api/products	Get all products
GET	/api/products/{id}	Get product by ID
POST	/api/products	Create new product
PUT	/api/products/{id}	Update existing product
DELETE	/api/products/{id}	Delete product
▶️ How to Run the Project
Prerequisites

.NET 8 SDK

Git

Steps
git clone https://github.com/ashikasameera-rgb/Web-API-Demo-using-in-Memory-DB.git 
cd WebApiInMemoryDemo
dotnet restore
dotnet run

📖 Swagger UI

Once the application is running, open your browser:

https://localhost:<port>/swagger


Swagger UI allows you to:

View all available API endpoints

Send test requests

Inspect request/response payloads

💾 In-Memory Database Behavior

Uses EF Core InMemory provider

Data is stored only in memory

Data is reset when the application restarts

Ideal for demos, testing, and learning purposes

🎯 Purpose of This Project

This demo was created to:

Demonstrate backend Web API skills

Show understanding of REST principles

Illustrate clean API design and structure

Provide a lightweight, easy-to-run example for evaluation

🔮 Possible Enhancements

DTOs & AutoMapper

Repository Pattern

Authentication (JWT)

SQL Server / MySQL integration

Unit & Integration Testing

Pagination & Filtering
