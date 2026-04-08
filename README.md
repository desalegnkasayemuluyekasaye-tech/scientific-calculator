# 🧮 Advanced Scientific Calculator PWA

A comprehensive Progressive Web App (PWA) calculator with advanced mathematical functions, binomial theorem calculations, and interactive graphing capabilities.

## 🚀 **Live Demo**

**[Try the Calculator](https://github.com/desalegnkasayemuluyekasaye-tech/scientific-calculator)**

## ✨ **Features**

### 📱 **Progressive Web App**

- ✅ **Installable** on any device (phones, tablets, computers)
- ✅ **Works offline** with service worker caching
- ✅ **App-like experience** with custom icon and full-screen mode
- ✅ **Fast loading** with optimized performance
- ✅ **Responsive design** for all screen sizes

### 🧮 **Calculator Modes**

#### **Basic Calculator**

- Standard arithmetic operations (+, -, ×, ÷)
- Memory functions (MS, MR, MC, M+, M-)
- Percentage calculations
- Sign toggle and backspace

#### **Advanced Scientific**

- Trigonometric functions (sin, cos, tan, sec, csc, cot)
- Inverse trigonometric functions
- Logarithmic functions (log, ln, log₂)
- Exponential functions (eˣ, 10ˣ, xʸ)
- Square root, cube root, factorial
- Constants (π, e)
- Angle mode switching (degrees/radians)

#### **Binomial Theorem Calculator**

- Full binomial expansion: (a + b)ⁿ
- Specific term calculation
- Coefficient finder
- Constant term finder
- Middle term(s) calculation
- Support for fractional expressions like (x - 4/x)ⁿ
- Two-variable binomial expansions

#### **Advanced Function Grapher**

- Plot multiple functions simultaneously
- Support for polynomial, trigonometric, exponential, and logarithmic functions
- Interactive zoom and pan
- Function analysis at specific points
- Customizable graph settings (range, grid, colors)
- Real-time function preview

#### **Combinatorics & Statistics**

- Permutations P(n,r)
- Combinations C(n,r)
- Factorial calculations
- Binomial coefficients
- Quick combinatorics functions

#### **Additional Features**

- Calculus operations (derivatives, integrals)
- Equation solver
- Polynomial operations
- Matrix calculations
- GPA calculator
- Calculation history with local storage

## 🛠️ **Technologies Used**

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)** - Core functionality and PWA features
- **Math.js** - Advanced mathematical computations
- **Service Worker** - Offline functionality and caching
- **Web App Manifest** - PWA configuration
- **Canvas API** - Interactive graphing and visualizations

## 📱 **Installation**

### **On Mobile Devices:**

1. Open the calculator URL in your mobile browser
2. Look for "Add to Home Screen" or "Install" prompt
3. Tap "Install" to add the app to your home screen
4. Launch like any native app!

### **On Desktop:**

1. Open the calculator URL in Chrome, Edge, or Firefox
2. Look for the install button (⊕) in the address bar
3. Click "Install" to add to your applications
4. Access from your desktop or start menu!

## 🚀 **Getting Started**

### **Basic Usage:**

1. **Select a mode** using the tabs at the top
2. **Enter calculations** using the on-screen buttons or keyboard
3. **View history** by clicking the history button
4. **Switch between modes** for different mathematical operations

### **Advanced Features:**

- **Binomial Expansion:** Enter expressions like `(x + 2)^5` or `(2x - 3/x)^4`
- **Graphing:** Add multiple functions and customize the display
- **Scientific Functions:** Use trigonometric and logarithmic operations
- **Memory Functions:** Store and recall values across calculations

## 🎯 **Use Cases**

- **Students:** Homework, exams, and learning mathematical concepts
- **Engineers:** Quick calculations and function analysis
- **Researchers:** Statistical analysis and data processing
- **Teachers:** Demonstrating mathematical concepts and graphing
- **General Use:** Everyday calculations with advanced features when needed

## 🔧 **Development**

### **Local Development:**

```bash
# Clone the repository
git clone https://github.com/yourusername/scientific-calculator.git

# Navigate to the project directory
cd scientific-calculator

# Open in your preferred code editor
code .

# Serve locally (optional)
python -m http.server 8000
# or
npx serve .
```

### **Deployment Note**

- When deploying to static hosts (GitHub Pages, Netlify, etc.), ensure an `index.html` exists at the site root. This repository includes `index.html` which redirects to `calculate.htm` so the site root won't return a 404.

### **File Structure:**

```
📁 scientific-calculator/
├── 📄 calculate.htm          # Main HTML file
├── 📄 calculate.js           # JavaScript functionality
├── 📄 calculate.css          # Styling and responsive design
├── 📄 manifest.json          # PWA configuration
├── 📄 sw.js                  # Service worker for offline functionality
├── 🖼️ icon-16.png            # Favicon (16x16)
├── 🖼️ icon-32.png            # Favicon (32x32)
├── 🖼️ icon-192.png           # Mobile icon (192x192)
├── 🖼️ icon-512.png           # Desktop icon (512x512)
└── 📄 README.md              # This file
```

## 🌟 **Key Features Showcase**

### **Binomial Theorem Excellence**

- Handles complex expressions like `(x - 4/x)^6`
- Finds constant terms automatically
- Supports multi-variable expansions
- Shows step-by-step calculations

### **Advanced Graphing**

- Plot functions like `sin(x) * exp(-x/5)`
- Interactive coordinate display
- Multiple functions with different colors
- Zoom, pan, and analysis tools

### **PWA Benefits**

- Works completely offline
- Installs like a native app
- Fast loading with caching
- Cross-platform compatibility

## 🤝 **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### **Areas for Contribution:**

- Additional mathematical functions
- UI/UX improvements
- Performance optimizations
- New calculator modes
- Bug fixes and testing

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 **Acknowledgments**

- **Math.js** library for advanced mathematical computations
- **Font Awesome** for beautiful icons
- **Progressive Web App** standards for modern web capabilities
- **Mathematical community** for inspiration and feature requests

## 📞 **Support**

If you encounter any issues or have questions:

- 🐛 **Report bugs** by opening an issue
- 💡 **Request features** through GitHub issues
- 📧 **Contact:** [desalegnkasayemuluyekasaye@gmail.com]
- 🌟 **Star this repo** if you find it useful!

---

**Made with ❤️ for the mathematical community**

_Transform your device into a powerful scientific calculator with just one click!_
