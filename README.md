# MongoDB
> All information, tutorials, code about mongoDB

To use mongoDB, use robomongo ( https://robomongo.org/download) as management studio to see records visually.

## To start mongo, open two terminal, 

write in one terminal, 

mongod, it will start the server

in other terminal, start with 
run command: mongo

it will start mongo database

now list dow all the databases
run: show dbs
run: use users
run: show collections

## Few Commands

1. To show all databases
run: show dbs

2. To create database command
run: use database-name

3. create collections run
run: db.createCollection('collectionName')

4. Insert values into collection
run: db.collectionName.insert({"name":"Amir","Password":"123", "Admin":"true" })

5. To list all the entries into the collection
run: db.collectionName.find();

6. To list all the entries to make them readable
run: db.collectionName.find().pretty();
