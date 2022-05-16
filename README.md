# networkAPI

## Description
MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data.

In this assignment, I built an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list.

Packages used includes Express.js for routing, and Mongoose packages.

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Installation](#installation)
- [Usage](#usage)
- [Acceptance Criteria](#acceptance-criteria)
- [Technology Used](#technology-used)
- [Video Link](#video-link)

## User Story
```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```
## Acceptance Criteria
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia Core for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia Core
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
## Installation

Clone the code into your terminal for the respective repository. Then, install npm by entering the command ```npm install```  into the terminal. Install express and mongoose by entering ```npm i express``` and ```npm i mongoose``` into the command line, respectively.
 for thoughts, users, friends, and reactions

## Usage
1. Install npm and dependencies: npm install
2. Open Insomnia and test API GET, POST, PUT, and DELETE routes for thoughts, users, friends, and reactions

## Technology Used
•	Node
•	Express.js
•	Javascript
•	Mongoose
•	MongoDB
•	Insomnia

## Video Link
- https://youtu.be/I8N5KrD9AfY