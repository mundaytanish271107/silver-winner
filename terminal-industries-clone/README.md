# Terminal Industries Website Clone

This is a clone of the Terminal Industries "About" page from https://terminal-industries.com/about

## Project Structure

```
terminal-industries-clone/
├── index.html          # Main HTML file (cleaned and simplified)
├── css/
│   └── entry.css      # Main stylesheet
├── js/
│   └── main.js        # Main JavaScript file
├── static/
│   └── favicon.svg    # Site favicon
└── README.md          # This file
```

## Features

- **Responsive Design**: The layout adapts to different screen sizes
- **Modern Styling**: Clean, professional design with Terminal Industries branding
- **Navigation**: Fixed header with navigation menu
- **Hero Section**: Large title and subtitle
- **Content Sections**: Information about the company and services
- **Features Grid**: Showcasing key features
- **Footer**: Contact information and links

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6+)
- SVG Graphics

## Color Scheme

- Dark Green: `#1a4d3a`
- Lime: `#abff02`
- White: `#ffffff`
- Light Gray: `#6b7280`
- Light Light Gray: `#a2a6b4`

## How to View

Simply open `index.html` in a web browser. No build process or server required.

### Option 1: Direct File Open
```bash
# Open in your default browser
open index.html  # macOS
xdg-open index.html  # Linux
start index.html  # Windows
```

### Option 2: Local Server
For better asset loading, you can use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (with http-server)
npx http-server -p 8000

# Then visit: http://localhost:8000
```

## Notes

- This is a simplified clone focusing on the core structure and styling
- Some dynamic features from the original site may not be fully functional
- External assets (images, videos) are not included but can be added to the `images/` directory
- The original site uses Nuxt.js and Vue.js; this clone uses vanilla HTML/CSS/JS

## Original Site

- URL: https://terminal-industries.com/about
- Company: Terminal Industries
- Description: A logistics technology company rethinking yard management systems

## License

This is a clone for educational/demonstration purposes. All rights to the original design and content belong to Terminal Industries.

## Date Cloned

October 26, 2025
