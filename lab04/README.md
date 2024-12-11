# NerdLuv - PHP Learning Exercise 📚

NerdLuv is an educational project designed to practice and demonstrate PHP programming concepts, during my bachelor degree. This dating website simulation was created as an exercise to master core PHP concepts including form handling, file I/O, and basic web application architecture.

## Educational Objectives

This exercise focuses on learning:
- PHP form processing and validation
- File-based data storage and retrieval
- PHP include statements for template management
- Basic matching algorithm implementation
- HTML/CSS integration with PHP
- GET/POST request handling
- Basic web application structure

## Features

- **New User Registration**: Users can sign up by providing:
  - Basic information (name, gender, age)
  - Personality type (based on Myers-Briggs Type Indicator)
  - Favorite operating system
  - Age preferences for matching
  - Gender preferences for matching

- **Match Finding**: Existing users can find potential matches based on:
  - Compatible personality types
  - Operating system preferences
  - Age range preferences
  - Gender preferences
  - Both users' matching criteria must align for a match to occur

## Technology Stack

- PHP for server-side processing
- HTML/CSS for frontend
- File-based storage system using text files
- No database required

## File Structure

- `index.php` - Main landing page
- `signup.php` - New user registration form
- `signup-submit.php` - Processes new user registration
- `matches.php` - Match search form
- `matches-submit.php` - Processes and displays matches
- `singles.txt` - Data storage for user profiles
- `top.html` & `bottom.html` - Shared page templates
- `nerdluv.css` - Styling for the entire site

## Setup Instructions

1. Clone the repository to your web server directory
2. Ensure PHP is installed and configured on your server
3. Make sure `singles.txt` has write permissions for the web server user
4. Access the site through your web browser at `http://your-server/path-to-nerdluv`

## Data Storage Format

User data is stored in `singles.txt` with the following format:
```
Name,Gender,Age,PersonalityType,OS,MinAgePreference,MaxAgePreference,GenderPreference
```

Example:
```
Ada Lovelace,F,96,ISTJ,Linux,24,99,M
```

## Matching Algorithm

The matching system considers multiple factors:
1. Gender preferences must align between users
2. Age must fall within each user's preferred range
3. Operating system preference must match
4. Personality types should have at least one matching trait

## Learning Outcomes

Through this project, you'll gain experience with:
- PHP syntax and basic constructs
- Form handling and data validation
- File operations in PHP
- Simple search and matching algorithms
- Code organization and separation of concerns
- HTML template inclusion
- Basic web security considerations

## Security Notes

- This is a learning exercise and not intended for production use
- Input validation and security measures should be implemented before production use
- Consider using a proper database instead of text files for data storage
- Implement proper user authentication and session management
- It's meant to practice with form validation

## Acknowledgments

This exercise was created as a learning tool for mastering PHP web development concepts. It's intended for educational purposes and demonstrates basic web application architecture and PHP programming principles.