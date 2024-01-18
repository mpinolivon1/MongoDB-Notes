## Connect to container

```sh 
docker-compose exec mongodb bash
```

## Connect with mongosh

```sh //Las URL las obtengo del MongoDB Compass - La primera URL es local y la segunda es la nube
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://manuel:Manuel01@mongodb101.lxk43we.mongodb.net/"
```

```sh
show dbs
show collections
```

```sh
cd 
db.products.find()

/* Para usar una bd y salir de la bd */
use (store)
exit


