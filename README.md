# MERN-Auth-Starter

This is a MERN (MongoDB, Express.js, React.js, Node.js) authentication starter project. It provides a basic setup for user registration and login functionality along with toast notifications for user interaction feedback.

## Features

- User registration with email and password
- User login with email and password
- Toast notifications for user feedback

## Prerequisites

Before running this application, ensure you have the following installed on your machine:

- Node.js
- MongoDB (Make sure MongoDB server is running)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/rahulsainlll/MERN-Auth-Starter.git
```
2. Navigate to the project directory:

```bash
cd mern-auth-starter
```

3. Install dependencies for both client and server:

```bash
cd client
npm install
cd ../server
npm install
```

4. Create a `.env` file in the `server` directory and add the following environment variables:
   
```bash
Mongo_URL=<your-mongodb-uri>
JWT_Secret=<your-jwt-secret>
```
Replace <your-mongodb-uri> with your MongoDB connection URI and <your-jwt-secret> with a secret key for JWT token encryption.

## Usage

Start the server:
```bash
cd server
npm start
```

Start the client:
```bash
cd client
npm run dev
```
Open your web browser and navigate to http://localhost:5173/ to access the application.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs, feature requests, or questions.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

