# WSS Personal Website

Modern personal website for Wildan Safaat Sutisna (WSS) - A complete portfolio and business website with bilingual support.

## Features

- 🌍 **Bilingual Support**: Full Indonesian/English language toggle
- 📱 **Responsive Design**: Mobile-first approach with Bootstrap 5
- 🎨 **Modern UI**: Clean, professional design with smooth animations
- 💼 **Portfolio Showcase**: Dedicated portfolio section with detailed project pages
- 📧 **Contact Integration**: Contact form and social media links
- 🎯 **SEO Optimized**: Proper meta tags and semantic HTML structure
- ⚡ **Performance**: Optimized assets and clean code

## Project Structure

```
WSS Web/
├── index.html              # Main homepage
├── portfolio.html          # Portfolio gallery page
├── portfolio-detail.html   # Dynamic portfolio detail page
├── 404.html               # Custom 404 error page
├── .htaccess              # Apache configuration
├── README.md              # Project documentation
└── assets/
    ├── css/
    │   ├── style.css         # Main stylesheet
    │   ├── portfolio.css     # Portfolio page styles
    │   └── portfolio-detail.css # Portfolio detail styles
    └── img/
        ├── profile.svg       # Profile avatar
        ├── about.svg         # About section image
        ├── project1-3.svg    # Main project thumbnails
        ├── blog1-3.svg       # Blog post images
        ├── client1-3.svg     # Client avatars
        ├── cta-image.png     # Call-to-action image
        └── portfolio/
            ├── *.jpg         # Project preview images
            ├── *-main.svg    # Project main detail images
            ├── *-gallery-*.svg # Project gallery images
            └── *-next.svg    # Next project preview images
```

## Pages Overview

### Homepage (index.html)
- Hero section with call-to-action
- Services showcase
- Portfolio preview with "View All" link
- About section
- Client testimonials
- FAQ section
- Blog preview
- Contact form

### Portfolio Page (portfolio.html)
- Project filtering (All, Web Design, Mobile Apps, Branding)
- Project grid with hover effects
- Pagination support
- Call-to-action section

### Portfolio Detail Page (portfolio-detail.html)
- Dynamic content loading based on URL parameters
- Project hero with image and CTA buttons
- Image gallery with responsive grid
- Process/methodology section
- Next project preview
- Breadcrumb navigation

## Projects Included

1. **KeyBoard** - Mechanical keyboard e-commerce platform
2. **SOFA** - Furniture design and sales website
3. **Work Media** - Digital marketing agency platform
4. **DDDone** - Task management application
5. **HandP** - Mobile messaging application

## Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with custom properties
- **Bootstrap 5**: Responsive framework
- **JavaScript**: Interactive functionality and language switching
- **SVG**: Scalable vector graphics for crisp visuals
- **Google Fonts**: Inter font family
- **Bootstrap Icons**: Icon library

## Language Support

The website supports both English and Indonesian languages with a convenient toggle button. All content including:
- Navigation menus
- Page content
- Button labels
- Form placeholders
- Project descriptions

## Getting Started

