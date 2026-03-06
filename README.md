# Telecom AI Website

A modern, professional website for Telecom AI - showcasing next-generation VoIP and AI automation solutions.

## 🌐 Live Demo

View the live website: [Telecom AI](https://benjaminnday-afk.github.io/Mywebsite)

## 📋 Overview

This is a complete multi-page website built with modern web technologies, featuring a dark theme, responsive design, and interactive elements. The website presents a fictional telecommunications AI company offering automated network solutions.

## ✨ Features

- **4 Complete Pages**
  - Homepage (index.html) - Hero section, services overview, CTA
  - How It Works (how-it-works.html) - 3-phase process, benefits section
  - Pricing (pricing.html) - 3 pricing tiers, FAQ section
  - Contact (contact.html) - Contact form, multiple contact methods

- **Unified Design System**
  - Consistent navigation across all pages
  - Dark theme with blue (#259df4) and green (#10b981) accents
  - Space Grotesk font family
  - Material Icons throughout

- **Modern UI/UX**
  - Responsive mobile-first design
  - Smooth scroll animations
  - Card hover effects
  - Glass morphism & backdrop blur
  - Gradient text effects
  - Interactive form validation

- **Technical Features**
  - Tailwind CSS for styling
  - Custom CSS animations
  - JavaScript for interactivity
  - Mobile hamburger menu
  - Scroll-reveal animations
  - Form handling with validation

## 🛠️ Technologies Used

- **HTML5** - Semantic structure
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Interactive functionality
- **Google Fonts** - Space Grotesk typography
- **Material Symbols** - Icon system

## 📁 Project Structure

```
Mywebsite/
├── index.html                 # Homepage
├── how-it-works.html         # Process & Benefits page
├── pricing.html              # Pricing tiers page
├── contact.html              # Contact form page
├── assets/
│   ├── css/
│   │   └── custom.css        # Custom styles & animations
│   ├── js/
│   │   └── main.js           # Interactive functionality
│   └── images/               # Image assets
├── stitch/                   # Original template files
│   ├── pricing_contact_hub/
│   ├── process_benefits/
│   └── telecom_ai_home_services/
└── README.md
```

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/benjaminnday-afk/Mywebsite.git
   cd Mywebsite
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local development server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Node.js (if you have http-server installed)
   npx http-server
   ```

3. **View the site**
   - Navigate to `http://localhost:8000` in your browser

## 🎨 Design System

### Colors
- **Primary**: `#259df4` (Blue) - Main brand color
- **Secondary**: `#10b981` (Green) - Accent color
- **Background Dark**: `#101a22` - Dark theme background
- **Background Light**: `#f5f7f8` - Light theme background

### Typography
- **Font Family**: Space Grotesk
- **Headings**: Bold (700) to Black (900)
- **Body**: Regular (400) to Medium (500)

### Components
- Navigation with active state indicators
- Service cards with hover animations
- Pricing cards with gradient borders
- Contact forms with validation
- FAQ accordions
- CTA buttons with hover effects

## 🔧 Customization

### Update Content
- Edit HTML files to change text, images, and content
- Modify `assets/css/custom.css` for style changes
- Update `assets/js/main.js` for functionality changes

### Change Colors
Update the Tailwind config in each HTML file:
```javascript
colors: {
    "primary": "#your-color",
    "secondary": "#your-color",
    // ...
}
```

### Add Pages
1. Create new HTML file
2. Copy header/footer from existing pages
3. Add navigation link in all pages
4. Update active navigation logic in `main.js`

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Key Features by Page

### Homepage (index.html)
- Full-screen hero with gradient effects
- Dashboard mockup visualization
- 4-card services grid
- Call-to-action section

### How It Works (how-it-works.html)
- 3-phase process with connecting line
- Benefits grid with checkmarks
- Feature cards with icons
- Dot pattern backgrounds

### Pricing (pricing.html)
- 3-tier pricing comparison
- "Most Popular" highlighted plan
- FAQ accordion section
- Glow effects on featured plan

### Contact (contact.html)
- Two-column layout
- Contact information cards
- Full contact form with validation
- Office hours display
- Additional connection methods

## 📝 JavaScript Features

- **Mobile Menu**: Hamburger navigation for mobile devices
- **Scroll Reveal**: Animations triggered on scroll
- **Smooth Scrolling**: Anchor link smooth scroll behavior
- **Form Validation**: Client-side form validation with notifications
- **Active Navigation**: Auto-highlight current page in nav
- **Sticky Header**: Header with scroll shadow effect

## 🎨 CSS Features

- Custom animations (fadeInUp, pulse, spin)
- Card hover effects
- Button interactions
- Loading states
- Scroll reveal animations
- Custom scrollbar styling
- Responsive utilities

## 🚀 Deployment

### GitHub Pages
1. Push code to GitHub repository
2. Go to repository Settings
3. Navigate to Pages section
4. Select main branch
5. Site will be live at `https://username.github.io/repository-name`

### Netlify / Vercel
1. Connect GitHub repository
2. Configure build settings (no build needed for static site)
3. Deploy automatically on every push

## 📄 License

© 2024 Telecom AI Inc. All rights reserved.

This is a demonstration project. Content and branding are fictional.

## 👤 Author

**Benjamin Nday**
- GitHub: [@benjaminnday-afk](https://github.com/benjaminnday-afk)
- Email: benjamin.nday@gmail.com

## 🙏 Acknowledgments

- Based on Stitch design templates
- Icons from Material Symbols
- Fonts from Google Fonts
- Built with Tailwind CSS

---

**Note**: This is a portfolio/demonstration website. All company information, pricing, and contact details are fictional and for display purposes only.
