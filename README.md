# Gambling Suite

<img width="1712" height="624" alt="GamblingSuite" src="https://github.com/user-attachments/assets/e84f3788-13db-4040-8792-05dd8a2a162f" />

Web application to learn Blackjack and Poker (Texas Hold'em).

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Architecture**: Static Web Application
- **Communication**: Client-side logic

## Project Structure

```
GamblingSuite-static/
├── index.html       # Main HTML file
├── app.js           # Application logic
├── styles.css       # Styling
├── .github/         # GitHub configuration
├── .git/            # Git repository
└── README.md
```

## Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- No backend server required

## Setup

### Local Development

1. Clone the repository:
```bash
git clone <repository-url>
cd GamblingSuite-static
```

2. Open in your browser:
```bash
# Option 1: Direct file open
open index.html

# Option 2: Using a local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000
```

The application will be available in your browser immediately.

## Features

### Blackjack
- Practice mode to learn basic strategy
- Instant feedback on decisions
- Accuracy statistics

### Poker (Texas Hold'em)
- Current hand analysis
- Optimal strategy recommendations

## Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select `main` branch as source
4. Your app will be available at `https://yourusername.github.io/GamblingSuite-static`

### Static Hosting

This application can be deployed to any static hosting service:
- Netlify
- Vercel
- GitHub Pages
- AWS S3
- Any web server (Apache, Nginx, etc.)

## Development

### Running Tests

```bash
# Open index.html in browser and check console for any errors
```

### Building for Production

No build step required. The application is ready to deploy as-is.


## Contributing

Feel free to submit issues and enhancement requests!
