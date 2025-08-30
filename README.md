# Personal Resume Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and experience as a computer science student or developer.

## Features

- 🎨 Modern and clean design
- 📱 Fully responsive (mobile-friendly)
- ⚡ Smooth animations and transitions
- 🖼️ Project showcase with image support
- 📧 Contact form with validation
- 🎯 Smooth scrolling navigation
- 🌙 Professional color scheme
- 📊 Skills and statistics display

## Getting Started

### 1. Customize Personal Information

Edit the `index.html` file to update your personal information:

#### Update the title and meta information:
```html
<title>Your Name - Computer Science Student</title>
```

#### Update the hero section:
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
<h2 class="hero-subtitle">Computer Science Student & Developer</h2>
```

#### Update the navigation logo:
```html
<div class="nav-logo">
    <a href="#home">Your Name</a>
</div>
```

#### Update education information:
```html
<div class="education-item">
    <h4>Bachelor of Science in Computer Science</h4>
    <p>Your University Name • Expected Graduation: 2024</p>
</div>
```

#### Update contact information:
```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-item">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-item">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, State</span>
</div>
```

### 2. Add Your Profile Picture

Replace the placeholder profile image in the hero section:

1. Add your profile picture to the project directory (e.g., `images/profile.jpg`)
2. Replace the placeholder div with an actual image:

```html
<div class="hero-image">
    <img src="images/profile.jpg" alt="Your Name" class="profile-image">
</div>
```

3. Add CSS for the profile image in `styles.css`:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

### 3. Customize Your Projects

#### Add Project Images

1. Create an `images` folder in your project directory
2. Add your project screenshots or images
3. Update the project cards in `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <img src="images/project1.jpg" alt="E-Commerce Platform">
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="your-demo-link" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
        </div>
    </div>
</div>
```

#### Update Project Information

For each project, update:
- Project name
- Project description
- Technologies used
- GitHub repository link
- Live demo link

### 4. Customize Skills

Update the skills section to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-python"></i>
    <span>Python</span>
</div>
```

Available Font Awesome icons for skills:
- `fab fa-python` - Python
- `fab fa-java` - Java
- `fab fa-js-square` - JavaScript
- `fab fa-react` - React
- `fab fa-node-js` - Node.js
- `fab fa-html5` - HTML5
- `fab fa-css3-alt` - CSS3
- `fab fa-git-alt` - Git
- `fab fa-github` - GitHub
- `fab fa-docker` - Docker
- `fas fa-database` - SQL

### 5. Update Statistics

Modify the statistics in the about section:

```html
<div class="stat-item">
    <h3>10+</h3>
    <p>Projects Completed</p>
</div>
```

### 6. Customize Social Links

Update the social media links in the contact section:

```html
<div class="social-links">
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <a href="your-instagram-url" class="social-link"><i class="fab fa-instagram"></i></a>
</div>
```

## File Structure

```
resume-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Add your images here
    ├── profile.jpg     # Your profile picture
    ├── project1.jpg    # Project screenshots
    ├── project2.jpg
    └── ...
```

## Customization Tips

### Colors
The website uses a modern color scheme. You can customize colors in `styles.css`:

- Primary blue: `#2563eb`
- Secondary blue: `#1d4ed8`
- Accent yellow: `#fbbf24`
- Dark text: `#1f2937`
- Light text: `#6b7280`

### Fonts
The website uses Inter font from Google Fonts. You can change it by updating the font import in `index.html` and the font-family in `styles.css`.

### Animations
The website includes smooth animations. You can adjust animation timing and effects in `styles.css` and `script.js`.

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed instantly
3. You'll get a custom URL

### Vercel
1. Connect your GitHub repository to Vercel
2. Vercel will automatically deploy your site
3. You'll get a custom URL

## Performance Optimization

- Optimize images before adding them (use tools like TinyPNG)
- Consider using WebP format for better compression
- Minimize CSS and JavaScript files for production

## SEO Optimization

- Update meta tags in the `<head>` section
- Add Open Graph tags for social media sharing
- Include a sitemap.xml file
- Add structured data markup

## Contact Form

The contact form currently shows a success message. To make it functional:

1. Use a form service like Formspree, Netlify Forms, or EmailJS
2. Or implement a backend solution with Node.js, PHP, or Python

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your website, feel free to:
- Check the comments in the code
- Refer to this README
- Look up HTML, CSS, and JavaScript documentation

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community!
