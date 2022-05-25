For the database, I used docker:

```bash
docker run --name sequelize-getting-started -e POSTGRES\_PASSWORD=postgres -d -p 5432:5432 postgres
```