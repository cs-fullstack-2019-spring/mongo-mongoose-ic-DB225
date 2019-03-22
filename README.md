# Mongo/Mongoose In Class

### Exercise 1: Create an Endpoint for a ToDo Web Service to Create Test Data

* Create a new Express web service called (manually, or with the Express Generator)
* Sign into your MLab account, and create a new collection called ```todotest``` (NOTE the connection String)
* Create a Mongoose data model called ```ToDoItem``` with 2 text fields ```username```,```todoitem``` and 1 boolean field ```isdone```


Create the web service endpoint ```/api/setuptodos``` that will create 3 records/instances of the ToDoitem model using hardcoded data, and return an array containing the created records back to the browser.

Example Request:
```http://localhost:3000/api/setuptodos```

Example Response:
```
[{"_id":"5c94f523099dc1328417b4a8","username":"kyancy","todo":"Get new Students with better manners","isDone":false,"__v":0},{"_id":"5c94f523099dc1328417b4a9","username":"kyancy","todo":"Get groceries","isDone":false,"__v":0},{"_id":"5c94f523099dc1328417b4aa","username":"kyancy","todo":"Clean computer room","isDone":false,"__v":0}]
```







