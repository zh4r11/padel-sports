# PadelSport Website 🏓

A beautiful, responsive multi-page website dedicated to the exciting world of Padel sport. Built with pure HTML, CSS, and JavaScript - no frameworks required!

## 🌟 Features

### Design & Layout
- **Modern & Elegant Design** - Clean layout with sporty yet sophisticated aesthetics
- **Responsive Design** - Perfect adaptation to desktop, tablet, and mobile screens
- **Elegant Color Palette** - Soft blue (#6fb3db), pastel green (#a8d5a8), white, and gray tones
- **Smooth Animations** - Fade-in effects and hover interactions throughout the site

### Pages Included
1. **Home** (`index.html`) - Hero section with call-to-action and sport overview
2. **About Padel** (`about.html`) - Complete guide to the sport, rules, and history
3. **Equipment** (`equipment.html`) - Comprehensive equipment guide and recommendations
4. **Clubs & Locations** (`clubs.html`) - Find courts and clubs with search functionality
5. **Gallery** (`gallery.html`) - Photo gallery with category filtering
6. **Contact** (`contact.html`) - Contact form and business information

### Interactive Features
- **Hamburger Menu** - Mobile-friendly navigation with smooth toggle
- **Active Page Highlighting** - Navigation automatically highlights current page
- **Scroll Animations** - Elements fade in as they come into view
- **Gallery Filtering** - Interactive photo filtering by category
- **Form Validation** - Real-time contact form validation
- **Back to Top Button** - Smooth scroll to top functionality
- **Notification System** - User feedback for form submissions

## 🚀 Getting Started

### Quick Setup
1. **Download/Clone** the project files
2. **Open** `index.html` in your web browser
3. **That's it!** No build process or dependencies required

### File Structure
```
padel-sport/
├── index.html              # Home page
├── about.html              # About Padel page
├── equipment.html          # Equipment guide
├── clubs.html              # Clubs & locations
├── gallery.html            # Photo gallery
├── contact.html            # Contact page
├── favicon.ico             # Website favicon
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   └── images/             # Image assets folder
├── js/
│   └── main.js             # JavaScript functionality
└── README.md               # This file
```

## 🎨 Customization

### Colors
The color palette is defined in CSS custom properties in `assets/css/style.css`:
```css
:root {
    --primary-color: #6fb3db;      /* Soft blue */
    --secondary-color: #a8d5a8;    /* Pastel green */
    --accent-color: #4a90b8;       /* Darker blue */
    --text-dark: #2c3e50;          /* Dark gray */
    --text-light: #7f8c8d;         /* Light gray */
    /* ... more variables */
}
```

### Adding Images
1. Place images in the `assets/images/` folder
2. Update the `src` attributes in HTML files
3. For hero sections, consider using high-quality sport photography

### Content Modification
- **Text Content**: Edit directly in the HTML files
- **Navigation**: Update the navigation menu in each HTML file
- **Styling**: Modify `assets/css/style.css`
- **Functionality**: Extend `js/main.js`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (full layout)
- **Tablet**: 768px - 1199px (adapted grid)
- **Mobile**: Below 768px (single column, hamburger menu)

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Semantic structure and accessibility
- **CSS3** - Advanced styling with Grid, Flexbox, and custom properties
- **Vanilla JavaScript** - No dependencies, pure ES6+

### Browser Support
- Chrome (recommended)
- Firefox
- Safari
- Edge
- Internet Explorer 11+ (with some feature limitations)

### Performance Features
- **Optimized CSS** - Efficient selectors and minimal reflow
- **Throttled Scroll Events** - Smooth scrolling without performance issues
- **Lazy Loading Ready** - Intersection Observer for animations
- **Lightweight** - No external dependencies

## 🎯 SEO & Accessibility

### SEO Features
- **Semantic HTML** - Proper heading hierarchy and structure
- **Meta Tags** - Descriptions and keywords for each page
- **Alt Text** - Ready for image descriptions
- **Structured URLs** - Clean, descriptive file names

### Accessibility
- **Keyboard Navigation** - Full keyboard support
- **Focus Management** - Visible focus indicators
- **Screen Reader Friendly** - Semantic HTML structure
- **Color Contrast** - WCAG compliant color combinations

## 🛠️ Customization Guide

### Adding a New Page
1. Create new HTML file (e.g., `tournaments.html`)
2. Copy the structure from an existing page
3. Update the navigation menu in all HTML files
4. Add the new page to the footer links
5. Update the active navigation highlighting in `js/main.js`

### Modifying the Gallery
1. Add new gallery items in `gallery.html`
2. Use the `data-category` attribute for filtering
3. Categories: `courts`, `action`, `tournaments`, `community`
4. The filtering is automatically handled by JavaScript

### Contact Form Integration
The contact form is ready for backend integration:
1. Update the `action` attribute in the form
2. Modify the JavaScript in `js/main.js` to send to your endpoint
3. The form includes validation and user feedback

## 🌐 Deployment

### Local Development
- Simply open `index.html` in a web browser
- Use a local server for testing (e.g., Python's `http.server`)

### Web Hosting
- Upload all files to your web hosting provider
- Ensure folder structure is maintained
- Update any absolute paths if necessary

### GitHub Pages
1. Push to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `username.github.io/repository-name`

## 📊 Analytics & Tracking

The website is ready for analytics integration:
- Add Google Analytics script before closing `</head>` tag
- Facebook Pixel can be added similarly
- Contact form submissions can be tracked as events

## 🎨 Design Credits

- **Color Palette**: Inspired by modern sports design trends
- **Typography**: System fonts for optimal loading and readability
- **Icons**: Emoji-based for universal compatibility
- **Layout**: CSS Grid and Flexbox for modern responsive design

## 📝 License

This project is open source and available under the MIT License. Feel free to use it for personal or commercial projects.

## 🤝 Contributing

Found a bug or have a feature request? Feel free to:
1. Open an issue
2. Submit a pull request
3. Suggest improvements

## 📞 Support

For questions about Padel or this website:
- Check the About Padel page for sport information
- Contact form is available on the Contact page
- Email: info@padelsport.com (example)

---

**Built with ❤️ for the global Padel community**

Enjoy exploring the exciting world of Padel! 🏓