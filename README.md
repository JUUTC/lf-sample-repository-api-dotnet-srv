# lf-sample-repository-api-dotnet-srv
Sample project for demonstrating how to work with our OAuth and Repository API clients.

## Steps to recreate this projecct

### Scafolding

```
dotnet new console --framework net6.0
```

### Run the project

```
dotnet run
```

### Add dependencies

```
dotnet add package Laserfiche.Oauth.Api.Client --version 2.0.0
```
(Currently, we have not yet released the 2.0 version (but will be soon), for now, we can use a local nuget package using command similar to the one below.)

```
dotnet add package Laserfiche.Repository.Api.Client --source {absolute_path_to_folder_containing_nupkg}
```

```
dotnet add package DotNetEnv
```

### Remove dependencies

```
dotnet remove package {package_id}
```