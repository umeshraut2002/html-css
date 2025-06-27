# 🚀 Multi-Brand Landing-Page Clones  

Clones of the public marketing/landing pages for **Swiggy**, **Amazon Prime**, **JioCinema/Hotstar**, **L’Oréal Paris**, and **Meesho** — built from scratch for learning and portfolio purposes. Each clone focuses on pixel-perfect layout, responsive design, and accessible markup while re-creating core interactions and animations.

> **⚠️ Disclaimer**  
> All trademarks, logos, and brand names are the property of their respective owners.  
> This project is **strictly for educational use** (no affiliation or commercial intent).

---

## ✨  Highlights

| Brand | Key Take-Aways | Tech Nuggets |
| ----- | -------------- | ------------ |
| **Swiggy** | Hero carousel, staggered scroll reveals, animated CTA buttons | CSS Grid, `intersectionObserver`, vanilla JS slider |
| **Amazon Prime** | Parallax promo sections & pricing tabs | CSS `scroll-snap`, `prefers-reduced-motion` |
| **JioCinema / Hotstar** | Video-in-hero, dynamic navbar blur on scroll | HTML5 `<video>` + lazy-load, Tailwind utilities |
| **L’Oréal** | High-end beauty aesthetic, glass-morphism cards | Custom CSS variables, backdrop-filter |
| **Meesho** | Mobile-first grid catalog, sticky discount banner | CSS container queries, native `dialog` modal |

---


Each sub-folder is a self-contained mini-project with its own `index.html`, `styles`, and `scripts`.

---

## 🛠️ Tech Stack

- **HTML5 + Semantic ARIA**
- **CSS3 / SCSS** (BEM naming, custom properties)
- **Vanilla JS (ES2023)**  
  _Optional_: Tailwind CSS or a tiny utility library where noted
- **Vite** for live-reloading dev server (or use VS Code → Live Server)

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/<your-username>/landing-page-clones.git
cd landing-page-clones

# 2. Install dev dependencies (optional – only for Vite users)
npm install

# 3. Spin up live preview (choose one project)
cd swiggy        # or amazon-prime, jiocinema-hotstar, loreal, meesho
npx vite         # or: code . && hit “Go Live” in VS Code

