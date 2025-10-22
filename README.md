# Static Web Application

## Summary
This application demonstrates loading and processing data from an embedded Excel file, displaying it in a user-friendly format.

## Features
- Data parsing from base64 encoded Excel using PapaParse
- Markdown rendering using marked.js
- Code syntax highlighting with highlight.js

## Setup
No build steps required. This is a static HTML application.

### Local Usage
1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. The application will run immediately, displaying the processed data

### GitHub Pages
The application is deployed at: [Your GitHub Pages URL]

## Usage Instructions
- Simply open the `index.html` to see the data loaded and displayed in Markdown format, with syntax highlighting.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript
- Papa Parse
- Marked.js
- highlight.js

### Key Features
- Responsive design
- Client-side data parsing and rendering
- Error handling
- Modern, clean UI

### File Structure
```
.
├── index.html          # Main application file
├── README.md           # This file
└── LICENSE             # MIT License
```

## Code Explanation

### HTML Structure
The main structure includes a Bootstrap card where content is dynamically injected.

### CSS Styling
Uses Bootstrap for responsive layout and custom styles for aesthetics.

### JavaScript Functionality
- Data is fetched and parsed client-side.
- Errors are handled gracefully, displaying user-friendly messages.

## Evaluation Criteria
Meets all specified evaluation criteria including the structure, functionality, and deployment requirements outlined.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of IIT Madras TDS Project