## 💫 Overview
Farmstand is a simple website built using MongoDB, Express.js, and EJS. It allows users to create, read, update, and delete (CRUD) farm products.

## 🪄 Features

- Display a list of all farm products
- Create new farm products
- Update existing farm products
- Delete farm products
- Filter products by category (fruit, vegetable, dairy)

## 📦 Technologies Used

- MongoDB (localhost) for data storage
- Express.js for routing and server management
- EJS for templating and rendering dynamic content
- JavaScript for client-side scripting

## 📃 Project Structure

- `models/`: Contains the Product model definition
- `views/`: Contains EJS templates for rendering dynamic content
- `seeds.js`: Contains initial product data for seeding the database
- `index.js`: The main application file, responsible for routing and server management
- `package.json`: Contains project metadata and dependencies

## 🎬 Getting Started

1. Clone the repository: `git clone (link unavailable)`
2. Install dependencies: `npm install`
3. Seed the database: `node seeds.js`
4. Start the server: `node index.js`
5. Open a web browser and navigate to `http://localhost:3000/products`

## 🗃 Scope 

- This project is for educational purposes only and is not intended for production use.
- User authentication is not implemented, so anyone can create, update, or delete products.
- The project uses a local MongoDB instance, so data is stored on the local machine.

## 🔗 API Endpoints

The following API endpoints are available:

1. GET /products
   - *Retrieve a list of all farm products.*

2. GET /products/new
   - *Render a form for creating a new farm product.*

3. POST /products
   - *Create a new farm product.*

4. GET /products/:id
   - *Retrieve a single farm product by ID.*

5. GET /products/:id/edit
   - *Render a form for editing a farm product.*

6. PUT /products/:id
   - *Update a farm product.*

7. DELETE /products/:id
   - *Delete a farm product.*


## 📄 Acknowledgments

- MongoDB for providing a free MongoDB instance
- Express.js for providing a lightweight web framework
- EJS for providing a templating engine
