ToDo-App
========

A Simple ToDo web-app made up in AngularJS as a Frontend Framework, while Node.JS as a Backend Framework. Here we made an API to talk to our backend server which handles all todos and stores them in MongoDB database.

## Requirements
1. MongoDB
2. NodeJs

## Instructions
1. First run a mongodb on your system

2. Then, install all dependencies of this app
```
    $ npm install
```
3. To run an app
```
    $ node server.js
```

## API End-Points and URI Structure
| HTTP Method  | URI                  | Description            |
|--------------|:---------------------|-----------------------:|
|GET           | /api/todos           | Get all of the todos   |
|POST          | /api/todos           | Create a single todos  |
|DELETE        | /api/todos/:todo_id  | Delete a single todo   |

## Screenshots
  * Screenshot on a Small-Screen devices

  ![Screenshot on a Small-Screen Devices](/screenshots/app-mobile.png)

  * Screenshot on a Big-Screen devices

  ![Screenshot on a Big-Screen Devices](/screenshots/app-laptop.png)

## Pending Features
1. Social Sites Login
2. Edit Todos

## Feedback and Suggestions
Send me an email [pratapakshay0@gmail.com](mailto:pratapakshay0@gmail.com)
