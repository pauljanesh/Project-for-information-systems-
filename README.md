Movie Watchlist (crud )
A  web application to manage your personal movie collection. Keep track of movies, mark them as watched, and organize your watchlist.

Getting Started

 Prerequisites;
 Node.js (v12 or higher)
 npm

 Installation;
Navigate to the project directory:
bash
cd project\ movie\ watchlist
cd backend
npm install
npm start

The application will be available at `http://localhost:3001`
 Features

- Secure login system with session management
- Add new movies with title, genre, year, rating, and description
- Edit movie details anytime
- Mark movies as watched/unwatched
- Delete movies from your collection
- Search and filter by genre
- Beautiful green theme with responsive design
 Project Structure
project movie watchlist/
├── frontend/
│   ├── index.html          (Main watchlist page)
│   ├── add.html            (Add movie form)
│   ├── edit.html           (Edit movie form)
│   ├── details.html        (Movie details view)
│   ├── login.html          (Login page)
│   └── style.css           (Styling)
├── backend/
│   ├── server.js           (Express server)
 web application to manage your movie watchlist.
Setup
1. Install backend dependencies:
-bash
cd backend
npm install
1. Start the server:
2. bash
npm start
1. Open `frontend/index.html` in your browser
 Features
 View all movies
 Add new movies
 Edit movie details
 Mark as watched/unwatched
 Delete movies
 Search and filter
 API

 GET `/api/movies` - Get all movies
 POST `/api/movies` - Add movie
 GET `/api/movies/:id` - Get movie
 PUT `/api/movies/:id` - Update movie
 PATCH `/api/movies/:id/watched` - Toggle watched
 DELETE `/api/movies/:id` - Delete movie

Project Overview;
The Movie Watchlist project is a web-based application that allows users to manage a list of movies they want to watch. The system enables users to add, view, edit, and delete movie records through a simple and user-friendly interface.
The application follows a client–server architecture, where the frontend handles user interaction and the backend manages application logic and data storage using a JSON file.

Objectives of the Project;
To build a simple movie management system
To implement CRUD operations using web technologies
To understand frontend and backend communication
To use JSON as a lightweight data storage solution
To gain practical experience with Node.js and Express.js

Technologies Used;
Frontend
HTML – Page structure
CSS – Styling and layout
JavaScript – Handling user actions and API calls
Backend
Node.js – Runtime environment
Express.js – Web framework for handling HTTP requests
JSON – Used for data storage (movies.json)

Project Structure;
Frontend
login.html – User login page
index.html – Main watchlist page
add.html – Add new movie form
edit.html – Edit movie details
details.html – View movie information
style.css – Styling for all pages

Backend
server.js – Express server and API logic
movies.json – Stores movie data persistently
package.json – Project configuration and dependencies
package-lock.json – Dependency version control
How the Project Works;
The user logs in using the login page
The main watchlist page displays all stored movies

The user can:
Add a new movie
Edit existing movie details
View movie information
Delete movies from the list
Frontend sends HTTP requests (GET, POST, PUT, DELETE) to the backend
The backend processes requests and updates movies.json
Updated data is sent back to the frontend and displayed

Data Storage Method;
Movie data is stored in a local JSON file (movies.json)
Acts as a simple file-based database
Data is persistent and remains saved after server restarts
Backend reads from and writes to the JSON file for every operation

Data Flow
Frontend
   ↓
server.js (Express API)
   ↓
movies.json

Key Features;
Full CRUD functionality
Persistent data storage using JSON
Simple and intuitive user interface
Clear separation of frontend and backend
Lightweight and easy to run locally

Limitations;
No advanced authentication system
Suitable only for single-user or small-scale use
JSON file storage is not ideal for large datasets
Future Enhancements;

Replace JSON file with MongoDB
Add user authentication and roles
Implement search and filter options
Add movie ratings and reviews
Deploy application to cloud hosting

Conclusion;
The Movie Watchlist project successfully demonstrates the fundamentals of full-stack web development using HTML, CSS, JavaScript, Node.js, Express.js, and JSON. It provides hands-on experience with CRUD operations and file-based data storage, making it a strong foundation for learning database-driven applications in the future.
