# Portfolio Website - Ganiye Basman

A modern, responsive single-page portfolio website showcasing web development projects.

## 📋 Overview

This portfolio website presents a clean and professional online presence for Ganiye Basman, a web developer. The site features a modern design with smooth animations and is fully responsive across all devices.

## 🎨 Features

- **Responsive Design:** Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI:** Clean, professional interface with gradient accents
- **Smooth Animations:** Interactive hover effects and fade-in animations
- **Project Showcase:** Display featured projects with descriptions and live view links
- **Accessibility:** Respects user preferences for reduced motion
- **Cross-Browser Compatible:** Works on all modern browsers

## 📁 File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── style.css          # Stylesheet with responsive design
└── README.md          # This file
```

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server required for local viewing

### How to Use

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. Click on **"View Live"** buttons to visit the projects

### Live Demo
The portfolio is live at: [Your Portfolio Link]

## 📱 Responsive Breakpoints

| Device | Screen Width | Layout |
|--------|------------|--------|
| Desktop | 769px+ | 2-column grid |
| Tablet | 481px - 768px | Single column |
| Mobile | ≤480px | Single column, optimized |

## 🎯 Sections

### 1. Header
- Displays your name and professional title
- Features an eye-catching gradient background
- Animated entrance effect

### 2. Projects Section
- Showcases featured projects in card format
- Each card includes:
  - Project title
  - Description
  - "View Live" button linking to the live project
- Hover effects for enhanced interactivity

**Featured Projects:**
- **Space Station Website** - HTML & CSS space layout exploration
- **Academy Cinemas** - Cinema landing page with Bootstrap/CSS

### 3. Footer
- Copyright notice
- Dark background for visual separation

## 🛠 Customization

### Add More Projects
To add additional project cards, insert the following code in the `projects-grid` div:

```html
<div class="project-card">
    <div class="project-content">
        <h3 class="project-title">Project Name</h3>
        <p class="project-description">
            Project description goes here.
        </p>
        <a href="https://your-project-url.com" class="btn btn-primary" target="_blank">
            View Live
        </a>
    </div>
</div>
```

### Customize Colors
Edit the CSS gradient colors in `style.css`:
- Change `#667eea` and `#764ba2` to your preferred colors
- Update the color scheme in the `:root` or directly in the styles

### Update Contact Information
- Modify the `footer` section to add social links or contact info
- Add new sections as needed (skills, about, contact form, etc.)

## 🎨 Design Highlights

- **Color Scheme:** Purple/Blue gradient (#667eea to #764ba2)
- **Font Family:** Segoe UI, system fallbacks
- **Layout:** CSS Grid with auto-fit
- **Spacing:** Consistent 40px gaps between cards
- **Shadow Effects:** Subtle shadows with hover enhancements

## ♿ Accessibility Features

- Semantic HTML structure
- ARIA-friendly button styling
- `rel="noopener noreferrer"` for external links
- Respects `prefers-reduced-motion` media query
- Proper contrast ratios for text readability

## 📊 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🔗 External Links

- [Space Station Website](https://gnysak-droid.github.io/SpaceStationWebS/)
- [Academy Cinemas](https://gnysak-droid.github.io/Academy-Cinemas-main3/)

## 📝 License

This project is open source and available for personal use.

## 👤 Author

**Ganiye Basman** - Web Developer

---

## 🚀 Deployment

### Deploy on GitHub Pages
1. Push this folder to a GitHub repository
2. Go to repository Settings → Pages
3. Select the branch and folder
4. Your site will be live at `https://username.github.io/repository-name/`

### Deploy on Other Platforms
- Netlify
- Vercel
- AWS S3
- Firebase Hosting

---

**Last Updated:** September 2024
