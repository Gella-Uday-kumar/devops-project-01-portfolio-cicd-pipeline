# Uday's Portfolio

A personal portfolio website for **Gella Uday Kumar** — DevOps Engineer | Cloud Enthusiast | Automating the Future.

Built with plain HTML, CSS, and JavaScript — no frameworks, no build step. Clone it, open it, and it just works.

🔗 **Live Demo:** https://Gella-Uday-kumar.github.io/portfolio/
*(replace `Gella-Uday-kumar` / `portfolio` above if your username or repo name is different)*

## Preview

![Portfolio Preview](assets/preview.png)

## Features

- Responsive dark-themed design with animated gradient accents and a glowing profile ring
- Light / dark theme toggle
- Sections: Home, About, Skills, Experience, Projects, Certifications, Contact
- Scroll-spy navigation that highlights the active section
- Mobile-friendly hamburger menu
- Clickable contact details (email, phone, location) and social links (GitHub, LinkedIn)
- Downloadable resume button
- Contact form with client-side confirmation message

## Tech Stack

- HTML5
- CSS3 (custom properties, Grid, Flexbox, animations)
- Vanilla JavaScript (no dependencies)
- [Google Fonts](https://fonts.google.com/) — Poppins & Inter

## Project Structure

```
portfolio/
├── index.html              # Main page markup
├── style.css                # All styling
├── script.js                 # Theme toggle, nav, scroll-spy, contact form
├── assets/
│   ├── profile.png           # Profile photo
│   ├── preview.png            # Screenshot used in this README
│   └── Gella_Uday_Kumar_Resume.pdf   # Downloadable resume
└── README.md
```

## Getting Started

### Run locally

1. Clone the repo:
   ```bash
   git clone https://github.com/Gella-Uday-kumar/portfolio.git
   cd portfolio
   ```
2. Open `index.html` directly in your browser, **or** serve it locally for the best experience (e.g. with the VS Code "Live Server" extension, or):
   ```bash
   python3 -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

### Deploy on GitHub Pages

1. Push this project to a GitHub repository.
2. Go to **Settings → Pages** in your repo.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, choose the `main` branch and `/ (root)` folder, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Customization

- **Resume:** Replace `assets/Gella_Uday_Kumar_Resume.pdf` with an updated file (keep the same filename, or update the `href` in the Download Resume button in `index.html`).
- **Photo:** Replace `assets/profile.png` with a new image (same filename, or update the `src` in `index.html`).
- **Links:** GitHub and LinkedIn URLs are set in the navbar and Contact section of `index.html` — update them if your usernames change.
- **Colors:** All colors are defined as CSS custom properties at the top of `style.css` under `:root`.

## Contact

- 📧 gellaudaykumar2329@gmail.com
- 📱 +91 9078702554
- 💼 [LinkedIn](https://www.linkedin.com/in/uday-kumar-612743253)
- 🐙 [GitHub](https://github.com/Gella-Uday-kumar)
- 📍 Bengaluru, India

## License

This project is free to use and adapt for personal portfolio purposes.
