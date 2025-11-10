# 🐾 Whisker Wonders - Professional Business Website

A multi-page responsive business website for a pet grooming salon featuring modern design, interactive elements, and comprehensive functionality for customer engagement.

## 🛠️ Technologies

**Frontend:** HTML5 • CSS3 • JavaScript ES6+ • Bootstrap 5.3 • jQuery 3.7

**Architecture:** Responsive Design • Dark/Light Mode • Local Storage API • Form Validation

## ✨ Key Features

### 🏢 Professional Business Presentation
- Multi-page structure with consistent navigation
- About Us page with company mission and values
- Services page with pricing table and vendor registration
- Contact form with validation and confirmation
- Pet registration system with data management

### 🎨 User Experience Design
- Dark/light mode toggle with persistent localStorage
- Mobile-first responsive design optimized for all devices
- Interactive forms with real-time validation and visual feedback
- Professional styling with custom CSS theming and Bootstrap integration
- Dynamic content management with live data processing

### 💡 Pet Owner-Focused Design Philosophy
This website was designed with pet owners' comfort and trust as primary considerations:

- Customer reviews prominently featured to build trust and credibility
- Warm color palette with calming green tones to reduce anxiety
- Authentic pet photography creates emotional connection over stock images
- Consistent professional branding builds confidence in service quality
- Mobile-first approach for busy pet owners accessing information on-the-go

## 🗂️ Architecture

### File Structure
```
whisker-wonders-business-website/
├── index.html              # About Us page
├── services.html           # Services and pricing
├── registration.html       # Pet registration system
├── contact.html           # Contact form
├── style/
│   └── mystyle.css        # Custom CSS with theming
├── scripts/
│   ├── script.js          # Main JavaScript functionality
│   ├── contact.js         # Contact form handling
│   ├── registration.js    # Registration form logic
│   └── services.js        # Services form management
└── images/
    ├── light-mode-logo.png
    ├── dark-mode-logo.png
    └── [pet photos and content images]
```

### CSS Theming System
```css
:root {
  --background-color: #f4f8f4;
  --surface-color: #e6efe9;
  --text-primary: #2f4f2f;
  --btn-primary: #1b3a1b;
}

.dark-mode {
  --background-color: #121212;
  --surface-color: #161f19;
  --text-primary: #e6efe9;
  --btn-primary: #2f6f2f;
}
```

### Pet Registration Model
```javascript
function Pet(Name, Age, Gender, Breed, Service, Type, Payment) {
  this.Name = Name;
  this.Age = Age;
  this.Gender = Gender;
  this.Breed = Breed;
  this.Service = Service;
  this.Type = Type;
  this.Payment = Payment;
}
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome 92+, Firefox 91+, Safari 14+, Edge 92+)
- No server required - runs entirely client-side

### Installation
```bash
git clone https://github.com/micahweathers/whisker-wonders-business-website.git
cd whisker-wonders-business-website
# Open index.html in your default browser
```

## 💡 Usage

### Pet Registration
1. Fill out pet information (name, age, breed)
2. Select service type and payment method
3. Submit registration for business review
4. View registered pets in dynamic table
5. Delete entries with confirmation dialog

### Navigation Features
- **About Us:** Company information and customer testimonials
- **Services:** Pricing table and vendor registration
- **Registration:** Pet management system with data persistence
- **Contact:** Professional inquiry form with validation

## 🎨 Design Philosophy

### Trust-Building Interface
Pet owner-centric design with emphasis on comfort and credibility. Customer testimonials and warm branding reduce anxiety about entrusting beloved pets to professional care.

### Dark/Light Mode Benefits
- User preference accommodation for different viewing conditions
- Professional appearance across lighting environments
- Energy efficiency on mobile devices
- Consistent branding in both themes

### Mobile-First Approach
Responsive design prioritizing mobile users who need quick access to business information, service booking, and contact details while managing pet care schedules.

## ⚡ Performance Features

### Optimization Strategies
- CSS custom properties for efficient theming
- Local storage for client-side data persistence
- Event delegation for dynamic content management
- Lightweight Bootstrap integration
- Optimized image loading

### Browser Compatibility
Modern web standards with graceful degradation for accessibility across devices and browsers.

## 🔧 Technical Implementation

### Form Validation System
Comprehensive client-side validation with real-time feedback:
- Required field validation with visual indicators
- Input type validation (email, number, text)
- Real-time error highlighting and removal
- Professional confirmation messaging

### Theme Management System
Persistent dark/light mode switching:
```javascript
const darkMode = localStorage.getItem("darkMode") === "true";
if (darkMode) {
    $body.addClass("dark-mode");
    $logo.attr("src", "./images/dark-mode-logo.png");
}
```

### Data Persistence
Local storage implementation with error handling:
- Pet registration data maintained across sessions
- Service additions stored for vendor functionality
- Theme preferences preserved between visits

## 📱 Responsive Design

### Mobile Features
- Stacked navigation for touch interfaces
- Optimized form layouts for smaller screens
- Touch-friendly button sizing
- Readable typography scaling

### Desktop Enhancements
- Multi-column layouts for efficient space usage
- Hover effects for interactive elements
- Professional presentation for business credibility
- Enhanced visual hierarchy

## 🎓 Portfolio Highlights

### Technical Skills Demonstrated
- Modern JavaScript ES6+ functionality
- CSS custom properties and theming
- Bootstrap framework integration
- Local storage API implementation
- Responsive design patterns

### Professional Practices
- Clean HTML semantic structure
- Organized CSS architecture
- Error handling and user feedback
- Accessibility considerations
- Cross-browser compatibility

## 🔮 Future Enhancements

### Enhanced Frontend Features
- Image upload preview with client-side validation
- Advanced form validation with custom error messaging
- Drag-and-drop file upload interface for pet photos
- Enhanced animations and micro-interactions

### Local Storage Expansion
- Multiple pet profiles per user with localStorage organization
- Export/import functionality for pet data (JSON format)
- Advanced filtering and search capabilities
- Data backup and restore features

### UI/UX Improvements
- Photo gallery component for pet images
- Interactive calendar widget for appointment display
- Enhanced responsive design for tablet devices
- Accessibility improvements (ARIA labels, keyboard navigation)

### JavaScript Functionality
- Real-time form field suggestions and auto-completion
- Advanced data visualization with charts for pet statistics
- Print-friendly layouts for pet information
- Offline functionality with service worker implementation

---

**Built with modern web technologies • Professional business solution**

*This project demonstrates responsive design implementation, business-focused UX design, local storage integration, and professional web development practices for real-world applications.*