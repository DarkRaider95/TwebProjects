# Kevin Bacon Movie Database

A simple web application that allows users to explore movie connections with Kevin Bacon and search for actor filmographies. This project was created for educational purposes, during my bachelor degree, to practice PHP, MySQL, and web development fundamentals.

## 🎯 Project Overview

This application implements the "Six Degrees of Kevin Bacon" concept, allowing users to:
- Search for any actor's filmography
- Find movies where a specific actor worked with Kevin Bacon
- View results in a clean, tabulated format

## 🛠️ Technologies Used

- PHP
- MySQL
- HTML5
- CSS3
- Session Management
- PDO for Database Connections

## 🔑 Features

- User Authentication System
- Session Management
- Two Search Modes:
  - All movies by a specific actor
  - Movies where an actor worked with Kevin Bacon
- Responsive Table Display
- Input Validation
- Secure Database Queries using PDO
- Clean and Professional UI

## 💾 Database Structure

The application uses a MySQL database named `imdb` with the following main tables:
- `actors`: Stores actor information
- `movies`: Contains movie details
- `roles`: Links actors to movies
- `user`: Stores user authentication data

## 🚀 Getting Started

1. Set up a MySQL server
2. Import the IMDB database
3. Update the database connection credentials in `common.php`
4. Configure your web server to serve PHP files
5. Place all files in your web server's directory
6. Access the application through your web browser

## 📝 Note

This project is for educational purposes and was created to practice:
- PHP backend development
- MySQL database management
- User authentication
- Session handling
- Web security practices
- Frontend development with HTML and CSS

## 🔐 Security Features

- Password validation
- Session management
- Protected routes
- SQL injection prevention using PDO
- Input sanitization

## ⚠️ Educational Disclaimer

This project is intended for learning purposes and demonstrates basic concepts of:
- Database connectivity
- User authentication
- Web security
- Frontend-backend integration
- Data filtering and display

Feel free to use this code as a learning resource, but note that additional security measures would be needed for a production environment.