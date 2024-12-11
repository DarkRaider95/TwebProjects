# Movie Review Website

A dynamic movie review website that displays movie information and critic reviews in a Rotten Tomatoes-inspired layout. The project includes support for multiple movies including The Matrix, Mortal Kombat, The Princess Bride, and TMNT.
This project was made during my bachelor degree for educational purposes.
## Features

- Dynamic movie data loading from text files
- Responsive two-column layout for reviews
- Fresh/Rotten rating system with visual indicators
- Detailed movie information display including:
  - Cast and crew
  - Runtime and release information
  - Movie synopsis
  - Critic reviews with sources
- Dynamic rating calculation
- Mobile-friendly design

## Technology Stack

- PHP for backend processing
- HTML5 for structure
- CSS3 for styling
- File-based data storage

## File Structure

```
├── movie.css           # Main stylesheet
├── movie.php          # Main PHP template
├── mortalkombat/      # Movie-specific data
│   ├── info.txt
│   ├── overview.txt
│   ├── overview.png
│   └── review*.txt
├── princessbride/     # Movie-specific data
├── thematrix/         # Movie-specific data
└── tmnt/             # Movie-specific data
```

## Data Format

### info.txt
Contains basic movie information in the format:
```
Movie Title
Year
Rating Score
```

### overview.txt
Contains detailed movie information including:
- Cast and crew
- Director
- Producer
- Rating
- Release date
- Runtime
- Synopsis

### review*.txt
Individual review files containing:
- Review text
- Rating (FRESH/ROTTEN)
- Critic name
- Publication source

## Setup

1. Set up a PHP-enabled web server
2. Clone the repository to your web root
3. Ensure proper file permissions for the movie data directories
4. Access through your web browser using: `http://your-server/movie.php?film=moviename`

## Validation

The site includes W3C validation for both HTML and CSS to ensure standards compliance.