Setting Up PostgreSQL with Docker
Run this command to create a PostgreSQL 15 container:


docker run -d \
  --name project-postgres \
  -p 5444:5432 \
  -e POSTGRES_USER=project \
  -e POSTGRES_PASSWORD=project \
  -e POSTGRES_DB=project-db \
  postgres:15
