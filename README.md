# GAE-PG-CloudSQL-NodeJS
An example of connecting a Python3 GAE application to a Cloud SQL Postgres DB 

## Credit
The code in the `cloudsql_postgresql` was lifted from [HERE](https://github.com/GoogleCloudPlatform/python-docs-samples/tree/4831bbae7d088286bb7d0e8cb0ca7a27e601b9ea/appengine/flexible/cloudsql_postgresql)

## Install
```
git clone git@github.com:cipherzzz/GAE-PY-SQL-Example.git && cd cloudsql_postgresql
```

## Configure
Replace the USER, PASSWORD, DATABASE, INSTANCE_CONNECTION_NAME in `app.yaml`

## Deploy it
```
gcloud app deploy
```

### Check it
```
gcloud app browse
```

You should see it attempting to access a table that doesn't exist in the db - artifact of the example but it proves connectivity.