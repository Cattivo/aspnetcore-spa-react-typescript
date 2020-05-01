# ASP.NET Core basic template with SPA
Template without UseSpa middleware.
It can be configured for hosting several SPA apps.

# API
Use Route attribute to your controllers to create new endpoints.
By default, any route, except routes defined on a controller, return ~/src/Fennec.Web/spa/build/index.html file.

# SPA
The app path is ~/src/Fennec.Web/spa
SPA is a default template created with 'npx create-react-app spa --template typescript'. It's excluded from Solution and MS Build.
Use with VS Code or another editor to work with separately.