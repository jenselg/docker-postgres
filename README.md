# Postgres Docker Container
Quick, ready to use Postgres database

## Quick How-To
1. Clone this repo
2. Create a `.env` file at the root of the folder
3. Set the following variables:
   * `POSTGRES_CONTAINER_NAME` (defaults to `docker-postgres` if not set)
   * `POSTGRES_VERSION` (defaults to `16` if not set)
   * `POSTGRES_PASSWORD` (this is for the `postgres` user and does not default to anything)
   * `POSTGRES_PORT` (defaults to `5432` if not set)
4. Run the container: `docker compose up -d`
5. Once started, it will create a folder with the same name as the container name in the root of the folder that will contain the database configs and data (defaults to `docker-postgres` if `POSTGRES_CONTAINER_NAME` is not set)