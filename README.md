# VISCU-VIC - Industrial Insulation Company Website

Modern, responsive landing page for VISCU-VIC, a Czech industrial insulation company specializing in technical and industrial insulation of ventilation and piping systems.

## Project Structure

```
viscu-vic-website/
│
├── index.html          # Main HTML file
├── style.css           # All CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
│
└── images/             # Image folder
    ├── hero.jpg        # Hero section background
    ├── 16.jpg    # Gallery image 1
    ├── 17.jpg    # Gallery image 2
    ├── 18.jpg    # Gallery image 3
    ├── 19.jpg    # Gallery image 4
    ├── 20.jpg    # Gallery image 5
    ├── 21.jpg    # Gallery image 6
    ├── 22.jpg    # Gallery image 7
    ├── 23.jpg    # Gallery image 8
    ├── 24.jpg    # Gallery image 9
    └── 25.jpg   # Gallery image 10
    └── 26.jpg   # Gallery image 11
    └── 27.jpg   # Gallery image 12
    └── 28.jpg   # Gallery image 13
    └── 29.jpg   # Gallery image 14
    └── 30.jpg   # Gallery image 15
    └── 31.jpg   # Gallery image 16
    └── 32.jpg   # Gallery image 17
    └── 33.jpg   # Gallery image 18
    └── 34.jpg   # Gallery image 19
    └── 35.jpg   # Gallery image 20
    └── 36.jpg   # Gallery image 21
    └── 37.jpg   # Gallery image 22
    └── 38.jpg   # Gallery image 23
    └── 39.jpg   # Gallery image 24
    └── 40.jpg   # Gallery image 25
    └── 41.jpg   # Gallery image 26
    └── 42.jpg   # Gallery image 27
    └── 43.jpg   # Gallery image 28
    └── 44.jpg   # Gallery image 29
```

## Features

### Design

- Modern industrial aesthetic
- Dark blue, white, and gray color scheme
- Fully responsive (mobile, tablet, desktop)
- Smooth animations and transitions
- Professional B2B style

### Sections

1. **Navigation** - Sticky header with smooth scroll
2. **Hero Section** - Large hero with CTA and statistics
3. **About Section** - Company information and focus areas
4. **Services Section** - 6 service cards with icons
5. **Materials Section** - Material badges
6. **Why Choose Us** - 4 feature highlights
7. **Clients Section** - Partner companies
8. **Coverage Section** - Geographic coverage information
9. **Projects Gallery** - 10-image carousel with auto-slide
10. **Contact Section** - Contact information cards
11. **Footer** - Company info and branding

### Functionality

- Responsive mobile menu
- Smooth scroll navigation
- Auto-sliding image carousel
- Manual carousel controls (arrows, dots, keyboard)
- Touch/swipe support for mobile
- Scroll reveal animations
- Active navigation highlighting

## Setup Instructions

1. **Download all files** to your project folder

2. **Create an `images` folder** in the same directory

3. **Add your images** to the `images` folder:
   - `hero.jpg` - Industrial background (recommended: 1920x1080px)
   - `project1.jpg` through `project10.jpg` - Project photos (recommended: 1600x1000px)

4. **Open `index.html`** in a web browser

## Image Recommendations

For best results, use high-quality industrial images:

- **Hero image**: Wide industrial scene (pipes, ventilation, machinery)
- **Project images**:
  - HVAC systems
  - Industrial piping
  - Insulation work
  - Mechanical rooms
  - Technical installations

### Recommended Image Sources

- Unsplash.com (industrial, factory, pipes keywords)
- Pexels.com (hvac, industrial keywords)
- Your own project photos

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Colors

Edit CSS variables in `style.css`:

```css
:root {
  --primary-color: #2563eb;
  --primary-dark: #1d4ed8;
  --secondary-color: #1e293b;
  /* ... */
}
```

### Content

All content is in Czech language. To modify:

- Edit text directly in `index.html`
- Update section titles and descriptions

### Carousel Speed

Adjust auto-slide interval in `script.js`:

```javascript
autoSlideInterval = setInterval(nextSlide, 5000); // 5000ms = 5 seconds
```

## Performance Tips

1. Optimize images before uploading (use tools like TinyPNG)
2. Recommended image formats: WebP or JPEG
3. Keep images under 500KB each
4. Use lazy loading for images (already implemented)

## Contact Information

**VISCU-VIC**

- Address: Jirkov, Mládežnická 1646, 431 11
- Email: viscuvic@gmail.com
- Coverage: Ústecký kraj and all of Czech Republic

## Company Meaning

**VISCU:**

- V – Vzduch (Air)
- I – Izolace (Insulation)
- S – Systém (System)
- C – Celek (Whole)
- U – Úspora (Savings)

**VIC:**

- V – Voda (Water)
- I – Instalace (Installation)
- C – Kvalita (Quality)

## License

© 2024 VISCU-VIC. All rights reserved.

## Support

For technical support or questions about the website, contact: viscuvic@gmail.com