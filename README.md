# E-commerce Website

A full-stack e-commerce platform built with MERN stack (MongoDB, Express.js, React, Node.js) offering a modern shopping experience with real-time cart management, user authentication, and responsive design.

## Features

- User authentication with JWT
- Real-time shopping cart management
- Product categorization and filtering
- Favorites list functionality
- Order tracking and history
- Responsive design for mobile and desktop
- Dynamic product search
- User profile management

## Tech Stack

### Frontend
- React.js 18
- Redux Toolkit with Redux Persist
- Styled Components
- Material-UI
- React Router DOM
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Bcrypt
- CORS

## Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/ecommerce-website.git
cd ecommerce-website
```

2. Install dependencies for both client and server
```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

3. Set up environment variables
```bash
# In the server directory, create a .env file with:
MODNO_DB=your_mongodb_connection_string
JWT=your_jwt_secret
```

4. Run the application
```bash
# Run server (from server directory)
npm start

# Run client (from client directory)
npm start
```

## Project Structure

```
client/
  ├── public/
  ├── src/
  │   ├── api/
  │   ├── components/
  │   ├── pages/
  │   ├── redux/
  │   └── utils/
server/
  ├── controllers/
  ├── middleware/
  ├── models/
  └── routes/
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.