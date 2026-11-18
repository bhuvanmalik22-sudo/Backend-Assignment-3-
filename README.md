# Student Management REST API

## Web Development III – Unit 2

The **Student Management REST API** is a backend project developed using **Node.js and Express.js**. It provides REST API endpoints for managing student records through CRUD operations.

The project uses modular routing, custom middleware, error handling, and an in-memory JavaScript array for storing student data.

---

## Project Objectives

The main objectives of this project are:

* Create an Express.js server
* Build REST API endpoints
* Perform CRUD operations on student records
* Use custom middleware
* Implement modular routing
* Handle errors using appropriate HTTP status codes
* Store student information using JavaScript array data
* Test the API using tools such as Postman

---

## Technologies Used

* **Node.js** – JavaScript runtime environment
* **Express.js** – Web framework for creating the REST API
* **Nodemon** – Development tool for automatically restarting the server
* **JavaScript** – Programming language
* **REST API** – API architecture used for student management

---

## Project Structure

```text
Assignment-2/
│
├── app.js
├── package.json
├── package-lock.json
│
├── data/
│   └── students.js
│
├── middleware/
│   └── logger.js
│
├── routes/
│   └── studentRoutes.js
│
└── node_modules/
```

---

## File and Folder Description

### 1. `app.js`

The `app.js` file is the main entry point of the application.

It is responsible for:

* Creating the Express application
* Configuring JSON request handling
* Loading the custom logger middleware
* Connecting the student routes
* Handling unknown routes
* Handling server errors
* Starting the server

The server runs on:

```text
http://localhost:3000
```

---

### 2. `data/students.js`

The `students.js` file contains the student records used by the application.

The student records are stored inside a JavaScript array.

Each student contains:

* ID
* Name
* Age
* Course
* Email

Example:

```javascript
{
  id: 1,
  name: "Aarav Mehta",
  age: 20,
  course: "Computer Applications",
  email: "aarav@example.com"
}
```

The project does not use MongoDB, MySQL, Mongoose, or any other database.

The student records are stored in memory using the JavaScript array.

---

### 3. `middleware/logger.js`

The `logger.js` file contains the custom logger middleware.

It records information about incoming HTTP requests, including:

* Request time
* HTTP method
* Requested URL

Example:

```text
[9/25/2026, 9:30:15 PM] GET /students
```

The middleware is registered in `app.js` using:

```javascript
app.use(logger);
```

---

### 4. `routes/studentRoutes.js`

The `studentRoutes.js` file contains the modular routes for student management.

It handles all major student CRUD operations:

```text
GET     /students
GET     /students/:id
POST    /students
PUT     /students/:id
DELETE  /students/:id
```

The routes are connected to the main application using:

```javascript
app.use("/students", studentRoutes);
```

---

### 5. `package.json`

The `pack

# postman-get
<img width="1600" height="898" alt="48deb01b-2ff6-4a0f-a591-8590ad4674d2" src="https://github.com/user-attachments/assets/a8599d0e-c196-42cc-879d-b96ba172a8b1" />

# postman-get/by-id
<img width="1600" height="898" alt="0f147ae0-73a6-40ab-8a25-c5d763bda4ec" src="https://github.com/user-attachments/assets/3c992d5d-a29b-4ca1-b8c5-ceedb44488bd" />

# postman-post
<img width="1600" height="876" alt="bf477c0d-7bdc-4258-b308-d4417a28e3f0" src="https://github.com/user-attachments/assets/59229588-73ea-42d9-80c2-ec14b47387f3" />

# postman-put
<img width="1600" height="1200" alt="65673f2c-f499-4959-b857-02a3c62228b2" src="https://github.com/user-attachments/assets/d2146f96-eb1f-490f-8bca-22d2a7c6c1d7" />

# postman-delete
<img width="1600" height="721" alt="c4bde998-b70d-4a68-b996-69f5ff1f89b6" src="https://github.com/user-attachments/assets/04453397-6dc4-4cd6-9499-bd588b27f340" />

# postman-get/low-stock
<img width="1024" height="521" alt="e92ee4ab-0423-46e9-8cb8-319e8c625848" src="https://github.com/user-attachments/assets/d5e3664f-0ae8-4dce-8dda-6b11bab9b7aa" />

# postman-get/category-summary
![Uploading 9f961921-fb92-4562-a2a8-0aacf9aea962.jpg…]()



