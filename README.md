# python-web-bazel-api-flask-postgres-pop

## Description
Creates an api of pop for a flask project.
Has the ability to query by parameters.
If path is not found, will default to 404 error.

## Tech stack
- bazel
- python
- flask

## Docker stack
- l.gcr.io/google/bazel:latest
- postgresql

## To run
`sudo ./install.sh -u`
- Get all pops: http://localhost/pop
  - Schema id, name, and color
- Query with params: http://localhost/pop <id>

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- https://stackabuse.com/using-sqlalchemy-with-flask-and-postgresql/
