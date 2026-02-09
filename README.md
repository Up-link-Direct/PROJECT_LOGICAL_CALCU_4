# PROJECT_LOGICAL_CALCU_4
# Logic Calculator — Truth Table Generator

A beautiful, interactive logic calculator built with React that generates truth tables for propositional logic expressions. Features a glassmorphic design with animated backgrounds, particles, and a smooth curtain intro.

![BSIS 1-1 Project](https://img.shields.io/badge/BSIS-1--1-blue) ![React](https://img.shields.io/badge/React-18-61dafb) ![License](https://img.shields.io/badge/license-MIT-green)

## ✨ Features

### 🧮 Logic Operations
- **Built-in Operators**: AND, OR, XOR, NAND, NOR, XNOR, IMPLIES, EQUIV
- **Variable Support**: 2-4 variables (P, Q, R, S)
- **Custom Expressions**: Write your own logic expressions with support for:
  - Boolean operators: `&&`, `||`, `!`
  - Keywords: `AND`, `OR`, `NOT`
  - Special operators: `^` (XOR), `->` (implies), `<->` (equiv)
  - Parentheses for grouping

### 🎨 Design Features
- **Glassmorphism UI**: Frosted glass effect with blur and transparency
- **Animated Background**: Dynamic gradient with floating orbs
- **Particle System**: 35+ floating particles for ambient depth
- **Smooth Animations**: Card entrance, row stagger, hover effects
- **Curtain Intro**: Welcome screen with slide-out panels
- **Background Music**: Ambient looping soundtrack
- **Fully Responsive**: Mobile, tablet, and desktop optimized

### 🛠️ Functionality
- **CSV Export**: Copy truth table to clipboard in CSV format
- **Real-time Generation**: Instant table updates on input change
- **Error Handling**: Clear feedback for invalid expressions
- **Two-Page Layout**: Calculator and Team Members sections
- **Keyboard Accessible**: Full keyboard navigation support

## 🚀 Quick Start

### Installation
No installation required! This is a single-file HTML application.

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/logic-calculator.git
   cd logic-calculator
   ```

2. **Open in browser**
   ```bash
   # Windows
   start index.html
   
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   ```

### GitHub Pages Deployment

1. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to repository **Settings** → **Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** → **/ (root)**
   - Click **Save**

3. Your calculator will be live at: `https://yourusername.github.io/logic-calculator/`

## 📖 Usage Guide

### Basic Operation
1. **Click "Enter Calculator"** on the welcome screen
2. **Select number of variables** (2, 3, or 4)
3. **Choose an operator** from the dropdown
4. **Click "Generate"** to create the truth table
5. **Click "Copy CSV"** to export the table

### Custom Expressions
Switch operator to **"Custom Expression"** and enter your own logic:

**Examples:**
- `P AND Q` — Logical conjunction
- `!(P && Q) || R` — Negated AND or R
- `P -> (Q || R)` — If P then (Q or R)
- `P <-> Q` — P if and only if Q
- `(P ^ Q) && !R` — (P XOR Q) and not R

### Navigation
- **Calculator Tab**: Truth table generator
- **Members Tab**: Team information

## 🧰 Technologies

- **React 18** (production build via CDN)
- **Babel Standalone** for JSX transformation
- **CSS3** animations and glassmorphism
- **HTML5 Audio** for background music
- **Vanilla JavaScript** (no build tools required)

## 📁 Project Structure

```
logic-calculator/
├── index.html          # Main application file (all-in-one)
├── 0.jpg              # Team member photo
├── README.md          # This file
└── Bensound - Slow Motion.mp3  # Background music (optional)
```

## 🎵 Audio Setup

The calculator uses background music from Bensound. You can:

1. **Use CDN** (default): Links to Bensound's CDN
2. **Use Local File**: Place `music.mp3` in the same folder
3. **Disable**: Remove the `<audio>` tag from `index.html`

To use a local file, update line 677-679 in `index.html`:
```html
<audio id="bgMusic" loop preload="auto">
  <source src="./your-music-file.mp3" type="audio/mpeg">
</audio>
```

## 🎓 Educational Purpose

This project was created for **BSIS 1-1** (Bachelor of Science in Information Systems, Block 1-1) to demonstrate:
- Propositional logic and truth tables
- Boolean algebra operations
- React component architecture
- Modern CSS techniques (glassmorphism, animations)
- Single-file web application development

## 🌟 Key Highlights

- **Zero Dependencies**: No npm, no build process, no bundler
- **Production Ready**: Uses minified React production builds
- **GitHub Pages Compatible**: Deploy instantly with static hosting
- **Lightweight**: Single HTML file (~1200 lines)
- **Offline Capable**: Works without internet (except fonts/music CDNs)

## 🖥️ Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Opera 76+

## 📝 License

MIT License - feel free to use this project for learning or personal projects.

## 👥 Contributors

**John Bien Gojar** — Developer, BSIS 1-1

## 🙏 Acknowledgments

- **React Team** — For the amazing library
- **Bensound** — For royalty-free music
- **Google Fonts** — Poppins, JetBrains Mono, Orbitron

## 📮 Contact & Support

For questions or suggestions:
- Open an issue on GitHub
- Submit a pull request

---

**Made with ❤️ for BSIS 1-1** | [View Demo](https://yourusername.github.io/logic-calculator/)
