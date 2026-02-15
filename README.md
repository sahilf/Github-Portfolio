# Sahil Fayaz - Portfolio Website

A modern, responsive portfolio website built with Jekyll and hosted on GitHub Pages.

## 📚 Education

| Institution | Degree | Duration | GPA |
|-------------|--------|----------|-----|
| Texas A&M University | Master of Computer Science | Aug 2024 - Present | 4/4 |
| PES University | Bachelor of Technology, Electronics and Communication Engineering | Aug 2017 - May 2021 | 9.24/10 |

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

## 💻 Skills

### Languages & Softwares
Java, Python, Matlab, HTML/CSS, MySQL, PostgreSQL, Neo4j, Mariadb, Springboot, Angular, Ruby, Rails, Flutter

### Java Skills & Libraries
REST APIs, Microservices Architecture, Spring Security, Messaging Systems

### Tools
Jenkins, Bitbucket, GitHub, JIRA, Docker

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

## 🚀 Recent Projects

### SpyderStack (Apr 2025 - Present)
- Built a distributed web crawler using goroutines and Redis pub/sub to enable scalable, concurrent scraping of job listings.
- Achieved 100K+ job entries crawled daily from over 200+ company career pages in under 15 minutes using an 8-core setup.
- Optimized data ingestion pipeline with batch based lazy MongoDB writes and a lightweight scraping framework, improving throughput and reducing system load.

### United States Space Force (USSF) GRC Control (Aug 2024 - Dec 2024)
- Developed a Ruby on Rails-based SaaS application for the USSF, enabling cybersecurity teams to efficiently scan and assess Docker images for vulnerabilities, ensuring compliance with NIST SP800-53 controls.
- Implemented advanced access control and versioning features, allowing USSF to track and manage Docker image vulnerabilities over time, ensuring continuous GRC compliance and security across environments.

### Lunch Calorie Prediction (Aug 2024 - Dec 2024)
- Developed a deep learning pipeline to predict calorie counts from lunch food images, integrating multimodal data (glucose levels, microbiome, demographics) for personalized nutrition predictions.
- Applied contrastive learning with CLIP models to fuse image and numerical embeddings, achieving accurate calorie predictions with Root Mean Squared Relative Error (RMSRE).
  
### Automation In Agricultural Field Using Decentralised Framework (Aug 2020 - May 2021)
- Designed a decentralized system, where bots autonomously allocate areas among themselves, generate paths within their designated zones, and traverse within them.
- Introduced a novel path-planning method for optimal navigation efficiency within a polygon. Published at IEEE International Conference on Electronics, Computing, and Communication Technologies (CONECCT), 2021. [Link](https://ieeexplore.ieee.org/document/9622347)

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

## 🏆 Achievements
- Gold Medal for securing 8th rank in Electronics & Communication Department, PES University.
- Second Place in Texas A&M's Tidal Hackathon among 300 student participants for building a contextual E-Reader.

## 👥 Leadership

### Rotaract Club of PES University
**Secretary & Director of Operations** (Aug 2019 - Jun 2021)
- As an Operations Director, responsible for logistics associated with various projects such as SUKH (Share yoUr Knowledge Happily) – a fundraiser for donating books to underprivileged students, The Gutsy Entrepreneur – a flagship business ideathon, Trek To Educate – a fundraiser trek conducted for computer literacy in rural areas.
- Volunteered for the Polio Vaccination Drive on National Immunisation Day.
- As a Secretary, worked on the Literacy Day bulletin and helped to organize and coordinate over 50 events in 2020-21.

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

- **Email**: sahilf2085@gmail.com / sahil.fayaz8899@gmail.com
- **LinkedIn**: [linkedin.com/in/sahil-f](https://www.linkedin.com/in/sahil-f/)
- **GitHub**: [github.com/sahilfayaz](https://github.com/sahilfayaz)

## 📄 License

This project is open source and available under the MIT License.

---

**Note**: Remember to update your GitHub username in the URLs and configure your repository settings for GitHub Pages deployment.
