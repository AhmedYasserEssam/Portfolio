# 🚀 Ahmed Emad - Data Science & Engineering Portfolio

A modern, responsive portfolio website showcasing Ahmed Emad's journey as a Data Science and Engineering student. Features a beautiful dark/light theme toggle, animated interactions, terminal-inspired design, and data science project showcases.

## ✨ Features

### 🎨 Design & UI
- **Modern, clean design** with a computer science theme
- **Terminal-inspired hero section** with typing animations
- **Dark/Light theme toggle** with smooth transitions
- **Fully responsive** - works on all devices
- **Smooth animations** and hover effects
- **Particle.js background** for visual appeal

### 📱 Sections Included
- **Home** - Hero section with terminal window and typing animation featuring Ahmed's name
- **About** - Data science biography with extensive technical skills in ML, data engineering, and AI
- **Projects** - Real projects: Orange Customer Service Chatbot, ETL Data Pipeline, Movie Recommendation System
- **Experience** - Orange Egypt internship, EUI education, DEPI Microsoft Data Engineer program, volunteering
- **Contact** - Contact form with Ahmed's real contact information and location

### 🛠 Interactive Features
- **Theme Toggle** - Switch between light and dark modes
- **Resume Download** - One-click resume download functionality
- **Smooth Scrolling** - Navigate between sections smoothly
- **Mobile Menu** - Responsive hamburger menu
- **Form Validation** - Contact form with validation
- **Scroll Animations** - Elements animate in on scroll
- **Active Navigation** - Auto-highlights current section

### 🎮 Easter Eggs
- **Konami Code** - Try entering the famous code!
- **Console Messages** - Check the browser console
- **Hover Animations** - Interactive elements throughout

## 🚀 Ahmed's Portfolio - Ready to View!

This portfolio is fully customized with Ahmed Emad's actual information:

✅ **Personalized Content:**
- Name: Ahmed Emad
- Role: Data Science & Engineering Student  
- Current Position: Data Science Intern @ Orange Egypt
- Location: Heliopolis, Cairo, Egypt
- Contact: ahmedyasser200580@gmail.com | +201067197511

✅ **Real Projects Showcased:**
- Orange Customer Service Chatbot (RAG, LLM Integration)
- End-to-End Retail Data Pipeline (Apache Airflow, ETL)
- Movie Recommendation System (Scala, Apache Spark)

✅ **Actual Experience:**
- Orange Egypt Data Science Internship
- EUI Computing & Information Sciences degree
- DEPI Microsoft Data Engineer program

3. **Customize the styling** in `styles.css` if needed:
   - Colors are defined in CSS custom properties at the top
   - Easy to change the color scheme
   - Fonts can be updated by changing the Google Fonts imports

4. **Add your resume**:
   - Replace the `resume.pdf` file with your actual resume
   - Or update the JavaScript to generate a custom resume format

5. **Deploy**:
   - Upload to any web hosting service
   - GitHub Pages, Netlify, or Vercel work great for static sites

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling and themes
├── script.js           # Interactive functionality
├── resume.pdf          # Your resume file
└── README.md           # This file
```

## 🎨 Customization Guide

### Colors
All colors are defined as CSS custom properties in `styles.css`:
```css
:root {
  --accent-primary: #3182ce;    /* Primary accent color */
  --accent-secondary: #63b3ed;  /* Secondary accent color */
  /* ... more colors */
}
```

### Content Updates
1. **Personal Info**: Update in the hero section and about section
2. **Skills**: Modify the skills grid in the about section
3. **Projects**: Replace with your actual projects
4. **Experience**: Update the tabs and content
5. **Social Links**: Add your real social media profiles

### Adding Projects
```html
<div class="project-card">
  <div class="project-header">
    <div class="project-folder">
      <i class="fas fa-folder"></i>
    </div>
    <div class="project-links">
      <a href="YOUR_GITHUB_LINK" class="project-link">
        <i class="fab fa-github"></i>
      </a>
      <a href="YOUR_LIVE_DEMO_LINK" class="project-link">
        <i class="fas fa-external-link-alt"></i>
      </a>
    </div>
  </div>
  <div class="project-content">
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">
      Description of your project...
    </p>
    <div class="project-tech">
      <span class="tech-tag">React</span>
      <span class="tech-tag">Node.js</span>
    </div>
  </div>
</div>
```

## 🔧 Technical Details

### Dependencies
- **Particles.js** - For animated background particles
- **Font Awesome** - For icons
- **Google Fonts** - Fira Code (monospace) and Inter (sans-serif)

### Browser Support
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Progressive enhancement - works without JavaScript

### Performance
- Optimized CSS with minimal external dependencies
- Efficient JavaScript with event delegation
- Responsive images and modern CSS techniques

## 🌟 Features in Detail

### Theme Toggle
- Automatic theme detection based on system preference
- Manual toggle with smooth transitions
- Theme preference saved in localStorage

### Typing Animation
- Multiple text strings rotation
- Realistic typing speed with pauses
- Blinking cursor animation

### Particle Background
- Interactive particle system
- Responds to mouse movement
- Optimized for performance

### Contact Form
- Form validation
- Success/error notifications
- Prevents spam with simple validation

## 📱 Mobile Optimization

- Responsive design works on all screen sizes
- Touch-friendly navigation
- Optimized images and fonts for mobile
- Fast loading times

## 🎯 SEO Ready

- Semantic HTML structure
- Meta tags ready for customization
- Fast loading times
- Mobile-friendly

## 📧 Support

If you need help customizing this portfolio or run into any issues:

1. Check the browser console for any JavaScript errors
2. Validate your HTML and CSS
3. Test on multiple browsers and devices
4. Feel free to modify and improve the code!

## 📄 License

This project is open source and available under the MIT License. Feel free to use it for your own portfolio!

---

**Made with ❤️ for the developer community**

Happy coding! 🎉
