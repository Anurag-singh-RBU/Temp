# Hotel Book Backend

## Overview
The Hotel Book backend is built using Node.js and Express. It serves as the API for the Hotel Book application, handling requests related to hotel bookings, user management, and other functionalities.

## Project Structure
- **src/**: Contains the main source code for the backend.
  - **controllers/**: Business logic for handling requests.
  - **models/**: Data models that interact with the database.
  - **routes/**: API endpoint definitions.
  - **app.js**: Sets up the Express application and middleware.
  - **server.js**: Entry point for starting the server.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the backend directory:
   ```
   cd hotel-book/backend
   ```
3. Install dependencies:
   ```
   npm install
   ```

## Running the Application
To start the backend server, run:
```
npm start
```
The server will listen on the specified port (default is 3000).

## API Endpoints
Refer to the routes defined in the `src/routes` directory for available API endpoints and their usage.

## Database
Ensure that the database is set up according to the schema defined in `database/schema.sql`. Migrations and seeds can be found in the respective directories.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License
This project is licensed under the MIT License.