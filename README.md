# madebyjoe

A minimalist, animated personal portfolio website featuring a typewriter effect that introduces Joe and showcases his various projects and services.

## ✨ Features

- **Animated Typewriter Effect**: Smooth word-by-word animation with customizable speed
- **Responsive Design**: Optimized for both desktop and mobile devices
- **Modern UI**: Clean, dark theme with orange accent colors
- **Interactive Links**: Hover effects and smooth transitions
- **Social Media Integration**: LinkedIn, Instagram, and Discord links
- **Performance Optimized**: Efficient CSS animations using CSS custom properties

## 🚀 Live Demo

Visit the live site: [madebyjoe.co](https://madebyjoe.co)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Custom properties (CSS variables) for animation control
  - Keyframe animations for typewriter effect
  - Flexbox for responsive layout
  - Media queries for mobile optimization
- **Google Fonts**: Montserrat font family
- **SVG Icons**: Custom social media icons

## 📁 Project Structure

```
madebyjoe/
├── index.html              # Main portfolio page
├── archive/
│   └── index_script_typewriter.html  # Alternative version with JavaScript
└── README.md               # This file
```

## 🎨 Customization

### Animation Speed Control

The animation speed can be easily adjusted by modifying the CSS custom property in `index.html`:

```css
:root {
    --global-speed: 2; /* Change this value to control all animation speeds */
}
```

- Higher values = faster animations
- Lower values = slower animations

### Color Scheme

The current color scheme uses:
- Background: `#191919` (dark gray)
- Text: `#ffffff` (white) with varying opacity levels
- Accent: `#f74f14` (orange) for links and hover effects

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop screens (1200px+)
- Tablet devices (768px - 1199px)
- Mobile devices (< 768px)

## 🔧 Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/madebyjoe.git
   cd madebyjoe
   ```

2. **Open in browser**:
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. **View the site**:
   - Navigate to `http://localhost:8000` (or the port shown in your terminal)

## 📝 Content

The portfolio showcases Joe's work across multiple domains:

- **🎨 Graphics**: [joe.graphics](https://joe.graphics)
- **🎬 Digital Assets & 3D**: [fromtheroot.studio](https://fromtheroot.studio)
- **🤖 AI Research**: [syntheticlabs.xyz](https://syntheticlabs.xyz)
- **🖥️ Infrastructure**: [cerebral.studio](https://cerebral.studio)
- **🔧 Automation**: [context.agency](https://context-agency.webflow.io)

## 📧 Contact

- **Email**: [hello@madebyjoe.co](mailto:hello@madebyjoe.co)
- **LinkedIn**: [joeconstanti](https://www.linkedin.com/in/joeconstanti/)
- **Instagram**: [ftr.studio](https://www.instagram.com/ftr.studio/)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

While this is a personal portfolio, suggestions and improvements are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 🙏 Acknowledgments

- Inspired by minimalist design principles
- Built with modern web standards
- Optimized for performance and accessibility

---

*Made with ❤️ by Joe* 