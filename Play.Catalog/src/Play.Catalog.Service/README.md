# Dotnet Aspnet Codegenerator

- dotnet tool uninstall -g dotnet-aspnet-codegenerator 
- dotnet tool install -g dotnet-aspnet-codegenerator
- dotnet-aspnet-codegenerator controller -name ItemsController -async -api -m Dtos -outDir Controllers

> Example : dotnet aspnet-codegenerator controller -name TodoItemsController -async -api -m TodoItem -dc TodoContext -outDir Controllers

### usefull-links
- [dotnet-aspnet-codegenerator](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/tools/dotnet-aspnet-codegenerator?view=aspnetcore-5.0)
- [first-web-api](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio-code)