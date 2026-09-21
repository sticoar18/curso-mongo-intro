# connect to container 
'''sh
docker-compose exec mongodb bash
'''


## connect eith mongosh
'''sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false" ---Url que nos de el servicio de atlas o la url en local (en local el contaniner debe estar levatando y corriendo mongodb)
'''

'''sh
show dbs
show collections
'''

'''sh
use("platzi_store")
db.products.find()
'''
