# Booklist Application

This is a simple Booklist application built using React, Node.js, Redis, and MySQL. It allows users to create, and see the book items.

# Features
  ```
  1. Create new book items with a title.
  2. View a list of all Book items from Cache/Database.
  3. Data is stored in a MySQL database and cached in Redis for faster retrieval.
```

# Technologies Used
  ```
1. React: A JavaScript library for building user interfaces.
2. Node.js: A JavaScript runtime environment for server-side development.
3. Express.js: A minimal and flexible web application framework for Node.js.
4. Redis: An in-memory data store used for caching.
5. MySQL: A popular relational database management system.

  ```
   

## Installation

1. Clone this repository.

```bash
https://github.com/minhaz11/booklist_app_express_react_redis_mysql.git
```
2. Navigate to the project directory:
```bash
e.g. cd booklist
```
3. Install dependencies for the frontend and backend:
```bash
cd frontend && npm install
cd ../backend && npm install
```

4. Import the books_list.sql file from backed folder to your database or create one with database name books_list with a table called books which only have title column:

5. To run this application :
```bash
cd frontend && npm start
cd ../backend && npm start
```
Once the application start, you can access the application in your browser for frontend
http://localhost:3000 and Backend  http://localhost:5000

## Usage

```
To create a new book item, enter the title in the input field and click the "Add Book" button.
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## Acknowledgements

```
React
Node.js
Express.js
Redis
MySQL
```
