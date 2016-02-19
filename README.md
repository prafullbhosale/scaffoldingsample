# scaffoldingsample
**This repo contains an Early version of a MVC web app using AspNetCore that supports scaffolding**

##Steps to build
- Install latest [dotnet cli](https://github.com/dotnet/cli)
- (Needed temporarily) 
  - Build [aspnet/scaffolding](https://github.com/aspnet/scaffolding)
  - Update Nuget.config -- Add the locally built artifacts\build folder in step 2.1 as a package source
- dotnet restore 
- dotnet build 
- dotnet aspnet-codegenerator -h 
