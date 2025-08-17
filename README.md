# 🚀 Portfolio Website - About Me + Resume

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, dark/light mode toggle, and is ready for GitHub Pages hosting.

## ✨ Features

- **Modern Landing Section** with animated hero content and floating cards
- **About Me Section** with profile photo and highlights
- **Skills Section** with categorized skill items and hover effects
- **Experience Timeline** with interactive timeline design
- **Projects Section** with project cards and overlay effects
- **Contact Section** with form and social links
- **Dark/Light Mode Toggle** with persistent storage
- **Responsive Design** for mobile, tablet, and desktop
- **Smooth Animations** and scroll effects
- **Mobile Navigation** with hamburger menu

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables and Grid/Flexbox
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter font family)

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # CSS styles and animations
├── script.js           # JavaScript functionality
├── resume.pdf          # Your resume (add your own)
└── README.md           # This file
```

## 🚀 Quick Start

1. **Download the files** to your local machine
2. **Customize the content** (see customization section below)
3. **Add your resume** - Replace `resume.pdf` with your actual resume
4. **Test locally** - Open `index.html` in your browser
5. **Deploy to GitHub Pages** (see deployment section)

## 🎨 Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

```html
<!-- Replace "Your Name" with your actual name -->
<title>Your Name - Portfolio</title>
<h1 class="hero-title">
    <span class="gradient-text">Your Name</span>
</h1>

<!-- Update tagline -->
<p class="hero-subtitle">Data Scientist & AI Enthusiast</p>

<!-- Update description -->
<p class="hero-description">
    Your personal description here...
</p>
```

### 2. Profile Photo

Replace the placeholder image in the About section:

```html
<!-- Replace with your actual photo -->
<img src="path/to/your/photo.jpg" alt="Your Name" class="profile-image">
```

### 3. About Section

Update the about text and highlights:

```html
<h3>Hello! I'm Your Name</h3>
<p>Your personal bio here...</p>

<!-- Update highlights -->
<div class="highlight-item">
    <i class="fas fa-graduation-cap"></i>
    <span>Your Degree</span>
</div>
```

### 4. Skills

Modify the skills in `index.html`:

```html
<div class="skill-item" data-skill="Your Skill">
    <i class="fab fa-your-icon"></i>
    <span>Your Skill</span>
</div>
```

### 5. Experience

Update the timeline items with your work experience:

```html
<div class="timeline-item" data-aos="fade-up">
    <div class="timeline-date">Your Date Range</div>
    <h3>Your Job Title</h3>
    <h4>Company Name</h4>
    <p>Your job description...</p>
    <div class="timeline-tags">
        <span class="tag">Skill 1</span>
        <span class="tag">Skill 2</span>
    </div>
</div>
```

### 6. Projects

Update the project cards with your actual projects:

```html
<div class="project-card" data-aos="fade-up">
    <div class="project-image">
        <img src="path/to/project/image.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="your-github-repo" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
                <a href="your-live-demo" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 7. Contact Information

Update your contact details:

```html
<a href="mailto:your.email@example.com" class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank" class="contact-method">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
</a>
<a href="https://github.com/yourusername" target="_blank" class="contact-method">
    <i class="fab fa-github"></i>
    <span>GitHub</span>
</a>
```

### 8. Colors and Theme

Customize colors in `style.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #10b981;    /* Secondary color */
    --accent-color: #f59e0b;       /* Accent color */
    /* ... other colors */
}
```

## 🌐 Deployment to GitHub Pages

### Option 1: Simple Repository

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click Save

### Option 2: User/Organization Site

1. Create a repository named `username.github.io`
2. Upload all files to the repository
3. Your site will be available at `https://username.github.io`

### Option 3: Project Site

1. Create a repository for your project
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at `https://username.github.io/repository-name`

## 📱 Responsive Design

The website is fully responsive and includes:

- **Mobile-first approach** with breakpoints at 768px and 480px
- **Touch-friendly interactions** for mobile devices
- **Optimized navigation** with hamburger menu for mobile
- **Flexible layouts** that adapt to different screen sizes

## 🎭 Animations and Effects

- **Scroll-triggered animations** using Intersection Observer
- **Smooth transitions** and hover effects
- **Parallax scrolling** for floating cards
- **Typing animation** for hero title
- **Fade-in effects** for sections and elements

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Customization Tips

1. **Keep it professional** - Use high-quality images and professional language
2. **Highlight achievements** - Focus on quantifiable results in your experience
3. **Update regularly** - Keep your portfolio current with new projects and skills
4. **Test thoroughly** - Check your site on different devices and browsers
5. **Optimize images** - Compress images for faster loading

## 🚀 Performance Features

- **Lazy loading** for images
- **Debounced scroll events** for better performance
- **CSS animations** instead of JavaScript where possible
- **Optimized transitions** with hardware acceleration

## 📞 Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS variables for easy color changes
3. Modify the JavaScript functions as needed
4. Test changes in your browser's developer tools

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🎉**

Your portfolio website is now ready to showcase your skills and experience to the world!
