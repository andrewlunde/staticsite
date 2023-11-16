# Static Site

Simple manifest driven cloudfoundry app using the staticfile buildpack

Deploy with this cf command
```
cf push
```

Find the route(URL) with this command
```
cf apps
```

Clean up by first deleting the route then the app itself
```
cf delete-route cfapps.us10.hana.ondemand.com --hostname staticsite -f
cf delete staticsite -f
```