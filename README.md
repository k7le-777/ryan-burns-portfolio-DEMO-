# 💼 Ryan Burns - Portfolio Website

A responsive personal portfolio website showcasing my journey from self-taught developer to bootcamp graduate, featuring projects, skills, and professional experience.

[🌐 **View Live Site**](https://k7le-777.github.io/ryan-burns-portfolio-DEMO-/) | [📝 **View Code**](https://github.com/k7le-777/ryan-burns-portfolio-DEMO-)

---

## 📋 About

Built as **Week 1 project for Step8Up's Level 4 Full Stack Bootcamp**, this portfolio represents my professional presence as a developer. It showcases my self-taught learning journey through The Odin Project and my transition into structured bootcamp training.

This is more than a project—it's my **digital handshake** with potential employers and collaborators.

---

## ✨ Features

- 🎨 **Professional Design** - Clean, modern interface focused on content
- 📱 **Fully Responsive** - Mobile-first approach, works on all devices
- 🎯 **Project Showcase** - Highlighting technical projects with descriptions
- 💼 **About Section** - My journey from warehouse worker to developer
- 🛠️ **Skills Display** - Technical skills and technologies I work with
- 📬 **Contact Information** - Multiple ways to connect with me
- ⚡ **Fast Loading** - Optimized performance and clean code
- ♿ **Accessible** - Semantic HTML and ARIA labels where needed

---

## 🛠️ Technologies

- **HTML5** - Semantic markup and structure
- **CSS3** - Custom styling, Flexbox, Grid, animations
- **Responsive Design** - Media queries for all screen sizes
- **GitHub Pages** - Free hosting and deployment
- **Git** - Version control and deployment workflow

---

## 🧠 Design Philosophy

### User Experience First

**Goal:** Make it easy for recruiters and employers to:
- Understand who I am in 10 seconds
- See my best work immediately
- Contact me without friction
- Get a sense of my personality and passion

### Mobile-First Approach

Built mobile-first, then enhanced for larger screens because:
- Many recruiters view portfolios on phones
- Forces focus on essential content
- Easier to scale up than scale down
- Better performance on all devices

### Accessibility Matters

- Semantic HTML for screen readers
- Sufficient color contrast for readability
- Clear focus states for keyboard navigation
- Alt text for images
- Logical heading hierarchy

---

## 🎨 Sections Overview

### 1. Hero Section
**First impression matters**
- Clear name and title
- Professional photo (optional)
- Concise tagline: "Self-Taught Developer | Bootcamp Graduate"
- Call-to-action buttons (View Work, Contact)

### 2. About Me
**My story in brief**
- Journey from warehouse work to coding
- 6 months self-study through The Odin Project
- Transition to intensive bootcamp
- What drives my passion for development

### 3. Projects
**Showcasing technical ability**
- Featured projects with live demos
- Technologies used for each
- Brief description of challenges solved
- Links to GitHub and deployed versions

### 4. Skills
**Technical competencies**
- Languages: JavaScript, HTML5, CSS3
- Tools: Git, Webpack, VS Code
- Frameworks: React, Node.js (learning)
- Soft Skills: Problem-solving, Communication

### 5. Contact
**Easy to reach**
- Email address
- LinkedIn profile
- GitHub profile
- Contact form (optional)

---

## 💡 Code Highlights

### Responsive Navigation
```css
/* Mobile-first navigation */
nav {
  display: flex;
  flex-direction: column;
}

/* Desktop navigation */
@media (min-width: 768px) {
  nav {
    flex-direction: row;
    justify-content: space-between;
  }
}
```

### Project Cards
```html
<div class="project-card">
  <img src="project-screenshot.png" alt="Project name">
  <h3>Project Title</h3>
  <p class="tech-stack">JavaScript | HTML | CSS</p>
  <p>Brief description of the project and what it demonstrates.</p>
  <div class="project-links">
    <a href="live-demo-url">Live Demo</a>
    <a href="github-url">View Code</a>
  </div>
</div>
```

### Smooth Scroll Navigation
```javascript
// Smooth scroll to sections
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    const target = document.querySelector(this.getAttribute('href'));
    target.scrollIntoView({ behavior: 'smooth' });
  });
});
```

---

## 🚀 Getting Started

### View Online
Visit [**my portfolio**](https://k7le-777.github.io/ryan-burns-portfolio-DEMO-/) to see it live!

### Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/k7le-777/ryan-burns-portfolio-DEMO-.git
cd ryan-burns-portfolio-DEMO-
```

2. **Open in browser**
```bash
open index.html
```

### Deploy to GitHub Pages

1. Go to repository Settings
2. Navigate to Pages section
3. Select branch: `main`, folder: `/ (root)`
4. Save and wait for deployment
5. Site will be live at: `https://k7le-777.github.io/ryan-burns-portfolio-DEMO-/`

---

## 🎯 Goals Achieved

✅ **Professional presence** - Established digital identity  
✅ **Showcase projects** - Highlighted technical abilities  
✅ **Tell my story** - Shared unique journey authentically  
✅ **Easy to contact** - Multiple connection points  
✅ **Mobile responsive** - Works on all devices  
✅ **Fast deployment** - Live within hours of starting  

---

## 🔮 Planned Improvements

### Short-term
- [ ] Add smooth animations and transitions
- [ ] Implement dark mode toggle
- [ ] Add project filter by technology
- [ ] Include testimonials section
- [ ] Optimize images for faster loading

### Long-term
- [ ] Blog section for technical writing
- [ ] Interactive JavaScript features
- [ ] Convert to React for easier updates
- [ ] Add analytics to track visitors
- [ ] Create case studies for major projects
- [ ] Multi-language support (English/Spanish)

---

## 📚 Lessons Learned

### Technical Skills
- **GitHub Pages deployment** - Understanding static site hosting
- **Responsive design patterns** - Mobile-first methodology
- **CSS Grid and Flexbox** - Modern layout techniques
- **Performance optimization** - Image compression, minification
- **Version control** - Git workflow for deployments

### Professional Development
- **Personal branding** - How to present myself as a developer
- **Content writing** - Articulating my journey clearly
- **Portfolio best practices** - What recruiters look for
- **Call-to-action design** - Guiding visitors to next steps

### Key Insight
> "A portfolio isn't just about showing what you've built—it's about showing who you are as a developer. My story of self-teaching, recognizing my limits, and seeking mentorship is just as important as my code."

---

## 📊 Portfolio Strategy

### Content Decisions

**What to Include:**
- Best 4-6 projects (quality over quantity)
- Clear technology stack for each project
- Live demos AND GitHub links (show the work)
- Authentic "About Me" story
- Professional but personable tone

**What to Exclude:**
- Tutorial projects (unless significantly modified)
- Broken or unfinished projects
- Too much technical jargon
- Generic stock photos
- Overly long descriptions

### Continuous Updates

I treat this portfolio as a **living document**:
- Add new projects as I complete them
- Update skills as I learn them
- Refine copy based on feedback
- Improve design as I grow
- Keep contact info current

---

## 🙏 Acknowledgments

- **Step8Up Bootcamp** - Week 1 project guidance
- **The Odin Project** - Teaching me the fundamentals
- **Developer community** - Portfolio inspiration
- **Bootcamp peers** - Feedback and suggestions

---

## 🤝 Let's Connect!

This portfolio is just the beginning. I'm actively seeking **junior developer opportunities** where I can:
- Contribute to meaningful projects
- Learn from experienced developers
- Grow my skills in a collaborative environment
- Build solutions that make a difference

### Reach Out:
- 💼 [LinkedIn](https://www.linkedin.com/in/ryan-burns-rb/)
- 📧 [Email](mailto:kyleburns7.kb@yahoo.com)
- 💻 [GitHub](https://github.com/k7le-777)
- 🌐 [Portfolio](https://k7le-777.github.io/ryan-burns-portfolio-DEMO-/)

---

<div align="center">

**My Journey: Self-Taught → Bootcamp → Your Team**

From asking *"How is a page fundamentally made?"*  
to building solutions that matter.

Open to opportunities | Based in Aylesbury, UK | Remote/Hybrid

⭐ Feedback welcome—star if you found this inspiring!

</div>