1. Clone or download the project files
2. Serve the files using any web server (Apache, Nginx, or Python's built-in server)
3. Open index.html in your browser

### Local Development

```bash
# Using Python's built-in server
python3 -m http.server 8000

# Or using PHP's built-in server
php -S localhost:8000

# Then open http://localhost:8000 in your browser
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Customization

### Adding New Projects
1. Add project images to `assets/img/portfolio/`
2. Update the projects array in `portfolio-detail.html`
3. Add project thumbnail to `portfolio.html`

### Language Updates
1. Modify the `translations` object in each HTML file
2. Add `data-lang` attributes to new content elements

### Styling Changes
1. Main styles: `assets/css/style.css`
2. Portfolio specific: `assets/css/portfolio.css`
3. Detail page specific: `assets/css/portfolio-detail.css`

## Contact

For questions or support, please contact Wildan Safaat Sutisna through the contact form on the website.

---

© 2024 Wildan Safaat Sutisna. All rights reserved.
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Performance Optimized**: Compressed assets and optimized loading
- **Custom 404 Page**: Beautiful error page with interactive elements
- **Contact Form**: Working contact form (backend integration needed)

## 📁 Project Structure

```
WSS Web/
├── index.html              # Main homepage
├── 404.html               # Custom 404 error page
├── .htaccess              # Apache configuration
└── assets/
    ├── css/
    │   └── style.css      # Custom CSS styles
    └── img/
        └── README.md      # Image requirements guide
```

## 🎨 Sections Included

1. **Hero Section** - Eye-catching introduction with profile card
2. **Services** - What you offer (Design & Development)
3. **Portfolio** - Latest work showcase
4. **About** - Professional background and stats
5. **Call-to-Action** - Engagement sections
6. **Testimonials** - Client feedback
7. **FAQ** - Frequently asked questions
8. **Blog** - Latest articles
9. **Contact** - Contact form and information
10. **Footer** - Links and social media

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom styles with modern features
- **Bootstrap 5** - Responsive framework
- **Bootstrap Icons** - Icon library
- **Google Fonts** - Inter font family
- **JavaScript** - Interactive functionality

## 🎯 Setup Instructions

### 1. Image Setup
Add your images to the `assets/img/` folder:
- `profile.jpg` - Your profile photo
- `about.jpg` - Professional photo
- `project1.jpg`, `project2.jpg`, `project3.jpg` - Portfolio images
- `blog1.jpg`, `blog2.jpg`, `blog3.jpg` - Blog images
- `client1.jpg`, `client2.jpg`, `client3.jpg` - Client avatars

### 2. Content Customization
Update the following in `index.html`:
- **Personal Information**: Name, title, bio, contact details
- **Services**: Modify service descriptions
- **Portfolio**: Update project titles, descriptions, and links
- **About Section**: Personal story and statistics
- **Testimonials**: Real client feedback
- **Blog**: Your latest articles
- **Contact**: Your actual contact information

### 3. Styling Customization
Modify `assets/css/style.css` to:
- Change color scheme (update CSS variables)
- Adjust fonts and typography
- Modify spacing and layout
- Add custom animations

### 4. Local Development
- Open `index.html` in your browser
- Use a local server for testing (recommended)
- Validate responsive design on different screen sizes

### 5. Deployment
Upload all files to your web hosting:
- Ensure folder structure is maintained
- Test all links and functionality
- Verify 404 page works correctly

## 🎨 Customization Guide

### Color Scheme
The website uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #8b5cf6;    /* Secondary brand color */
    --accent-color: #f59e0b;       /* Accent color */
    --dark-bg: #1e1b4b;           /* Dark background */
    --light-bg: #f8fafc;          /* Light background */
}
```

### Typography
The website uses the Inter font family. To change fonts:
1. Update the Google Fonts link in HTML
2. Modify the font-family in CSS

### Layout
- Bootstrap grid system for responsive layout
- Custom CSS for specific design elements
- Flexbox for component alignment

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and up
- **Tablet**: 768px to 1199px
- **Mobile**: 767px and below

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📈 Performance Features

- Compressed CSS and optimized images
- Lazy loading for better performance
- Minified external libraries
- Efficient CSS animations

## 🚀 Future Enhancements

- [ ] Add dark/light mode toggle
- [ ] Implement contact form backend
- [ ] Add blog functionality
- [ ] Integrate analytics
- [ ] Add PWA features
- [ ] Implement content management

## 📞 Support

For any questions or customization help, contact Wildan Safaat Sutisna:
- Email: wildan@example.com
- Phone: +62 812 3456 7890

## 📄 License

This project is created for personal use. Feel free to use as inspiration for your own projects.

---

**Built with ❤️ by Wildan Safaat Sutisna**
