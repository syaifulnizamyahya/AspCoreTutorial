#### Db migration console command

> Install-Package Microsoft.VisualStudio.Web.CodeGeneration.Design -Version 2.0.0
>
> Add-Migration Initial
>
> Update-Database

#### Scaffolding command
> dotnet aspnet-codegenerator razorpage -m Movie -dc MovieContext -udl -outDir Pages\Movies --referenceScriptLibraries