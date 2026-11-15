# Kashaf — Mathematics × Technology

A personal portfolio website for Kashaf, a BS Mathematics student at Bahauddin Zakariya University, Multan, Pakistan. The site presents an honest snapshot of academic background, programming practice, AI-assisted application development, projects, and technical learning.

🌐 **Live portfolio:** https://kashaf-math.github.io/

## Design & technology

- Semantic HTML5
- CSS3 with responsive layouts and a custom beige, cream, navy, brown, and sage palette
- Vanilla JavaScript for the accessible mobile navigation and current-year footer
- Google Fonts (DM Sans and Manrope), with system-font fallbacks
- Custom SVG favicon and inline mathematical illustration
- No framework, build step, API key, or paid service required

## Project structure

```
.
├── index.html
├── style.css
├── script.js
├── 404.html
├── README.md
└── assets/
    └── favicon.svg
```

## Run locally

1. Download or clone this repository.
2. Open the folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension if installed.

There are no package installations or environment variables.

## Deploy with GitHub Pages

This repository is named `kashaf-math.github.io`, so its user-site address is:

`https://kashaf-math.github.io/`

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then save.
5. After GitHub Pages finishes publishing, open the website address above.

## Deploy with Vercel

1. Sign in to Vercel using the GitHub account that owns this repository.
2. Choose **Add New → Project**.
3. Import `kashaf-math/kashaf-math.github.io`.
4. Keep the framework preset as **Other**.
5. Leave the build command and output directory empty; this is a static HTML/CSS/JavaScript site.
6. Select **Deploy**.

When the GitHub repository is connected to Vercel, new commits to `main` can trigger automatic deployments. Check the deployment status in the Vercel dashboard.

## Updating the site with Git

From a terminal opened in the project folder:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

If you have not cloned the repository yet:

```bash
git clone https://github.com/kashaf-math/kashaf-math.github.io.git
cd kashaf-math.github.io
```

## Content accuracy notes

- C++ is presented as practical programming experience through learning and console projects.
- Python is labelled as currently being learned.
- My Life Manager is described as developed with Google AI Studio assistance; Android APK packaging was performed by Kashaf using Android Studio.
- Axiom is described as an offline, knowledge-base and rule-based educational assistant—not a generative AI or machine-learning chatbot.
- ZGDC means **Zakariyan Google Developer Club**.
- The Mathematics Tutor Chatbot remains unpublished and awaiting source-code verification.
- No unverified project repositories, screenshots, professional experience, certificates, or testimonials are fabricated.

## Final testing checklist

- [ ] Open the site at desktop, tablet, and mobile widths.
- [ ] Test every navigation anchor and the mobile menu.
- [ ] Test GitHub, LinkedIn, email, and My Life Manager links.
- [ ] Confirm keyboard focus is visible and the menu closes with Escape.
- [ ] Check that reduced-motion preferences are respected.
- [ ] Confirm there is no horizontal overflow on a narrow screen.
- [ ] Check the browser console for errors after deployment.

---

**Kashaf** · Where Mathematics Meets Technology.
