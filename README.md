# ⚡ PowerUp — Web Redesign

### Brand-consistent CSS redesign of [powerupasd.it](https://powerupasd.it)

<br>

![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)

<br>

> A custom CSS redesign of the PowerUp ASD gym website.  
> The goal: make the website look and feel as cohesive as the rest of the brand — social content, posters, flyers, and all.

<br>

[🎨 Brand Identity](#-brand-identity) · [📸 Preview](#-preview) · [📁 Repository Structure](#-repository-structure) · [👤 Author](#-author)

</div>

---

## 🏋️ About PowerUp

PowerUp is a gym and fitness association based in Mazzarino and Riesi (Italy).

The existing website runs on a managed platform with a fixed template. This project applies a **custom CSS layer** on top of the original HTML to bring the website in line with the official PowerUp brand identity — the same identity used across all social media content, posters, flyers, and print materials.

---

## 🎨 Brand Identity

The design system used throughout this project:

### Colors

| Role | Name | Hex |
|---|---|---|
| Primary | Electric Green | `#00FF00` |
| Background | Black | `#000000` |
| Surface / Text | White | `#FFFFFF` |

### Typography

| Role | Font | Usage |
|---|---|---|
| Display / Hero | **Orbitron** | Section titles, hero headings |
| UI / Navigation | **Exo 2** | Nav, buttons, labels, captions |
| Body | **Satoshi** | Paragraphs, descriptions, general text |

### Logo

The PowerUp logo is available in the `assets/logo/` directory in multiple formats (SVG, PNG on dark background, PNG on light background).

---

## 📁 Repository Structure

```
powerup-web-redesign/
│
├── css/
│   ├── style.css        # global styles, CSS variables, reset
│   ├── navbar.css       # navigation bar
│   ├── hero.css         # hero section
│   ├── cards.css        # course and pricing cards
│   └── footer.css       # footer
│
├── assets/
│   ├── logo/
│   │   ├── powerup-logo.svg
│   │   ├── powerup-logo-white.png
│   │   └── powerup-logo-black.png
│   └── img/             # custom graphics and photos
│
├── preview/
│   ├── before.png       # screenshot of the original site
│   └── after.png        # screenshot of the redesigned site
│
└── README.md
```

---

## 🛠️ Technical Approach

- **CSS only** — no modifications to the original HTML
- **CSS custom properties** — all brand colors and fonts defined as variables in `:root`
- **Google Fonts** — Orbitron, Exo 2, and Satoshi via `@import`
- **Specificity-first** — selectors written to override the platform's default styles cleanly

---

## 🔭 Roadmap

- [ ] Global variables and reset (`style.css`)
- [ ] Navigation bar
- [ ] Hero section
- [ ] Course cards
- [ ] Pricing section
- [ ] Schedule
- [ ] Staff
- [ ] Footer
- [ ] Before/after screenshots

---

## 👤 Author

**Flavio Lanzafame**
Graphic designer & web designer for PowerUp ASD.
Responsible for brand identity, logo, social media content, print materials, and this web redesign.

→ [@flaviolanzafame](https://github.com/flaviolanzafame)

---

## 📄 License

© 2026 Flavio Lanzafame. All Rights Reserved.  
© 2026 Associazione Sportiva Dilettantistica PowerUp. All Rights Reserved.

Unauthorized copying, modification, distribution, or use of this work,
in whole or in part, is strictly prohibited without prior written permission from the authors.

See [LICENSE](LICENSE) for details.

> The PowerUp logo and brand assets are property of PowerUp ASD and are used here with permission.

---

<div align="center">

Built with CSS · and the PowerUp energy ⚡

</div>
