# Hotel Maharaja Digital Menu

A premium, modern digital menu system built for Hotel Maharaja featuring glassmorphism design, smooth animations, and professional restaurant ordering functionality.

## 🌟 Features

### 🎨 Design & User Experience
- **Glassmorphism Effects** - Modern frosted glass design with backdrop blur
- **Premium Typography** - Custom fonts (Cinzel Decorative, Lora, Playfair Display, Poppins)
- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Smooth Animations** - Hover effects, transitions, and micro-interactions
- **Professional Color Scheme** - Elegant gold and brown theme

### 🍽️ Menu Functionality
- **Category Navigation** - Sticky sidebar with smooth scrolling to menu sections
- **Interactive Menu Items** - High-quality images, detailed descriptions, and pricing
- **Veg/Non-Veg Indicators** - Clear visual identification for dietary preferences
- **Add to Cart System** - Interactive ordering with quantity controls
- **Order Management** - Professional modal for order summary and modifications
- **Sound Effects** - Audio feedback for enhanced user experience

### 🛠️ Technical Features
- **Content Security Policy** - Secure implementation with proper CSP headers
- **Event Delegation** - Optimized JavaScript performance
- **Cross-browser Compatibility** - Works on all modern browsers
- **SEO Optimized** - Proper HTML structure and meta tags
- **Performance Optimized** - Fast loading and smooth interactions

## 🚀 Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Design**: Glassmorphism, CSS Grid, Flexbox
- **Fonts**: Google Fonts (Cinzel Decorative, Lora, Playfair Display, Poppins)
- **Animations**: CSS Keyframes, Transitions
- **Audio**: Web Audio API for sound effects
- **Responsive**: Mobile-first design approach

## 📁 Project Structure

```
hotel-maharaja-menu/
├── index.html          # Main application file
├── images/             # Food item images
│   ├── butter_chicken.jpg
│   ├── chicken_biryani.jpg
│   └── ... (other dish images)
├── glass/              # Background and logo images
│   ├── hhh.jpg        # Background image
│   └── MG.png         # Hotel logo
└── README.md          # Project documentation
```

## 🛠️ Installation & Setup

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for best experience)

### Quick Start
1. **Clone or Download** the project files
2. **Open `index.html`** in your web browser
3. **Enjoy the interactive menu!**

### Local Development Server
For the best experience with all features:

```bash
# Using Python (if installed)
python -m http.server 8000

# Using Node.js (if installed)
npx serve .

# Open http://localhost:8000 in your browser
```

## 📱 Usage Guide

### For Customers
1. **Browse Categories** - Use the sticky navigation to jump to different menu sections
2. **View Menu Items** - Each dish includes image, description, and price
3. **Add to Cart** - Click the "Add" button to add items to your order
4. **Manage Order** - Use the floating cart button to view and modify your order
5. **Place Order** - Finalize your order through the modal interface

### Menu Categories
- **Soups** (Veg & Non-Veg)
- **Starters** (Veg & Non-Veg)
- **Main Course** (Veg & Non-Veg)
- **Rice & Noodles**
- **Beverages**
- **Desserts**

## 🎨 Customization

### Changing Menu Items
Edit the `menuData` object in the JavaScript section of `index.html`:

```javascript
const menuData = {
    "Soups (Veg)": [
        {
            name: "Your Dish Name",
            description: "Dish description",
            price: 150,
            image: "images/your-image.jpg",
            type: "veg"
        }
    ],
    // Add more categories and items...
};
```

### Customizing Colors
Modify CSS custom properties in the `:root` section:

```css
:root {
    --primary-color: #d4af37;    /* Gold */
    --secondary-color: #8b4513;  /* Brown */
    --accent-color: #cd853f;     /* Orange */
}
```

### Adding Sound Effects
Replace audio files in the `playSound()` function:

```javascript
function playSound(soundType) {
    // Add your custom audio files
}
```

## 📊 Browser Support

- ✅ Chrome 80+
- ✅ Firefox 75+
- ✅ Safari 13+
- ✅ Edge 80+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🏨 About Hotel Maharaja

Hotel Maharaja is a premium family restaurant located in Kudal, Sindhudurg, offering authentic Indian cuisine with modern presentation. This digital menu system enhances the dining experience with an elegant, interactive interface.

## 📞 Support

For support or questions:
- 📍 Location: Kudal, Sindhudurg
- 📞 Contact: +91-XXXX-XXXXXX
- 🕒 Hours: 10:00 AM - 11:00 PM

---

**Built with ❤️ for Hotel Maharaja**
