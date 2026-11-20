<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/header-dark.svg">
    <img src="docs/header-light.svg" width="680" alt="DJ Adriano">
  </picture>
</p>

<h3 align="center">A one-page website for a wedding DJ & host</h3>

<p align="center">
  <br>
  A promotional site for <b>Adriano</b>, a DJ and host for weddings and special events.
  <br>
  Fast and fully static: no frameworks, no build step, just clean HTML and CSS.
  <br><br>
</p>

<p align="center">
  <a href="https://adrianodj.pl"><img src="https://img.shields.io/badge/Visit_adrianodj.pl-D8BD82?style=for-the-badge&labelColor=1A233F" alt="Visit adrianodj.pl"></a>
</p>


### 📸 Preview
<img src="docs/divider.svg" width="200" alt="">

![DJ Adriano website - homepage](assets/screenshot-homepage.webp)

### ✨ Features
<img src="docs/divider.svg" width="200" alt="">

#### 🧭 Single-page layout
Smooth in-page navigation between **About**, **Gallery** and **Contact**.

#### 📱 Responsive design
Adapts from desktop down to mobile, with a **hamburger menu** on small screens.

#### ♿ Accessibility-minded
**Semantic HTML**, ARIA labels, and alt text on media.

#### 🎬 Promo video and gallery
A **promo video** and an image gallery showcasing events.

#### ✉️ Contact section
Direct **email**, **phone**, and a reservation call-to-action.

#### 🧩 PWA basics
**Favicons** and a **web manifest** for a polished look on all devices.

### 🛠️ Tech stack
<img src="docs/divider.svg" width="200" alt="">

| Category | Stack |
|---|---|
| **Markup** | ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) semantic, hand-written markup |
| **Styles** | ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) custom styles with CSS variables (no framework) |
| **Fonts** | ![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=flat-square&logo=googlefonts&logoColor=white) Cormorant Garamond & Manrope |
| **Hosting** | ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![OVH](https://img.shields.io/badge/domain-OVH-123F6D?style=flat-square&logo=ovh&logoColor=white) |

### 🗂️ Project structure
<img src="docs/divider.svg" width="200" alt="">

```
DJ-site/
├── index.html          # The page markup
├── dj-site.css         # All styles
├── site.webmanifest    # PWA manifest
├── assets/             # Logo, photos, promo video
├── docs/               # README graphics
└── icons/              # UI icons and favicons
```

### 🚀 Running locally
<img src="docs/divider.svg" width="200" alt="">

No build tools or dependencies are required.

**1. Get the files**: clone the repo (or download it as a ZIP).

```bash
git clone https://github.com/majkab8/DJ-site.git
cd DJ-site
```

**2. Open the site**, either:

- **Directly:** double-click `index.html` to open it in your browser, or
- **Serve locally** (recommended, so paths behave like production):

```bash
# Python 3
python -m http.server 8000
```

Then visit http://localhost:8000.

### ☁️ Deployment
<img src="docs/divider.svg" width="200" alt="">

The site is deployed on [Vercel](https://vercel.com) and served from the custom domain **adrianodj.pl**. Any push to the `main` branch triggers an automatic redeploy.

### 💬 Contact
<img src="docs/divider.svg" width="200" alt="">

- **Bookings & enquiries for the DJ**: see the contact section on the [live site](https://adrianodj.pl).
- **Questions about this website or its code**: reach out via [GitHub](https://github.com/majkab8).

### 📜 License
<img src="docs/divider.svg" width="200" alt="">

© 2026 DJ Adriano. All rights reserved.
This code is published for portfolio purposes only and may not be reused, copied, or redistributed without permission.
