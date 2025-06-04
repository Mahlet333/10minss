# Ten Minutes - Living Comic 🕐

An interactive web-based comic experience that explores the complex decisions students face in their daily lives. This project combines storytelling, interactive elements, and modern web technologies to create an engaging narrative experience.

## 🌟 Features

### Interactive Storytelling
- **Time-Based Narrative**: Experience a 10-minute journey through a student's life with a real-time countdown
- **Branching Paths**: Make critical choices that affect the story's outcome (e.g., "STAY & CHAT" vs "RUN TO ROOM")
- **Dynamic Panels**: Interactive comic panels with sound effects and atmospheric audio
- **Immersive Experience**: Full-screen mode (⤢) for distraction-free reading
- **Sound Integration**: Background sounds and effects for each panel
- **Stress System**: Increasing tension as time runs low

### Modern UI/UX
- **Responsive Design**: Seamless experience across all devices
- **Comic-Style Aesthetics**: Custom fonts (Permanent Marker, Architects Daughter) and visual effects
- **Smooth Animations**: Panel transitions, click effects, and stress animations
- **Accessible Navigation**: Keyboard controls (arrow keys) and touch-friendly interface
- **Mobile Menu**: Responsive navigation with burger menu
- **Interactive Elements**: Click effects, panel explosions, and atmospheric animations

### Technical Features
- **Pure HTML/CSS/JavaScript**: No external dependencies required
- **Optimized Performance**: Efficient DOM manipulation and image loading
- **Mobile-First Approach**: Designed for all screen sizes with specific breakpoints
- **Cross-Browser Compatibility**: Works on modern browsers
- **Sound Management**: Dynamic audio loading and cleanup
- **Responsive Images**: Automatic panel sizing and aspect ratio maintenance

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of web development (for customization)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ten-minutes.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ten-minutes
   ```
3. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

## 📁 Project Structure

```
ten-minutes/
├── index.html          # Main HTML file with comic structure
├── style.css          # Styles, animations, and responsive design
├── script.js          # Interactive functionality and story logic
├── assets/           # Media files
│   ├── images/      # Comic panel images (1.png through 15.png)
│   ├── team/        # Team member photos (naz.png, khater.png, mahlet.png, bilal.png)
│   └── sounds/      # Audio files for panels and effects
└── README.md         # Project documentation
```

## 🎨 Customization

### Story Structure
The story is defined in `script.js` with the following key elements:
- 15 unique panels with branching paths
- Two major decision points:
  1. Friend interaction (STAY & CHAT vs RUN TO ROOM)
  2. Room choices (MAKE RAMEN vs DO LAUNDRY)
- Each panel includes:
  - Caption text
  - Image path
  - Sound effects
  - Next panel logic
  - Choice options (where applicable)

### Modifying Styles
- Main styles are in `style.css`
- Custom fonts: Permanent Marker and Architects Daughter
- Color scheme: Primary (#ff6b35), Secondary (#ffc107), Background (#2c3e50)
- Responsive breakpoints:
  - Mobile: < 480px
  - Tablet: 481px - 768px
  - Desktop: > 768px

### Team Page
Team members are managed in `script.js` with the following structure:
```javascript
{
    name: String,
    role: String,
    image: String,
    bio: String
}
```

## 🛠️ Technical Details

### CSS Features
- Custom animations (explode, stressFloat, shake, ripple)
- Responsive design using CSS Grid and Flexbox
- Mobile-first media queries
- Custom font integration
- Advanced hover effects and interactions
- Comic-style card designs
- Dynamic panel sizing

### JavaScript Features
- Dynamic panel loading and management
- 10-minute timer with stress system
- Choice management and story branching
- Modal system for about page and panel details
- Responsive navigation with mobile menu
- Fullscreen mode toggle
- Team page generation
- Sound effect management
- Click effects and animations

### Performance Optimizations
- Optimized image loading with error handling
- Efficient DOM manipulation
- Smooth animations with hardware acceleration
- Responsive image handling
- Mobile-friendly interactions
- Sound cleanup on panel changes
- Memory management for animations

## 📱 Responsive Design

The application is fully responsive with specific optimizations for:
- Desktop computers (> 768px)
- Tablets (481px - 768px)
- Mobile phones (< 480px)
- Different screen orientations
- Mobile menu for smaller screens
- Dynamic panel sizing
- Touch-friendly controls

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Custom fonts from Google Fonts (Permanent Marker, Architects Daughter)
- Inspiration from traditional comic books
- Sound effects from Pixabay
- Support from the student community

## 📞 Contact

For questions, feedback, or collaboration:
- Email: ma7030@nyu.edu
- Project Link: https://mahlet333.github.io/10minss/

## 👥 Team

### Irem Naz Celen
Creative Director

### Abdelrahman Khater
Lead Developer

### Mahlet Atrsaw 
Developer and Visual Designer

### Ahmed Bilal
UX Researcher

---

Made with ❤️ by the Ten Minutes Team 
