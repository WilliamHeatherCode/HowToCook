How To Cook is a MERN stack application

client folder (src) contains all front end code.
Website page paths are stored in App.js


server folder contains all back end code and database managment.
Database is set to port 5000 in the index.js file.

Setup:
To setup website through the IDE:
```cd client``` and then ```npm i && npm start```
After client is running on http://localhost:3000/
```cd server``` and then ```npm i && npm start```
This starts the server


To run the website through docker:
```docker build -t “clientside” ./client/```
```docker build -t “serverside” ./server/```
```docker-compose up```
The website can then be accessed from http://localhost:3000/

Premade login for the website:
Email: william.b.heather@gmail.com
Password: Test123


