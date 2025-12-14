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

-- Start the server:

 bash

npm start

Open `frontend/index.html` in your browser
   
 Features
 1.View all movies
 2.Add new movies
 3.Edit movie details
 4.Mark as watched/unwatched
 5.Delete movies
 6.Search and filter
 7.API

- GET `/api/movies` - Get all movies
 POST `/api/movies` - Add movie
 GET `/api/movies/:id` - Get movie
 PUT `/api/movies/:id` - Update movie
 PATCH `/api/movies/:id/watched` - Toggle watched
 DELETE `/api/movies/:id` - Delete movie

Project Overview;
The Movie Watchlist project is a web-based application that allows users to manage a list of movies they want to watch. The system enables users to add, view, edit, and delete movie records through a simple and 
user-friendly interface.
The application follows a client–server architecture, where the frontend handles user interaction and the backend manages application logic and data storage using a JSON file.

Objectives of the Project;

1.To build a simple movie management system
2.To implement CRUD operations using web technologies
3.To understand frontend and backend communication
4.To use JSON as a lightweight data storage solution
5.To gain practical experience with Node.js and Express.js

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

1. Add a new movie
2. Edit existing movie details
3. View movie information
4. Delete movies from the list
5. Frontend sends HTTP requests (GET, POST, PUT, DELETE) to the backend
6. The backend processes requests and updates movies.json
7. Updated data is sent back to the frontend and displayed

Data Storage Method;
1. Movie data is stored in a local JSON file (movies.json)
2. Acts as a simple file-based database
3. Data is persistent and remains saved after server restarts
4. Backend reads from and writes to the JSON file for every operation

Data Flow
Frontend
   ↓
server.js (Express API)
   ↓
movies.json

Key Features;
1. Full CRUD functionality
2. Persistent data storage using JSON
3. Simple and intuitive user interface
4. Clear separation of frontend and backend
5. Lightweight and easy to run locally

Limitations;
1. No advanced authentication system
2. Suitable only for single-user or small-scale use
3. JSON file storage is not ideal for large datasets

Future Enhancements;

1. Replace JSON file with MongoDB
2. Add user authentication and roles
3. Implement search and filter options
4. Add movie ratings and reviews
5. Deploy application to cloud hosting

Conclusion;
The Movie Watchlist project successfully demonstrates the fundamentals of full-stack web development using HTML, CSS, JavaScript, Node.js, Express.js, and JSON. It provides hands-on experience with CRUD operations and file-based data storage, making it a strong foundation for learning database-driven applications in the future.

references are :

https://github.com/louiseka/film-watchlist

https://chatgpt.com/share/693da91b-fb80-8002-bed6-f211720b742f

https://github.com/hinedy/Movie-Watchlist

https://share.google/LCsbxWbBPTCkIi3Sb 

google drive link:https://drive.google.com/drive/folders/1dQX0XtDDNcQbMZy4qLp9FK0aFpXY4EeE?usp=sharing
