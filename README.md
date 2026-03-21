# LT Landscape Website

A modern, responsive website for LT Landscape - a professional landscaping business.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with a nature-inspired color scheme
- **Smooth Animations**: Engaging scroll animations and transitions
- **Mobile Menu**: Hamburger menu for easy navigation on mobile devices
- **Contact Form**: Functional contact form with validation
- **Service Showcase**: Highlight your landscaping services
- **Gallery Section**: Display your work and projects
- **SEO Friendly**: Semantic HTML structure for better search engine optimization

## Sections

1. **Hero Section**: Eye-catching landing area with call-to-action buttons
2. **Services**: Showcase of landscaping services offered
3. **About**: Information about LT Landscape
4. **Gallery**: Portfolio of completed projects
5. **Contact**: Contact form and business information
6. **Footer**: Additional links and social media

## Getting Started

1. Open `index.html` in a web browser
2. No build process or dependencies required - it's a pure HTML/CSS/JavaScript website

If you host this project on GitHub Pages, the published site will be served directly from the files in this repository.

### Contact form (Formsubmit)

The form uses **[Formsubmit.co](https://formsubmit.co)** (free). **Visitors never need to confirm anything.** The first time someone submits, check **lt.landscape@yahoo.com** for a **one-time** email from Formsubmit to activate that address — after you click the link, future submissions arrive automatically.

## Customization

### Colors
Edit the CSS variables in `styles.css` to match your brand:
```css
:root {
    --primary-color: #2d5016;
    --secondary-color: #4a7c2a;
    --accent-color: #6b9f3d;
    /* ... */
}
```

### Contact Information
Update the contact details in `index.html`:
- Phone number
- Email address
- Service area

### Images
Replace the placeholder gallery items with your actual project photos:
- Add your images to an `images` folder
- Update the `gallery-placeholder` divs with `<img>` tags

### Form Submission
The contact form currently shows an alert. To make it functional:
1. Set up a backend service (e.g., Formspree, EmailJS, or your own server)
2. Update the form submission handler in `script.js`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 LT Landscape. All rights reserved.

