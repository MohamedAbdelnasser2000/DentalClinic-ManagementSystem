# Dental Clinic Management System

An ASP.NET Core dental clinic management application built with **.NET 8**, **Entity Framework Core**, and **ASP.NET Core Identity**. The project demonstrates a database-backed clinic workflow with a structured web application and role-aware access.

## Technology Stack

- C# and ASP.NET Core
- .NET 8
- Entity Framework Core
- ASP.NET Core Identity
- SQL Server and SQLite support
- Razor-based web interface

## Project Structure

The main application is located in `DentalClinicSystem/`. The solution also includes the Visual Studio solution file and documentation assets associated with the clinic-management experience.

## Getting Started

### Prerequisites

- .NET 8 SDK
- SQL Server or SQLite, depending on the selected configuration

### Run locally

```bash
git clone https://github.com/MohamedAbdelnasser2000/DentalClinic-ManagementSystem.git
cd DentalClinic-ManagementSystem
dotnet restore
dotnet ef database update
dotnet run --project DentalClinicSystem
```

Open the local URL printed by the application.

## Configuration and Security

Store connection strings and Identity configuration through User Secrets or environment variables. Never commit passwords, API keys, or production database credentials. The `.vs` and `.vscode` directories are local IDE artifacts and should remain excluded through `.gitignore`.

The repository also contains a `bash.exe.stackdump` diagnostic artifact. Remove it in a separate cleanup commit if it is not required, because it is not part of the application.

## Portfolio Context

This repository should be presented as an additional clinic-management implementation alongside `Dental-Clinic-MS`. Keep only the stronger and more complete version pinned on the public profile to avoid making the portfolio appear repetitive.

## Contact

- LinkedIn: [Mohamed Abdelnasser](https://www.linkedin.com/in/mohamed-abdelnasser-krsoon-8b448134b)
- Email: [mnkq2000@gmail.com](mailto:mnkq2000@gmail.com)

## License

No license has been declared yet. Add an explicit license before accepting external contributions or presenting the project as reusable open-source software.
