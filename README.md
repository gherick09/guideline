# guidline
dotnet new webapi -n EmployeeApi
cd EmployeeApi
dotnet run



dotnet aspnet-codegenerator controller -name ProductsController -api -outDir Controllers
dotnet tool install -g dotnet-aspnet-codegenerator
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
