# Epinio Angular samples

## Package and deploy

Run the following commands to deploy the applications

```bash
# Web App (Single Page Application)
epinio push --name ngsample --path ngsample --env BP_WEB_SERVER=nginx --env BP_WEB_SERVER_ROOT=dist/ngsample --env BP_NODE_RUN_SCRIPTS=build --env BP_WEB_SERVER_ENABLE_PUSH_STATE=true
# NODE_ENV=development
```

## Contribute

All the projects are created from Angular templates.

## References

* [paketo-buildpacks/samples/web-servers/angular-nginx-sample](https://github.com/paketo-buildpacks/samples/tree/main/web-servers/angular-nginx-sample)
* [Paketo Buildpacks > Build and Serve a Frontend Framework App](https://paketo.io/docs/howto/web-servers/#build-and-serve-a-frontend-framework-app)
