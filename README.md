# 🚀 Modern Portfolio Website

A stunning, responsive portfolio website featuring a MacBook Air-style loading screen, Three.js 3D animations, and smooth scroll effects. Built with vanilla HTML, CSS, and JavaScript.

![Portfolio Preview](https://img.shields.io/badge/Portfolio-Live-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

- 🖥️ **MacBook Air Loading Screen** - Elegant Apple-style loading animation with countdown
- 🎨 **Three.js 3D Background** - Interactive particle system and geometric shapes
- 📱 **Fully Responsive** - Works perfectly on all devices (mobile, tablet, desktop)
- 🌊 **Smooth Animations** - Scroll-triggered animations and transitions
- 🎯 **Modern UI/UX** - Clean, professional design with gradient accents
- 🚀 **Fast Performance** - Optimized for speed and smooth interactions
- 📧 **Contact Form** - Functional contact section (ready for backend integration)
- 🎭 **Custom Cursor** - Enhanced user experience on desktop
- 📊 **Multiple Sections**:
  - Hero with dynamic typing effect
  - About with statistics
  - Education timeline
  - Project showcase
  - Tech stack with learning progress
  - Contact form

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties, flexbox, and grid
- **JavaScript (ES6+)** - Vanilla JS for interactions
- **Three.js** - 3D graphics and animations
- **Google Fonts** - Poppins & Space Grotesk

## 📦 Installation

### Prerequisites
- A modern web browser
- A code editor (VS Code recommended)
- Node.js (optional, for local development server)

### Quick Start

1. **Clone or download** this repository
   ```bash
   git clone <your-repo-url>
   cd my_portfolio-website
   ```

2. **Open the project**
   - Simply open `index.html` in your browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with live-server)
     npx live-server
     ```

3. **Customize your content**
   - Edit `index.html` to add your information
   - Modify colors in `style.css` (see customization section)
   - Update projects, education, and contact details

## 🎨 Customization Guide

### 1. Personal Information

Edit `index.html` and replace:
- **Line 49**: Change "Your Name" to your actual name
- **Line 50**: Update the subtitle/role
- **Line 52**: Modify the description
- **Lines 151-195**: Update About section content
- **Lines 203-254**: Edit education timeline
- **Lines 267-347**: Update project cards with your projects
- **Lines 446-471**: Add your contact information

### 2. Color Scheme

Edit `style.css` at the `:root` section (around line 118):

```css
:root {
    --primary-color: #667eea;      /* Main brand color */
    --secondary-color: #764ba2;    /* Secondary accent */
    --accent-color: #f093fb;       /* Highlight color */
    --text-primary: #ffffff;       /* Main text */
    --text-secondary: #a0aec0;     /* Secondary text */
    --bg-primary: #0a0e27;         /* Background */
    --bg-secondary: #1a1f3a;       /* Secondary background */
}
```

### 3. Loading Screen Duration

Edit `script.js` (line 10):
```javascript
const duration = 3000; // Change to your preferred duration in milliseconds
```

### 4. Three.js Particles

Edit `script.js` (line 48) to change particle count:
```javascript
const particlesCount = 1000; // Increase/decrease for more/fewer particles
```

### 5. Fonts

Replace Google Fonts in `index.html` (lines 8-10) with your preferred fonts.

## 🚀 Deployment to Vercel

### Method 1: Using Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   cd my_portfolio-website
   vercel
   ```

3. **Follow the prompts** and your site will be live!

### Method 2: Using Vercel Dashboard

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub/GitLab/Bitbucket
3. Click **"New Project"**
4. Import your repository
5. Click **"Deploy"**
6. Your site is live! 🎉

### Method 3: Git Integration

1. Push your code to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-github-repo-url>
   git push -u origin master
   ```

2. Connect to Vercel via GitHub integration
3. Auto-deploy on every push!

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (limited support, no Three.js)

## 📧 Contact Form Integration

The contact form is ready for integration. Choose one of these services:

### Option 1: EmailJS
1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Get your API keys
3. Update `script.js` contact form handler

### Option 2: Formspree
1. Sign up at [formspree.io](https://formspree.io/)
2. Update form action attribute
3. No JavaScript required

### Option 3: Custom Backend
Create your own API endpoint and update the form submission handler in `script.js`.

## 🎯 Performance Tips

1. **Optimize Images**: Use compressed images for projects
2. **Lazy Loading**: Implement lazy loading for images below the fold
3. **CDN**: Consider using a CDN for Three.js in production
4. **Minify**: Minify CSS and JS for production
5. **Caching**: Leverage browser caching via Vercel headers

## 🐛 Troubleshooting

### Three.js not loading
- Check console for errors
- Ensure CDN link is working
- Try using a different Three.js version

### Loading screen stuck
- Check JavaScript console
- Verify `script.js` is loaded correctly
- Clear browser cache

### Animations not working
- Ensure JavaScript is enabled
- Check for console errors
- Verify IntersectionObserver support

## 📝 License

MIT License - feel free to use this template for your own portfolio!

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 👨‍💻 Author

**Your Name**
- Website: [your-website.com](https://your-website.com)
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

## 🌟 Show Your Support

Give a ⭐️ if you like this project!

## 📸 Screenshots

### Desktop View
![Desktop](https://via.placeholder.com/800x400?text=Desktop+View)

### Mobile View
![Mobile](https://via.placeholder.com/400x800?text=Mobile+View)

### Loading Screen
![Loading](https://via.placeholder.com/800x400?text=Loading+Screen)

---

**Made with ❤️ and lots of ☕**

## 🔥 Quick Customization Checklist

- [ ] Update name and personal information
- [ ] Change colors in CSS variables
- [ ] Add your projects
- [ ] Update education section
- [ ] Add your tech stack
- [ ] Update contact information
- [ ] Add your social media links
- [ ] Replace placeholder images
- [ ] Test on multiple devices
- [ ] Deploy to Vercel
- [ ] Connect custom domain (optional)
- [ ] Set up contact form backend
- [ ] Add Google Analytics (optional)

## 🚀 Next Steps

After deployment, consider adding:
- Blog section
- Project case studies
- Testimonials
- Dark/Light theme toggle
- Multi-language support
- SEO optimization
- Analytics integration
- Performance monitoring

Happy coding! 🎉
