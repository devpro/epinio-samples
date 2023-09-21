# Epinio React samples

## Package and deploy

Run the following commands to deploy the applications

```bash
# Web App (Single Page Application)
epinio push --name reactsample --path sample-app --env BP_WEB_SERVER=nginx --env BP_WEB_SERVER_ROOT=build --env BP_NODE_RUN_SCRIPTS=build --env BP_WEB_SERVER_ENABLE_PUSH_STATE=true
```

## References

* [paketo-buildpacks/samples/web-servers/react-frontend-sample](https://github.com/paketo-buildpacks/samples/tree/main/web-servers/react-frontend-sample)
* [Paketo Buildpacks > Build and Serve a Frontend Framework App](https://paketo.io/docs/howto/web-servers/#build-and-serve-a-frontend-framework-app)
* [react.dev](https://react.dev/)
* [create-react-app.dev](https://create-react-app.dev/)
