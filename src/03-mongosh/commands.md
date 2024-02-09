## Connect to container

```sh
docker compose exec mongodb bash
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root@localhost:27017/?tls=false"
mongosh "mongodb+srv://admin:Samimajo10@mongodbclase.przdums.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("platzi_strore")
db.products.find()
```