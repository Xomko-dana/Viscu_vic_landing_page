# 🏭 VISCU-VIC Website - Setup Guide

Complete industrial insulation company landing page ready to deploy!

## ✅ Files Created

```
viscu-vic-website/
├── index.html          ✓ Main HTML file
├── style.css           ✓ Complete CSS styles
├── script.js           ✓ JavaScript functionality
├── README.md           ✓ Documentation
├── SETUP-GUIDE.md      ✓ This file
└── images/             ✓ Image folder
```

## 🚀 Quick Start

### 1. Add Your Images

Place these images in the `images/` folder:

- **hero.jpg** - Industrial background (1920x1080px recommended)
- **project1.jpg** through **project10.jpg** - Project photos

### 2. Open the Website

Simply open `index.html` in your web browser:

```bash
# On Mac:
open index.html

# On Linux:
xdg-open index.html

# On Windows:
start index.html
```

Or just double-click `index.html` in your file explorer.

## 🌐 Deploying Online

### Free Hosting Options:

1. **Netlify** (Recommended)
   - Go to https://netlify.com
   - Drag and drop the entire `viscu-vic-website` folder
   - Get instant free hosting with HTTPS

2. **GitHub Pages**
   - Create a GitHub repository
   - Upload all files
   - Enable GitHub Pages in settings

3. **Vercel**
   - Go to https://vercel.com
   - Import your folder
   - Deploy in seconds

## ✏️ Customization

### Change Colors

Edit `style.css` at the top:

```css
:root {
  --primary-color: #2563eb; /* Change this for main color */
  --primary-dark: #1d4ed8; /* Darker version */
}
```

### Change Content

All text is in `index.html` - search and replace as needed.

### Change Carousel Speed

In `script.js`, find:

```javascript
autoSlideInterval = setInterval(nextSlide, 5000); // 5000 = 5 seconds
```

Change 5000 to any value in milliseconds.

## 📱 Features Included

✅ Fully responsive (mobile, tablet, desktop)
✅ Smooth scrolling navigation
✅ Auto-sliding project carousel
✅ Touch/swipe support for mobile
✅ Smooth animations
✅ Active navigation highlighting
✅ Keyboard navigation (arrow keys for carousel)
✅ SEO-friendly semantic HTML
✅ Modern industrial design
✅ Czech language throughout

## 🐛 Troubleshooting

**Images not showing?**

- Check that image files are in the `images/` folder
- Verify file names match exactly (case-sensitive)
- Check file extensions (.jpg, not .JPG or .jpeg)

**Menu not working on mobile?**

- Clear browser cache
- Try a different browser
- Check browser console for errors (F12)

**Carousel not auto-sliding?**

- Make sure JavaScript is enabled
- Check that script.js is in the same folder as index.html

## 📧 Contact Information

Update contact details in `index.html`:

- Line ~350: Email link
- Line ~330: Address
- Bottom footer: Company info

## 🎨 Design Philosophy

- **Modern Industrial**: Clean, professional, technical
- **Dark Theme**: Dark blue/gray with blue accents
- **Trustworthy**: B2B professional appearance
- **Minimalist**: Focus on content, not clutter

## 📄 Browser Support

✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid, Custom Properties
- **Vanilla JavaScript** - No frameworks needed
- **SVG Icons** - Crisp at any size
- **Responsive Images** - Optimized loading

## 📦 File Sizes

- index.html: ~22KB
- style.css: ~16KB
- script.js: ~6KB
- **Total (without images)**: ~44KB

Very lightweight and fast loading!

## 🎯 Next Steps

1. ✅ Add your images to `/images` folder
2. ✅ Customize contact information
3. ✅ Test on mobile and desktop
4. ✅ Deploy to hosting service
5. ✅ Share with customers!

---

**Created for VISCU-VIC**
Technické a průmyslové izolace
viscuvic@gmail.com

Built with ❤️ in Czech Republic
