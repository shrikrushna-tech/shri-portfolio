# 🌐 Shrikrushna Satav — Personal Portfolio Website

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Live-brightgreen?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

> A clean, responsive personal portfolio website showcasing my skills, projects, certifications, and journey as a Full Stack Developer.

---

## 📸 Preview

> Open `portfolio.html` in your browser to view the full site.

---

## 🚀 Features

- ✅ **Fully Responsive** — works on mobile, tablet, and desktop
- 🖼️ **Profile Photo** — embedded directly in the hero section
- 🏆 **Real Certificates** — Cisco, NASSCOM, and Infosys Springboard certs with lightbox viewer
- 🎨 **Warm Editorial Design** — Playfair Display + Outfit fonts, cream/terracotta color palette
- ⚡ **Smooth Animations** — scroll-reveal effects and skill bar animations
- 📬 **Contact Form** — with client-side validation
- 🗂️ **Single File** — no build tools or dependencies needed

---

## 📁 Project Structure

```
portfolio/
│
├── portfolio.html        # Main portfolio file (all-in-one: HTML + CSS + JS)
└── README.md             # Project documentation
```

> All assets (profile photo, certificates) are embedded as Base64 inside `portfolio.html` — no external image files required.

---

## 🛠️ Tech Stack

| Layer      | Technology                        |
|------------|-----------------------------------|
| Markup     | HTML5                             |
| Styling    | CSS3 (Custom Properties, Grid, Flexbox) |
| Scripting  | Vanilla JavaScript (ES6+)         |
| Fonts      | Google Fonts (Playfair Display, Outfit, Space Mono) |
| Icons      | SVG inline icons + Emoji          |

---

## 📂 Sections

| # | Section       | Description                                      |
|---|---------------|--------------------------------------------------|
| 1 | **Hero**      | Name, title, profile photo, CTA buttons, stats   |
| 2 | **About**     | Profile info card, personal bio, tech tags       |
| 3 | **Skills**    | Frontend, Backend, Database, Tools with bar chart|
| 4 | **Projects**  | Hospital Management System with live UI mockup   |
| 5 | **Certificates** | Cisco, NASSCOM, Infosys — with lightbox viewer|
| 6 | **Journey**   | Timeline of learning milestones 2022–2026        |
| 7 | **Contact**   | Links + contact form with validation             |

---

## 🏆 Certifications Included

| Certificate | Issuer | Date |
|---|---|---|
| Introduction to Modern AI | Cisco Networking Academy | Feb 16, 2026 |
| Yuva AI for All | INDIAai · NASSCOM FutureSkills Prime | Feb 16, 2026 |
| Basics of Python | Infosys Springboard | Sep 30, 2025 |

---

## ⚙️ How to Run

No setup required — just open the file in a browser:

```bash
# Option 1: Simply double-click portfolio.html

# Option 2: Serve locally with Python
python -m http.server 8000
# Then open http://localhost:8000/portfolio.html

# Option 3: Use VS Code Live Server extension
# Right-click portfolio.html → "Open with Live Server"
```

---

## 🌍 Deployment

You can deploy this portfolio for free on any static hosting platform:

### Netlify (Recommended)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop `portfolio.html` onto the deploy zone
3. Your site is live instantly ✅

### GitHub Pages
```bash
# 1. Create a new GitHub repository
git init
git add portfolio.html README.md
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main

# 2. Go to Settings → Pages → Source: main branch → Save
# 3. Your site will be live at: https://YOUR_USERNAME.github.io/portfolio
```

### Vercel
```bash
npm i -g vercel
vercel --prod
```

---

## ✏️ Customization

To personalize this portfolio, open `portfolio.html` and update:

```html
<!-- 1. Your name -->
<h1 class="hero-name">Shrikrushna<span class="accent">.</span><br>Satav</h1>

<!-- 2. Your email -->
<a href="mailto:YOUR_EMAIL@example.com">

<!-- 3. Your LinkedIn & GitHub URLs -->
<a href="https://linkedin.com/in/YOUR_HANDLE">
<a href="https://github.com/YOUR_USERNAME">

<!-- 4. Stats in hero section -->
<div class="stat-num">3+</div>   <!-- Projects -->
<div class="stat-num">8+</div>   <!-- Technologies -->
```

To change the **color theme**, update the CSS variables at the top:

```css
:root {
  --accent: #c84b2f;   /* Primary accent color (terracotta red) */
  --bg: #f8f5f0;       /* Background color (warm cream) */
  --ink: #1a1410;      /* Text color */
}
```

---

## 📬 Contact

| Platform | Link |
|----------|------|
| 📧 Email | shrikrushna.satav@email.com |
| 💼 LinkedIn | [linkedin.com/in/shrikrushna-satav](https://linkedin.com/in/shrikrushna-satav) |
| 🐙 GitHub | [github.com/shrikrushna-satav](https://github.com/shrikrushna-satav) |

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

Feel free to use this as a template for your own portfolio — just replace the content with your own details!

---

<div align="center">

Made with ❤️ by **Shrikrushna Satav** · © 2026

</div>
