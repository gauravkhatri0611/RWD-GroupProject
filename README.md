# 💧 Ultima Replenishers – Frontend Website (Final Project)

A fully responsive, animated, HTML/CSS-based e-commerce experience inspired by Ultima Replenishers.  
This project includes a complete home page, product catalog, product detail pages, store locator, subscribe & save page, and a complete design system.

---

## 🚀 Live Demo
Provide your deployed link here:  
**https://your-vercel-url.vercel.app/**

---

## 📂 Project Overview

This project demonstrates:

- Responsive HTML/CSS layout  
- Custom CSS design system  
- Mega menu with hover interactions  
- Product card components  
- Store locator with Google Maps embed  
- Scroll-triggered animations  
- WCAG-safe gradients and accessibility improvements  
- Component-based reusable CSS  
- Pure HTML/CSS — *no JS frameworks*

---

## 📁 Folder Structure

/ (root)
│── index.html
│── menu-all-flavors.html
│── menu-mocktini.html
│── menu-variety-packs.html
│── product-teafresher.html
│── subscribe-save.html
│── find-in-stores.html
│── learn.html
│── styles.css
│── README.md
└── images/

yaml
Copy code

---

## 🧪 Features

### 🌟 UI Features
- Hydration-themed droplet animations  
- Shimmering badges (WCAG safe)  
- Floating product animations  
- Responsive product grid (CSS Grid & Flexbox)

### 🛒 E-Commerce Features
- Product detail pages with gallery  
- Add-to-Cart UI (non-functional)  
- Flavor filters (front-end UI only)

### 📍 Store Locator
- Embedded, real Google Maps instance  
- Search UI (front-end only)  

### 📣 Marketing Components
- Subscribe & Save section  
- Newsletter form layout  
- Social media bar  

---

## 🖌 Design System (CSS Tokens)

All tokens are placed at the top of **styles.css**:

- Colors  
- Typography  
- Spacing scale  
- Shadows  
- Animation keyframes  
- Component styling  

---

## 🔧 Running Locally

Clone the project:

```bash
git clone https://github.com/yourusername/ultima-replenishers.git
cd ultima-replenishers
Open in browser:

Option A: double-click index.html

Option B (recommended): VS Code Live Server

Deploy:

bash
Copy code
vercel deploy
🎓 Educational Purpose
This project demonstrates a complete front-end UI system suitable for:

Web development assignments

Portfolio showcase

E-commerce UI practice

Figma → HTML/CSS translation

📄 License
This project is for educational and personal portfolio use only.

yaml
Copy code

---

# ---------------------------------------------------------
# **2️⃣ FIGMA UI KIT.md (Complete UI Kit Specification)**
# ---------------------------------------------------------

```markdown
# 🎨 ULTIMA REPLENISHERS — FIGMA UI KIT

This document describes *every component, token, spacing rule, grid system, and reusable asset* needed to recreate your entire UI in Figma.

It is structured like a Figma Design System:

---

# 1. FOUNDATIONS

## 1.1 Color Styles (add these as Figma color tokens)

### Brand Colors
| Token | Hex |
|-------|------|
| Purple / Dark | `#3a1b7a` |
| Purple / Mid | `#4b2ca5` |
| Purple / Light | `#8a3cff` |
| Pink / Base | `#ff2c8b` |
| Pink / Dark | `#c01461` |
| Yellow | `#ffc600` |

### Neutrals
| Token | Hex |
|-------|------|
| Text / Main | `#2a1454` |
| Text / Muted | `#7e6796` |
| White | `#ffffff` |
| Background / Light | `#faf7ff` |
| Card / Light | `#f7f2ff` |

---

## 1.2 WCAG-Safe Gradient Tokens
Use these for badges & hero accents.

