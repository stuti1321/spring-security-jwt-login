# spring-security-jwt-login
For installing the project download the zip file.
Extract all the files and open in intellij IDE or any other IDE. 
After opening the project install the required plugin lambok . 
Run SpringSecurityJwtExampleApplication.java 
Now open Postman application and send a post request on localhost:9595/authenticate 
In body > raw > JSON give the reguired JSON 
{"userName":"stuti",
  "password":"password" }
  or any other user register/created userName,password 
  A token will be generated , copy the same token .
  Now make another request of GET as localhost:9595/ and in autherization > bearer token . In the token tab add the copied token .
  Only authenticated user will be able to see the message as Welcome to GreenStitch.
