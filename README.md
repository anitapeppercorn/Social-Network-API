## Social Network API

### Description

MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. Because the foundation of these applications is data, this work shows an understanding how to build and structure the API 

## Contents
- [Description](#Description)
- [Demo & Models](#Demo&Models)
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [Concepts](#Concepts)
- [License](#License)
- [Author](#Author)

## Description

We have built an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. I used Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the Express.js and Mongoose packages, I use the Moment.js package to format time.

The Repository is hosted at https://github.com/anitapeppercorn/Social-Network-API
Because this application won’t be deployed, there is walkthrough video that demonstrates functionality and all of the acceptance criteria being met. 

## Demo & Models
https://youtu.be/D1Ay1BSe2_I - Video 1
https://youtu.be/XW04jTC6l2I - Video 2


## User Story
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia Core for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia Core
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Concepts
Here is an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. We use Express.js for routing, a MongoDB database, and the Mongoose ODM. In addition to using the Express.js and Mongoose packages, we use the Moment.js package to format time. 

This application isn't be deployed, here is a walkthrough video that demonstrates functionality and all of the acceptance criteria being met. 

- Created models with Mongoose.
- Used virtuals to extend the models' functionality.
- Created subschemas and subdocuments with Mongoose.
- Validated models to normalize data.

## License
[MIT License](./LICENSE)
![license](https://img.shields.io/badge/License-MIT-blue)

## Author: Anita Ganti

View the authors' portfolio at:  
https://anitapeppercorn.github.io/anitaprofileportfolio/
![Badge](https://img.shields.io/badge/Github-anitapeppercorn-4cbbb9) 
![Profile Image](https://github.com/anitapeppercorn.png?size=50)

[Table of Content](#Table-of-Content) --- [Back to Top](#Social-Network-API) --- # Social-Network-API
