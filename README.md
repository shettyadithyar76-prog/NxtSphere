# NxtSphere — Personal Portfolio

Hi, I am Adithya Shetty. This repository contains NxtSphere, my personal developer portfolio built from scratch using pure HTML5 and CSS3. 

I deliberately built this without JavaScript, frameworks, or external CSS libraries to focus on mastering core web fundamentals: semantic structure, Flexbox, CSS Grid, responsive design, and CSS-driven interactivity.

I am a first-year Computer Science and Engineering (Artificial Intelligence) student at NIAT in ALARD University, Pune. Coding, exploring emerging technologies, and learning how humans perceive and interact with software are what drive me, with the long-term goal of building high-impact systems at MAANG companies.

---

## What It Features

- Pure CSS Dark Mode: An interactive theme toggle built without JavaScript using `:has(#theme-toggle:checked)`. It swaps custom CSS variables for backgrounds, borders, card surfaces, and text contrast.
- Wireframe Blueprint Alignment: Built to follow an assessment wireframe layout, keeping a unified 1080px grid boundary, balanced column heights in the About section, and consistent horizontal margins.
- Clean 5-Column Skills Grid: Realistic, honest self-ratings for my current skill level (HTML, CSS, Python, JavaScript, and Communication) paired with lightweight SVG icons and subtle progress bars.
- Project Cards: Two side-by-side cards highlighting projects I have worked on, with descriptions, technology tags, and direct links to their repositories.
- Zero Horizontal Scrolling: Enforced strict root container rules (`max-width: 100%` and `overflow-x: hidden`) tested across mobile, tablet, and widescreen viewports (320px up to 1920px).
- Functional Contact Form & Socials: Direct contact details with icons, a contact form, and links to my developer and coding profiles.

---

## Tech Stack

- HTML5: Semantic markup (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`)
- CSS3: Custom properties, Flexbox, CSS Grid, media queries, smooth scrolling
- Vector Graphics: Handcrafted inline SVG icons
- External Dependencies: None

---

## Project Structure

```text
NxtSphere/
├── images/
│   ├── profile-avatar.svg         # Hero avatar illustration
│   ├── about-illustration.svg     # Academic / IDE mockup graphic
│   ├── project-1.svg              # Injection Dojo cybersecurity terminal preview
│   └── project-2.svg              # Tinybench benchmarking chart preview
├── screenshots/
│   ├── desktop-screenshot.png     # Desktop preview (Light Mode)
│   ├── desktop-dark-screenshot.png# Desktop preview (Dark Mode)
│   └── mobile-screenshot.png      # Mobile responsive preview
├── index.html                     # Semantic website markup
├── style.css                      # Unified styles, themes, and responsive rules
└── README.md                      # Project documentation
```

---

## Projects Featured

1. [Injection Dojo](https://github.com/sarthakchambhare16-wdym/injection-dojo)
   - Hacktoberfest team project focused on AI prompt injection security.
   - Built as an interactive practice ground where students learn how prompt injection vulnerabilities occur and how to defend against them.

2. [Tinybench](https://github.com/shettyadithyar76-prog/tinybench)
   - A solo open-source project written in Python.
   - A lightweight benchmarking utility designed to profile throughput, memory overhead, and latency across open-weight AI models.

---

## Skills & Current Progress

| Skill | Category | Rating | Notes |
| :--- | :--- | :---: | :--- |
| HTML | Frontend | 96% | Semantic markup, accessibility, clean document hierarchy |
| CSS | Frontend | 94% | Flexbox, CSS Grid, responsive design, dark mode variables |
| Python | Systems & AI | 90% | Scripting, benchmarking tools, algorithm foundations |
| JavaScript | Frontend | 68% | Intermediate DOM manipulation, ES6 syntax, working knowledge |
| Communication | Interpersonal | 96% | Collaboration, hackathons, technical presentation |

---

## Profiles & Connect

- LinkedIn: [adithya-shetty-096229436](https://www.linkedin.com/in/adithya-shetty-096229436/)
- GitHub: [@shettyadithyar76-prog](https://github.com/shettyadithyar76-prog)
- LeetCode: [@Funke_Codez](https://leetcode.com/u/Funke_Codez/)
- Kaggle: [@adithyacodez](https://www.kaggle.com/adithyacodez)

---

## Running Locally

Because there are no package managers or build tools required, running the site locally takes just a second:

1. Clone or download this repository:
   ```bash
   git clone https://github.com/shettyadithyar76-prog/NxtSphere.git
   cd NxtSphere
   ```
2. Open `index.html` directly in your web browser, or use VS Code Live Server / Python HTTP server:
   ```bash
   python -m http.server 8000
   ```

---

## Hosting on GitHub Pages

1. Push this repository to GitHub.
2. In your repository, go to Settings > Pages.
3. Under Build and deployment > Source, select Deploy from a branch.
4. Set the branch to main and folder to / (root), then click Save.
5. GitHub will deploy the site at `https://"yourusername".github.io/NxtSphere/`.

---

## License

This project is licensed under the MIT License.
