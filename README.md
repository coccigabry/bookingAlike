# Booking-Alike

A Full-Stack JavaScript application built with React.js, Node.js, Express and MongoDB .
A clone of the famous travel marketplace.

## Features

- **User authentication** (JWT based)
- **RESTful API** with CRUD operations
- **Responsive design** with mobile-first approach
- **Database integration** with MongoDB/Mongoose

## Tech Stack

### Frontend
- React.js 18+
- React Router v6

### Backend
- Node.js 16+
- Express.js
- MongoDB (with Mongoose ODM)
- JWT for authentication
- Bcrypt for password hashing
- DotEnv for loading environment variables from a .env file into process.env

## Prerequisites

Before running the project, ensure you have installed:
- Node.js (v16 or higher)
- npm (v8 or higher) or yarn
- MongoDB (local or Atlas connection string)

## Installation

1. Clone the repository using Bash:
   
   git clone https://github.com/yourusername/project-name.git   cd project-name   

2. Install dependencies for both frontend and backend using Bash:

   Install backend dependencies from project root directory

   cd backend && npm install
   
   Install frontend dependencies from project root directory

   cd client && npm install   

4. Set up environment variables:
   
   Create `.env` files in both `backend` and `client` directories based on the provided `.env.example` files.

6. Start the development servers using Bash:
    
   Start backend from project root directory

   npm start
   
   Start frontend from project root directory

   npm run dev  

   This will concurrently start both frontend and backend.

## Environment Variables

### Backend (.env)
START_MONGODB=`url begin`
MONGODB_USERNAME=`username`
MONGODB_PASSWORD=`psw`
END_MONGODB=`querystrings`

## Contributing

Pull requests are welcome! Please follow these steps:
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Gabriele Cocilovo - coccigab@gmail.com  
