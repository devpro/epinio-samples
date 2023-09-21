# Epinio .NET samples

## Package and deploy

Run the following commands to deploy the applications

```bash
# Web API (REST)
epinio push --name aspnetapisample --path src/WebApi --env ASPNETCORE_ENVIRONMENT=Development

# Web App from Razor Page
epinio push --name aspnetrazorsamp --path src/RazorWebApp --env ASPNETCORE_ENVIRONMENT=Development
```

## Contribute

All the projects are created from .NET templates.

For Paketo Buildpacks to be able to create artifacts that run, the file `Procfile` must be added (see [Override the Start Process Set by the Buildpack](https://paketo.io/docs/howto/dotnet-core/#override-the-start-process-set-by-the-buildpack)).
