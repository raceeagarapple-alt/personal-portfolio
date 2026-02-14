# Race Eagar's Personal Website

A beautiful, modern personal portfolio website built with HTML, CSS, and JavaScript.

## Features

- 🎨 **Modern Design**: Clean, gradient-based design with smooth animations
- 📱 **Fully Responsive**: Works perfectly on all devices (desktop, tablet, mobile)
- ⚡ **Interactive Elements**: Hover effects, smooth scrolling, and micro-interactions
- 🌙 **Dark/Light Mode Ready**: CSS variables for easy theme switching
- 🎯 **SEO Optimized**: Semantic HTML5 structure
- 🚀 **Performance Optimized**: Minimal dependencies and fast loading

## Sections

- **Hero**: Eye-catching introduction with call-to-action
- **About**: Personal information and statistics
- **Projects**: Showcase of featured work with tech stacks
- **Skills**: Technical skills and technologies
- **Contact**: Contact form and social links

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter)

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

## Customization

### Personal Information

Edit the following in `index.html`:

- Your name in the hero section
- Contact information in the contact section
- Project details and links
- Skills and technologies

### Colors

Modify CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... other variables */
}
```

### Adding Projects

To add new projects, duplicate the project-card structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder">
            <i class="fas fa-your-icon"></i>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Title</h3>
        <p class="project-description">Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
            <!-- more tags -->
        </div>
        <div class="project-links">
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="#" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

## Interactive Features

- **Mobile Navigation**: Hamburger menu for mobile devices
- **Smooth Scrolling**: Navigation links scroll smoothly to sections
- **Scroll Animations**: Elements fade in as you scroll
- **Parallax Effects**: Hero section has subtle parallax scrolling
- **Form Handling**: Contact form with success notifications
- **Easter Egg**: Try the Konami code! (↑↑↓↓←→←→BA)
- **Mouse Trail**: Subtle cursor trail effect for extra interactivity

## Browser Support

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Deployment

This website can be deployed to any static hosting service:

- Netlify
- Vercel
- GitHub Pages
- AWS S3
- Firebase Hosting

Simply upload the files and your site will be live!

## License

This project is open source and available under the [MIT License](LICENSE).

---

Built with ❤️ by Race Eagar
