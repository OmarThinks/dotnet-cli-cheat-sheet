# CLI Commands:



## Get current .NET version:

```
dotnet --list-sdks
```


---

```
dotnet run
dotnet watch run
```


---


## Installs:


```bash
dotnet tool install --global dotnet-ef
dotnet tool install -g dotnet-aspnet-codegenerator
# dotnet tool install -g Microsoft.dotnet-httprepl # testing (Optional)

dotnet add package Swashbuckle.AspNetCore
#dotnet add package Microsoft.EntityFrameworkCore.InMemory # Optional
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package Microsoft.EntityFrameworkCore.Design
```



## Database:


```
dotnet ef migrations add <Mod Name [InitialCreate]>
dotnet ef database update --context PizzaContext
```





# Links:


## Examples:

- [Minimal API](https://github.com/MicrosoftDocs/minimal-api-work-with-databases) `dotnet new web -o PizzaStore`
- [RazorPagesPizza](https://github.com/jongalloway/RazorPagesPizza) `dotnet new webapp -o RazorPagesPizza`
- [ContosoPizza](https://github.com/david-iaggbs/ContosoPizza) `dotnet new webapi -o ContosoPizza`


## How tos:

- [Azure CLI](pages/azure-cli.md)
- [Add Model](pages/model.md)
- [Add CORS](https://docs.microsoft.com/en-us/aspnet/core/security/cors?view=aspnetcore-6.0)
- [Data Annotaions](https://docs.microsoft.com/en-us/dotnet/api/system.componentmodel.dataannotations)
- [repl](https://docs.microsoft.com/en-us/aspnet/core/web-api/http-repl/?view=aspnetcore-6.0)











# dotnet-cli-cheat-sheet


Every thing you may need about dotnet, you can find 
it in the documentation.  
The problem is that documentation relies heavily 
on Visual Studio Code.   
VSCode is very slow, This reduces the performance.  
Here we I will do my best to create a 
documentation on the relies on CLI, instead of VSCode. 





<h1>
<a href="cs/README.md">1) C#</a>
</h1>

This is the programming language used in the development of 
ASP.NET Applications.





<h1>
<a href="nuget/README.md">2) NuGet</a>
</h1>
How to install and use packages.









<h1>
<a href="auth/README.md">
3) Auth</a>
</h1>
Authentication and Authorization











<h1>
<a href="webapp/README.md">4) Web App</a>
</h1>
How to create we applications, Without using RESTful APIs.




<h1>
<a href="mvc/README.md">
5) MVC</a>
</h1>
Creating MVC application using CLI







<h1>
<a href="api/README.md">
6) API</a>
</h1>
Creating API application using CLI





<h1>
<a href="relationships/README.md">
7) Relationships</a>
</h1>
Establishing Relationships













