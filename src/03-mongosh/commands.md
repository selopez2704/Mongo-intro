## connect to container
```sh
docker-compose exec mongodb bash
```
## connect with mongosh
```sh
mongosh "<MONGO-URL>"
```

```sh
show dbs
show collections
```

```sh
use("test")
db.products.find()
```
