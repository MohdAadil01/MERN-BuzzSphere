# MERN BuzzSphere

BuzzSphere is a full-stack social media application built with the MERN (MongoDB, Express, React, Node.js) stack. Users can create accounts, post updates, like and comment on posts, and interact with other users.

## Table of Contents

- [Features](#features)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- User Authentication (Sign Up, Sign In, Sign Out)
- Create, Read, Update, Delete (CRUD) Posts
- Like and Comment on Posts
- Follow and Unfollow Users
- Real-time Notifications
- Responsive Design

## Screenshots

![Screenshot 2024-06-11 000146](https://github.com/MohdAadil01/BuzzSphere/assets/125737087/830e4618-d66f-401b-b036-db5183b5db94)
![Screenshot 2024-06-11 000548](https://github.com/MohdAadil01/BuzzSphere/assets/125737087/63fd6ce0-b939-45c2-8e9e-6abe0fd35f38)
![Screenshot 2024-06-11 000612](https://github.com/MohdAadil01/BuzzSphere/assets/125737087/9dd90ed3-2b2f-4932-a4d6-8ea7cf677503)


## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/MohdAadil01/MERN-BuzzSphere.git
    ```

2. Navigate to the project directory:
    ```bash
    cd MERN-BuzzSphere
    ```

3. Install the server dependencies:
    ```bash
    cd server
    npm install
    ```

4. Install the client dependencies:
    ```bash
    cd ../client
    npm install
    ```

## Usage

1. Start the server:
    ```bash
    cd server
    npm start
    ```

2. Start the client:
    ```bash
    cd ../client
    npm start
    ```

3. Open your browser and navigate to `http://localhost:3000` to see the app in action.

## API Documentation

### Endpoints

- **Auth**
  - `POST /api/auth/register` - Register a new user
  - `POST /api/auth/login` - Log in a user

- **User**
  - `GET /api/users` - Get all users
  - `GET /api/users/:id` - Get user by ID
  - `PUT /api/users/:id` - Update user
  - `DELETE /api/users/:id` - Delete user
  - `PUT /api/users/:id/follow` - Follow a user
  - `PUT /api/users/:id/unfollow` - Unfollow a user

- **Posts**
  - `POST /api/posts` - Create a post
  - `GET /api/posts/:id` - Get a post by ID
  - `PUT /api/posts/:id` - Update a post
  - `DELETE /api/posts/:id` - Delete a post
  - `PUT /api/posts/:id/like` - Like/Unlike a post


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

