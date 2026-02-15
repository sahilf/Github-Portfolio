# Sahil Fayaz - Portfolio Website

A modern, responsive portfolio website built with Jekyll and hosted on GitHub Pages.

## 🌟 Features

- **Modern Design**: Clean, professional layout with gradient hero section
- **Responsive**: Fully responsive design that works on all devices
- **Sections**:
  - Hero/Introduction
  - About Me
  - Technical Skills
  - Work Experience (Timeline view)
  - Featured Projects
  - Education
  - Leadership & Community
  - Contact Information
- **Smooth Animations**: Fade-in effects and hover interactions
- **SEO Optimized**: Meta tags and sitemap for better search visibility
- **Fast Loading**: Optimized CSS and minimal JavaScript

## 🚀 Quick Start

### Prerequisites
- Ruby (2.7 or higher)
- Bundler gem

### Local Development

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Run locally:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View in browser:**
   Open `http://localhost:4000` in your browser

### Deploying to GitHub Pages

1. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Updated portfolio"
   git push origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository settings
   - Navigate to "Pages" section
   - Select source: `main` branch
   - Your site will be live at `https://yourusername.github.io/portfolio`

## 📁 Project Structure

```
portfolio/
├── _layouts/
│   └── default.html          # Main layout template
├── assets/
│   └── css/
│       └── style.scss        # Custom styles
├── _config.yml               # Jekyll configuration
├── index.html                # Homepage
├── projects.md               # Detailed projects page
├── Gemfile                   # Ruby dependencies
└── README.md                 # This file
```

## 🎨 Customization

### Adding Your Photo

1. Add your headshot image to `assets/img/` folder
2. Uncomment and update in `_config.yml`:
   ```yaml
   logo: /assets/img/your-photo.png
   ```

### Updating Content

- **Personal Info**: Edit `_config.yml` for basic information
- **Homepage**: Edit `index.html` to update sections
- **Projects**: Edit `projects.md` to add more project details
- **Styling**: Modify `assets/css/style.scss` for design changes

### Color Scheme

Colors are defined in CSS variables in `style.scss`:
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #1e40af;
  /* Modify these to change the color scheme */
}
```

## 🔧 Technologies Used

- **Jekyll**: Static site generator
- **GitHub Pages**: Hosting
- **HTML5/CSS3**: Structure and styling
- **SCSS**: CSS preprocessing
- **Markdown**: Content formatting

## 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: < 768px

## 🎯 Future Enhancements

- [ ] Add blog section
- [ ] Integrate Google Analytics
- [ ] Add dark mode toggle
- [ ] Include resume download
- [ ] Add project filtering
- [ ] Implement contact form with backend

## 📧 Contact

- **Email**: sahilf2085@gmail.com
- **LinkedIn**: [linkedin.com/in/sahil-f](https://www.linkedin.com/in/sahil-f/)
- **GitHub**: [github.com/sahilfayaz](https://github.com/sahilfayaz)

## 📄 License

This project is open source and available under the MIT License.

---

**Note**: Remember to update your GitHub username in the URLs and configure your repository settings for GitHub Pages deployment.
