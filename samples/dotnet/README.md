# Epinio .NET samples

## Package and deploy

Run the following commands to deploy the applications

```bash
# Web API (REST)
epinio push --name dotnetapisample --path src/WebApi --env ASPNETCORE_ENVIRONMENT=Development
```

## Contribute

All the projects are created from .NET templates. For Paketo Buildpacks to be able to create artifacts that run, the file `Procfile` must be added.
