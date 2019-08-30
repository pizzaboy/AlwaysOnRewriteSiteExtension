# Always On request rewrites to existing file - site extension for Azure

Azure App service Always on sends a basic request to the root of the app. In some cases this is not wanted, for example if the app requires authorisation it will return a 403 and will log an error. This site extension will rewrite the request to retrieve favicon.png from the root.


