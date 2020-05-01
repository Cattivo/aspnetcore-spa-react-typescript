# ASP.NET Core basic template with SPA
React+TypeScript  
Template without UseSpa middleware.  
It can be configured for hosting several SPA apps.  

### API
Use Route attribute to your controllers to create new endpoints.  
By default, any route, except routes defined in controllers, returns `~/src/AspNetCoreSpaTemplate.Web/spa/build/index.html` file.  

### SPA
The app path is `~/src/AspNetCoreSpaTemplate.Web/spa`  
SPA is a default template created with 'npx create-react-app spa --template typescript'.  
It's excluded from the solution and MS Build process.  
Use with VS Code or another editor to work with separately.  
