# Mikhil Khattar — Portfolio

> Head of Marketing Analytics | 7+ Years Driving Revenue Through Data-Driven Paid Marketing & Web Analytics

🔗 **Existing Site:** [mikhil.co.in](https://mikhil.co.in)
📅 **Book a Call:** [calendly.com/mikhil-khattar-1/call](https://calendly.com/mikhil-khattar-1/call)

---

## 🎯 About

A modern, premium portfolio website for **Mikhil Khattar**, Head of Digital Marketing & Analytics at Sumeru Inc. Designed to showcase his expertise in GA4, GTM, Looker Studio, and closed-loop attribution systems, with the goal of driving more consulting projects.

Built as a single `index.html` file with GSAP animations, deployed on Vercel.

---

## 🛠 Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Structure and semantic markup |
| **CSS3** | Styling, responsive design, hover interactions |
| **JavaScript (Vanilla)** | Interactivity and dynamic behavior |
| **GSAP 3.12.5** | Scroll-triggered animations and reveals |
| **GSAP ScrollTrigger** | Scroll-based animation control |
| **Google Fonts (DM Sans, DM Serif Display, Fira Code)** | Typography system |
| **Vercel** | Hosting and deployment |
| **GitHub** | Version control |

---

## ✨ Features & Animations

### Preloader
- Horizontal line draws from center outward
- Name and role text fade in sequentially
- Smooth fade-out transition to main content
- Completely different from standard circle/spinner preloaders

### Hero Section (Split-Screen Layout)
- **Left panel:** Headline, description, CTA buttons on white/light background
- **Right panel:** Navy blue background with stat grid and large "MK" background text
- **Counter animations:** Numbers count up from 0 to target value (7+, $3M+, 4.8★, 8)
- **Parallax:** Background text shifts horizontally on scroll

### Navigation
- Transparent by default, gains blurred background on scroll (80px threshold)
- "Book a Call" CTA button always visible in nav (navy filled button)
- Smooth scroll to sections on click
- Active state highlighting

### Scrolling Marquee
- Infinite horizontal ticker strip below hero
- Lists all skills/tools (GA4, GTM, Looker Studio, etc.)
- Seamless loop with duplicated content
- Subtle 12% opacity — atmospheric, not distracting
- Dot separators between items

### Section Reveal Animations
- All elements with class `.r` start at `opacity:0; translateY(30px)`
- ScrollTrigger batch processing reveals them with stagger
- Smooth `power2.out` easing
- Triggers at 90% viewport entry

### Interactive Elements
- **Approach cards:** Background color change on hover
- **Case study cards:** Full color inversion on hover (white → navy with white text)
- **Skill items:** Background highlight and color change on hover
- **Contact links:** Shift right (translateX 6px) on hover
- **CTA buttons:** Background/color swap on hover with smooth transition

### Design System
- **Color Palette:** White (#fcfcfc) background, navy (#1a2744) primary, sky blue (#4a7cc9) accent
- **Typography:** DM Serif Display (serif) for headings, DM Sans for body, Fira Code for dates
- **Layout:** Alternating section backgrounds (white / light gray / navy)
- **Grid system:** Sharp-edged cards with 0 gap borders (Gigantic Media inspired)
- **Section numbering:** (01), (02), (03) prefix system

---

## 📄 Sections

1. **Hero (Split-Screen)** — Headline "Data doesn't deliver value by itself", stats grid, CTAs
2. **Marquee** — Infinite scrolling skills ticker
3. **About** — Bio, approach to analytics, business-driven methodology
4. **How I Work** — 3-phase approach cards:
   - Audit & Diagnose
   - Architect & Build
   - Optimize & Scale
5. **Experience (Timeline)** — 4 roles with dot indicators:
   - Head of Digital Marketing & Analytics, Sumeru Inc (2020-Present)
   - Sr. Paid Marketing Specialist, Sumeru Inc (2020)
   - Digital Marketing Manager, Tulas International School (2018-2019)
   - Digital Marketing Consultant, The Art of Living (2017-2018)
6. **Case Studies** — 8 case study cards + 1 CTA card (3-column grid):
   - Nature's Energy (E-Commerce)
   - PMD Beauty (Beauty/DTC) — 92.13% tracking accuracy
   - Soft Star Shoes (Fashion)
   - Nectar Medical (Health)
   - Gear Supply (E-Commerce)
   - BehindTheChair.com (Content/Travel)
   - ThinkLouder Dashboard (SaaS)
   - ThinkLouder Data Analysis (SaaS)
   - "Your brand next?" CTA card
7. **Client Reviews** — 4 testimonials:
   - 3 Upwork reviews (all 5-star, 4.8 overall rating)
   - 1 LinkedIn recommendation (Maria Lapushkina)
8. **Skills (Dark Section)** — 20 tools in bordered grid layout
9. **CTA Banner** — "Your tracking is broken. Your dashboards aren't telling the truth." with Calendly link
10. **Contact (Split Layout)** — Left: heading + description, Right: Calendly, LinkedIn, Website links

---

## 🎯 Conversion-Focused CTAs

Every CTA is strategically written to drive GA4/GTM/Looker Studio consulting projects:

| Location | CTA Text | Action |
|---|---|---|
| Nav | "Book a Call" | → Calendly |
| Hero | "Free Analytics Audit" | → Calendly |
| Case Studies Grid | "Need a custom analytics strategy?" | → Calendly |
| CTA Banner | "Get Your Free Analytics Audit" | → Calendly |
| Contact | "Book a Free Consultation" | → Calendly |

All booking links point to: `calendly.com/mikhil-khattar-1/call`

---

## 🚀 Deployment

### Prerequisites
- A GitHub account
- A Vercel account (free)

### Steps
1. Create a new GitHub repository (e.g., `mikhil-portfolio-v2`)
2. Add `index.html` file with the portfolio code
3. Add this `README.md` file
4. Go to [vercel.com](https://vercel.com)
5. Click "Add New Project" → Import the GitHub repo
6. Set Framework Preset to "Other"
7. Click Deploy
8. Site is live at `your-project.vercel.app`

### Custom Domain
To connect to `mikhil.co.in` or a new domain:
1. In Vercel → Settings → Domains → Add domain
2. Update DNS records at your domain registrar
3. Vercel handles SSL automatically

---

## 📱 Responsive Design

- **Desktop (901px+):** Split-screen hero, 3-column grids, full animations
- **Tablet/Mobile (900px and below):** Single column, stacked hero, simplified grid, collapsed nav

---

## 📂 File Structure

```
mikhil-portfolio/
├── index.html    ← Single file contains everything (HTML + CSS + JS)
└── README.md     ← This file
```

No build step. No npm. No framework. One HTML file deployed on Vercel.

---

## 🎨 Color Reference

| Color | Hex | Usage |
|---|---|---|
| Background | `#fcfcfc` | Page background |
| Background Alt | `#f4f5f8` | Alternating section background |
| Navy (Primary) | `#1a2744` | Headings, hero panel, CTA banner, dark sections |
| Navy Light | `#1a2f5a` | Secondary dark elements |
| Accent (Sky Blue) | `#4a7cc9` | Links, highlights, timeline dots, results text |
| Text Primary | `#1a1a2e` | Body text |
| Text Mid | `rgba(26,26,46,.5)` | Descriptions |
| Text Light | `rgba(26,26,46,.25)` | Overlines, metadata |
| Border | `rgba(26,39,68,.08)` | Card borders, dividers |

---

## 🔑 Key Design Decisions

### Why White + Navy (not dark theme)?
Mikhil's audience is business stakeholders, brand owners, and marketing directors seeking analytics consulting. A light, corporate aesthetic communicates professionalism, trust, and authority — aligning with B2B expectations.

### Why Serif Headings?
DM Serif Display gives headings an editorial, authoritative quality. Combined with DM Sans body text, it creates a premium agency feel that positions Mikhil as a senior expert, not a junior freelancer.

### Why Case Study Cards Invert on Hover?
The navy-on-hover effect draws attention to individual case studies and creates a micro-interaction that encourages exploration. The color inversion mimics a "selection" state that feels intentional and premium.

### Why Multiple CTAs?
With 5 strategic Calendly entry points, every scroll depth has a conversion opportunity. Users don't need to scroll to the bottom — they can book from the nav, hero, case studies, banner, or contact section.

---

## 🏗 Built With

This portfolio was designed and developed through AI-assisted development using **Claude (Anthropic)**, demonstrating how modern AI tools can be leveraged to create production-quality websites without traditional development workflows.

---

## 📝 License

Personal portfolio. All content © 2026 Mikhil Khattar.

---

## 📬 Contact

- **Calendly:** [calendly.com/mikhil-khattar-1/call](https://calendly.com/mikhil-khattar-1/call)
- **LinkedIn:** [linkedin.com/in/mikhil-khattar](https://www.linkedin.com/in/mikhil-khattar/)
- **Website:** [mikhil.co.in](https://mikhil.co.in)
- **Upwork:** 4.8★ Rating — GA4, GTM, Looker Studio Expert
