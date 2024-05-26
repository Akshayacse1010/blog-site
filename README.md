# MERN Blog Website

A full-stack blog website built using the MERN stack (MongoDB, Express, React, Node.js).


## Introduction

This project is a blog website where users can create, edit, and delete blog posts. It demonstrates the use of the MERN stack to build a full-stack web application with a focus on RESTful API design and a responsive, interactive front-end.

## Features

- User authentication and authorization
- Create, read, update, and delete blog posts
- Responsive design
- Rich text editor for blog content
- Comments section for each blog post
- Profile page for users

## Technologies Used

- **MongoDB**: NoSQL database for storing blog posts and user information
- **Express**: Node.js web framework for building the RESTful API
- **React**: Front-end library for building the user interface
- **Node.js**: JavaScript runtime for the server-side application

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. Clone the repository:
bash
    git clone https://github.com/yourusername/mern-blog.git
    cd mern-blog
  

2. Install server dependencies:

  bash
    cd server
    npm install
  

3. Install client dependencies:

 bash
    cd ../client
    npm install
   

### Configuration

1. Create a `.env` file in the `server` directory and add the following environment variables:

 plaintext
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    PORT=5000
   

2. Create a `.env` file in the `client` directory if you have any client-specific environment variables.

### Running the Application

1. Start the MongoDB server:

    ```bash
    mongod
    ```

2. Start the server:

    ```bash
    cd server
    npm start
    ```

3. Start the client:

    bash
    cd ../client
    npm start
    

The application should now be running on [http://localhost:3000](http://localhost:3000) (client) and [http://localhost:5000](http://localhost:5000) (server).

## Usage

- Register a new user account or log in with an existing account.
- Create, edit, and delete blog posts.
- View all blog posts and read individual posts.
- Comment on blog posts.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



---

Thank you for using this blog website! I hope it serves as a useful example of a full-stack MERN application.
