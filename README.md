# Visit Taniti - Travel Destination Website

A simple HTML/CSS website for the travel destination "Visit Taniti" featuring four main pages: Home, Things To Do, Dining, and Plan Your Trip.

## Pages

- **Home** (`index.html`) - Main landing page with upcoming events
- **Things To Do** (`things-to-do.html`) - Entertainment, sights, and beaches
- **Dining** (`dining.html`) - Restaurants and bars information
- **Plan Your Trip** (`plan-your-trip.html`) - Travel information including air service, accommodations, and cruises

## GitHub Pages Setup

This repository is configured to work with GitHub Pages. To enable it:

1. Go to your repository on GitHub: `https://github.com/zprdarrell/Task1Prototype`
2. Click on **Settings** (in the repository navigation bar)
3. Scroll down to the **Pages** section in the left sidebar
4. Under **Source**, select:
   - **Branch**: `master` (or `main` if that's your default branch)
   - **Folder**: `/ (root)`
5. Click **Save**
6. GitHub will provide you with a URL like: `https://zprdarrell.github.io/Task1Prototype/`

Your site will be live at that URL within a few minutes!

## Local Development

Simply open any HTML file in your web browser, or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## File Structure

```
Task1Prototype/
├── index.html              # Home page
├── things-to-do.html       # Things To Do page
├── dining.html             # Dining page
├── plan-your-trip.html     # Plan Your Trip page
├── styles.css              # Shared stylesheet
└── README.md               # This file
```