Gradient Name: **Berry Sunset**  
linear-gradient(120deg, #590028, #a1004f, #8500d2, #5a0be5)

yaml
Copy code

---

## 1.3 Typography Styles

Create these in Figma:

| Token | Size | Weight | Usage |
|-------|-------|---------|-------|
| Display / XL | 48px | 700 | Hero |
| Heading / L | 32px | 700 | Section titles |
| Heading / M | 24px | 600 | Card titles |
| Body / M | 16px | 400 | Paragraphs |
| Body / S | 14px | 400/500 | Badges / labels |
| Caption | 12px | 400 | Controls |

Font Family: **Poppins**

---

## 1.4 Spacing Scale

| Token | Value |
|--------|--------|
| Space 1 | 4px |
| Space 2 | 8px |
| Space 3 | 12px |
| Space 4 | 16px |
| Space 5 | 24px |
| Space 6 | 32px |
| Space 7 | 48px |
| Space 8 | 64px |

Use these for Auto-Layout padding, gaps, and alignment.

---

# 2. COMPONENT LIBRARY

Each component should be built as a **Figma Component**.

---

## 2.1 Buttons

### Primary Button  
- Auto Layout: horizontal  
- Padding: 14px 26px  
- Radius: 12px  
- Fill: `Purple/Mid`  
- Text: `Poppins 16px / Bold`  

### Secondary Button  
- Stroke: `Purple/Mid`  
- Fill: White  
- Hover Variant: Purple fill + white text  

---

## 2.2 Product Card Component

Create a **master component** with variants:

- Default
- Hover
- On Sale
- New Badge

**Structure:**
- Container: 22px radius, card shadow  
- Product Image  
- Product Title  
- Product Type  
- Flavor Tags (Auto Layout, pill style)  
- Rating Row  
- Price Row  
- CTA button  

---

## 2.3 Badge Component

- Capsule shape  
- Fill = gradient token  
- Text = 12px Bold, white  
- Create a Figma "Shimmer" animation note (Figmotion or prototype loop)

---

## 2.4 Hero Section

Layers:

1. Droplet animations (add as floating ellipses with 15–20% opacity)
2. Hero text block  
3. Right-side product collage image  
4. Background soft radial gradients  

---

## 2.5 Navigation Bar

Auto Layout:

- Logo  
- Menu links  
- Mega menu (component)  
- Right icons  

Mega menu variants:
- Default
- Hover-open

---

## 2.6 Store Locator Map Component

Frame:
- 16:9 ratio  
- Embedded Google Maps placeholder  
- Search input  
- “Filter Products” pill  
- “0 stores found” card  

---

## 2.7 Subscribe & Save Banner

Layout:
- Left: drink image  
- Right: headline, description, form, social icons  

---

# 3. PAGE TEMPLATES (Figma Frames)

Create full page templates:

### Pages:
- Homepage  
- All Flavors  
- Product Detail (TeaFresher)  
- Variety Packs  
- Mocktini Page  
- Subscribe & Save  
- Find in Stores  
- Learn Page  

Use a **1440px desktop grid**:
12 columns
80px margins
24px gutters

css
Copy code

Mobile grid:
4 columns
16px margins

yaml
Copy code

---

# 4. PROTOTYPE FLOWS

Create clickable flows:

- Homepage → Product page  
- Mega menu interactions  
- Explore button scroll  
- Store locator search  
- Subscribe form hover state  

---

# 5. EXPORT GUIDELINES

- Export product images as **PNG** or **WEBP**  
- Export icons as **SVG**  
- Keep images under **300–500kb**  

---

# ---------------------------------------------------------
# **3️⃣ KANBAN BOARD.md (Final + Future Development)**
# ---------------------------------------------------------

```markdown
# 🗂 Ultima Replenishers — Project Kanban Board  
*(For 3 team members: Sukhbir, Person 2, Person 3)*

Use in Notion / Trello / Jira / GitHub Projects.

---

# COLUMNS:
### 📝 Backlog (Future Improvements)
### 🚧 In Progress
### 🔍 Review
### ✅ Completed

---

# 📝 BACKLOG — Future Enhancements

| Task | Owner | Priority | Notes |
|------|--------|----------|-------|
| Add full dark-mode theme | Sukhbir | Medium | Extend token system |
| Add product comparison table | Person 2 | Low | New component |
| Add micro-interactions to footer icons | Person 2 | Low | Hover pulses |
| Reduce layout shift (CLS optimization) | Person 3 | Medium | Image height placeholders |
| Convert store locator to functional version | Sukhbir | High | JS integration |
| Add sticky filter bar to All Flavors page | Person 2 | Medium | New UI pattern |
| Add cart slide-out drawer | Sukhbir | Medium | Pure CSS version possible |
| Add accessibility validation summary | Person 3 | High | WCAG AAA test |

---

# 🚧 IN PROGRESS (Active Work)

| Task | Owner | Status |
|------|--------|--------|
| Refactoring CSS tokens into modular sections | Person 3 | 60% |
| Creating Figma alignment with live build | Sukhbir | 50% |
| Adding optional JS enhancements (non-required) | Person 2 | 25% |

---

# 🔍 REVIEW

| Task | Reviewer | Notes |
|------|----------|-------|
| Homepage animation timings | Person 3 | Needs easing improvements |
| Badge shimmer accessibility | Sukhbir | Check contrast + speed |
| Store locator layout | Person 2 | Check mobile view |

---

# ✅ COMPLETED (Archived)

| Task | Owner |
|------|--------|
| Build homepage hero section |
| Product carousel | 
| All flavors product grid | 
| Mocktini page | 
| Subscribe & save |
| Variety packs PDP | 
| TeaFresher PDP | 
| Footer layout |
| Mega menu hover | 
| Full design system tokens | Completed collaboratively |
| Store locator basic version | 
