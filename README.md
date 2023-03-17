# ORM-E-Commerce
Assignment which requires you to make a backend service for an e-commerce application. This app runs with MySQL and express js.

- First update the .env file with your db info

- Install the dependancies

```sh
npm install
```

- Seed the database with

```sh
npm run seed
```

- Start the Server with

```sh
npm start
```

Technical challenges include:

- Running express servers
- ORM Sequelize for MySQL
- API Routing
- route error handling
- Relational Models
- Database Seeding

![“GET Categories,” “GET Products,” and “GET tags,”.][def]

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![“GET Category by ID,” “GET One Product,” and “GET tag by id,”. ][def2]

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![“CREATE Category,” “UPDATE Category,” and “GET tag by id.” ][def3]

[def]: ./Assets/video1.mov
[def2]: ./Assets/video2.mov
[def3]: ./Assets/video3.mov