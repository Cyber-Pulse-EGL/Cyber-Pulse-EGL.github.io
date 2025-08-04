# 🛡️ Cyber Pulse - Cyber Security Awareness Program

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)

> **Empowering Teams to Stay Safe Online** - A comprehensive cybersecurity awareness platform designed to educate, protect, and build stronger digital defenses for organizations worldwide.

## 🚀 Overview

Cyber Pulse is a modern, responsive web application that serves as the central hub for cybersecurity awareness initiatives. Built with cutting-edge web technologies, it provides organizations with essential security resources, expert team information, and comprehensive training materials.

### ✨ Key Features

- **🎨 Modern Design**: Beautiful, responsive UI with glassmorphism effects and smooth animations
- **📱 Mobile-First**: Fully responsive design that works seamlessly across all devices
- **♿ Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation
- **⚡ Performance**: Optimized loading with lazy loading and efficient resource management
- **🔐 Security Resources**: Comprehensive library of security tools and training materials
- **👥 Expert Team**: Detailed profiles of cybersecurity professionals
- **📄 Resource Downloads**: Direct access to security guides and documentation
- **💌 Newsletter**: Stay updated with latest security insights and trends

## 🛠️ Technology Stack

- **Frontend Framework**: Vanilla JavaScript with modern ES6+ features
- **CSS Framework**: Tailwind CSS v3 with custom extensions
- **Icons**: Font Awesome 6.4.0
- **Fonts**: Inter (Google Fonts)
- **Build Tools**: Native HTML/CSS/JS (no build process required)
- **Hosting**: Static web hosting compatible

## 🎯 Target Audience

- **IT Professionals**: Security teams and system administrators
- **Organizations**: Companies looking to improve cybersecurity awareness
- **Educational Institutions**: Schools and training centers
- **Security Enthusiasts**: Individuals interested in cybersecurity best practices

## 📋 Prerequisites

- Modern web browser (Chrome 80+, Firefox 75+, Safari 13+, Edge 80+)
- Web server for local development (optional)
- Internet connection for external resources (CDN fonts, icons)

## 🚀 Quick Start

### Option 1: Direct File Opening
```bash
# Clone the repository
git clone https://github.com/your-org/cyber-security-awareness.git

# Navigate to project directory
cd cyber-security-awareness

# Open index.html in your browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 2: Local Server (Recommended)
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server -p 8000

# Using PHP
php -S localhost:8000

# Then visit: http://localhost:8000
```

## 📁 Project Structure

```
cyber-security-awareness/
├── index.html              # Main application file
├── README.md              # Project documentation
├── assets/                # Static assets (images, documents)
│   ├── network-details.pdf
│   └── og-image.jpg
├── favicon.ico           # Site favicon
└── sw.js                # Service worker (optional)
```

## 🎨 Design Features

### Visual Elements
- **Gradient Backgrounds**: Custom CSS gradients for modern appeal
- **Glassmorphism**: Translucent cards with backdrop blur effects
- **Floating Animations**: Subtle background animations
- **Hover Effects**: Interactive button and card transformations
- **Responsive Grid**: Flexible layouts for all screen sizes

