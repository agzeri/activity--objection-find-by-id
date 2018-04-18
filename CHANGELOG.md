# CHANGELOG

#### (1) Create a simple route to retrieve a single Tweet. Don't worry for the connection with Database, yet.

*Test the route using Postman or curl command.*

#### (2) Create a dynamic param in the route, to handle the Id from Tweet record.

#### (3) Name that dynamic param tweetId

#### (4) Retrieve the tweetId param from the endpoint using the request object.

##### Steps

_Print that number in console log_
_Make a request to /api/tweets/[0-9]_
_Read your console and what happen with every request that you do_

#### (5) Save the tweeId (param from req) in a const and cast it to a Number value

##### Steps

#### (6) Before working with our Model, let's inspect our SQL table to know the name from your PRIMARY KEY

##### Steps

#### (7) Use the method .where() available from Objection library. We'll need to filter our data using the Id.

#### (8) Write the query from your Tweet model to retrieve the information.

#### (9) Refactor your code and use .findById() method, instead of .where() function.

#### (10) Insert a new tweet manually to our database, and retrieve that tweet using our new endpoint.

#### Optional

###### You can test our endpoint using curl command
