writeCode

Write code to:-

- create a database named `mountains`   use db.mountains
- a collection inside that database named `himalayas`   db.mountains.createCollection(himalayas)
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`.  db.mountains.insert(`{name: 'Dhauldhar range', height: '4000 mtrs'}`)

- insert multiple document using insertMany command    db.mountains.insertMany({})
- find all documents from mountains. db.mountains.find()
- find a single document using name. db.mountains.find('name')
