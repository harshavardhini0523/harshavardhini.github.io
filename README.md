# Harshavardhini - Portfolio Website

A modern, responsive portfolio website showcasing skills, projects, and experience.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, mobile navigation, contact form
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized assets and efficient code
- **Cross-browser Compatible**: Works on all modern browsers

## 🚀 Live Demo

Visit the live website: [Your GitHub Pages URL]

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── Harshavardhini Resume - L.pdf  # Resume file
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with flexbox, grid, and animations
- **JavaScript**: Interactive features and dynamic content
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font family for typography

## 📋 Sections

1. **Hero/Home**: Introduction and call-to-action
2. **About**: Personal information and statistics
3. **Skills**: Technical skills organized by category
4. **Projects**: Featured projects with descriptions and links
5. **Experience**: Work experience timeline
6. **Contact**: Contact form and information

## 🚀 Deployment Options

### Option 1: GitHub Pages (Recommended)

1. **Create a new repository** on GitHub (name it `your-username.github.io` for user page or any name for project page)

2. **Upload your files** to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Access your site** at: `https://your-username.github.io/your-repo-name`

### Option 2: Netlify

1. **Visit [Netlify](https://netlify.com)** and sign up
2. **Drag and drop** your project folder to Netlify dashboard
3. **Your site** will be deployed automatically with a random URL
4. **Optional**: Set up custom domain in site settings

### Option 3: Vercel

1. **Visit [Vercel](https://vercel.com)** and sign up
2. **Import your project** from GitHub
3. **Deploy** with default settings
4. **Access your site** at the provided URL

### Option 4: Local Development

```bash
# Navigate to project directory
cd portfolio

# Option 1: Python HTTP Server
python -m http.server 8000

# Option 2: Node.js HTTP Server (if you have Node.js)
npx serve .

# Option 3: PHP Built-in Server (if you have PHP)
php -S localhost:8000
```

Visit `http://localhost:8000` in your browser.

## ✏️ Customization Guide

### 1. Personal Information

**Update HTML content** in `index.html`:
- Replace "Harshavardhini" with your name
- Update the hero description
- Modify the about section text
- Update contact information

**Update social links**:
```html
<!-- In the social-links section -->
<a href="https://github.com/your-username" target="_blank">
<a href="https://linkedin.com/in/your-profile" target="_blank">
<a href="mailto:your.email@example.com">
```

### 2. Skills Section

**Modify skills** in the skills section:
```html
<div class="skill-items">
    <span class="skill-item">Your Skill</span>
    <span class="skill-item">Another Skill</span>
    <!-- Add more skills -->
</div>
```

### 3. Projects Section

**Update project cards**:
```html
<div class="project-card">
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Your project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/your-username/project" target="_blank">
            <a href="https://your-project-demo.com" target="_blank">
        </div>
    </div>
</div>
```

### 4. Experience Section

**Update timeline items**:
```html
<div class="timeline-item">
    <div class="timeline-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p class="timeline-date">Start Date - End Date</p>
        <ul>
            <li>Your achievement or responsibility</li>
            <li>Another achievement</li>
        </ul>
    </div>
</div>
```

### 5. Colors and Styling

**Change the color scheme** in `styles.css`:
```css
/* Update the gradient colors */
background: linear-gradient(135deg, #your-color1 0%, #your-color2 100%);

/* Update primary colors */
:root {
    --primary-color: #your-primary-color;
    --secondary-color: #your-secondary-color;
}
```

### 6. Resume File

Replace `Harshavardhini Resume - L.pdf` with your own resume file and update the link in the HTML.

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🔧 Development

### Prerequisites

- Text editor (VS Code, Sublime Text, etc.)
- Modern web browser
- Basic knowledge of HTML, CSS, and JavaScript

### Making Changes

1. **Edit files** using your preferred text editor
2. **Refresh browser** to see changes
3. **Test responsiveness** using browser dev tools
4. **Commit changes** to git when satisfied

### Performance Tips

- **Optimize images**: Use WebP format and appropriate sizes
- **Minify CSS/JS**: Use tools like [CSS Minifier](https://cssminifier.com/)
- **Enable caching**: Add appropriate headers if self-hosting
- **Use CDNs**: For external libraries (already implemented)

## 📞 Support

If you need help customizing or deploying your portfolio:

1. **Check the documentation** above
2. **Search for solutions** on Stack Overflow
3. **GitHub Issues**: Create an issue if you find bugs
4. **Community**: Join web development communities for help

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

## 🙏 Credits

- **Design Inspiration**: Modern portfolio trends
- **Icons**: Font Awesome
- **Fonts**: Google Fonts (Inter)
- **Colors**: Custom gradient palette

---

**Happy coding!** 🚀 Make this portfolio your own and showcase your amazing work to the world.