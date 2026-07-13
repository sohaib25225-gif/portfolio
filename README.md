# Sohaib Ahmad — Portfolio Website

A modern, responsive personal portfolio website showcasing projects, experience, and skills in AI/ML and full stack development. Built as a single-page application with clean design, smooth animations, and a developer-focused aesthetic.

## Description

This portfolio website serves as a professional online presence for Sohaib Ahmad, a BSAI student and Full Stack Developer Intern. The site features a dark theme with cyan and violet accent colors, terminal-style UI elements, and a grid-based background that reflects a technical, modern aesthetic. It includes sections for about, experience, certifications, projects, skills, and contact information.

## Features

- **Responsive Design**: Fully responsive layout that adapts to mobile, tablet, and desktop screens
- **Single-Page Application**: Smooth scrolling navigation between sections
- **Terminal-Styled Hero Section**: Interactive terminal component with typing cursor animation
- **Project Showcase**: Grid-based project cards with hover effects and external links to GitHub repositories
- **Timeline Component**: Visual timeline for experience and education history
- **Certification Display**: Cards showcasing professional certifications
- **Skills Section**: Tagged skill pills displaying technical competencies
- **Contact Section**: Multiple contact methods including email, phone, LinkedIn, and GitHub
- **Scroll Reveal Animations**: Sections fade in as they enter the viewport
- **Custom Typography**: Uses Space Grotesk, Inter, and JetBrains Mono fonts for a modern developer aesthetic
- **Accessibility Features**: Respects prefers-reduced-motion user preferences

## Tech Stack

- **HTML5**: Semantic markup structure
- **CSS3**: Custom properties (CSS variables), Grid, Flexbox, animations, media queries
- **JavaScript (Vanilla)**: Intersection Observer API for scroll animations, mobile menu toggle
- **Google Fonts**: Space Grotesk, Inter, JetBrains Mono
- **Git**: Version control

## Project Structure

```
PortFolio/
├── assets/
│   └── profile.jpg          # Profile photo used in hero section
├── index.html               # Main HTML file (contains all code)
├── .git/                    # Git repository data
└── README.md                # This file
```

The entire website is built as a single HTML file with inline CSS (in `<style>` tags) and inline JavaScript (in `<script>` tags). This approach makes it lightweight, fast to load, and easy to deploy.

## Installation & Setup

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server or build tools required

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/sohaib25225-gif/PortFolio.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd PortFolio
   ```

3. **Open the website**
   - Simply open `index.html` in your web browser by double-clicking it, or
   - Use a local development server (optional, for better file:// protocol handling):
     ```bash
     # If you have Python 3 installed:
     python -m http.server 8000

     # If you have Node.js installed:
     npx serve
     ```
   - Then navigate to `http://localhost:8000` in your browser

## Usage

Once the website is open in your browser:

- **Navigation**: Click navigation links in the header to jump to different sections (About, Experience, Certifications, Projects, Contact)
- **View Projects**: Click on any project card to visit the corresponding GitHub repository
- **Contact**: Use the contact section to reach out via email, phone, LinkedIn, or GitHub
- **Mobile Menu**: On smaller screens, click the menu button (☰) to access navigation

### Customization

To customize this portfolio for your own use:

1. Open `index.html` in a text editor
2. Update personal information:
   - Line 6: Page title
   - Line 7: Meta description
   - Lines 282-293: Hero section content
   - Lines 321-332: About section text and facts
   - Lines 342-360: Experience and education timeline
   - Lines 370-388: Certifications
   - Lines 399-475: Projects (update links, descriptions, and tech stack tags)
   - Lines 486-494: Skills
   - Lines 506-511: Contact information
3. Replace `assets/profile.jpg` with your own photo
4. Modify CSS variables (lines 12-22) to change the color scheme

## Author

**Sohaib Ahmad**

- **GitHub**: [https://github.com/sohaib25225-gif](https://github.com/sohaib25225-gif)
- **LinkedIn**: [https://www.linkedin.com/in/sohaib-ahmad-181478367](https://www.linkedin.com/in/sohaib-ahmad-181478367)
- **Email**: sohaib25225@gmail.com
- **Location**: Shabqadar, Charsadda, Pakistan
- **Education**: BSAI (4th Semester), Abasyn University, Peshawar
- **Current Role**: Full Stack Developer Intern @ Decode Labs

---

*Built with HTML, CSS & JavaScript — 2026*
