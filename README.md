# 🚴 Bike Store API

A robust API for managing bike inventory, placing orders, and calculating revenue.

## 📜 Features

- **Product Management**: Add, update, delete, and retrieve bike products.
- **Inventory Control**: Automatically adjust stock when an order is placed.
- **Order Management**: Place orders and handle stock availability.
- **Revenue Calculation**: Aggregate total revenue via MongoDB aggregation.
- **Error Handling**: Clear error messages for invalid operations.
- **Stock Status**: Update inStock based on product quantity.

## 🛠️ Tech Stack

- **Backend**: Node.js, Express.js
- **Database**: MongoDB with Mongoose
- **Language**: TypeScript

## 🚀 Installation and Setup

### Prerequisites

- Node.js (v14+)
- MongoDB (local or cloud instance)

## Steps

1. **Clone the repository**:

```bash

git clone https://github.com/umayeremon/Bike-Store-API-B4A2

cd Bike-Store-API-B4A2

```

2. **Install dependencies**:

```bash

npm install
```

3. **Set up environment variables**:

- Create a .env file in the project root and add the following variables:

```env

PORT=5000

DB_URL= mongodb+srv://B4A2:dW4D9GDKY30vke3K@cluster0.2fsgp3y.mongodb.net/b4a2?retryWrites=true&w=majority&appName=Cluster0
```

4. **Run the application**:

```bash

npm run dev
```

- The server will start on http://localhost:5000.

5. **Test the API**: Use a tool like Postman or cURL to test the endpoints.

## 📋 API Endpoints

### Products

- POST /api/products - Create a new product.
- GET /api/products - Get all products.
- GET /api/products/:id - Get a specific product.
- PUT /api/products/:id - Update a product.
- DELETE /api/products/:id - Delete a product.

## Orders

- POST /api/orders - Place an order.
- GET /api/orders/revenue - Get total revenue from all orders.

## 🧑‍💻 Contributing

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch
5. Open a pull request.
