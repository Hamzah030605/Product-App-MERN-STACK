# MERN Stack Product Management App

A full-stack MERN application for managing products with CRUD operations.

## Features

- ✅ Create, Read, Update, Delete products
- ✅ MongoDB database integration
- ✅ React frontend with Chakra UI
- ✅ Express.js backend API
- ✅ Responsive design

## Tech Stack

**Frontend:**
- React 19
- Chakra UI
- Vite
- Zustand (State Management)

**Backend:**
- Node.js
- Express.js
- MongoDB with Mongoose
- dotenv



## Live Demo

🚀 **[View Live App](https://product-app-mern-stack.onrender.com)**




## UserInterface

<img width="1511" height="997" alt="Screenshot 2025-08-10 at 11 30 06" src="https://github.com/user-attachments/assets/9fe17fce-fa39-4ae8-93dc-d9a522966ad9" />


## Local Development

### Prerequisites
- Node.js
- MongoDB Atlas account

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/mern-crash-course.git
cd mern-crash-course
```

2. Install backend dependencies
```bash
npm install
```

3. Install frontend dependencies
```bash
cd frontend
npm install
```

4. Create `.env` file in root directory
```env
MONGO_URI=your_mongodb_connection_string
```

5. Run the application
```bash
# Run backend (from root directory)
npm run dev

# Run frontend (in new terminal)
cd frontend
npm run dev
```

## API Endpoints

- `GET /api/products` - Get all products
- `POST /api/products` - Create a new product
- `PUT /api/products/:id` - Update a product
- `DELETE /api/products/:id` - Delete a product

## Deployment

This app is configured for deployment on Vercel with the included `vercel.json` configuration.

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request
