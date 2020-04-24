# Angular-Routing
Materials for the ["Angular Routing"](http://bit.ly/Angular-routing) course on Pluralsight.

`APM-Start`: The starter files. **Use this to code along with the course**.

`APM-Final`: The completed files. Use this to see the completed solution from the course.

See the `README.md` file under each folder for details on installing and running the application.

Please see the `CHANGELOG.md` for the most recent changes to this repo.

Angular Routing https://app.pluralsight.com/library/courses/angular-routing By Deborah Kurata

## base ref

```cmd
ng build --base-href /mySubUrl
```

## RouterModule

### RouterModule.forRoot()

- declares the router directive
- manages our route configuration
- registers the router service
- used once for the application

### RouterModule.forChild()

- declares the router directive
- manages our route configuration
- does NOT register the router service
- used in feature modules
- Many Router Outlet
