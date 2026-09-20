# compose-template

## Create user in Postgres database

```sql
CREATE USER docmost WITH PASSWORD '<theS3cr3t!password>' ;
GRANT CONNECT ON DATABASE docmost TO docmost;
GRANT ALL PRIVILEGES ON DATABASE docmost TO docmost;
```
