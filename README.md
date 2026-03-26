# Build with AI — Workshop by GDG Jammu

### University of Jammu | Organized by GDG Jammu

> **Build your personal developer portfolio using AI-powered tools — and deploy it live.**

This workshop is designed for **absolute beginners** in the Computer Science branch. You don't need any prior experience with AI, APIs, or web deployment. By the end of this session, you'll have a fully functional, AI-generated portfolio website live on the internet — built by you.

---

## What you'll build

A **personal developer portfolio** website that:

- Showcases your skills, projects, and bio
- Is fully customized to your personality
- Deploys live on GitHub Pages (`yourname.github.io`)
- Gets featured on the **GDG Jammu Community Showcase**
- Includes an **AI-powered resume generator** (bonus feature)

---

## Tools We'll Use

### Google Stitch

Google Stitch is a **prototyping and design-to-code tool** that lets you create fully functional web applications using natural language prompts. Instead of writing every line of HTML, CSS, and JavaScript from scratch, Stitch understands what you describe and generates production-ready code instantly.

**Why it matters for this workshop:** You'll describe your portfolio — your style, your vibe, your content — and Stitch will generate the entire frontend for you. Think of it as having a senior developer pair-programming with you, except it works at the speed of thought.

**What you can do with Stitch:**
- Generate complete web pages from text descriptions
- Iterate on designs by refining your prompts
- Export clean, deployable code
- Prototype ideas in minutes instead of hours

### Antigravity IDE

Antigravity is Google's **AI-native code editor** designed to make development faster and more intuitive. It's not just an editor with autocomplete — it understands your entire project context and helps you write, debug, and ship code with AI built directly into the workflow.

**Why it matters for this workshop:** Once Stitch generates your base portfolio, you'll use Antigravity to customize it — tweak styles, add sections, fix bugs, and add the AI resume feature. It's where the real "building" happens.

**What you can do with Antigravity:**
- Edit and customize code with AI-assisted suggestions
- Debug issues with natural language explanations
- Add new features by describing what you want
- Manage your project files and push to GitHub

---

## Prerequisites & Setup

Please complete these steps **before** arriving at the workshop. This will save us valuable time and ensure you can start building immediately.

### Required Accounts (Free)

