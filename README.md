Database Setup:

Neon.tech/Docker: Set up a PostgreSQL or SQL database on Neon.tech or using Docker.

Database Schema: Design the database schema with tables for products (vegetables/fruits) and orders. The product table should include fields like id, name, and price. The orders table should include fields like id, buyer_name, buyer_contact, delivery_address, items (serialized as JSON), and status.

ORM/Query Builder (Optional): Consider using an ORM like Prisma or Sequelize, or a query builder like Knex.js, to simplify database interactions.

Backend API Development:

API Routes: Create API routes for the following functionalities:

GET /api/products: Fetch the product catalogue.

POST /api/orders: Place a new order.

GET /api/orders/:id: View order details (for buyers).

GET /api/orders: View all orders (for admins).

PUT /api/orders/:id: Update order status (for admins).

POST /api/products: Add a new product (for admins).

PUT /api/products/:id: Edit an existing product (for admins).

DELETE /api/products/:id: Remove a product (for admins).

HTTP Methods: Use appropriate HTTP methods (GET, POST, PUT, DELETE) for each API endpoint.

Error Handling: Implement proper error handling and validation for each API route.

Authentication (Optional): If implementing authentication, add API routes for login and user management.
