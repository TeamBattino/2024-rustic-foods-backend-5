# 2024-rustic-foods-backend-5

## Start postgresql in docker

```bash
docker run --name postgres -e POSTGRES_PASSWORD=postgres -p 5432:5432 -d postgres
```

Put the following in your `.env` file

```bash
DATABASE_URL=postgres://postgres:postgres@localhost/postgres
```
