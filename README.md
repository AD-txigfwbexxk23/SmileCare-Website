# SmileCare Network Website

A beautiful, responsive website for SmileCare Network, a non-profit organization dedicated to providing accessible dental care to underserved communities.

## 🌟 Features

### Design & User Experience
- **Modern, Responsive Design**: Beautiful pastel blue theme with clean typography
- **Mobile-First Approach**: Fully responsive across all devices
- **Smooth Animations**: Interactive elements with hover effects and transitions
- **Accessibility**: ARIA labels, semantic HTML, and keyboard navigation support

### Pages & Content
- **Home Page**: Hero section with call-to-action buttons
- **What We Do**: Services, impact statistics, and how to help
- **Who We Are**: Mission, vision, team, and organization story
- **Donate**: Multiple donation options with detailed form
- **Community**: Patient stories, events, and volunteer spotlights
- **Take Action**: Volunteer opportunities and advocacy tools
- **Shop**: Merchandise and products supporting the mission

### Interactive Features
- **Smooth Scrolling**: Navigation and anchor links
- **Form Validation**: Contact forms with client-side validation
- **Donation System**: Multiple donation amounts and recurring options
- **Newsletter Signup**: Email subscription functionality
- **Social Media Integration**: Links to social platforms
- **Back to Top Button**: Appears on scroll for better UX

## 📁 File Structure

```
SmileCare Network/
├── index.html              # Home page
├── what-we-do.html         # Services and programs
├── who.html               # About us and team
├── donate.html            # Donation page
├── community.html         # Community stories and events
├── take-action.html       # Volunteer and advocacy
├── shop.html             # Merchandise store
├── styles/
│   └── main.css          # Main stylesheet
├── js/
│   └── main.js           # JavaScript functionality
└── README.md             # This file
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#a8d8ff` (Pastel blue background)
- **Accent Blue**: `#7cbdf3` (Shadows and highlights)
- **Dark Blue**: `#5a9bd4` (Hover states)
- **White**: `#ffffff` (Text and backgrounds)
- **Dark Text**: `#2c3e50` (Content text)

### Typography
- **Primary Font**: Raleway (Clean, modern sans-serif)
- **Display Font**: Pacifico (Stylish cursive for headings)
- **Icons**: Font Awesome 5.15.4

### Components
- **Cards**: Consistent card design with hover effects
- **Buttons**: Primary and secondary button styles
- **Forms**: Styled form inputs with validation
- **Navigation**: Responsive header with mobile considerations

## 🚀 Getting Started

1. **Clone or Download**: Get the website files
2. **Open in Browser**: Simply open `index.html` in any modern web browser
3. **Local Development**: Use a local server for best experience:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 900px - 1199px
- **Mobile**: Below 900px
- **Small Mobile**: Below 600px

## 🔧 Customization

### Colors
Edit the CSS custom properties in `styles/main.css`:
```css
:root {
  --blue-bg: #a8d8ff;
  --blue-accent: #7cbdf3;
  --white: #ffffff;
  --dark-blue: #5a9bd4;
  --text-dark: #2c3e50;
}
```

### Content
- Update text content in HTML files
- Replace placeholder images with actual photos
- Modify contact information and social media links

### Functionality
- Add form processing for donations and volunteer applications
- Integrate with a CMS for content management
- Connect to a database for dynamic content

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari, Chrome Mobile

## 📊 Performance Features

- **Optimized Images**: Placeholder icons using Font Awesome
- **Minimal Dependencies**: Only external fonts and icons
- **Fast Loading**: Lightweight CSS and JavaScript
- **SEO Ready**: Semantic HTML structure

## 🔒 Security Considerations

- **Form Validation**: Client-side validation implemented
- **HTTPS Ready**: All external resources use HTTPS
- **XSS Protection**: Proper HTML encoding
- **Privacy**: No tracking or analytics by default

## 🛠️ Development

### Adding New Pages
1. Copy an existing HTML file
2. Update the title, content, and navigation
3. Ensure consistent header and footer
4. Test responsiveness

### Styling Changes
1. Edit `styles/main.css`
2. Use CSS custom properties for consistency
3. Test across different screen sizes
4. Validate CSS syntax

### JavaScript Enhancements
1. Edit `js/main.js`
2. Add new event listeners as needed
3. Test functionality across browsers
4. Ensure graceful degradation

## 📞 Support

For questions or customization requests:
- **Email**: info@smilecarenetwork.org
- **Phone**: (555) 123-4567
- **Address**: 123 Care Street, Health City, HC 12345

## 📄 License

This website template is created for SmileCare Network. All rights reserved.

---

**SmileCare Network** - You Matter. Your Smile Matters. ❤️ 