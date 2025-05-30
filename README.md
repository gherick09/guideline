# guideline
ASP.net Core VS code Creation
-dotnet new webapi -n EmployeeApi
-cd EmployeeApi
-dotnet run

For Controller Generation
-dotnet aspnet-codegenerator controller -name ProductsController -api -outDir Controllers
-dotnet tool install -g dotnet-aspnet-codegenerator
-dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
