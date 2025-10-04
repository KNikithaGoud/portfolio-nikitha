# Nikitha Kammadanam - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and experience as a Computer Science student specializing in AI & ML.

## 🌟 Features

- **Modern Design**: Dark theme with purple/navy gradient background
- **Animated Sparkles**: Beautiful falling sparkles animation
- **Responsive**: Works perfectly on all devices
- **Interactive**: Smooth scrolling, hover effects, and animations
- **Glass Morphism**: Modern glass effect UI elements
- **Contact Form**: Functional contact form with validation

## 🛠️ Technologies Used

- HTML5
- CSS3 (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript
- Glass Morphism Design
- Responsive Web Design

## 📁 Project Structure

```
nikitha-portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
├── app.js             # JavaScript functionality
├── assets/
│   └── profile.jpg    # Profile image
├── README.md          # This file
└── .gitignore         # Git ignore rules
```

## 🚀 Getting Started

### Local Development

1. Clone or download this repository
2. Add your profile image as `assets/profile.jpg`
3. Open `index.html` in your browser
4. That's it! No build process required.

### Deployment

#### GitHub + Vercel (Recommended)

1. **Upload to GitHub:**
   - Create new repository: `nikitha-portfolio`
   - Upload all files to the repository

2. **Deploy to Vercel:**
   - Go to [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Click Deploy

#### Alternative Platforms
- **Netlify**: Drag and drop the folder
- **GitHub Pages**: Enable in repository settings
- **Firebase Hosting**: Use Firebase CLI

## 📧 Contact Form Setup

To make the contact form functional, you can integrate with EmailJS:

1. Sign up at [EmailJS.com](https://emailjs.com)
2. Get your Service ID, Template ID, and Public Key
3. Replace the form submission code in `app.js`

```javascript
// Replace the setTimeout simulation with:
emailjs.sendForm('YOUR_SERVICE_ID', 'YOUR_TEMPLATE_ID', form, 'YOUR_PUBLIC_KEY')
    .then(() => {
        submitStatus.textContent = 'Message sent successfully!';
        form.reset();
    })
    .catch(() => {
        submitStatus.textContent = 'Failed to send message. Please try again.';
    });
```

## 🎨 Customization

### Colors
Update CSS custom properties in `:root`:

```css
:root {
  --color-black: #000000;
  --color-navy: #0a2540;
  --color-purple: #5b2c6f;
  --color-light-purple: #8b5fbf;
  --color-white: #ffffff;
}
```

### Content
- Update personal information in `index.html`
- Modify projects, skills, and certifications
- Replace profile image in `assets/` folder

### Animations
- Adjust sparkle count in `initSparkles()` function
- Modify transition speeds in CSS variables
- Customize scroll animations in `initScrollAnimations()`

## 📱 Responsive Design

- **Desktop**: Full grid layouts with animations
- **Tablet**: Adapted layouts with touch-friendly navigation
- **Mobile**: Stacked layout with hamburger menu

## 🌟 Key Features Explained

### Sparkles Animation
- Continuous falling white sparkles
- Random positioning and timing
- Performance optimized with cleanup

### Glass Morphism
- Backdrop blur effects
- Semi-transparent backgrounds
- Modern aesthetic

### Skill Bars
- Animated progress indicators
- Triggered on scroll
- Smooth gradient fills

### Contact Form
- Real-time validation
- Error message display
- Success feedback

## 📊 Performance

- **Lightweight**: No heavy frameworks
- **Fast Loading**: Optimized CSS and JavaScript
- **Smooth animations**: Hardware-accelerated transitions
- **Mobile optimized**: Touch-friendly interactions

## 🔧 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Contact

**Nikitha Kammadanam**
- Email: knikithagoud06@gmail.com
- Phone: +91 8520897438
- LinkedIn: [nikitha-kammadanam](https://www.linkedin.com/in/nikitha-kammadanam-0861b0295)
- GitHub: [KNikithaGoud](https://github.com/KNikithaGoud)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio trends
- CSS animations and effects techniques
- Glass morphism design principles

---

⭐ **If you like this portfolio, please give it a star!** ⭐

*Made with ❤️ by Nikitha Kammadanam*
