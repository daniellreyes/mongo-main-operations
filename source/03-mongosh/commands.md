## Connect to container

```sh
docker-compose exec mongodb bash 
```

## Connect with mongosh

```sh
mongosh "mongodb://root:root123@localhost:27017/?authMechanism=DEFAULT&tls=false"
mongosh "mongodb+srv://daniellreyes26:admindaniell123@cluster0.ipfyhqc.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
use("daniell_store")
db.products.find()
```

## Para salir -> .exit