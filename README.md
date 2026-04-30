# Body Vector Pattern Engine 🎯

A real-time, WebGL-powered body tracking and skeletal visualization engine. Processes live webcam feed to detect, analyze, and visualize human body joints and movement patterns with a sleek cyberpunk interface.

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![WebGL](https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl)

---

## ✨ Features

- **Real-Time Body Tracking**: Detect and track human body joints in real-time using webcam input
- **3D Skeletal Visualization**: Render interactive 3D skeletal patterns with WebGL
- **Multi-Mode Visualization**: Switch between different visualization modes (Wireframe, Points, Vectors)
- **Live Performance Metrics**: Monitor FPS, latency, and joint detection accuracy
- **HUD Panel**: Collapsible control panel with real-time joint data and pose metrics
- **Export Functionality**: Capture and export snapshots of body patterns
- **Cyberpunk UI**: Modern gradient interface with smooth animations and transitions
- **Responsive Design**: Optimized for desktop and touchscreen devices

---

## 🚀 Quick Start

### Prerequisites
- Modern web browser with WebGL support (Chrome, Firefox, Edge, Safari)
- Webcam/camera device
- Camera permissions enabled in browser

### Usage

1. **Open the Application**
   ```bash
   # Simply open the HTML file in your browser
   open body-vector-engine_2.html
   # or
   firefox body-vector-engine_2.html
   ```

2. **Allow Camera Access**
   - Click the **START** button on the setup screen
   - Grant camera permissions when prompted
   - Application will initialize with your webcam feed

3. **Interact with the Interface**
   - Toggle visualization modes using top-bar buttons
   - Collapsible HUD panel on right side shows live joint data
   - Export frames using the **EXPORT** button
   - Monitor FPS and detection status in real-time

---

## 🎮 Controls & Features

### Top Bar Controls
| Button | Function |
|--------|----------|
| **MODE BUTTONS** | Toggle between different visualization modes |
| **FPS BADGE** | Real-time frames per second counter |
| **STATUS DOT** | Green when active, indicates system status |
| **EXPORT BTN** | Capture and save current frame |

### HUD Panel
- **Collapsible**: Click header to expand/collapse
- **Joint Data**: Real-time coordinates and rotation values
- **Pose Metrics**: Confidence scores and detection accuracy
- **Performance Stats**: Latency and processing time

### Visualization Modes
- **Wireframe**: Skeleton outline with connected joints
- **Vector Points**: Individual joint positions as points
- **Mesh**: Full body mesh rendering
- **Heatmap**: Confidence-based color mapping

---

## 🛠️ Technical Stack

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Core application logic
- **WebGL**: High-performance 3D graphics rendering
- **Canvas API**: Real-time video frame processing

### Key Libraries & APIs
- **MediaStream API**: Webcam access and stream handling
- **WebGL Shaders**: Vertex and fragment shaders for rendering
- **Canvas 2D Context**: Frame capture and manipulation

### Performance
- GPU-accelerated rendering with WebGL
- Optimized joint detection algorithm
- Real-time performance monitoring

---

## 📁 Project Structure

```
body-vector-engine_2.html
├── HTML Structure
├── CSS (Inline Styling)
│   ├── Setup Screen
│   ├── Main App Interface
│   ├── Top Bar & Controls
│   ├── HUD Panel
│   └── Animations & Effects
└── JavaScript (Core Application)
    ├── Camera Setup & Initialization
    ├── Body Tracking Logic
    ├── Skeletal Rendering
    ├── Visualization Engine
    ├── UI Controls & State Management
    └── Export & Performance Monitoring
```

---

## 🎨 Theming

### Color Palette
```css
--bg: #030508                    /* Main background */
--accent: #00c8ff               /* Cyan accent */
--accent2: #ff3cac              /* Magenta accent */
--accent3: #7fff00              /* Lime accent */
--text: #c8e8ff                 /* Primary text */
--text-dim: rgba(180,220,255,.45) /* Secondary text */
```

