# Task Manager API

Run:

```
heroku create sua-task-manager-api
```

To set environment variables run:

```
heroku config:set key=value
```

To remove environment variables run:

```
heroku config:unset key=value
```

To push your changes in heroku:

```
git push heroku master
```

Domain:
- sua-task-manager-api.herokuapp.com/

Setup of the MongoDB Atals
- Connect your application: mongodb+srv://taskapp:<password>@cluster0-dxxh8.mongodb.net/task-manager-api?retryWrites=true&w=majority
- Set this value to the respective environment variable


Test:
- Postman with the Production Environment
- Compass with the Production Database
