# Portfolio Website - 3D & Embedded Developer

A modern, responsive portfolio website showcasing expertise in 3D development and embedded systems integration.

## 🎯 Project Overview

This portfolio website features a clean, professional design with smooth animations and interactive elements, designed to highlight projects and skills at the intersection of 3D development and embedded systems.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Smooth Animations**: CSS-based fade-in animations with delay sequencing
- **Project Showcase**: Featured projects section with detailed cards
- **Technology Tags**: Visual tech stack indicators for each project
- **Modern UI**: Clean, professional design with consistent color scheme

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Custom styling with animations and responsive design
- **JavaScript**: Interactive elements and animations

### Project Technologies Featured
- **Python**: Automation and scripting
- **Blender API**: 3D pipeline tools
- **Three.js & WebGL**: 3D web visualization
- **Embedded Systems**: Hardware integration projects

## 📁 Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── styles.css             # Main stylesheet
├── script.js              # JavaScript functionality
├── assets/                # Images, icons, and other assets
│   ├── images/
│   └── icons/
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code, Sublime Text, etc.)
- (Optional) Local server for testing

### Installation

1. **Clone or Download**
   ```bash
   git clone [repository-url]
   ```
   Or download the ZIP file and extract it

2. **Open in Browser**
   - Simply open `index.html` in your web browser
   - For best development experience, use a local server:
     ```bash
     # Python 3
     python -m http.server 8000
     
     # or with Node.js
     npx serve
     ```

## 🎨 Customization

### Content Updates
1. **Projects**: Add new projects in the projects section following the existing card structure
2. **Skills**: Update skill tags in the projects section
3. **Styling**: Modify colors, fonts, and animations in `styles.css`

### Adding New Projects
To add a new project card, copy the following template:

```html
<div class="project-card animate-fade-in">
    <div class="project-visual">
        [EMOJI or IMAGE]
    </div>
    <div class="project-content">
        <h3 class="project-title">Project Title</h3>
        <p class="project-description">
            Project description goes here.
        </p>
        <div class="skill-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### Style Customization
- **Colors**: Modify CSS variables in `styles.css`
- **Animations**: Adjust timing in animation classes
- **Layout**: Change grid settings for different screen sizes

## 📱 Responsive Breakpoints

The website uses the following responsive breakpoints:

- **Mobile**: < 768px (single column layout)
- **Tablet**: 768px - 1024px (adjusted grid layouts)
- **Desktop**: > 1024px (full grid layouts)

## 🎯 Performance Considerations

- Minimal external dependencies
- Optimized CSS animations (GPU accelerated where possible)
- Semantic HTML for accessibility
- Progressive enhancement approach

## 🔧 Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or feedback, please reach out through:
- **Email**: [lampkengking@gmail.com]
- **LinkedIn**: [Your LinkedIn Profile]
- **Portfolio**: [Live Website URL]

---

**Note**: This portfolio template is designed to be easily customizable. Feel free to adapt it to your specific needs and personal brand.
