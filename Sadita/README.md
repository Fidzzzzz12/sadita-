# Satwa Medika Utama - Obat Sapi Ternak

A modern landing page for cattle health products and services, converted from React to vanilla HTML/CSS/JavaScript.

## Features

- ✅ Responsive design with Tailwind CSS
- ✅ Modern UI/UX with red brand theme
- ✅ Product showcase with inline SVG images
- ✅ Customer testimonials
- ✅ Interactive FAQ section with accordion
- ✅ Smooth scrolling navigation
- ✅ Fast loading with optimized assets
- ✅ No external dependencies (except Tailwind CDN)

## Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (CDN)
- **Vanilla JavaScript** - Interactive features
- **Google Fonts** - Inter font family

## Getting Started

### Simple Method
1. Open `index.html` in a web browser
2. All content is self-contained in the HTML file

### Local Server (Recommended)
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000`

## Project Structure

```
Sadita/
├── index.html          # Main HTML file with all content
├── css/
│   └── custom.css      # Custom CSS styles and animations
├── js/
│   └── main.js         # Minimal JavaScript file
├── package.json        # Simplified for vanilla JS
└── README.md           # This file
```

## Sections Included

1. **Hero Section** - Main banner with call-to-action buttons
2. **Problem Section** - Common cattle farming issues with icons
3. **Solution Section** - Company introduction and approach
4. **Products Section** - Three main products (GIZCOW, TOP MINERAL, BIOMIX)
5. **Benefits Section** - Key advantages and benefits
6. **Testimonials Section** - Customer reviews and trust indicators
7. **FAQ Section** - Interactive accordion with common questions
8. **Footer** - Company information and copyright

## Interactive Features

- **FAQ Accordion** - Click to expand/collapse questions
- **Smooth Scroll** - Navigation links scroll smoothly to sections
- **Hover Effects** - Cards and buttons have hover animations
- **Responsive Design** - Works on mobile, tablet, and desktop
- **Loading Animations** - Fade-in effects on scroll

## Customization

### Changing Brand Colors
Edit the Tailwind config in `index.html`:
```javascript
colors: {
  brand: {
    50: '#faf5f5',
    100: '#f5ebeb',
    // ... change as needed
  }
}
```

### Adding Products
Edit the products section directly in `index.html` around line 300-500.

### Modifying Content
All content is now directly in `index.html`. Find the relevant section and edit the HTML.

## Performance Optimizations

- **Inline SVG Images** - No external image requests
- **CDN Resources** - Fast loading of Tailwind CSS and fonts
- **Minimal JavaScript** - Only essential interactive features
- **Optimized HTML** - Clean, semantic markup

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Conversion Notes

This project was successfully converted from a React + TypeScript application to vanilla HTML/CSS/JavaScript:

- ✅ All React components converted to static HTML
- ✅ JavaScript rendering replaced with direct HTML content
- ✅ External images replaced with inline SVG data URLs
- ✅ Interactive features preserved with vanilla JavaScript
- ✅ Maintained responsive design and animations
- ✅ Improved loading speed and reduced dependencies

## License

© 2026 PT. Satwa Medika Utama. All rights reserved.