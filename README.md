# Shahad Al Khaleejs Trading Company Website

A modern, responsive website for Shahad Al Khaleejs Trading Company - a leading construction and industrial services company in Saudi Arabia.

## Features

- 🌐 Bilingual support (English/Arabic)
- 📱 Fully responsive design
- 🎨 Modern UI/UX with smooth animations
- 📋 Management structure organogram
- 📸 Photo gallery
- 📜 Certificates showcase
- 📞 Contact information

## Tech Stack

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid)
- JavaScript (Vanilla JS)
- Bootstrap 5.3
- Bootstrap Icons

## CI/CD Pipeline

[![Deploy to GitHub Pages](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/deploy.yml/badge.svg)](https://github.com/YOUR_USERNAME/YOUR_REPO/actions/workflows/deploy.yml)

This project uses GitHub Actions for continuous integration and deployment:

- **Validation**: Automatically validates HTML, CSS, and JavaScript files
- **Deployment**: Automatically deploys to GitHub Pages on push to main branch

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
   cd YOUR_REPO
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

3. Visit `http://localhost:8000` in your browser

## Deployment

The website is automatically deployed to GitHub Pages when changes are pushed to the `main` branch.

To manually trigger deployment:
1. Go to Actions tab in GitHub
2. Select "Deploy to GitHub Pages" workflow
3. Click "Run workflow"

## Project Structure

```
.
├── index.html          # Main HTML file
├── style.css          # Main stylesheet
├── main.js            # Main JavaScript file
├── logo.png           # Company logo
├── certificates/     # Certificate images
├── .github/
│   └── workflows/
│       └── deploy.yml # CI/CD pipeline
└── README.md          # This file
```

## License

Copyright © 2025 Shahad Al Khaleejs Trading Company. All Rights Reserved.
