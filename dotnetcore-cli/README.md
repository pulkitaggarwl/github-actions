# GitHub Action for the .NET Core CLI

GitHub Action to build, test, package or publish a dotnet application, or run a custom dotnet command."

## Usage
```
action "build" {
  uses = "actions/azure/dotnetcore-cli@master"
  args = "publish dotnetcore-app/aspnet-core-dotnet-core/aspnet-core-dotnet-core.csproj  -c Release -o \"/github/workspace/dotnetpackage\""
  }
  
```


