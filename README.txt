This application demonstrate CRUD Operations using Entity Framework Core in .Net 6 WebAPI 

Libraries required to use Entity Framework:

Microsoft.EntityFrameworkCore
Microsoft.EntityFrameworkCore.Design
Microsoft.EntityFrameworkCore.SqlServer


Commands used for Code first migration:

1 - dotnet ef -> to check installed EF details

2 - dotnet ef migrations add CreateInitial - > This will create Migrations folder with migration and snapshot file
3 - dotnet ef database update -> this will create new db even if we dont have it yet