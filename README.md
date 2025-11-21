# Travel+ Agency Website

A modern, interactive travel agency website built with HTML, CSS, and JavaScript. Features a responsive design, multi-language support, modal-based navigation, and comprehensive booking system.

## Features

### 🌍 Multi-Language Support
- English and Spanish translations
- Dynamic language switching for all content
- Persistent language selection

### 🎯 Interactive Navigation
- Modal-based category browsing (Trips, Offers, Hotels, Packages, Cruises)
- Sequential modal experience for booking
- Smooth animations and transitions

### 🏖️ Comprehensive Booking System
- User registration and login modals
- Detailed booking forms with pre-filled data
- Secure checkout process with payment information
- Booking summary and confirmation

### 🎨 Modern Design
- Responsive layout for all devices
- Futuristic color schemes with smooth gradients
- Hover effects and animations
- Dark/light theme compatibility

### 📱 Responsive Design
- Mobile-first approach
- Adaptive layouts for tablets and desktops
- Touch-friendly interactions

### 🛒 Promotions & Offers
- Interactive promotional banners
- Special offers modal with detailed promotions
- Time-sensitive offers and discounts

## Technologies Used

- **HTML5**: Semantic markup and accessibility
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Interactive functionality and DOM manipulation
- **LoremFlickr API**: Dynamic travel imagery

## File Structure

```
travel-agency/
├── index.html          # Main HTML file
├── styles.css          # CSS styling and animations
├── script.js           # JavaScript functionality
└── README.md          # Project documentation
```

## How to Run

1. Clone or download the project files
2. Open `index.html` in a modern web browser
3. The website is fully functional offline

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Features Overview

### Navigation
- Click category buttons to open detailed modals
- Use the welcome banner for promotions
- Language switcher in the footer

### Booking Process
1. Select a category (Trips/Offers/Hotels/Packages/Cruises)
2. Click on any card to open booking details
3. Fill booking form and proceed to checkout
4. Complete payment information

### User Management
- Sign up for new accounts
- Login functionality (placeholder)
- Account creation with validation

### Promotions
- Click the welcome section for special offers
- View detailed promotional terms
- Limited-time offers with expiration notices

## Customization

### Colors
Modify CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #00bfff;
    --secondary-color: #20b2aa;
    --accent-color: #ffa500;
}
```

### Content
Update translations in `script.js`:
```javascript
const translations = {
    en: {
        "welcome-title": "Your Custom Title"
    },
    es: {
        "welcome-title": "Tu Título Personalizado"
    }
};
```

### Images
Replace LoremFlickr URLs with your own images:
```html
<img src="your-image.jpg" alt="Description">
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is open source and available under the MIT License.

## Contact

For questions or support, please contact the development team.