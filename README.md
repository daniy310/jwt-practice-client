# 🤖  Jwt Practice Client

![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/38ce7fe9-99ab-459a-a290-dd4b4a6ed65f)
![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/1e894a7f-6ac2-4a02-b783-b142e79293a6)
![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/bb5da660-49d6-43b3-80dc-19e2c2e554c0)
![image](https://github.com/daniy310/jwt-practice-client/assets/68704220/7c8e0623-3849-48a9-9ca4-33e1aa63a69f)


This project demonstrates the client-side of a PERN full stack application.

It includes :
 - 3 main components
   - Register for registering a new account in our database - using postgreSQL and password bcrypt encryption
   - Login for logging into the app
   - Dashboard - a mock for the logged users
 - React Toastify notifications for each auth action
 
On each auth action a JWT is generated with a secret code and an expiration period and then it is set in the local storage. 
If the JWT exists, the authentication is made automatically and from the /login or /register routes the user will be redirected to /dashboard. 

For each action an http request is sent to the server ran locally.

Server repo : https://github.com/daniy310/jwt-practice-server
