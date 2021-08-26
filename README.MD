**End point to generate token**

http://localhost:8084/token 

**Request**

`{
 "userName":"ashish",
 "id":"132",
 "role":"manager"
 }`
 
 **Response**
 eyJhbGciOiJIUzUxMiJ9.eyJzdWIiOiJhc2hpc2giLCJ1c2VySWQiOiIxMzIiLCJyb2xlIjoibWFuYWdlciJ9.RV7gpg8gBBfZ9cunKfBhz9ttYWbrFn6uLueawOLtQVD8tqneHGYREtTxiuCGq94nZCoJyJVATHbN4wcg-_uJ5A
 
 ***
 
**TESTING**

Hit the API 

http://localhost:8084/rest/hello 

if the token is not passed in header it gives an error that the token is not passed
pass the token in header and it should allow to go further page