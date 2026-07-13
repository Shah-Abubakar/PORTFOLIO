# Portfolio Website

** [View Live Demo](https://portfolio2-five-orcin.vercel.app/)**

My personal portfolio website — a cinematic, scroll-driven experience showcasing my projects, skills, and vision as an AI aspirant.

---

## Overview

| Aspect | Details |
|--------|---------|
| **Purpose** | Central hub for my work — projects, skills, contact |
| **Target Audience** | University admissions |
| **Style** | Modern, cinematic, glass style, scroll-driven video |

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Structure |
| **Tailwind CSS** | Styling (via CDN) |
| **React 18** | UI components |
| **GSAP + ScrollTrigger** | Scroll animations |
| **Babel** | JSX compilation in browser |
| **Custom Video Scroll** | Background video scrubs with scroll position |

---

## Features

| Feature | Description |
|---------|-------------|
| **Scroll-driven video background** | Video scrubs forward/backward as you scroll |
| **Glass-morphism cards** | Frosted, blurred UI with border glow |
| **Flip cards** | Project cards flip to show detailed workflows |
| **Smooth scroll animations** | GSAP-powered, GPU-optimized entrance animations |
| **Hamburger navigation** | Collapsible menu that expands smoothly |
| **Fully responsive** | Works on mobile, tablet, and desktop |

---

## Project Sections

| Section | Content |
|---------|---------|
| **Hero** | Name + scroll indicator |
| **About** | Personal background and vision |
| **Skills** | App Dev, AI Tools, Practical Thinking, Automation |
| **Projects** | KAIZEN, NextSTEP, Hire Me, Appointment Bot |
| **Contact** | Email, phone, location |

---

## Video Background Details

| Setting | Value |
|---------|-------|
| **Video file** | `MV1.mp4` |
| **Behavior** | Time scrubs based on scroll % (0% → 100%) |
| **Performance** | RAF loop + throttled seeks (max 60fps) |
| **Fallback** | Black background if video fails |

---

## How to Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/Shah-Abubakar/REAL-PORTFOLIO.git

# 2. Navigate to the folder
cd REAL-PORTFOLIO

# 3. Open index.html in your browser
# Or use Live Server (VS Code extension)
