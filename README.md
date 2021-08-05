# Npgsql Entity Framework Core Provider - Code First

This is a workshop in order to understand the code first Entity Framework Core with PostgreSQL, you should have install postgreSQL and get a conection string. 

1. `dotnet new console -o Blogging`
2. `dotnet add package Microsoft.EntityFrameworkCore.Sqlite`
3. Create the model to migrate
4. Install dotnet-ef
    `dotnet tool install --global dotnet-ef`
5. Install Microsoft.EntityFrameworkCore.Design
    `dotnet add package Microsoft.EntityFrameworkCore.Design`
6. Create the frist migration
    `dotnet ef migrations add InitialCreate`
7. Run the migration
    `dotnet ef database update`
8. Run the main to test the conection and transact
