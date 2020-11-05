# Mock server for OpenAPI specifications

## How-to-run
Start Prism mock server with the following command.

```bash
$ docker-compose up

```

Then, you can try the backend-API with `http://localhost:30071/api/v1/***`.

### Example
```bash
$ curl http://localhost:30071/api/v1/databases

{"count":1,"records":[{"id":1,"database_id":"small_driving_behavior_database","name":"Small Driving Behavior Database","description":"","location":"/share/small_DrivingBehaviorDatabase"}],"sort_key":"id","per_page":50,"page":1}

```
