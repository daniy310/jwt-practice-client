# 🤖  Jwt Practice Client

![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/f140d862-8a02-45cc-b26b-bbcf97067c88)
![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/94b99a3d-5030-4adc-9fb6-2e36482a0494)
![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/628dab42-071d-4e24-ad16-45d3fb90a672)


This project demonstrates the client-side of a PERN full stack application.

It includes :
 - 3 main components
   - Register for registering a new account in our database - using postgreSQL and password bcrypt encryption
   - Login for logging into the app
   - Dashboard - a mock for the logged users
 
On each auth action a JWT is generated with a secret code and an expiration period and then it is set in the local storage. 
If the JWT exists, the authentication is made automatically and from the /login or /register routes the user will be redirected to /dashboard. 

For each action an http request is sent to the server ran locally.

Server repo : https://github.com/daniy310/jwt-practice-server