### Color Palette
- **Primary**: Cyan to Blue gradient (#06b6d4 → #0369a1)
- **Secondary**: Green to Emerald gradient (#10b981 → #047857)
- **Background**: Slate variations (#f8fafc → #0f172a)
- **Accent**: Various vibrant colors for visual hierarchy

## 👥 Team Section

The website features detailed profiles of cybersecurity experts:

- **Jayandra Wickramasinghe** - Consultant, Cyber Security
- **Suranga Gunatilake** - Associate Lead, Cyber Security
- **Aman Shaluka** - Cyber Security Analyst
- **Livindu Peiris** - Cyber Security Analyst
- **Buddhima Abeypala** - Cyber Security Analyst
- **Ashen Wijesingha** - Cyber Security Analyst

Each profile includes contact information, specializations, and social media links.

## 📚 Resources Available

### 📄 Documentation
- **Network Connectivity Guide**: Comprehensive PDF documentation
- **Security Best Practices**: Industry-standard guidelines
- **Training Materials**: Educational content and tutorials

### 🔗 External Links
- **Resource Library**: Cloud-based security tools collection
- **Feedback System**: User feedback and suggestion portal
- **Training Videos**: Video tutorials and demonstrations

## 🔧 Customization

### Updating Team Information
1. Locate the team section in `index.html`
2. Update team member details in the article elements
3. Replace placeholder images with actual photos
4. Update contact information and social links

### Modifying Colors
```css
:root {
    --primary-gradient: linear-gradient(135deg, #your-colors);
    --secondary-gradient: linear-gradient(135deg, #your-colors);
    /* Add your custom color schemes */
}
```

### Adding New Sections
1. Create new section element with unique ID
2. Add navigation link in header
3. Implement smooth scrolling functionality
4. Add responsive breakpoints as needed

## 📱 Responsive Breakpoints

- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px - 1440px
- **Large Desktop**: 1440px+

## ♿ Accessibility Features

- **ARIA Labels**: Comprehensive screen reader support
- **Keyboard Navigation**: Full keyboard accessibility
- **Focus Management**: Visible focus indicators
- **Alt Text**: Descriptive image alternatives
- **Color Contrast**: WCAG AA compliant contrast ratios
- **Skip Links**: Quick navigation for screen readers

## 🚀 Performance Optimizations

- **Lazy Loading**: Images load on demand
- **Minified Resources**: Optimized external libraries
- **Efficient Animations**: Hardware-accelerated CSS transitions
- **Resource Preloading**: Critical resources loaded early
- **Service Worker**: Offline functionality (optional)

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 80+ | ✅ Full Support |
| Firefox | 75+ | ✅ Full Support |
| Safari | 13+ | ✅ Full Support |
| Edge | 80+ | ✅ Full Support |
| Internet Explorer | 11 | ⚠️ Limited Support |

## 📈 SEO Optimization

- **Meta Tags**: Comprehensive meta information
- **Open Graph**: Social media sharing optimization
- **Semantic HTML**: Proper HTML5 structure
- **Schema Markup**: Structured data for search engines
- **Performance**: Fast loading times and Core Web Vitals optimization

## 🔒 Security Considerations

- **Content Security Policy**: XSS protection
- **HTTPS Required**: Secure connection mandatory
- **Input Validation**: Form security measures
- **External Resources**: Trusted CDN sources only

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

### Reporting Issues
1. Check existing issues first
2. Create detailed bug reports
3. Include browser and OS information
4. Provide steps to reproduce

### Submitting Changes
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

### Code Standards
- Use semantic HTML5 elements
- Follow BEM CSS methodology
- Write clean, commented JavaScript
- Ensure accessibility compliance
- Test across multiple browsers

## 📞 Support & Contact

### Development Team
**Endpoint and Cloud Security Team at Eguardian**

### Contact Information
- **Email**: support@eguardian.com
- **Phone**: +94 (117) 394 300
- **Address**: Level 16, Access Tower 2, No. 278/4, Union Place, Colombo 02, Sri Lanka
- **Support**: 24/7 Emergency Support Available

### Feedback
- **Feedback Form**: [Internal Feedback Portal](http://192.168.1.54:8080/public/feedback_form.html)
- **Resource Access**: [Team Login Portal](http://192.168.1.54:8080/public/login.html)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Eguardian Security Team**: For expertise and guidance
- **Open Source Community**: For tools and libraries
- **Design Inspiration**: Modern web design trends and best practices

## 🔄 Version History

### v1.0.0 (Current)
- Initial release
- Complete responsive design
- Team profiles and resource sections
- Mobile navigation and accessibility features
- Performance optimizations

---

<div align="center">

**Built with ❤️ by the Eguardian Cybersecurity Team**

[Website](https://your-website.com) • [Documentation](https://docs.your-website.com) • [Support](mailto:support@eguardian.com)

</div>
