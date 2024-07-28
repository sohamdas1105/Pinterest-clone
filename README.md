Got it! Below is the updated README file for a Pinterest clone project that uses JavaScript for both front-end and back-end development.

---

# Pinterest Clone

## Overview
This project is a clone of Pinterest, a popular image-sharing social media platform. The Pinterest clone allows users to upload, organize, and share images and videos on virtual pinboards. It includes features like user authentication, image upload, board creation, and image search.

## Features
- User Registration and Authentication
- Image Upload and Storage
- Board Creation and Management
- Pinning Images to Boards
- Search for Pins and Boards
- Like and Comment on Pins
- Responsive Design for Mobile and Desktop

## Technologies Used
### Front-End
- HTML5
- CSS3
- JavaScript (ES6+)
- React.js
- Redux

### Back-End
- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM)

### Other Tools and Libraries
- AWS S3 (Image Storage)
- Docker
- Git & GitHub

## Installation
### Prerequisites
- Node.js and npm
- MongoDB
- Docker (optional for containerized deployment)

### Back-End Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pinterest-clone.git
   cd pinterest-clone/backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the environment variables:
   - Create a `.env` file in the `backend` directory.
   - Add the following environment variables to the `.env` file:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     AWS_ACCESS_KEY_ID=your_aws_access_key_id
     AWS_SECRET_ACCESS_KEY=your_aws_secret_access_key
     JWT_SECRET=your_jwt_secret
     ```

4. Start the back-end server:
   ```bash
   npm start
   ```

### Front-End Setup
1. Navigate to the `frontend` directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the environment variables:
   - Create a `.env` file in the `frontend` directory.
   - Add the following environment variables to the `.env` file:
     ```
     REACT_APP_API_URL=http://localhost:5000/api
     ```

4. Start the front-end development server:
   ```bash
   npm start
   ```

## Usage
1. Open your web browser and navigate to `http://localhost:3000`.
2. Register a new account or log in with an existing account.
3. Start creating boards and pinning images!

## Docker Setup (Optional)
To run the application using Docker, follow these steps:

1. Ensure Docker is installed and running on your machine.

2. Clone the repository and navigate to the project directory:
   ```bash
   git clone https://github.com/yourusername/pinterest-clone.git
   cd pinterest-clone
   ```

3. Build and run the Docker containers:
   ```bash
   docker-compose up --build
   ```

4. Open your web browser and navigate to `http://localhost:3000`.

## Contributing
Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-branch-name`
3. Make your changes and commit them: `git commit -m 'Add new feature'`
4. Push to the branch: `git push origin feature-branch-name`
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Inspired by the original [Pinterest](https://www.pinterest.com/) platform.
- Thanks to all the open-source projects and libraries used in this project.

---

Feel free to modify the content as needed to match your project specifics.
