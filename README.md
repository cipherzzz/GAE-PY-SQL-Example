# GAE-PG-CloudSQL-NodeJS
An example of connecting a Python3 GAE application to a Cloud SQL Postgres DB 

## Configure
Replace the USER, PASSWORD, DATABASE, INSTANCE_CONNECTION_NAME in `app.yaml`

## Deploy it
```gcloud app deploy```

### Check it
```gcloud app browse```

You should see it attempting to access a table that doesn't exist in the db - artifact of the example but it proves connectivity.