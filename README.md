The projet layout is the following:
```
    src
    │   app.js           # App entry point
    |----api             # Express route controllers for all the endpoints of the app
        |---routes
    |----config          # Environment variables and configuration related stuff
    |----jobs            # Jobs definitions for agenda.js
    |----loaders         # Split the startup process into modules
    |----models          # Database models
    |----services        # All the business logic is here
    |----subscribers     # Event handlers for async task
```

This project was inspired on: [bullet-proof-node-js](https://dev.to/santypk4/bulletproof-node-js-project-architecture-4epf)
