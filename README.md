# Secrets

## Getting Started

To get you started you can simply Download this Repo and CD Over to the Directory.

Now install all the dependencies :

```
npm install
```

## Prerequisites :

### 1) Start the MongoDB server :

Run the Following Command in your local Terminal.
```
mongod
```

### 2) Run the Application :

The project is preconfigured with a simple development web server. The simplest way to start this server is:

    npm start

### 3) Server :
Head Over to Port 300 to see your Server.
```
http://localhost:300/
```
## Working :

This Website is Built using Node.js and Express.js and MonogoDb for Database Handling.
 1) User can Login to the Website Using Google and Facebook Authentication where if Successfully Logged in can give their Secret to the Server which will be stored in Mongodb Server.

 2) The Secret of Individual User is stored in mongoDb server including their Details acquired from Google/Facebook.

 3) Users can view their Secrets by logging in or add a new one by registering using Google/Facebook Login.
