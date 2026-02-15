# Nandini Mamillapalli - Portfolio Website

A modern, responsive portfolio website showcasing my work in Machine Learning, AI, and Full Stack Development.

## 🌐 Live Demo

**[View Live Portfolio](https://6991bda8be9967cec172d7d7--fastidious-naiad-e0de7b.netlify.app/)**

## 🚀 Features

- **Animated Neural Network Background** - Interactive background with moving nodes and connections
- **Smooth Animations** - Scroll-triggered reveal animations and hover effects
- **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern Design** - Clean, professional UI with gradient accents
- **SEO Optimized** - Proper meta tags and semantic HTML

## 📁 Project Structure

```
portfolio-website/
├── index.html      # Main HTML file
├── style.css       # All styles and animations
├── script.js       # JavaScript for interactions and animations
└── README.md       # This file
```

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- Vanilla JavaScript
- Google Fonts (Outfit, JetBrains Mono)

## 📦 Deployment on Netlify

### Option 1: Deploy via GitHub

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/imNandini19/portfolio.git
   git push -u origin main
   ```

2. **Deploy on Netlify**
   - Go to [Netlify](https://www.netlify.com/)
   - Click "Add new site" → "Import an existing project"
   - Connect your GitHub account
   - Select your portfolio repository
   - Click "Deploy site"
   - Your site will be live in a few minutes!

3. **Custom Domain (Optional)**
   - Go to Site settings → Domain management
   - Add your custom domain

### Option 2: Deploy via Drag & Drop

1. Go to [Netlify](https://www.netlify.com/)
2. Drag and drop the entire `portfolio-website` folder into the Netlify interface
3. Your site will be deployed instantly!

### Option 3: Deploy via Netlify CLI

1. **Install Netlify CLI**
   ```bash
   npm install -g netlify-cli
   ```

2. **Login to Netlify**
   ```bash
   netlify login
   ```

3. **Deploy**
   ```bash
   netlify deploy --prod
   ```

## 🎨 Customization

### Adding Project Screenshots

1. **Create an `images` folder** in your portfolio directory:
   ```
   portfolio-website/
   ├── images/
   │   ├── project1.png
   │   ├── project2.png
   │   └── ...
   ├── index.html
   ├── style.css
   └── script.js
   ```

2. **Take screenshots** of your projects:
   - Open your project in browser
   - Take a clean screenshot (recommended size: 1200x800px)
   - Save as PNG or JPG
   - Name them meaningfully (e.g., `expense-tracker.png`)

3. **Update HTML** - Replace emoji with image:
   ```html
   <!-- Before -->
   <div class="project-visual">🎯</div>
   
   <!-- After -->
   <div class="project-visual">
       <img src="images/escalation-classifier.png" alt="Escalation Risk Classifier Screenshot">
   </div>
   ```

4. **Tips for great screenshots**:
   - Use actual project running (not just code)
   - Show the UI/interface
   - Make sure it's clear and high quality
   - For ML projects: show results, graphs, or demo interface
   - Crop out unnecessary parts

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary: #00D9FF;      /* Cyan */
    --secondary: #FF006E;    /* Pink */
    --accent: #FFB800;       /* Gold */
    --dark: #0B0C10;         /* Dark background */
}
```

### Content
Update your information in `index.html`:
- Personal details
- Projects
- Skills
- Achievements
- Contact information

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

This project is open source and available for personal use.

## 👤 Author

**Venkata Nandini Mamillapalli**
- GitHub: [@imNandini19](https://github.com/imNandini19)
- LinkedIn: [iamnandini19](https://linkedin.com/in/iamnandini19)
- Email: nandinii78159@gmail.com

## 🙏 Acknowledgments

- Google Fonts for the beautiful typography
- Inspiration from modern portfolio designs
- Built with passion for ML & AI

---

**Made with ❤️ by Nandini**
