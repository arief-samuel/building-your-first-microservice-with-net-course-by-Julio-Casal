# Dotnet Aspnet Codegenerator

- dotnet tool uninstall -g dotnet-aspnet-codegenerator 
- dotnet tool install -g dotnet-aspnet-codegenerator
- dotnet-aspnet-codegenerator controller -name ItemsController -async -api -m Dtos -outDir Controllers

> Example : dotnet aspnet-codegenerator controller -name TodoItemsController -async -api -m TodoItem -dc TodoContext -outDir Controllers

### usefull-links
- [dotnet-aspnet-codegenerator](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/tools/dotnet-aspnet-codegenerator?view=aspnetcore-5.0)
- [first-web-api](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio-code)
- 
- 

### Using httprepl

> Usage: httprepl https://localhost:5001
- [http-repl](https://docs.microsoft.com/en-us/aspnet/core/web-api/http-repl/?view=aspnetcore-5.0&tabs=windows)


### ActionResult Signature Class
- Have specific type for the return ex: CreatedAtAction(), 
### IActionResult Signature Class
- Dont really have specific type for the return ex: NoContent()
