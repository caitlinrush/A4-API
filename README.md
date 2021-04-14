API created with Node, Express, MongoAtlas and deployed with Heroku for PROG34014 Assignment 4


**By Caitlin Rush, 991534296**

---------------------------------

## RESPONSE CODES

| Code | Meaning |
| ------------------- |:-------------|
| `200 OK` | The request was successful 
| `201 Created` | The request was fulfilled 
| `404 Not Found` | The requested resource could not be found because either it does not exist or the requested item could not be found in the database
| `500 Internal Server Error` | An internal error occurred on the server side
| `501 Not Implemented` | The requested endpoint is currently not available, but may be implemented in the future

## ENDPOINTS

###### View All Items
| Endpoint | /api/items
| ------------- |:-------------|
| *Request Type* | GET

###### View a Single Item
| Endpoint | /api/items/:item_name
| ------------- |:-------------|
| *Request Type* | GET

###### Add a New Item
| Endpoint | /api/items
| ------------- |:-------------|
| *Request Type* | POST
| *Request Body* | A JSON object containing the data that should be added to the API's data store

###### Delete an Item
| Endpoint | /api/items/:item_name
| ------------- |:-------------|
| *Request Type* | DELETE

###### Update an Item
| Endpoint | /api/items/:item_id
| ------------- |:-------------|
| *Request Type* | PUT




