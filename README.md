# Workout
[Deployed Link](https://dandukes-workout.herokuapp.com/)

[Github Repo](https://github.com/DanDukes/Workout/)

## Author

Dan "Dukes" DeGeare

dan@degeare.com

[LinkedIn](https://www.linkedin.com/in/danieldegeare/)

[GitConnected](https://gitconnected.com/dandukes)

![landing](https://raw.githubusercontent.com/DanDukes/Workout/master/public/images/landing.png)

 ![Adding exercise](https://raw.githubusercontent.com/DanDukes/Workout/master/public/images/adding.png)
 
 ![Dashboard](https://raw.githubusercontent.com/DanDukes/Workout/master/public/images/dashboard.png)
 
 ![MongoDB](https://raw.githubusercontent.com/DanDukes/Workout/master/public/images/mongoDB.png)


## Purpose
A simple Javascript, Express, and MongoDB application to build and keep track of workouts.  Includes a stats dashboard.

## Functionality
The Workout tracker simply allows a user to record their daily workouts, and then view some statistics about the total amount of exercise they have done in a week.  To get started, simply add new exercise to kick off a session, and then either continue with workout by adding more excersices to it, or finish up.  To view stats, click on Dashboard in the NavBar. 

 ## Running locally

 1. Install any dependencies: ```npm install```;
 2. Start a local instance of MongoDb ```mongod``` /
 3. Seed the database: ```npm run seed```;
 4. Run: ```npm start```;
 5. The default  port is *3000*, so to access you must go to **http://localhost:3000**

## Technologies
  * HTML, CSS, JavaScript, SemanticCSS, Mongoose, Express
  
## Known Bugs/ Other Features
  * There isa a bug with the total Distance calcultion if a workout is entered with a 0 or null number
  
