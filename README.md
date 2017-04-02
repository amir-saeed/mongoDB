# mongoDB
All information, tutorials, code about mongoDB

To use mongoDB, use robomongo ( https://robomongo.org/download) as management studio to see records visually.

*To start mongo, open two terminal, 

write in one terminal, 

mongod, it will start the server

in other terminal, start with 
run command: mongo

it will start mongo database

now list dow all the databases
run: show dbs
run: use users
run: show collections

*Few Commands

1. To show all databases
show dbs

2. To create database command
use database-name

3. create collections run
db.createCollection('collectionName')

4. Insert values into collection
db.collectionName.insert({"name":"Amir","Password":"123", "Admin":"true" })

5. To list all the entries into the collection
db.collectionName.find();

6. To list all the entries to make them readable
db.collectionName.find().pretty();
