# Personal Portfolio - Dhanush Devaraj

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 📁 Project Structure

```
personal_website/
├── index.html          # Main portfolio page
├── styles.css          # Styling and responsive design
├── script.js           # Interactive features
└── README.md           # This file
```

## 🎨 Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Scrolling**: Easy navigation between sections
- **Mobile Menu**: Hamburger menu for mobile devices
- **Contact Form**: Integrated email form
- **Modern UI**: Professional color scheme and typography
- **Animations**: Smooth fade-in and hover effects
- **SEO Friendly**: Proper HTML structure and meta tags

## 📝 Customization Guide

### 1. **Basic Information**
   - Edit the meta tags in `index.html` (title, description)
   - Update your name throughout the document
   - Change the job title from "Executive" to your actual title

### 2. **About Section**
   - Replace the placeholder text with your professional summary
   - Update years of experience
   - Update education details

### 3. **Professional Experience**
   - Add your work experience in the Timeline section
   - Include company name, position, dates, and description
   - You can add more `timeline-item` div elements as needed

### 4. **Skills**
   - Modify the skill cards in the Skills section
   - Update the skill names and descriptions
   - Add or remove skill cards as needed

### 5. **Projects**
   - Replace "Project Title" with your actual projects
   - Add project descriptions
   - Update project tags to reflect your work
   - Replace placeholder images with actual project screenshots
   - Add links to live projects or GitHub repositories

### 6. **Contact Information**
   - Update email: Change `dhanushdevaraj@gmail.com` to your email
   - Update LinkedIn: Already set to `linkedin.com/in/dhanushdevaraj97`
   - Add other social media links as needed

### 7. **Colors**
   - Modify the CSS variables in `styles.css` under `:root`
   - Main colors:
     - `--primary-color`: Main dark color (#2c3e50)
     - `--secondary-color`: Accent blue (#3498db)
     - `--accent-color`: Red accent (#e74c3c)

## 🚀 How to Use

1. **Open locally**: Double-click `index.html` in your file explorer, or
2. **Use a local server**: 
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (with http-server)
   npx http-server
   ```
   Then open `http://localhost:8000` in your browser

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎯 Next Steps

1. Fill in your personal information
2. Add your professional experience
3. Update skills with your expertise
4. Add your projects with descriptions
5. Test on different devices
6. Deploy to a hosting service (GitHub Pages, Netlify, Vercel, etc.)

## 🌐 Deployment Options

- **GitHub Pages**: Free hosting with version control
- **Netlify**: Easy drag-and-drop deployment
- **Vercel**: Optimized for web performance
- **Traditional Hosting**: Any web server that serves static files

## 🔁 CI / CD: GitHub Pages (automatic)

This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml` that automatically deploys the site to GitHub Pages whenever you push to the `personalportfolio` branch.

Quick steps to publish:

```bash
# create the branch (if not already)
git checkout -b personalportfolio
git add .
git commit -m "Add portfolio and Pages workflow"
git push -u origin personalportfolio
```

After the push the workflow will run (check the Actions tab). Once the job completes your site will be published by GitHub Pages — the URL will typically be `https://<your-github-username>.github.io/<repo-name>/`.

If you prefer a manual snapshot build directory, update the workflow's `path` in `.github/workflows/deploy.yml` to point to that folder (for example `build` or `public`).

## 📧 Contact Form

The contact form uses a mailto link to open the user's default email client. For a more robust solution, you can:
- Use a backend service (Node.js, Python, etc.)
- Use third-party services (Formspree, Basin, etc.)
- Connect to a serverless function

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Feel free to use this template for your personal portfolio.

---

**Happy Building! 🚀**
