# REST
This demo expands upon the MVC demo in [Section 14_Express_HBS_MVC](https://github.com/RobertFrenette/E-31_Spring_2019/tree/master/14_Express_HBS_MVC) 
by implemeting a REST Service for CRUD operations.

## Execute in Terminal
```
$ cd demo
$ npm install
  ...
$ npm start
```

## Test in Postman (HTTP Verb / CRUD Action)

### POST / Create
[http://localhost:3000/api/create](http://localhost:3000/api/create)

![Create](img/create.png?raw=true "Create")


### GET / Read
+ Replace MOUNTAIN_ID in URI below with _id returned in Create above

[http://localhost:3000/api/MOUNTAIN_ID](http://localhost:3000/api/MOUNTAIN_ID)

![Read](img/read.png?raw=true "Read")


### PUT / Update
+ Replace MOUNTAIN_ID in URI below with _id returned in Read above

[http://localhost:3000/api/update/MOUNTAIN_ID](http://localhost:3000/api/update/MOUNTAIN_ID)

![Update](img/put_update.png?raw=true "Update")


### DELETE / Delete
+ Replace MOUNTAIN_ID in URI below with _id returned in Update above

[http://localhost:3000/api/delete/MOUNTAIN_ID](http://localhost:3000/api/delete/MOUNTAIN_ID)

![Delete](img/delete.png?raw=true "Delete")
