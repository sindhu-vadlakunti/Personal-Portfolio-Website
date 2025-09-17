# Sindhu Vadlakunti - Portfolio Website

A modern, responsive, and interactive portfolio website showcasing my skills, projects, and experience as an aspiring Software Engineer and AI Enthusiast.

## 🌟 Features

- **Modern UI/UX** with smooth animations and transitions
- **Fully Responsive** design that works on all devices
- **Dark/Light Mode** toggle with system preference detection
- **Interactive Elements** with custom cursor effects
- **Animated Sections** using GSAP and ScrollTrigger
- **Project Showcase** with detailed descriptions and technologies used
- **Skills Section** organized by categories
- **Certifications Timeline** to display achievements
- **Contact Form** with client-side validation
- **Performance Optimized** for fast loading
- **SEO Friendly** with proper meta tags

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (v14 or higher) and npm (for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Install dependencies** (if you want to customize or build)
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   # For live development with hot-reload
   npx live-server
   ```
   Or simply open the `index.html` file in your browser.

## 🛠 Customization

### Personal Information

1. Open `index.html` and update the following sections:
   - Update the hero section with your name and title
   - Modify the about section with your personal information
   - Update the contact information

2. Update the profile picture:
   - Replace `images/profile.jpg` with your profile picture
   - Recommended size: 350x450px

### Projects

Edit the `projectsData` array in `js/main.js` to add/update your projects:

```javascript
const projectsData = [
  {
    title: 'Project Title',
    category: 'Project Category',
    description: 'Project description...',
    technologies: ['Tech 1', 'Tech 2', 'Tech 3'],
    image: 'images/projects/project-image.jpg',
    links: [
      { icon: 'github', url: '#' },
      { icon: 'external-link-alt', url: '#' }
    ]
  },
  // Add more projects as needed
];
```

### Skills

Update the `skillsData` array in `js/main.js` to reflect your skills:

```javascript
const skillsData = [
  {
    category: 'Category Name',
    icon: 'fas fa-icon-name',
    skills: ['Skill 1', 'Skill 2', 'Skill 3']
  },
  // Add more skill categories as needed
];
```

### Certifications & Awards

Update the `certificationsData` array in `js/main.js`:

```javascript
const certificationsData = [
  {
    title: 'Certification/Award Title',
    company: 'Issuing Organization',
    date: 'Year',
    description: 'Brief description...'
  },
  // Add more certifications/awards as needed
];
```

## 🎨 Styling

The website uses CSS variables for easy theming. You can update the color scheme by modifying the variables in `css/style.css`:

```css
:root {
  --primary-color: #00f7ff;
  --secondary-color: #b700ff;
  --accent-color: #ff00f7;
  --dark-color: #0a0a1a;
  --darker-color: #050510;
  --light-color: #ffffff;
  --gray-color: #a0a0b0;
  /* ... */
}
```

## 📱 Responsive Design

The website is fully responsive and works on all device sizes. The layout adjusts based on the screen width:

- **Desktop**: Full layout with side navigation
- **Tablet**: Stacked layout with adjusted spacing
- **Mobile**: Single column layout with a hamburger menu

## 🚀 Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Repository Settings > Pages
3. Select the `main` branch and click Save
4. Your site will be live at `https://username.github.io/repository-name`

### Netlify

1. Drag and drop the project folder to Netlify
2. Your site will be deployed automatically
3. Configure custom domain if needed

### Vercel

1. Import your GitHub repository to Vercel
2. Vercel will automatically detect the project and deploy it
3. Configure custom domain if needed

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [GSAP](https://greensock.com/gsap/) for animations
- [Particles.js](https://vincentgarreau.com/particles.js/) for the background effect
- [AOS](https://michalsnik.github.io/aos/) for scroll animations

## 📧 Contact

- Email: 22r11a05j2@gcet.edu.in
- LinkedIn: [sindhusanjeev](https://www.linkedin.com/in/sindhusanjeev)
- GitHub: [yourusername](https://github.com/yourusername)

---

Made with ❤️ by Sindhu Vadlakunti
