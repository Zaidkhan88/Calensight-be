# Calendar App - 🗓 - Backend

Calendar app is a web application for manage your life **private** events using a Calendar. Create an account and start organizing your days.

You are the only admin of ***your*** events, being able to:

- [x] Create events
  - Title, notes (optional), start date, end date
- [x] Update events
- [x] Delete events
- [ ] View other people events (now only private events from march 2023)

Visit the **deployed** app at **[Calendar App](https://calendar-back-leti.onrender.com/auth/login)**

Check the frontend code and tech stack at [Calendar Front github repository](https://github.com/Zaidkhan88/Calensight-fe)



## What is this repository ?

It's the source code for the backend of the calendar app.

### Tech stack

This project was created using the M.E.R.N. stack that stands for MongoDB, Express.js, React.js and Node.js

#### Backend

- **Backend runtime -** [node.js](https://nodejs.org/en/)
- **Web Api framework -** [express.js](https://expressjs.com/)
- **Database -** [mongoDB](https://www.mongodb.com/)
- **Main programming languaje -** [javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

##### Dependencies

Read other project dependencies in the [package.json](package.json) file.

#### Frontend

Check the frontend code and tech stack at [Calendar Front github repository](https://github.com/Zaidkhan88/Calensight-fe)

## How to use this project

1. Rename the [.env.template](.env.template) file to ***.env*** and prepare to complete the info.
2. In the *.env* file, set the **PORT** your app will be running and the **SECRET_JWT_SEED** that will be used to sign and verify the json web tokens, it can be any string, the longer the string, the better.
4. Get the connection string for [mongoDB](https://www.mongodb.com/) database. Check [docs](https://www.mongodb.com/blog/post/quick-start-nodejs-mongodb-how-to-get-connected-to-your-database).
5. Run the app:
   - Local mode: Run the command [npm run dev](#npm-run-dev).
6. Consume the api with the [available endpoints](#available-endpoints), example: get all the events -> *GET* /host/api/events.


## Available scripts

### ```npm run dev```

Starts the node server using *nodemon* dependency, run this for development purposes, it will automatically detect changes and refresh the server.
