# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Modern Design** - Clean, professional look with smooth animations
- **Fully Responsive** - Works on all devices (desktop, tablet, mobile)
- **Smooth Scrolling** - Navigation links scroll smoothly to sections
- **Interactive Elements** - Hover effects, skill bars, project cards
- **Contact Form** - Working form with validation
- **Dark/Light Theme** - Modern dark hero section with light content

## Sections

1. **Home** - Hero section with name, title, and social links
2. **About** - Personal information and stats
3. **Skills** - Technical skills with progress bars
4. **Projects** - Portfolio of your work
5. **Contact** - Contact form and information

## How to Customize

### 1. Personal Information

Open `index.html` and update:

- **Name**: Search for "Your Name" and replace
- **Title**: Search for "Professional Title" and replace
- **Tagline**: Update the tagline text
- **Stats**: Modify years experience, projects, clients numbers

### 2. Social Links

In `index.html`, find the social links section and update `href="#"` with your actual profile URLs:

```html
<a href="https://github.com/yourusername" target="_blank">
<a href="https://linkedin.com/in/yourusername" target="_blank">
<a href="https://twitter.com/yourusername" target="_blank">
```

### 3. Skills

In `index.html`, modify the skills section:

```html
<div class="skill-card">
    <i class="fab fa-html5"></i>
    <h3>HTML5</h3>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 95%"></div>
    </div>
    <span class="skill-percentage">95%</span>
</div>
```

- Change the icon class (e.g., `fa-html5`, `fa-react`, `fa-python`)
- Update the skill name and percentage
- Adjust the `style="width: XX%"` to match your proficiency

### 4. Projects

In `index.html`, update each project card:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Project One</h3>
        <p>Your project description here...</p>
        <div class="project-tags">
            <span>React</span>
            <span>Node.js</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourproject" target="_blank">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://yourproject.com" target="_blank">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

### 5. Contact Information

In `index.html`, update the contact section:

```html
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <div>
        <h3>Email</h3>
        <p>your.email@example.com</p>
    </div>
</div>
```

### 6. Colors

In `styles.css`, modify the CSS variables:

```css
:root {
    --primary-color: #2563eb;      /* Main accent color */
    --primary-dark: #1d4ed8;       /* Darker shade */
    --secondary-color: #10b981;    /* Secondary color */
    --dark-color: #1e293b;         /* Text color */
    --light-color: #f8fafc;        /* Background color */
}
```

### 7. Profile Image

Replace the image placeholder in the About section:

```html
<div class="about-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
</div>
```

Add to CSS:
```css
.profile-photo {
    width: 100%;
    border-radius: 20px;
    object-fit: cover;
}
```

## Icons

This portfolio uses Font Awesome icons. Available icons:
- https://fontawesome.com/icons

## Fonts

Uses Google Fonts (Poppins). Change in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

## Deployment

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Push your files
3. Go to Settings → Pages
4. Select main branch and save

### Option 2: Netlify
1. Drag and drop your project folder to Netlify
2. Your site will be deployed automatically

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project folder

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT License - Feel free to use this portfolio for your personal website!

---

**Note**: This is a template portfolio. Make sure to replace all placeholder content with your actual information before deploying.