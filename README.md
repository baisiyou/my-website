# Dr. Rubing Zhang - Personal Portfolio Website

A luxurious, modern, and responsive personal portfolio website showcasing research, publications, and professional experience.

## Features

- 🎨 **Modern & Luxurious Design**: Beautiful gradient backgrounds, smooth animations, and elegant typography
- 📱 **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- ✨ **Smooth Animations**: Intersection Observer-based animations for engaging user experience
- 🚀 **Fast & Lightweight**: Optimized for performance
- 🎯 **Easy Navigation**: Smooth scrolling with active section highlighting

## Sections

1. **Hero Section**: Eye-catching introduction with key statistics
2. **About Me**: Professional profile and highlights
3. **Research Interests**: Four main research areas
4. **Technical Skills**: Programming, tools, and instrumentation expertise
5. **Professional Experience**: Timeline of career progression
6. **Selected Projects**: Key AI and research projects
7. **Education**: Academic qualifications
8. **Publications**: Selected publications and patents
9. **Contact**: Contact information and contact form

## Getting Started

### Prerequisites

No prerequisites needed! This is a static website that runs directly in your browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser

That's it! The website is ready to use.

### Local Development

For a better development experience, you can use a local server:

#### Using Python (if installed):
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open `http://localhost:8000` in your browser.

#### Using Node.js (if installed):
```bash
npx http-server
```

#### Using PHP (if installed):
```bash
php -S localhost:8000
```

## File Structure

```
profolio_zrb/
│
├── index.html          # Main HTML file
├── styles.css          # All styling and animations
├── script.js           # JavaScript for interactivity
├── README.md           # This file
└── Cv_ai.txt          # Original CV data
```

## Customization

### Colors

Edit the CSS variables in `styles.css` to customize the color scheme:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... more variables */
}
```

### Content

Edit `index.html` to update:
- Personal information
- Experience details
- Projects
- Publications
- Contact information

### Contact Form

The contact form currently shows an alert when submitted. To make it functional, you'll need to:

1. Set up a backend service (e.g., Formspree, Netlify Forms, or your own server)
2. Update the form action in `index.html` or modify the JavaScript in `script.js` to send data to your backend

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox, Grid, and animations
- **JavaScript (ES6+)**: Interactivity and animations
- **Font Awesome**: Icons
- **Google Fonts**: Inter and Playfair Display fonts

## License

This portfolio website is created for personal use.

## Contact

**Dr. Rubing Zhang**
- Email: rb.zhang68@gmail.com
- Phone: 1-514-998-6168
- Address: 4225 Rue de l'Oural, Brossard QC J4Y0A3

---

Made with ❤️ for showcasing professional achievements and research contributions.

