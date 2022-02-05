writeCode

Write code to:-

- create a database named `sports`.    use sports
- list all databases present in local mongod server.    show dbs
- create 3 collections named `cricket`, `football`, `TT` in sports databse.   
db.createCollection(cricket)
db.createCollection(football). or db.football.insertMany(players)
db.createCollection(TT)

- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.   // db.cricket.insertMany(players)
- list all collections in sports database. // show collections
- rename `TT` collection to `tennis`.  // db.renameCollection('tennis')
- create a capped collection called `khokho` which should have max 3 documents.
  Try inserting more than 3 and see what happens?
- check whether a collection is capped or not?  //db.football.isCapped()
- drop all documents from `football` collection.  //db.football.remove()
- delete cricket collection completely.  db.cricket.drop()
- delete sports database.   db.dropDatabase()
- check which database you are connected to ?   db - shows to which one is connected
- connect to test database.  use test - connects to it
