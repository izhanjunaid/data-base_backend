# Makeup E-commerce Admin Panel

An admin panel for managing makeup products with virtual try-on capabilities.

## Features

- Product management with multiple shades
- Image upload for products and shades
- Virtual try-on reference images
- Stock management
- Category management

## Setup Instructions

1. Clone the repository
2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory with:
   ```
   MONGODB_URI=your_mongodb_connection_string_here
   PORT=5000
   ```

4. Install frontend dependencies:
   ```bash
   cd client
   npm install
   ```

5. Create an `uploads` directory in the root folder:
   ```bash
   mkdir uploads
   ```

6. Start the development servers:

   In the root directory:
   ```bash
   npm run dev
   ```

   In the client directory:
   ```bash
   npm start
   ```

## API Endpoints

- GET `/api/products` - Get all products
- GET `/api/products/:id` - Get single product
- POST `/api/products` - Create new product
- PUT `/api/products/:id` - Update product
- DELETE `/api/products/:id` - Delete product
- GET `/api/categories` - Get all categories

## Technologies Used

- Backend:
  - Node.js
  - Express
  - MongoDB
  - Multer (for file uploads)

- Frontend:
  - React
  - Material-UI
  - Axios
  - React Router #   d a t a - b a s e _ b a c k e n d  
 #   m o n g o _ b a c k e n d  
 