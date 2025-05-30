# Movie Theater Backend

This is a backend application for a movie theater management system built using Node.js and MongoDB. It provides a RESTful API to manage movie data, including creating, retrieving, updating, and deleting movies.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/movie-theater-backend.git
   ```

2. Navigate to the project directory:
   ```
   cd movie-theater-backend
   ```

3. Install the dependencies:
   ```
   npm install
   ```

4. Create a `.env` file in the root directory and add your MongoDB connection string:
   ```
   MONGODB_URI=your_mongodb_connection_string
   ```

## Usage

To start the application, run:
```
npm start
```

The server will start on the specified port (default is 3000).

## API Endpoints

### Movies

- **GET** `/api/movies` - Retrieve all movies
- **GET** `/api/movies/:id` - Retrieve a movie by ID
- **POST** `/api/movies` - Create a new movie
- **PUT** `/api/movies/:id` - Update a movie by ID
- **DELETE** `/api/movies/:id` - Delete a movie by ID

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.#   B E - m o v i e - t h e a t e r  
 