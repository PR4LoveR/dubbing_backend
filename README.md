# Lviv Regional Puppet Theater
## Demo test
## Backend technology stack:
- .NET Core 2.2
- ASP.NET Core (with SignalR Core)
- ORM: Entity Framework Core
- DB: MS SQL Server
- Unit tests: xUnit
- GitHub Actions

## How to setup:  
```
dotnet restore
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```
## API documentation:
http://localhost:5000/swagger

