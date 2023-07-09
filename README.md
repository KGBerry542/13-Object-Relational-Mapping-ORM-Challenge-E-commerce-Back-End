# E-commerce Back End

This project provides a back-end solution for an e-commerce website using the latest technologies. It utilizes Express.js, Sequelize ORM, and MySQL database to implement the API routes for managing categories, products, and tags.

## Features

- API routes for categories, products, and tags
- Supports CRUD (Create, Read, Update, Delete) operations
- Database models for categories, products, tags, and product-tag associations
- Sample data seeding for testing and development

## Getting Started

To get started with the project, follow these steps:

1. Install the project dependencies using `npm install`.

2. Set up your MySQL database and configure the database connection in `.env` and `config/connection.js` files.

3. Run the database schema script in `db/schema.sql` to create the database.

4. Seed the database with sample data by running `npm run seed` command.

5. Start the server using `node server.js` or `npm start`.

6. Test the API routes using a tool like Insomnia or Postman.

## API Routes

- `/api/categories` - CRUD operations for categories
- `/api/products` - CRUD operations for products
- `/api/tags` - CRUD operations for tags

Refer to the code and comments in the respective route files for more details on the available routes and their functionalities.

## License

This project is licensed under the [MIT License](LICENSE).
