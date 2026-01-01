# 🎨 Almarai AI Demo Website

A professional static demo website showcasing AI-generated product visuals for the Almarai brand. This demo features a clean, modern design that maintains Almarai's corporate identity while demonstrating the potential of AI-generated product imagery.

![Almarai Demo](https://img.shields.io/badge/Status-Demo-green)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

- **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
- **Hero Slider**: Auto-playing carousel with smooth transitions and manual controls
- **Product Gallery**: Filterable product grid with category tabs
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Brand Authentic**: Maintains Almarai's official color palette and typography
- **Performance Optimized**: Lazy loading, debounced scroll events, and optimized assets
- **Accessibility**: Keyboard navigation, ARIA labels, and semantic HTML

## 🎯 Project Structure

```
almarai/
├── index.html                 # Main HTML file
├── css/
│   └── styles.css            # All styles and responsive design
├── js/
│   └── main.js               # JavaScript functionality
├── assets/
│   └── images/
│       ├── almarai-logo.svg  # Almarai logo
│       ├── hero-*.jpg        # Hero section images
│       ├── products/         # Product images
│       │   ├── milk-*.jpg
│       │   ├── juice-*.jpg
│       │   ├── cheese-*.jpg
│       │   └── yogurt-*.jpg
│       └── gallery/          # Gallery scene images
│           └── scene-*.jpg
├── IMAGE-SETUP-GUIDE.html    # Detailed guide for adding images
└── README.md                 # This file
```

## 🚀 Quick Start

### 1. Clone or Download

```bash
# If using Git
git clone <your-repo-url>
cd almarai

# Or simply download and extract the ZIP file
```

### 2. Add Your Images

**IMPORTANT**: The site currently uses placeholder image paths. You need to add your own images.

See **[IMAGE-SETUP-GUIDE.html](IMAGE-SETUP-GUIDE.html)** for detailed instructions on:
- Required image dimensions and specifications
- How to generate AI images
- Where to find stock photos
- Folder structure setup

### 3. Open the Site

Simply open `index.html` in your web browser:
```bash
# Windows
start index.html

# Mac
open index.html

# Linux
xdg-open index.html
```

Or use a local development server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit: `http://localhost:8000`

## 🎨 Brand Colors

The design uses Almarai's official brand colors:

| Color | Hex Code | Usage |
|-------|----------|-------|
| Primary Green | `#006633` | Buttons, headers, accents |
| Dark Green | `#004d26` | Hover states, depth |
| White | `#FFFFFF` | Background, text on dark |
| Cream | `#FAF8F5` | Section backgrounds |
| Text Primary | `#1A1A1A` | Main content text |
| Text Secondary | `#666666` | Descriptions, captions |

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile Landscape**: 481px - 767px
- **Mobile Portrait**: 480px and below

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `css/styles.css`:

```css
:root {
    --color-primary: #006633;
    --color-primary-dark: #004d26;
    /* ... more colors */
}
```

### Adding More Products

1. Add product HTML in `index.html` within `.products-grid`
2. Follow the existing product card structure
3. Add appropriate `data-category` attribute for filtering

### Adjusting Hero Slider Speed

In `js/main.js`, find and modify:

```javascript
slideInterval = setInterval(nextSlide, 5000); // Change 5000 to desired milliseconds
```

## 🌐 Deployment to Netlify

### Option 1: Drag and Drop
1. Visit [netlify.com](https://netlify.com)
2. Create an account (free)
3. Drag your project folder to the deployment zone
4. Done! Your site is live

### Option 2: GitHub Integration
1. Push your code to a GitHub repository
2. Connect repository to Netlify
3. Netlify auto-deploys on every push

### Build Settings
No build process needed! This is a static site.
- **Build command**: (leave empty)
- **Publish directory**: `.` (root)

## ✅ Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📦 What's Included

### HTML Features
- Semantic HTML5 structure
- SEO-friendly meta tags
- Accessibility attributes (ARIA labels)
- Open Graph tags ready

### CSS Features
- Modern CSS3 with CSS Grid and Flexbox
- CSS custom properties (variables)
- Smooth transitions and animations
- Mobile-first responsive design

### JavaScript Features
- Vanilla JavaScript (no dependencies)
- Auto-playing hero slider with controls
- Product filtering system
- Smooth scroll navigation
- Scroll-triggered animations
- Lazy loading images
- Touch/swipe support for mobile
- Keyboard navigation

## 🔒 Important Legal Note

**Demo Disclaimer**: This is a demonstration website showcasing AI-generated product visuals. 

- Almarai® and its logo are registered trademarks of Almarai Company
- This demo is **NOT** affiliated with or endorsed by Almarai Company
- All product images should be AI-generated or properly licensed
- Use for demonstration and portfolio purposes only
- Do not use for commercial purposes without proper authorization

## 📝 TODO / Enhancement Ideas

- [ ] Add more product categories
- [ ] Implement lightbox for gallery images
- [ ] Add product quick view modal
- [ ] Create loading animations
- [ ] Add more language support (Arabic)
- [ ] Implement search functionality
- [ ] Add newsletter subscription form
- [ ] Create additional page templates
- [ ] Add video backgrounds option
- [ ] Implement dark mode toggle

## 🛠️ Technical Stack

- **HTML5**: Structure and content
- **CSS3**: Styling and animations
- **Vanilla JavaScript**: Interactivity and functionality
- **No frameworks**: Pure, lightweight code
- **No build tools**: Works out of the box

## 📊 Performance Tips

1. **Optimize Images**: Compress all images before adding them
2. **Use WebP**: Convert images to WebP format for better compression
3. **CDN**: Consider using a CDN for faster global delivery
4. **Caching**: Enable browser caching for static assets
5. **Minify**: Minify CSS and JS for production

## 🤝 Contributing

This is a demo project. Feel free to:
- Fork and modify for your own purposes
- Report issues or suggest improvements
- Use as a template for similar projects

## 📄 License

This demo code is provided as-is for demonstration purposes.

**Important**: 
- The Almarai brand, logo, and trademarks belong to Almarai Company
- Any images you add must be properly licensed or AI-generated
- This demo should not be used commercially without authorization

## 💡 Credits

- **Design Inspiration**: L'Oréal Paris demo website
- **Brand**: Almarai (for educational/demo purposes only)
- **Development**: Custom HTML/CSS/JS implementation

## 📞 Support

For questions about this demo:
- Open an issue in the repository
- Check the IMAGE-SETUP-GUIDE.html for image help
- Review the code comments for implementation details

---

**Built with ❤️ for demonstration purposes**

*This is a demo website showcasing AI-generated visuals. All trademarks belong to their respective owners.*
