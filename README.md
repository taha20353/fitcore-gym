# FitCore Gym

A responsive landing page for a fictional premium fitness facility, built with pure HTML and CSS using a float-based layout.

**Live Demo:** [https://taha20353.github.io/fitcore-gym](https://taha20353.github.io/fitcore-gym)

---

## 📋 Overview

FitCore Gym is a single-page marketing website for a modern fitness center. It showcases the gym's features, member testimonials, key statistics, and a membership signup form. The project was built as **Assignment 2** with a focus on mastering CSS layout techniques without relying on Flexbox or CSS Grid.

---

## ✨ Features

- **Hero Section** — Eye-catching headline, call-to-action buttons, and hero image with smooth anchor scrolling
- **Why Choose Us** — Three color-coded feature cards (Premium Equipment, Expert Trainers, Flexible Hours) with CSS-generated icon shapes
- **More Than Just a Gym** — Two-column section highlighting Group Classes, Nutrition Guidance, and Recovery Zone
- **Member Reviews** — Three testimonial cards with avatars, member results, and quotes
- **Statistics Box** — Highlighted metrics (2500+ members, 15+ trainers, 50+ classes, 24/7 access)
- **Membership Form** — Full signup form with name, email, phone, membership type, and fitness goals
- **Footer** — Multi-column footer with quick links, contact info, and social media links
- **Fully Responsive** — Breakpoints at 1024px, 900px, 700px, and 450px for tablet and mobile devices
- **Smooth Scrolling** — Anchor navigation with `scroll-behavior: smooth`

---

## 🛠️ Built With

- **HTML5** — Semantic markup
- **CSS3** — Float-based layout, pseudo-elements, transitions, media queries
- **Google Fonts** — Inter typeface

**No JavaScript. No frameworks. No Flexbox. No Grid.**

---

## 📁 Project Structure

```
fitcore-gym/
├── index.html
├── css/
│   └── style.css
├── images/
│   ├── hero-section-img.png
│   ├── why-choose-us.png
│   ├── avatar-1.jpg
│   ├── avatar-2.jpg
│   └── avatar-3.jpg
└── README.md
```

---

## 🎨 Design Highlights

- **Layout Technique:** Float-based columns cleared with `<div class="clear"></div>` utility
- **Icon Shapes:** Feature card icons are pure CSS using `::after` pseudo-elements with `transform: translate(-50%, -50%)`
- **Color Palette:**
  - Blue: `#DBEAFE` / `#155DFC`
  - Green: `#D0FAE5` / `#009966`
  - Purple: `#F3E8FF` / `#9810FA`
  - Dark footer: `#111827`
- **Typography:** Inter with weights 400 and 700
- **Container:** `66%` width with `max-width: 1200px`, centered via `margin: 0 auto`

---

## 📱 Responsive Breakpoints

| Breakpoint | Behavior |
|------------|----------|
| **> 1024px** | Full desktop layout |
| **≤ 1024px** | Narrower container, smaller gym image |
| **≤ 900px** | Feature/review cards go 2-up, stats 2-up, footer stacks to 2 columns |
| **≤ 700px** | Hero and all sections stack vertically, form fields full-width |
| **≤ 450px** | Buttons full-width, stats stack 1-up, reduced padding |

---

## 🚀 Getting Started

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/taha20353/fitcore-gym.git
   ```

2. Navigate into the folder:
   ```bash
   cd fitcore-gym
   ```

3. Open `index.html` in your browser — no build step required.

### Deploy to GitHub Pages

1. Push your code to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch** → `main` → `/ (root)`
4. Your site will be live at `https://<username>.github.io/<repo-name>`

---

## 🔗 Sections & Anchor Links

| Section | ID | Linked From |
|---------|-----|-------------|
| Hero | `#hero` | Footer "Home" |
| Why Choose Us | `#why-choose-us` | Hero "Learn More", Footer |
| Reviews | `#social-proof` | Footer |
| Membership Form | `#membership-form` | Hero "Start Your Journey", Footer |

---

## ✅ What I Learned

- Building multi-column layouts using **floats** and the clearfix pattern
- Creating **responsive breakpoints** with media queries
- Using **CSS pseudo-elements** (`::after`) to generate decorative shapes
- Structuring a landing page with **semantic HTML** and reusable utility classes
- Implementing **smooth anchor scrolling** with a single CSS property

---

## 📄 License

This project is for educational purposes as part of a web development assignment. Free to use and adapt.

---

## 👤 Author

**Taha**
- GitHub: [@taha20353](https://github.com/taha20353)
- Demo: [fitcore-gym](https://taha20353.github.io/fitcore-gym)

---

*Built with ❤️ using pure HTML & CSS.*
