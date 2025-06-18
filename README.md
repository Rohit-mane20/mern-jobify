# MERN Jobify

## Introduction
MERN Jobify is a job listing application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). This application allows users to view, add, edit, and delete job listings. It features user authentication(JWT) and a responsive design.

## Features
- User authentication (registration and login)
- Job listing management (add, edit, delete)
- Responsive design
- User-friendly interface

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Node.js and npm installed on your machine
- MongoDB installed or access to a MongoDB database

## Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Rohit-mane20/mern-jobify.git
   cd mern-jobify-v2-main
   ```

2. **Install server dependencies**
   Navigate to the root of the project and run:
   ```bash
   npm install
   ```

3. **Set up the database**
   - Create a MongoDB database and update the connection string in the `server.js` file.

4. **Run the server**
   ```bash
   node server.js
   ```

5. **Install client dependencies**
   Navigate to the `client` directory:
   ```bash
   cd client
   npm install
   ```

6. **Run the client**
   ```bash
   npm start
   ```

7. **Access the application**
   Open your browser and go to `http://localhost:3000` to view the application.

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
