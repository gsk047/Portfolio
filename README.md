# S. Gowtham — QA Engineer Portfolio

> **Personal portfolio website** for S. Gowtham, a QA Engineer with ~5 years of experience in Banking & Financial Services, API automation, and cloud observability.

---

## 🔗 Live Preview

https://gsk047.github.io/Portfolio/

---

## 📋 About

This is a single-page personal portfolio built with **pure HTML & CSS** — no frameworks, no build tools, no dependencies. It showcases professional experience, technical skills, key achievements, awards, and education in a clean dark-themed layout.

---

## ✨ Features

- **Zero-dependency** — plain HTML + CSS, no JavaScript frameworks or npm packages required
- **Fully responsive** — four-tier media query system targeting desktops, tablets (768px), large phones (640px), narrow phones (480px)
- **Dark theme** with a custom CSS variable design system (`--bg`, `--accent`, `--card`, etc.)
- **Smooth animations** — `fadeUp` keyframe entries and a pulsing status indicator
- **Accessible** — `min-height: 44px` touch targets on all nav/meta links, `lang` attribute set, iOS Safari font-scale fix applied
- **Sections:** Hero · Stats Strip · Skills · Experience · Key Achievements · Awards & Recognition · Education

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, keyframes) |
| Fonts | Sora (body) + JetBrains Mono (code/labels) via Google Fonts |
| Hosting | GitHub Pages / any static host |

---

## 📂 Project Structure

```
Portfolio/
└── index.html        # Entire site — HTML structure + embedded CSS
```

---

## 🚀 Getting Started

No build step required. Just open the file in a browser:

```bash
# Clone the repository
git clone https://github.com/gsk047/Portfolio.git

# Open in browser
open index.html
# or on Windows:
start index.html
```

---

## 🌐 Deploying to GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under *Source*, select the `main` branch and `/ (root)`.
4. Click **Save**. Your portfolio will be live at:

```
https://gsk047.github.io/Portfolio/
```

> **Before deploying:** open `index.html` and replace `YOUR_GITHUB_USERNAME` in the GitHub hero-meta link with `gsk047`.

---

## 🎨 Customisation

All design tokens live in the `:root` block at the top of the `<style>` tag:

```css
:root {
  --bg:       #0a0c10;   /* page background   */
  --accent:   #00d4aa;   /* primary teal       */
  --accent2:  #0099ff;   /* secondary blue     */
  --text:     #e8eaf0;   /* body text          */
  --muted:    #6b7280;   /* secondary text     */
}
```

To update personal details, search for the following in `index.html`:

| What to change | Where to find it |
|---|---|
| Name & title | `<title>` tag and `<h1>` in the hero section |
| Email address | `mailto:` links in hero-meta and footer |
| Phone number | `tel:` link in hero-meta |
| LinkedIn URL | `href` on the LinkedIn anchor |
| GitHub URL | Replace `YOUR_GITHUB_USERNAME` in hero-meta |
| Stats (years, cases, %) | `.stats` div block |
| Skills | `.skills-categories` section |
| Experience bullets | `.exp-list` inside `#experience` |
| Achievements | `.achieve-grid` inside `#achievements` |
| Education | `.edu-card` inside the Education section |

---

## 👤 About the Developer

**S. Gowtham** — QA Engineer @ Virtusa (Client: Bank of Montreal)

- 5+ years of QA experience in Banking & Financial Services
- Expert in **Rest Assured**, **Playwright (TypeScript)**, **Selenium WebDriver**, **Postman**
- Deep domain knowledge: **SWIFT MT/MX**, **ISO 20022**, **Wire Payments**, **IBM Mainframe**
- Cloud observability with **AWS CloudWatch**, **DLQ/SQS/SNS**, **Lambda**, **DynamoDB**
- Reduced regression cycle time by **35–40%** and manual API effort by **60%**
- 🏆 Star Employee of the Year — Virtusa
- 🏆 Client Recognition Award — Bank of Montreal

📧 gowthamsk047@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/s-gowtham-71897220b)
🐙 [GitHub](https://github.com/gsk047)

---

## 📄 License

This project is open source. Feel free to fork and adapt it for your own portfolio.
