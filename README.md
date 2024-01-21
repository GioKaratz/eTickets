# eTickets  

This ASP.NET Core application, built with the eTickets framework, focuses on managing and presenting electronic tickets. It leverages services for actors, producers, cinemas, movies, and orders, ensuring a comprehensive ticketing experience. The application incorporates secure authentication and authorization mechanisms through ASP.NET Core Identity and Cookie Authentication. The use of Entity Framework Core with SQL Server provides a robust data storage solution. Additionally, the implementation includes session management and seed data initialization for a seamless user experience

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Setup](#setup)

## Introduction

eTickets: Your go-to solution for seamless electronic ticket management. Built on ASP.NET Core, this application offers services for actors, producers, cinemas, movies, and orders. With secure authentication, efficient data handling, and a user-friendly interface, eTickets ensures a smooth and reliable ticketing experience. Explore the world of electronic tickets with ease and convenience.

## Technologies

List the technologies or frameworks used in your project.

- .NET 8.0:
- ASP.NET Core
- Entity Framework Core
- ASP.NET Core Identity
- SQL Server
- Visual Studio 2022

## Setup

- Clone or Download the Project
- Open the Project in Visual Studio
- Restore Dependencies
```bash
# cmd
dotnet restore
```

- Configure Database Connection in the appsettings.json file
- Initial Database Migration
```bash
# cmd
dotnet ef migrations add InitialCreate
dotnet ef database update
```

- Build and Run the Project
```bash
# cmd
dotnet build
dotnet run
