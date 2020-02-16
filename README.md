# Check ASP.NET with Unity

Check if ASP.NET can be run on Unity environment.

## Environments

- ASP.NET latest version (check periodically with [Github Actions])
- Unity 2019.1.0f2

[Github Actions]: https://github.com/features/actions

## Conclustion

It is not available because *[Microsoft.AspNetCore.All]* supports only *netcoreapp2.2*. Of course, It might be available with some custom composition but it is not sure when dependencies of it break.

[Microsoft.AspNetCore.All]: https://www.nuget.org/packages/Microsoft.AspNetCore.All/
