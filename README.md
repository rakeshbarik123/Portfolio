# Rakesh Barik - Portfolio Website

A modern, responsive, and creative portfolio website showcasing the work and skills of Rakesh Barik, an 18-year-old aspiring developer.

## 🌟 Features

### Design & Theme
- **Modern & Creative Design**: Colorful gradient accents and contemporary styling
- **Dark/Light Mode Toggle**: Seamless theme switching with persistent preference storage
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Hover effects, typing animations, and scroll-triggered transitions

### Navigation & Structure
- **Multi-page Layout**: Home, About, Skills, Projects, Resume, and Contact sections
- **Sticky Navigation**: Fixed navbar with smooth scrolling effects
- **Mobile-Friendly**: Hamburger menu for mobile devices
- **Active Link Highlighting**: Dynamic navigation state based on scroll position

### Interactive Elements
- **Typing Effect**: Animated tagline with multiple phrases
- **Skill Progress Bars**: Animated progress indicators
- **Image Modals**: Clickable project screenshots with modal view
- **Contact Form**: Functional contact form with email integration
- **Smooth Scrolling**: Enhanced user experience with smooth page transitions

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern web standards
- **CSS3**: Advanced styling with Flexbox, Grid, and CSS animations
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **Font Awesome**: Icon library for UI elements
- **Google Fonts**: Poppins font family for typography

## 📁 Project Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── assets/             # Images and resources
    ├── profile.jpg     # Profile picture
    ├── about-image.jpg # About section image
    ├── alltools-1.jpg  # Project screenshot 1
    ├── alltools-2.jpg  # Project screenshot 2
    ├── alltools-3.jpg  # Project screenshot 3
    └── resume.pdf      # Resume file
```

## 🎨 Sections Overview

### 1. Home (Hero Section)
- Profile picture with hover effects
- Animated typing effect for tagline
- Call-to-action buttons
- Scroll indicator

### 2. About Me
- Personal bio and background
- Statistics display (age, languages, experience)
- Professional image with gradient overlay

### 3. Skills
- Interactive skill cards with progress bars
- Technology icons and descriptions
- Animated progress indicators

### 4. Projects
- Featured project: AllTools
- Live demo link and GitHub integration
- Project screenshots with modal view
- Technology tags

### 5. Resume
- Resume preview card
- Download functionality
- Personal details display

### 6. Contact
- Contact information display
- Functional contact form
- Social media links
- Email integration

## 🚀 Getting Started

1. **Clone or Download** the repository
2. **Open** `index.html` in your web browser
3. **Customize** the content:
   - Update personal information in `index.html`
   - Replace placeholder images in `assets/` folder
   - Modify colors and styling in `styles.css`
   - Add your resume PDF to `assets/resume.pdf`

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Features Implementation

### Theme Toggle
```javascript
// Automatic theme persistence
const savedTheme = localStorage.getItem('theme') || 'light';
document.documentElement.setAttribute('data-theme', savedTheme);
```

### Typing Effect
```javascript
// Dynamic typing animation
const phrases = ["Aspiring Developer", "Student", "Tech Enthusiast"];
// Implements realistic typing and deleting effects
```

### Smooth Scrolling
```javascript
// Enhanced navigation experience
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    // Smooth scroll implementation with offset calculation
});
```

## 🔧 Customization Guide

### Colors
Update CSS custom properties in `:root` for light mode and `[data-theme="dark"]` for dark mode:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... more colors */
}
```

### Content
1. **Personal Information**: Update name, age, email, and bio in `index.html`
2. **Skills**: Modify skill cards and progress percentages
3. **Projects**: Add your projects with descriptions and links
4. **Images**: Replace placeholder images with your actual photos

### Styling
- **Gradients**: Customize gradient combinations in CSS
- **Animations**: Adjust timing and effects in CSS and JavaScript
- **Layout**: Modify grid and flexbox layouts as needed

## 📧 Contact Form Integration

The contact form uses `mailto:` links to open the user's default email client. For advanced functionality, consider integrating with:
- **EmailJS** for client-side email sending
- **Netlify Forms** for form handling
- **Backend API** for server-side processing

## 🌐 Browser Support

- **Chrome** (recommended)
- **Firefox**
- **Safari**
- **Edge**
- **Mobile browsers**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you make improvements, consider sharing them back with the community!

## 📞 Contact

**Rakesh Barik**
- Email: barikrakesh310@gmail.com
- GitHub: [rakeshbarik123](https://github.com/rakeshbarik123)
- Portfolio: [Live Demo](https://rakeshbarik123.github.io/AllTools/)

---

⭐ **Star this repository if you found it helpful!**

*Built with ❤️ by Rakesh Barik*
