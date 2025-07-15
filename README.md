# e-Commerce

A full-stack e-commerce application built with React (frontend) and Node.js/Express (backend), leveraging MongoDB for data management. This repository contains both the client and server codebases, organized for scalable development.

## Technologies Used

- **Frontend (client):**
  - React
  - Redux Toolkit & Redux Persist
  - Material-UI (MUI)
  - Axios
  - Styled Components
  - React Router DOM

- **Backend (server):**
  - Node.js
  - Express
  - Mongoose (MongoDB)
  - JWT Authentication
  - Bcrypt (password hashing)
  - CORS
  - Dotenv
  - Nodemon

## Project Structure

```
e-Commerce/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   ├── package-lock.json
│   └── README.md
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── error.js
│   ├── index.js
│   ├── package.json
│   └── package-lock.json
│
└── README.md
```

## Getting Started

### Prerequisites

- Node.js & npm installed
- MongoDB instance (local or cloud)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/raysoham067/e-Commerce.git
   cd e-Commerce
   ```

2. **Install dependencies for both client and server:**
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```

3. **Set up environment variables:**
   - Create a `.env` file in the `server/` directory for MongoDB connection, JWT secret, etc.

4. **Start the development servers:**

   - **Server:**
     ```bash
     cd server
     npm start
     ```
   - **Client:**
     ```bash
     cd client
     npm start
     ```

## Features

- User authentication (JWT-based)
- Product listing and management
- Cart and order management
- Responsive UI with Material-UI
- RESTful API with Express
- Secure password storage

## Contributing

Contributions are welcome! Please open issues or submit pull requests.

## License

This project is licensed under the ISC License.

## Author

[raysoham067](https://github.com/raysoham067)
