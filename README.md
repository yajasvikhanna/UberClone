# Uber Clone

This project is an Uber clone application that provides real-time monitoring and notifications to users and captains using Socket.io. It also integrates Google Maps for location services and uses JWT for authentication. The frontend is built with React.js, and the backend server is built using Express in Node.js. MongoDB is used as the database.

#Demo
![Demo](UberClone/uberClone/assets/demo1.gif)
![Demo](UberClone/uberClone/assets/demo.gif)


## Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=social&logo=linkedin)](https://www.linkedin.com/in/yajasvikhanna)  
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=social&logo=leetcode)](https://leetcode.com/u/yajasvikhanna/)




## Features

- **JWT Authentication**: Secure authentication using JSON Web Tokens.
- **Real-Time Monitoring and Notifications**: Real-time updates and notifications using Socket.io.
- **Google Maps Integration**: Location services integrated with Google Maps API.
- **CORS Handling**: Proper handling of Cross-Origin Resource Sharing (CORS).
- **React.js Frontend**: User interface built with React.js.
- **Express.js Backend**: Server built with Express in Node.js.
- **MongoDB Database**: Data storage using MongoDB.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Express.js, Node.js
- **Database**: MongoDB
- **Real-Time Communication**: Socket.io
- **Authentication**: JWT (JSON Web Tokens)
- **Maps Integration**: Google Maps API
- **CORS Handling**: CORS middleware

## Getting Started

### Prerequisites

- Node.js
- npm (Node Package Manager)
- MongoDB

### Installation

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/uber-clone.git
    cd uber-clone
    ```

2. **Install backend dependencies**:
    ```sh
    cd backend
    npm install
    ```

3. **Install frontend dependencies**:
    ```sh
    cd ../frontend
    npm install
    ```

### Configuration

1. **Backend Configuration**:
    - Create a `.env` file in the `backend` directory and add the following environment variables:
        ```properties
        PORT=3000
        DB_CONNECT=mongodb+srv://<username>:<password>@cluster0.mongodb.net/your-db-name
        JWT_SECRET=yourSecretKey
        GOOGLE_MAPS_API_KEY=yourGoogleMapsApiKey
        ```

2. **Frontend Configuration**:
    - Create a `.env` file in the `frontend` directory and add the following environment variable:
        ```properties
        VITE_BASE_URL=https://your-backend-url.com
        ```

### Running the Application

1. **Start the backend server**:
    ```sh
    cd backend
    npm start
    ```

2. **Start the frontend development server**:
    ```sh
    cd ../frontend
    npm run dev
    ```

### Deployment

- **Backend**: Deploy the backend server to a platform like Render, Heroku, or any other cloud service.
- **Frontend**: Deploy the frontend to a platform like Vercel, Netlify, or any other static site hosting service.

### Usage

- **User Authentication**: Users can register and log in using JWT authentication.
- **Real-Time Updates**: Users and captains receive real-time updates and notifications.
- **Google Maps**: Users can view and interact with maps for location services.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [Express.js](https://expressjs.com/)
- [React.js](https://reactjs.org/)
- [Socket.io](https://socket.io/)
- [MongoDB](https://www.mongodb.com/)
- [Google Maps API](https://developers.google.com/maps)
