## DOCKER
docker file size reduction
Use multi-stage builds to exclude unnecessary artifacts from earlier stages in the final image
Add a .dockerignore file to our project to exclude unnecessary files or directories
Change our Dockerfile to use smaller base images.

## LINUX 
curl host:port (used to check whether website is communicating with outer network or not)

## PSQL
psql -h HOSTNAME -U USERNAME DATABASE
Connection options:
  -h, --host=HOSTNAME      database server host or socket directory (default: "local socket")
  -p, --port=PORT          database server port (default: "5432")
  -U, --username=USERNAME  database user name (default: "root")
  -w, --no-password        never prompt for password
  -W, --password           force password prompt (should happen automatically)


select * from pg_catalog.pg_tables; (Use this to view all tables)
SELECT * FROM TABLENAME; (Use this to access the content of a table)
