# Project2 - Inventario API

One-liner: API REST para gestión de inventario con CRUD, filtros y paginación.  
Stack: .NET 8, ASP.NET Core, Entity Framework Core, SQL Server, Docker.

## Endpoints básicos
- `GET /items` (con paginación y filtros)
- `GET /items/{id}`
- `POST /items`
- `PUT /items/{id}`
- `DELETE /items/{id}`

## Requisitos
- .NET 8 SDK
- SQL Server / Docker

## Ejecutar local
1. Configura la cadena de conexión en `appsettings.json` o `.env`.
2. `dotnet restore`
3. `dotnet run`

## Tests
```bash
dotnet test