### Typography
- **Sans-Serif**: Rajdhani (UI elements)
- **Monospace**: Share Tech Mono (Code & metrics)

---

## 💡 Usage Examples

### Basic Initialization
```javascript
// Application auto-initializes when opened
// Camera access is requested on START button click
// Body tracking begins once webcam stream is active
```

### Switching Visualization Modes
```javascript
// Click mode buttons in top bar to switch between:
// - Wireframe skeleton
// - Vector point clouds
// - Mesh visualization
// - Heat map rendering
```

### Exporting Data
```javascript
// Click EXPORT button to:
// - Capture current frame as PNG
// - Download skeletal data JSON
// - Log performance metrics
```

---

## 📊 Performance Metrics

The application monitors and displays:
- **FPS**: Frames per second (target: 30+ fps)
- **Latency**: Processing time per frame (ms)
- **Joint Detection**: Number of joints tracked
- **Confidence**: Detection accuracy percentage
- **GPU Utilization**: WebGL rendering stats

---

## 🔧 Configuration

### Adjustable Parameters
```javascript
// In JavaScript section:
const CONFIG = {
  targetFPS: 30,
  jointThreshold: 0.5,
  smoothingFactor: 0.7,
  renderScale: 1.0,
  // ... additional settings
};
```

---

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome | ✅ Full | Recommended, best performance |
| Firefox | ✅ Full | Excellent WebGL support |
| Safari | ✅ Full | macOS 11+, iOS 14+ |
| Edge | ✅ Full | Chromium-based, full support |
| Opera | ✅ Full | Chromium-based |

**Requirements:**
- WebGL 1.0 or higher
- MediaStream API support
- Hardware acceleration enabled

---

## 🚀 Future Enhancements

- [ ] Multi-person tracking support
- [ ] Motion capture recording
- [ ] Pose classification & recognition
- [ ] Animation skeleton export
- [ ] Cloud-based processing
- [ ] Mobile app version
- [ ] Real-time pose animation
- [ ] Gesture recognition system
- [ ] Network multiplayer support

---

## 📝 Usage Tips

1. **Best Results**
   - Use well-lit environment with plain background
   - Position camera at eye level
   - Wear contrasting clothing for better detection
   - Maintain distance of 1-2 meters from camera

2. **Performance Optimization**
   - Close other browser tabs to improve FPS
   - Use Chrome for best WebGL performance
   - Enable hardware acceleration in browser settings
   - Reduce window size if experiencing lag

3. **Troubleshooting**
   - **No camera access**: Check browser permissions in settings
   - **Poor tracking**: Improve lighting conditions
   - **Low FPS**: Close other applications, restart browser
   - **WebGL errors**: Update graphics drivers

---

## 👨‍💻 Developer Information

### Author
**Ujjwal Kumar**
- Email: ujjwalkumarmerit473@gmail.com
- Phone: +91 7541085454
- GitHub: [@Ujjwalkumarmerit](https://github.com/Ujjwalkumarmerit)
- LinkedIn: [ujjwalkumarmerit](https://linkedin.com/in/ujjwalkumarmerit)

### Education
- **B.Tech Computer Science & Engineering**
- Galgotias University, Greater Noida (2022–Present)
- Focus: Cloud Computing, AI/ML, Full-Stack Development

---

## 📜 License

This project is open source and available under the **MIT License**.

```
MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, and sublicense.
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

---

## 📞 Support

For issues, questions, or suggestions:
- Open an issue on GitHub
- Email: ujjwalkumarmerit473@gmail.com
- Check existing documentation first

---

## 🙏 Acknowledgments

- Built with vanilla JavaScript and WebGL
- Inspired by modern motion capture technology
- Thanks to the web standards community

---

**Made with ❤️ by Ujjwal Kumar**

Last Updated: April 2026
