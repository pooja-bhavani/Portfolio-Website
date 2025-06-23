# Personal Portfolio Website

A clean, responsive, and accessible personal portfolio website built with HTML, CSS, and JavaScript. Features a dark theme by default with smooth animations and a professional link showcase.

## 🌟 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Dark Theme**: Modern dark theme with beautiful gradients and colors
- **Smooth Animations**: Subtle scroll animations and hover effects
- **Accessibility**: Full keyboard navigation and screen reader support
- **Performance Optimized**: Lightweight and fast-loading
- **Clean Code**: Well-commented and easy to customize

## 🚀 Quick Start

1. Clone or download the files
2. Customize the content in `index.html`
3. Update your personal information and links
4. Add your profile picture
5. Open `index.html` in your browser

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🎨 Customization Guide

### Personal Information
Edit the following sections in `index.html`:

```html
<!-- Update your name and title -->
<h1 class="hero-title">Your Name</h1>
<p class="hero-subtitle">Full Stack Developer & Designer</p>

<!-- Update your bio -->
<p class="hero-description">
    Your personal introduction goes here...
</p>
```

### Profile Picture
Replace the placeholder image URL in the `src` attribute:
```html
<img src="your-profile-picture.jpg" alt="Profile Picture" id="profile-pic">
```

### Social Links
Update the `href` attributes in the link cards:
```html
<!-- Example: GitHub link -->
<a href="https://github.com/yourusername" class="link-card" target="_blank">
```

### Colors and Styling
Customize the color scheme by modifying CSS variables in `styles.css`:
```css
:root {
    --bg-primary: #0f0f23;        /* Main background */
    --accent-primary: #4f46e5;     /* Primary accent color */
    --text-primary: #e2e8f0;       /* Main text color */
    /* ... more variables */
}
```

## 🔗 Adding New Links

To add a new link card, copy this template and customize:

```html
<a href="your-link-here" class="link-card" target="_blank" rel="noopener noreferrer">
    <div class="link-icon your-custom-class">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="link-content">
        <h3>Platform Name</h3>
        <p>Description of the link</p>
    </div>
    <div class="link-arrow">
        <i class="fas fa-external-link-alt"></i>
    </div>
</a>
```

Then add custom styling for your icon:
```css
.link-icon.your-custom-class {
    background: linear-gradient(135deg, #color1 0%, #color2 100%);
}
```

## 🎯 Available Icons

The website uses Font Awesome icons. Some popular options:
- `fab fa-github` - GitHub
- `fab fa-linkedin-in` - LinkedIn
- `fas fa-envelope` - Email
- `fab fa-twitter` - Twitter
- `fas fa-blog` - Blog
- `fas fa-file-alt` - Resume/CV
- `fab fa-instagram` - Instagram
- `fab fa-youtube` - YouTube
- `fas fa-globe` - Website

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## ♿ Accessibility Features

- Keyboard navigation support
- Screen reader compatibility
- High contrast mode support
- Reduced motion preferences
- Focus indicators
- Skip links
- ARIA labels and roles

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them back with the community!

## 💡 Tips

1. **Profile Picture**: Use a high-quality, professional photo (200x200px recommended)
2. **Bio**: Keep it concise but engaging (2-3 sentences)
3. **Links**: Only include your most important/active profiles
4. **Colors**: Test your color choices for accessibility contrast
5. **Performance**: Optimize images before adding them

## 🔧 Development

To make changes:
1. Edit the HTML structure in `index.html`
2. Modify styles in `styles.css`
3. Add functionality in `script.js`
4. Test on different screen sizes
5. Validate HTML and CSS

## 📞 Support

If you need help customizing this template, feel free to:
- Check the comments in the code
- Refer to this README
- Look up CSS/HTML/JavaScript documentation
- Test changes incrementally

---

**Happy coding! 🚀**
