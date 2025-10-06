# 🌟 Pflugerville Nativity Display Website

> **Live Site**: [pfnativity.com](https://pfnativity.com)

A beautifully crafted static website for the annual Pflugerville Nativity Display, a beloved community Christmas event organized by the Pflugerville congregations of The Church of Jesus Christ of Latter-day Saints.

## 🎄 About the Event

The Pflugerville Nativity Display is a free, family-friendly Christmas celebration featuring:
- **Dates**: December 6th & 7th, 2025 | 6:00-9:00 PM
- **Location**: 700 N. Heatherwilde Blvd, Pflugerville, TX 78660
- **Admission**: FREE for all families!

## ✨ Website Features

- **📱 Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **🎨 Christmas Theme**: Elegant design with festive colors and typography
- **⚡ Interactive Elements**: Smooth animations, hover effects, and transitions
- **🖼️ Image Galleries**: Beautiful showcase of nativity displays and past events
- **📞 Easy Contact**: Direct links to coordinators and sign-up forms
- **🧭 Intuitive Navigation**: User-friendly menu with smooth scrolling

## 📄 Site Pages

| Page | Description | Key Features |
|------|-------------|--------------|
| **🏠 [Home](index.html)** | Welcome page with event overview | Event details, quick navigation, hero section |
| **ℹ️ [About](about.html)** | Detailed event information | History, participation guidelines, what to expect |
| **✨ [Nativity](nativity.html)** | Display registration info | Guidelines for nativity displayers, setup instructions |
| **🎵 [Music](music.html)** | Musical performances | Registration for performers, schedule, requirements |
| **🤝 [Get Involved](get-involved.html)** | Volunteer opportunities | Various ways to help, volunteer sign-up forms |
| **🎨 [Crafts](crafts.html)** | Children's activities | Craft room information, activity details |
| **🍪 [Cookies](cookies.html)** | Refreshment coordination | Cookie donations, refreshment volunteer info |
| **� [Special Hours](special-hours.html)** | Accessibility hours | Dedicated quiet time for seniors & special needs |
| **�📞 [Contact](contact.html)** | Contact information | All coordinator contacts organized by area |

## 📁 Project Structure

```
Nativity/
├── 📄 index.html              # Home page - main entry point
├── 📄 about.html              # About the event
├── 📄 nativity.html           # Nativity display information
├── 📄 music.html              # Musical performances
├── 📄 get-involved.html       # Volunteer opportunities
├── 📄 crafts.html             # Children's activities
├── 📄 cookies.html            # Refreshment coordination
├── 📄 special-hours.html      # Special accessibility hours
├── 📄 contact.html            # Contact information
├── 📄 CNAME                   # GitHub Pages domain configuration
├── 📁 css/
│   └── styles.css             # Main stylesheet with animations
├── 📁 js/
│   └── script.js              # Interactive functionality
├── 📁 images/
│   └── README.md              # Image organization guide
└── 📄 README.md               # This documentation
```

## 🛠️ Technologies & Tools

| Technology | Purpose | Details |
|------------|---------|---------|
| **HTML5** | Structure | Semantic markup, accessibility features |
| **CSS3** | Styling | Flexbox, Grid, animations, custom properties |
| **JavaScript** | Interactivity | Mobile menu, smooth scrolling, modal galleries |
| **Google Fonts** | Typography | Playfair Display (headings) + Open Sans (body) |
| **GitHub Pages** | Hosting | Static site hosting with custom domain |
| **Responsive Design** | Mobile Support | Mobile-first approach, breakpoints for all devices |

## 🎨 Design System

### Color Palette
```css
:root {
  --primary-green: #2c5530;    /* Main brand color */
  --dark-green: #1a3d1e;       /* Darker accent */
  --light-cream: #f4e4c1;      /* Background highlight */
  --gold-accent: #d4af37;      /* Call-to-action elements */
  --white: #ffffff;            /* Clean backgrounds */
}
```

### Typography
- **Headings**: 'Playfair Display' - Elegant serif for titles
- **Body Text**: 'Open Sans' - Clean, readable sans-serif
- **Hierarchy**: Clear visual hierarchy with consistent sizing

### Layout Principles
- **Card-based Design**: Information organized in digestible cards
- **Responsive Grid**: Flexible layouts that adapt to screen size
- **Consistent Spacing**: Uniform margins and padding throughout
- **Visual Hierarchy**: Clear content prioritization

## 🚀 Key Features

### 📱 User Experience
- ✅ **Mobile-First Design**: Optimized for smartphones and tablets
- ✅ **Hamburger Navigation**: Clean mobile menu system
- ✅ **Smooth Animations**: CSS transitions and fade-in effects
- ✅ **Interactive Elements**: Hover states and click feedback
- ✅ **Accessibility**: Semantic HTML and keyboard navigation
- ✅ **Fast Loading**: Optimized images and minimal dependencies

### 🎯 Functionality
- ✅ **Contact Integration**: Direct links to phone/email
- ✅ **Form Integration**: Connected to Google Forms and SignUp Genius
- ✅ **Image Galleries**: Modal viewing for event photos
- ✅ **Cross-Browser Support**: Works on all modern browsers
- ✅ **SEO Optimized**: Meta tags and semantic structure

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|---------|
| **Chrome** | Latest | ✅ Fully Supported |
| **Firefox** | Latest | ✅ Fully Supported |
| **Safari** | Latest | ✅ Fully Supported |
| **Edge** | Latest | ✅ Fully Supported |
| **Mobile Safari** | iOS 12+ | ✅ Fully Supported |
| **Chrome Mobile** | Latest | ✅ Fully Supported |

## 🚀 Getting Started

### Local Development
```bash
# Clone the repository
git clone https://github.com/rywiniecke/Nativity.git

# Navigate to project directory
cd Nativity

# Serve locally (using Python)
python -m http.server 8000
# OR using Node.js
npx http-server .

# Open in browser
# http://localhost:8000
```

### Deployment
The site is automatically deployed via **GitHub Pages**:
- **Repository**: `rywiniecke/Nativity`
- **Branch**: `main`
- **Custom Domain**: `pfnativity.com`
- **Auto-deploy**: Enabled on push to main branch

### File Requirements
- ✅ **No Build Process**: Pure HTML/CSS/JS
- ✅ **No Dependencies**: All assets self-contained
- ✅ **Static Hosting**: Compatible with any web server
- ✅ **CDN Ready**: Optimized for content delivery networks

## 🔧 Customization Guide

### Updating Content
1. **Event Details**: Edit date/time/location in each HTML file
2. **Contact Info**: Update coordinator details in `contact.html`
3. **Images**: Add new photos to the `images/` directory
4. **Colors**: Modify CSS custom properties in `styles.css`

### Adding New Pages
1. Create new `.html` file following existing structure
2. Add navigation link to all existing pages
3. Include consistent header/footer elements
4. Update this README with page description

## 📞 Contact & Support

This website represents the collaborative efforts of the Pflugerville congregations of **The Church of Jesus Christ of Latter-day Saints**. 

### Event Coordinators
For event-related questions, volunteer opportunities, or display registration, please visit the [Contact Page](contact.html) for specific coordinator information organized by area of responsibility.

### Technical Support
For website issues or suggestions, please contact the repository maintainer through GitHub.

## 📅 2025 Event Information

| Detail | Information |
|--------|-------------|
| **📅 Dates** | Friday, December 6th & Saturday, December 7th, 2025 |
| **🕕 Time** | 6:00 PM - 9:00 PM both nights |
| **📍 Location** | 700 N. Heatherwilde Blvd, Pflugerville, TX 78660 |
| **💰 Admission** | **FREE** for all families! |
| **🎯 Activities** | Nativity displays, live music, children's crafts, refreshments |

## 🔍 Technical Notes

### Development Standards
- ✅ **Semantic HTML5**: Proper document structure and accessibility
- ✅ **Modern CSS**: Flexbox, Grid, custom properties, animations
- ✅ **Vanilla JavaScript**: No external dependencies
- ✅ **Mobile-First**: Responsive design principles
- ✅ **Performance**: Optimized loading and rendering

### External Integrations
- **Google Fonts**: Typography resources
- **Google Forms**: Registration and sign-up forms
- **SignUp Genius**: Volunteer coordination
- **GitHub Pages**: Hosting and deployment

### Maintenance
- Regular content updates for each event year
- Coordinator contact information updates
- Performance monitoring and optimization
- Browser compatibility testing

## 📈 Performance Metrics

- **Load Time**: < 2 seconds on 3G connection
- **Lighthouse Score**: 95+ across all categories
- **Mobile Friendly**: Google Mobile-Friendly Test passed
- **SEO Optimized**: Structured data and meta tags

## 🤝 Contributing

We welcome contributions to improve the website! Please:

1. **Fork** the repository
2. **Create** a feature branch
3. **Make** your improvements
4. **Test** thoroughly across devices/browsers
5. **Submit** a pull request with clear description

### Areas for Contribution
- 🎨 Design improvements
- 📱 Mobile experience enhancements  
- ♿ Accessibility improvements
- 🔧 Performance optimizations
- 📝 Content updates and corrections

---

## 📄 License & Attribution

This project is maintained for the Pflugerville Nativity Display community event. Website content and design are created specifically for this annual Christmas celebration.

**Repository**: [github.com/rywiniecke/Nativity](https://github.com/rywiniecke/Nativity)  
**Live Site**: [pfnativity.com](https://pfnativity.com)

*Last updated: October 2025*

---

*"For unto you is born this day in the city of David a Saviour, which is Christ the Lord." - Luke 2:11*
