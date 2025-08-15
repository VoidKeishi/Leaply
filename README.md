# Leaply - International Education Platform

A clean, modern web interface for Leaply, a platform that helps students apply to universities and scholarships abroad. The design combines minimalism with a fresh, nature-inspired aesthetic, symbolizing growth, trust, and professionalism.

## 🎨 Design Features

### Color Palette
- **Primary Green**: #8dc641 (vibrant, energetic green)
- **Secondary Green**: #cae122 (bright accent green)
- **Accent Green**: #3bb64b (medium green for interactions)
- **Dark Green**: #016839 (deep green for emphasis)
- **Background**: #FFFFFF (clean white)
- **Section Gray**: #F5F5F5 (subtle backgrounds)
- **Text Gray**: #B0B0B0 (secondary text)

### Design Principles
- **Fresh & Airy**: Generous whitespace and clean layouts
- **Nature-Inspired**: Leaf-themed elements and organic curves
- **Professional**: Clean typography and subtle shadows
- **Growth-Oriented**: Visual metaphors for progress and development

## 📱 Pages & Features

### Landing Page (`index.html`)
- Hero section with leaf-themed paper airplane logo
- Benefits showcase (Smart Matching, A-Z Guidance, Scholarships)
- Featured universities with interactive cards
- Success stories carousel
- Call-to-action sections

### Search Page (`search.html`)
- University and scholarship search functionality
- Advanced filtering (country, field, level)
- Card-based grid layout with detailed information
- Bookmark functionality for saving favorites
- Responsive search results

### Student Profile (`profile.html`)
- Personal dashboard with progress tracking
- Application status management
- Step-by-step progress indicators
- Personalized recommendations
- Document management system
- Timeline and milestone tracking

### About Page (`about.html`)
- Company mission and values
- Team introductions with avatars
- Impact statistics and achievements
- Floating animations and visual elements

### Contact Page (`contact.html`)
- Multiple contact methods (email, phone, chat)
- Comprehensive contact form with validation
- FAQ section with common questions
- Office location and hours
- Interactive support options

## 🚀 Technical Implementation

### Structure
```
/
├── index.html          # Landing page
├── search.html         # University & scholarship search
├── profile.html        # Student dashboard
├── about.html          # About company
├── contact.html        # Contact & support
├── css/
│   └── style.css       # Main stylesheet with design system
├── js/
│   └── main.js         # Interactive features & functionality
└── images/             # Image assets (placeholder directory)
```

### CSS Architecture
- **CSS Custom Properties**: Centralized design tokens
- **Mobile-First**: Responsive design approach
- **Component-Based**: Reusable UI components
- **Utility Classes**: Helper classes for quick styling

### JavaScript Features
- Mobile navigation toggle
- Smooth scrolling navigation
- Search and filter functionality
- Carousel/slider components
- Form validation
- Progress tracking
- Animation on scroll
- Toast notifications

## 📱 Responsive Design

### Breakpoints
- **Desktop**: 1200px+ (primary design)
- **Tablet**: 768px - 1199px
- **Mobile**: < 768px

### Mobile Features
- Collapsible navigation menu
- Stacked layouts for better mobile viewing
- Touch-friendly button sizes
- Optimized forms for mobile input

## 🎯 Key Components

### Navigation
- Clean header with logo and navigation links
- Mobile hamburger menu
- Sticky navigation on scroll
- Active state indicators

### Cards
- University/scholarship cards with hover effects
- Bookmark functionality
- Consistent information display
- Statistics and tags

### Forms
- Real-time validation
- Clean, rounded input fields
- Error state handling
- Accessibility features

### Progress Tracking
- Visual step indicators
- Completion percentages
- Status badges (completed, active, pending)
- Interactive progress updates

## 🌱 Brand Elements

### Logo
- Leaf-themed paper airplane concept
- Curly "L" in logo typography
- Green color scheme
- Growth and journey symbolism

### Typography
- **Font**: Inter (clean, modern sans-serif)
- **Headings**: Bold, clear hierarchy
- **Body**: Regular weight for readability
- **Logo**: Slightly curly "L" with straight text

### Visual Elements
- Soft, blurred shadows
- Rounded corners on components
- Organic curve dividers
- Nature-inspired icons and metaphors

## 🔧 Setup & Usage

1. **Clone or download** the project files
2. **Open** `index.html` in a web browser
3. **Navigate** between pages using the header navigation
4. **Test** responsive design by resizing browser window

### Development
- No build process required - vanilla HTML, CSS, and JavaScript
- Fonts loaded from Google Fonts CDN
- All assets are self-contained

## 🎨 Customization

### Colors
All colors are defined as CSS custom properties in `:root` for easy customization:

```css
:root {
  --primary-green: #8dc641;
  --secondary-green: #cae122;
  --accent-green: #3bb64b;
  --dark-green: #016839;
  --background-white: #FFFFFF;
  /* ... */
}
```

### Spacing
Consistent spacing system using CSS custom properties:

```css
:root {
  --space-xs: 0.5rem;
  --space-sm: 0.75rem;
  --space-md: 1rem;
  /* ... */
}
```

## 📊 Features Implemented

- ✅ Responsive design (desktop, tablet, mobile)
- ✅ Interactive navigation with mobile menu
- ✅ Search and filtering functionality
- ✅ Progress tracking system
- ✅ Form validation
- ✅ Carousel/slider components
- ✅ Bookmark functionality
- ✅ Toast notifications
- ✅ Smooth scrolling
- ✅ Animation on scroll
- ✅ Accessibility considerations

## 🚀 Future Enhancements

### Potential Additions
- User authentication system
- Real database integration
- Advanced search algorithms
- Payment processing for premium features
- Live chat support
- Mobile app development
- Multi-language support
- Email integration
- Calendar integration for deadlines
- Document upload and storage

### Technical Improvements
- Progressive Web App (PWA) features
- Service worker for offline functionality
- Advanced animations and micro-interactions
- A/B testing framework
- Analytics integration
- SEO optimization
- Performance optimization

## 📄 Browser Support

- ✅ Chrome/Chromium 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+

## 📞 Support

For questions about implementation or customization:
- Email: support@leaply.com
- Phone: +1 (555) 123-4567

---

**Leaply** - Empowering dreams through international education since 2024.
