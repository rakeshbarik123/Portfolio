# 🎯 Quick Setup Guide

Follow these steps to customize your portfolio website with your personal information.

## 📸 Step 1: Replace Images

Replace these placeholder images with your actual photos:

### Required Images:
1. **Profile Picture** (`assets/profile.jpg`)
   - Size: 400x400px (square)
   - Format: JPG, PNG, or WebP
   - Use a professional headshot or clear photo

2. **About Section Image** (`assets/about-image.jpg`)
   - Size: 600x600px (square)
   - Format: JPG, PNG, or WebP
   - Can be a casual photo or workspace image

3. **Project Screenshots** (`assets/alltools-*.jpg`)
   - Replace with your actual project screenshots
   - Size: 800x500px (landscape)
   - Show your project's interface or key features

## 📄 Step 2: Update Resume

Replace `assets/resume.pdf` with your actual resume:
- Export your resume as PDF
- Keep filename as `resume.pdf`
- Ensure file size is under 5MB

## ✏️ Step 3: Customize Content

### Personal Information (in `index.html`):

**Line 43:** Update navigation logo name
```html
<span>Your Name</span>
```

**Line 59:** Update hero title
```html
<h1 class="hero-title">Hi, I'm <span class="highlight">Your Name</span></h1>
```

**Line 65:** Update hero description
```html
<p class="hero-description">
    Your age and brief description
</p>
```

**Line 82:** Update about section bio
```html
<p>
    Replace with your personal bio...
</p>
```

**Line 100-110:** Update statistics
```html
<div class="stat">
    <h3>Your Age</h3>
    <p>Years Old</p>
</div>
```

### Contact Information:

**Line 280:** Update email
```html
<p>your-email@example.com</p>
```

**Line 290:** Update GitHub username
```html
<p>your-github-username</p>
```

**Line 300:** Update social links
```html
<a href="mailto:your-email@example.com" class="social-link">
<a href="https://github.com/your-username" target="_blank" class="social-link">
```

## 🎨 Step 4: Customize Colors (Optional)

Edit `styles.css` to change the color scheme:

**Lines 10-20:** Update color variables
```css
:root {
    --primary-color: #your-color;
    --secondary-color: #your-color;
    --accent-color: #your-color;
}
```

### Popular Color Schemes:
- **Blue Theme:** `#3b82f6`, `#1e40af`, `#60a5fa`
- **Purple Theme:** `#8b5cf6`, `#7c3aed`, `#a78bfa`
- **Green Theme:** `#10b981`, `#059669`, `#34d399`
- **Orange Theme:** `#f59e0b`, `#d97706`, `#fbbf24`

## 🚀 Step 5: Add Your Projects

### To add a new project:

1. **Add HTML structure** in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <img src="assets/your-project.jpg" alt="Your Project">
        <div class="project-overlay">
            <div class="project-links">
                <a href="your-live-demo-link" target="_blank" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
                <a href="your-github-link" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span class="tech-tag">HTML5</span>
            <span class="tech-tag">CSS3</span>
            <span class="tech-tag">JavaScript</span>
        </div>
    </div>
</div>
```

2. **Add project image** to `assets/` folder
3. **Update links** with your actual URLs

## 🛠️ Step 6: Update Skills

### To modify skills:

1. **Change skill names** and descriptions in HTML
2. **Update progress percentages** in `data-progress` attributes
3. **Change icons** using Font Awesome classes

### Available Font Awesome Icons:
- `fab fa-html5` - HTML5
- `fab fa-css3-alt` - CSS3
- `fab fa-js-square` - JavaScript
- `fab fa-react` - React
- `fab fa-node-js` - Node.js
- `fab fa-python` - Python
- `fas fa-database` - Database
- `fas fa-mobile-alt` - Mobile Development

## 📱 Step 7: Test Your Website

1. **Open** `index.html` in your browser
2. **Test** all navigation links
3. **Verify** responsive design on mobile
4. **Check** contact form functionality
5. **Test** dark/light mode toggle

### Quick Test Commands:
- **Open website:** Double-click `open-website.bat`
- **Check responsiveness:** Use browser developer tools (F12)
- **Test mobile:** Use device simulation in dev tools

## 🌐 Step 8: Deploy Your Website

Follow the instructions in `DEPLOYMENT.md` to publish your portfolio online.

### Recommended Platforms:
1. **GitHub Pages** (Free, easy setup)
2. **Netlify** (Free, automatic deployments)
3. **Vercel** (Free, fast performance)

## 🎉 You're Done!

Your portfolio website is now customized and ready to showcase your skills!

### Next Steps:
- [ ] Replace all placeholder content
- [ ] Add your actual projects
- [ ] Test thoroughly
- [ ] Deploy online
- [ ] Share with potential employers

---

**Need Help?** Check the README.md file for detailed documentation or create an issue if you encounter problems.

**Good luck with your portfolio! 🚀**