| # | Account | Why you need it | Sign up |
|---|---------|----------------|---------|
| 1 | **Google Account** | Access to Stitch, Antigravity & Cloud credits | [accounts.google.com](https://accounts.google.com) |
| 2 | **GitHub Account** | Host your portfolio & fork the starter repo | [github.com/signup](https://github.com/signup) |

### Required Downloads

| # | Tool | Download Link |
|---|------|--------------|
| 1 | **Antigravity IDE** | [**antigravity.google/download**](https://antigravity.google/download) |
| 2 | **Git** (if not already installed) | [git-scm.com/downloads](https://git-scm.com/downloads) |
| 3 | **Google Chrome** (recommended browser) | [google.com/chrome](https://google.com/chrome) |

### Free Google Cloud Credits

Google is providing **free Cloud credits** for all workshop attendees. Claim yours here:

**[Claim Free Google Cloud Credits](https://trygcp.dev/claim/design-to-code-with-antigravity-and-stitch-mcp#vf=6qd)**

> **Important:** Please redeem your credits **before** the workshop starts. You'll need an active Google Cloud account to use certain AI features during the session.

### System Requirements

- Any laptop (Windows / macOS / Linux / ChromeOS)
- Stable internet connection
- A modern web browser (Chrome recommended)
- At least 2 GB of free disk space (for Antigravity IDE)

---

## Workshop Flow

```
┌─────────────────────────────────────────────────────────┐
│  PHASE 1 — Generate (45 min)                           │
│  Use Google Stitch to create your portfolio from        │
│  natural language prompts. Pick your style, add your    │
│  info, and generate production-ready code.              │
├─────────────────────────────────────────────────────────┤
│  PHASE 2 — Customize (30 min)                          │
│  Open your project in Antigravity IDE. Tweak colors,   │
│  add sections, fix details, make it truly yours.        │
├─────────────────────────────────────────────────────────┤
│  PHASE 3 — Deploy (20 min)                             │
│  Fork this starter repo, push your code, and go live   │
│  on GitHub Pages. Your portfolio is now on the web.     │
├─────────────────────────────────────────────────────────┤
│  PHASE 4 — Showcase + Bonus (25 min)                   │
│  Submit your portfolio to the GDG Jammu Community       │
│  Showcase. Bonus: Add an AI resume generator feature.   │
└─────────────────────────────────────────────────────────┘
```

---

## Quick Start

### Step 1: Fork this repository

Click the **Fork** button at the top right of this page to create your own copy.

### Step 2: Clone your fork

```bash
git clone https://github.com/YOUR-USERNAME/build-with-ai-portfolio.git
cd build-with-ai-portfolio
```

### Step 3: Open in Antigravity IDE

Launch Antigravity and open the cloned folder. The starter is intentionally barebones — **you'll generate your portfolio during the workshop!**

```
build-with-ai-portfolio/
├── index.html          ← Placeholder (replace with your Stitch output)
├── assets/             ← Your photo & project screenshots go here
│   └── projects/
├── resume/             ← Bonus: AI Resume Generator
├── manifest.json       ← PWA config (auto-installs on phones)
├── sw.js               ← Service worker (offline support)
├── LICENSE
└── README.md
```

### Step 4: Build your portfolio

1. Open **Google Stitch** and describe the portfolio you want
2. Export the generated code
3. Replace the placeholder `index.html` with your generated portfolio
4. Add your own `style.css` and `script.js` as needed
5. Open in **Antigravity IDE** to customize, tweak, and polish

### Step 5: Deploy to GitHub Pages

```bash
git add .
git commit -m "My portfolio — built at GDG Jammu Build with AI workshop"
git push origin main
```

Then go to **Settings → Pages → Source: main branch** in your GitHub repo. Your site will be live at `https://YOUR-USERNAME.github.io/build-with-ai-portfolio`

---

## Claim Your Badge

Completed the workshop? Claim your official **Build with AI** badge on your Google Developer Profile!

**[Claim Your Build with AI Badge](http://goo.gle/bwai-attendee-2026)**

> This badge will appear on your Google Developer Profile and verifies your participation in the Build with AI program. Share it on LinkedIn, your resume, and your new portfolio!

---

## What you'll learn

By the end of this workshop, you will have hands-on experience with:

- **AI-assisted development** — Using Stitch and Antigravity to build real applications
- **Web fundamentals** — HTML, CSS, and JavaScript structure (even if AI writes most of it, you'll understand it)
- **Git & GitHub** — Version control, forking, committing, and pushing code
- **GitHub Pages** — Free static site hosting and deployment
- **PWA basics** — Making your website installable on phones
- **Prompt engineering** — How to describe what you want so AI builds it right
- **AI API integration** — How apps talk to AI models (bonus section)

---

## Resources

### During the workshop
- [Google Stitch Documentation](https://stitch.google)
- [Antigravity IDE Guide](https://antigravity.google)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

### Keep learning after the workshop
- [Google AI for Developers](https://ai.google.dev)
- [Web Development Fundamentals — web.dev](https://web.dev/learn)
- [Git & GitHub for Beginners — freeCodeCamp](https://www.freecodecamp.org/news/git-and-github-for-beginners/)
- [GDG Jammu Community](https://gdg.community.dev/gdg-jammu/)

---

## Submit Your Portfolio to the GDG Jammu Showcase

Once your portfolio is live, submit it to be featured on the **GDG Jammu Community Showcase**:

1. Make sure your GitHub Pages site is live and accessible
2. Visit the submission form (shared during the workshop)
3. Enter your name, GitHub Pages URL, and a one-line bio
4. Your portfolio will appear on **gdgjammu.com/community**

---

## Troubleshooting

<details>
<summary><strong>GitHub Pages not showing my site</strong></summary>

- Go to your repo **Settings → Pages**
- Make sure source is set to **main** branch
- Wait 2-3 minutes — GitHub needs time to build
- Check that your file is named `index.html` (not `Index.html` or `home.html`)

</details>

<details>
<summary><strong>Git push is failing</strong></summary>

- Make sure you forked the repo (not just cloned the original)
- Check that you're pushing to YOUR fork: `git remote -v` should show your username
- If using HTTPS, GitHub may ask for a Personal Access Token instead of password

</details>

<details>
<summary><strong>Antigravity won't install</strong></summary>

- Check system requirements at [antigravity.google/download](https://antigravity.google/download)
- On Windows: run as Administrator
- On Mac: allow in System Preferences → Security & Privacy
- Fallback: use VS Code with GitHub Copilot as an alternative

</details>

<details>
<summary><strong>Stitch isn't generating what I want</strong></summary>

- Be specific in your prompts: "A dark theme portfolio with a hero section, project cards, and a contact form" works better than "make me a website"
- Iterate: refine your prompt based on what you get
- Ask a mentor for help — that's what we're here for!

</details>

---

## Workshop Mentors

If you're stuck during the workshop, raise your hand or reach out to any of the mentors wearing **GDG Jammu** badges. We're here to help!

---

## License

This starter template is open source under the [MIT License](LICENSE). Feel free to use, modify, and share your portfolio however you like.

---

<div align="center">

**Built by [GDG Jammu](https://gdg.community.dev/gdg-jammu/)**

*Build with AI Workshop — University of Jammu*

Star this repo if you found it helpful!

</div>
