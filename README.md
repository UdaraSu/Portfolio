# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and a fully responsive layout that works on all devices.

## Features

- 🎨 **Modern Design** - Clean, professional UI with smooth animations
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - Optimized for performance
- 🎯 **Smooth Scrolling** - Enhanced navigation experience
- 💫 **Animations** - Engaging scroll animations and transitions
- 📧 **Contact Form** - Ready-to-use contact form (backend integration needed)
- 🌐 **SEO Friendly** - Proper meta tags and semantic HTML

## Sections

1. **Hero Section** - Eye-catching introduction with typing animation
2. **About** - Personal information and statistics
3. **Skills** - Technical skills and technologies organized by category
4. **Projects** - Showcase of featured projects with links
5. **Contact** - Contact information and form

## Getting Started

### Prerequisites

No prerequisites needed! This is a static website that runs directly in your browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

### Local Development

For a better development experience, you can use a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## Customization

### Personal Information

1. **Name and Title** - Edit the hero section in `index.html`:
   - Line 40: Change "Your Name"
   - Line 45: Update typing text array in `script.js` (line 60)

2. **About Section** - Update the about text in `index.html` (around line 100)

3. **Skills** - Modify the skills in `index.html` (around line 120)

4. **Projects** - Update project cards in `index.html` (around line 160):
   - Project titles and descriptions
   - Project links (GitHub and live demo)
   - Technology tags

5. **Contact Information** - Update contact details in `index.html` (around line 220):
   - Email address
   - Phone number
   - Location

6. **Social Links** - Update social media links in `index.html`:
   - Hero section (around line 55)
   - Footer (around line 260)

### Styling

- **Colors** - Modify CSS variables in `styles.css` (lines 5-15)
- **Fonts** - Change the Google Fonts import in `index.html` (line 10)

### Profile Image

Replace the placeholder icon with your actual photo:
1. Add your image to the project folder
2. Update the `.image-placeholder` div in `index.html` (around line 70) with an `<img>` tag

## Contact Form

The contact form is currently set up to show an alert on submission. To make it functional:

1. **Backend Integration** - Connect to a backend service (e.g., Formspree, EmailJS, or your own server)
2. **Update `script.js`** - Modify the form submission handler (around line 150) to send data to your service

Example with EmailJS:
```javascript
emailjs.send('service_id', 'template_id', formData)
    .then(() => alert('Message sent!'))
    .catch(() => alert('Error sending message'));
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## File Structure

```
Port/
├── index.html      # Main HTML file
├── styles.css      # All styles and animations
├── script.js       # JavaScript functionality
└── README.md      # This file
```

## Performance Tips

- Optimize images before adding them
- Consider using a CDN for fonts and icons (already implemented)
- Minify CSS and JS for production
- Enable gzip compression on your server

## License

This portfolio template is free to use for personal and commercial projects.

## Credits

- Fonts: [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)
- Icons: [Font Awesome](https://fontawesome.com/)

---

**Need help?** Feel free to customize this template to match your personal brand and style!

# Portfolio