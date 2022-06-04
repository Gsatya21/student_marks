# Student_management_system
A Full Stack Web Application built with Node.js, Express.js, MongoDB and Bootstrap for managing all the tasks and activities of a student within an Institution.

# Roles

  - A powerful Login and Authentication System - Role based authentication and authorization.
  - Student Details – Displays the details of all the students, and provides following services:
        a. Adding a new student.
        b. Editing / Modifying the data of an existing student.
        c. Deleting / Removing the data of an existing student.

  - Course Details – Lis the details of all the courses available in the institution, and provides following services:
        a. Adding a new course.
        b. Editing an existing course.
        c. Deleting a course.
  - Fee Details.
  - Marks and Grades.
  - Attendance.


### Installation

This project requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd student-management-system
$ npm install -d
$ nodemon
```



### Todos

 - Import the users.json file to the local MongoDB server.
 ```sh
$ mongoimport --db student-mgmt-sys --collection users --file users.json
```
 - And run the application in the development mode.
