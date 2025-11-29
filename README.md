# UnbundI

# Responsive Landing Page (HTML, CSS, JavaScript)

A fully responsive single‑page landing website built with semantic HTML, modern CSS, and vanilla JavaScript. It includes six core sections commonly used in product or agency landing pages and is suitable for front‑end assessments, portfolio projects, and practice converting Figma designs to code. [web:11]

---

## ✨ Features

- Sticky top navigation bar with smooth scrolling to sections. [web:11]  
- Responsive hero section with headline, supporting text, primary and secondary call‑to‑action buttons, and image placeholder. [web:47]  
- Features section with three cards to highlight key value propositions. [web:47]  
- About section with two‑column layout and statistic cards. [web:47]  
- Pricing section with three pricing tiers and a highlighted “Popular” plan. [web:47]  
- Testimonials section with three client quotes and roles. [web:47]  
- Contact / Call‑to‑Action section with simple form (name + email). [web:11]  
- Mobile‑friendly layout using CSS Grid, Flexbox, and media queries. [web:27]  

---

## 🧱 Tech Stack

- **HTML5** – Semantic structure for all sections (`header`, `section`, `footer`, etc.). [web:11]  
- **CSS3** – Custom styling using Flexbox, Grid, CSS variables, and responsive breakpoints. [web:27]  
- **Vanilla JavaScript** – Mobile navigation toggle and smooth scrolling for internal links. [web:11]  

No external frameworks (React, Bootstrap, Tailwind, etc.) are used, which aligns with typical HTML/CSS/JS assignment requirements. [web:47]  

---

## 📂 Project Structure


You can add an optional `assets/` folder for images or icons if required by your design. [web:11]  

---

## 🚀 Getting Started

### Prerequisites

This is a static project, so you only need a modern web browser (Chrome, Edge, Firefox, Safari) and a code editor such as VS Code. [web:54]  

### Local Setup

1. **Clone or download** this repository into a local folder. [web:60]  
2. Open the project folder in your editor. [web:54]  
3. Open `index.html` directly in a browser (double‑click or drag into the browser), or run a simple static server (for example VS Code Live Server) to preview changes with auto‑reload. [web:11]  
4. Resize the browser window to verify the layout on desktop, tablet, and mobile widths. [web:27]  

---

## 🛠 Usage & Customization

### Updating Content

- Edit headings, paragraphs, and button labels inside `index.html` to match the content from your Figma design or assignment brief. [web:11]  
- Replace placeholder texts in the Features, About, Pricing, Testimonials, and Contact sections with real copy. [web:47]  

### Styling

- Global color variables are defined at the top of `style.css` (`--primary`, `--bg`, etc.); adjust them to match your brand colors. [web:47]  
- Modify font sizes, spacing, and card styles in the relevant CSS sections (e.g., `.hero`, `.grid-3`, `.card`, `.price-card`) to better mirror the given UI. [web:27]  
- Add custom fonts using `@import` or `<link>` from services like Google Fonts in `index.html` if your design specifies them. [web:11]  

### Behavior

- The hamburger icon toggles the mobile navigation by adding/removing the `.open` class on the nav element. You can enhance this with animations or active‑link highlighting in `script.js`. [web:11]  
- Smooth scrolling is implemented for in‑page links (`href="#section-id"`). Extend this logic if you want scroll‑spy or intersection‑observer‑based effects. [web:11]  

---

## 🌐 Deployment

Because this is a static site, deployment is straightforward on most hosting services. [web:11]  

### GitHub Pages

1. Push the project to a GitHub repository. [web:60]  
2. In the repo settings, enable GitHub Pages and select the **main branch / root** as the source. [web:60]  
3. After a few minutes, GitHub will provide a public URL like:  

   `https://your-username.github.io/your-repo-name`  

4. Test the URL on desktop and mobile to ensure responsiveness. [web:27]  

### Netlify / Vercel (Alternative)

- Create a new site, link your Git repository, and choose the root folder as the publish directory (no build command needed). [web:11]  
- Once deployed, update the “Live Demo” link below. [web:11]

-

---

## ✅ Assignment Notes

If this project is being used for a front‑end assessment based on a Figma design:

- Select any six sections from the Figma file and map each one to the corresponding section in `index.html` (e.g., hero, features, about, pricing, testimonials, contact). [web:47]  
- Adjust spacing, fonts, colors, and alignments in `style.css` so that the visual output closely matches the Figma design while maintaining clean, semantic markup. [web:47]  
- Ensure mobile and tablet breakpoints match the design’s responsive behavior, as responsiveness is a key evaluation criterion. [web:27]  

---

## 📄 License & Credits

This project uses only self‑written HTML, CSS, and JavaScript intended for learning and assessment purposes. When adapting it from a Figma file or tutorial, respect any design licenses and avoid copying proprietary text or assets without permission. [web:55]
