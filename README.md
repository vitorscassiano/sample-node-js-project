The projet layout is the following:
```
    src
    │   app.js           # App entry point
    |----api             # Express route controllers for all the endpoints of the app
        |---routes
        |---middlewares
    |----config          # Environment variables and configuration related stuff
    |----jobs            # Jobs definitions for agenda.js
    |----loaders         # Split the startup process into modules
    |----models          # Database models
    |----services        # All the business logic is here
    |----subscribers     # Event handlers for async task
```
