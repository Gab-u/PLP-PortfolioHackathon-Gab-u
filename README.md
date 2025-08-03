
# 🚀 Gabriel Sakwa - Portfolio Website

Welcome to my personal **Portfolio Website**, built using **HTML5** and **CSS3**. This responsive single-page application highlights my profile, education, skills, and contact information in a clean and elegant layout.

---

## 📂 Project Structure

```
portfolio-website/
│
├── index.html              # Main HTML file with all sections
├── styles.css              # CSS styling (responsive & desktop)
├── bghome.png              # Background image for the home section
├── image.png               # Profile image in the about section
├── CV Gabriel Sakwa.pdf    # Resume/CV for download
└── README.md               # Project documentation
```

---

## 🌐 Live Demo

The site is hosted on netlify
[Netlify](https://gab-u.netlify.app/)

---

## 🛠 Technologies Used

- **HTML5**
- **CSS3**
- **Flaticon Icon Libraries** for menu, social icons, and calendars
- **Responsive Design** with `@media queries`

---

## 🧰 Features

- Fully responsive layout: Works seamlessly on desktop, tablet, and mobile.
- Sticky navigation header with smooth scrolling.
- Hero section with call-to-action buttons.
- Clean “About Me” and “Skills” section.
- Timeline layout for education and experience.
- Styled contact form (non-functional – placeholder only).
- Footer with copyright.
- Animated elements for enhanced visual appeal.

---

## 🔧 Setup Instructions

1. **Clone or download** this repository.
   ```bash
   git clone https://github.com/yourusername/portfolio-website.git
   ```
2. **Open the project** in any code editor (e.g., VS Code).
3. You can preview the site by simply **opening `index.html` in your browser**.
4. Optional: Upload the project to **GitHub** or deploy using **Netlify/Vercel**.

---

## 📱 Responsive Design

This portfolio uses **media queries** to adapt to different screen sizes:
- `max-width: 1024px` – Tablets
- `max-width: 768px` – Small tablets
- `max-width: 480px` – Mobile phones

To test responsiveness:
1. Open `index.html` in your browser.
2. Use Chrome DevTools (F12 → Toggle Device Toolbar) to preview mobile/tablet layouts.

---

## ✍️ Customization Guide

You can easily personalize the website by editing the following:

| Section         | File         | What to Change                          |
|----------------|--------------|------------------------------------------|
| Name/Logo       | `index.html` | Line inside `<a class="logo">Gabriel</a>` |
| Hero Message    | `index.html` | Text inside `<section class="home">`      |
| About Me        | `index.html` | Text inside `<section class="about">`     |
| Skills          | `index.html` | List under `<section class="skills">`     |
| Education       | `index.html` | Timeline under `<section class="education">` |
| Profile Picture | `image.png`  | Replace image file                       |
| Resume          | `CV Gabriel Sakwa.pdf` | Replace with your PDF            |

---

## ❗ Limitations

- Contact form is **non-functional** (no backend).
- Menu toggle button exists (`#menu-icon`) but requires **JavaScript** to function.
- No animations on scroll unless added manually or via JS.

---

## ✅ To Do (Future Enhancements)

- Add JavaScript to toggle the mobile menu.
- Connect the contact form to a form handler like **Formspree**, **Netlify Forms**, or **Google Forms**.
- Add animations using `AOS` or `GSAP`.
- Include a dark/light mode toggle.

---

## 📄 License

This project is open-source and free to use. You may modify and share it for personal and educational use. Attribution appreciated!

---

## 🙋‍♂️ Author

**Gabriel Sakwa**  
[GitHub](https://github.com/Gab-u) | [LinkedIn](https://www.linkedin.com/in/gabrielsakwa/) | gabrielsakwa@gmail.com

---

_Thanks for visiting my portfolio! Let's build something amazing together._
