# POSTGRES  Kullanılarak  Directus compose dosyası

1. [şifre üret](https://duckduckgo.com/?q=pw)
2. [KEY üret](https://duckduckgo.com/?q=guid)
3. [SECRET üret](https://duckduckgo.com/?q=guid)
4. `docker compose up` yap

## Örnek `.env` dosyası

DB_PASSWORD ile POSTGRES_PASSWORD aynı olacak

```js
KEY=58106b34-2963-412e-9521-a371c70188e5
SECRET=141f2ca3-ff79-436d-8d90-4edd6d974ac9
ADMIN_EMAIL=admin@mail.co
ADMIN_PASSWORD=gitTRad3
DB_CLIENT=pg
DB_HOST=database
DB_PORT=5432
DB_DATABASE=directus
DB_USER=directus
DB_PASSWORD=rTLjUzY2
POSTGRES_ROOT_PASSWORD=z862ds5c
POSTGRES_DATABASE=directus
POSTGRES_USER=directus
POSTGRES_PASSWORD=rTLjUzY2
```
