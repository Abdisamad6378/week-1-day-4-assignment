# Week 1, Day 4 Assignment: Portfolio Enhancement

Welcome to my personal developer portfolio website! This project is an enhanced, single-page, fully responsive showcase designed to highlight my skills, projects, and contact details with premium styling.

## 🚀 Live Demo & Deployment
- **GitHub Repository**: [week-1-day-4-assignment](https://github.com/Abdisamad6378/week-1-day-4-assignment)
- **Live GitHub Pages URL**: [Live Portfolio Site](https://abdisamad6378.github.io/week-1-day-4-assignment/)

---

## 🎨 Key Features Implemented

### 1. Skills Section with Animated Progress Bars (Task 1)
- Displays 8 technical and soft skills categorized into two clean columns.
- Uses **pure CSS** keyframe animations (`@keyframes animateProgressBar`) to animate progress bars smoothly from `0%` to their target width when the page loads.
- Implements custom CSS variables (`--w`) in the inline HTML styles to dynamically pass the target width to a single, reusable animation block.
- Added a subtle hover transition that brightens and glows the active bar.

### 2. Smooth Scrolling Navigation (Task 2)
- Anchors (`id="about"`, `id="skills"`, `id="projects"`, `id="contact"`) mapped to the navigation links.
- Employs `scroll-behavior: smooth` for elegant scroll transitions.
- Added `scroll-padding-top: 80px` to offset the height of the sticky navigation bar so that section titles are never hidden underneath.

### 3. Fully Responsive Layout (Task 3)
- **Desktop (1024px+)**: Full multi-column split grid layouts.
- **Tablet (768px - 1023px)**: Two-column grid layouts with resized text and scaled images.
- **Mobile (Below 768px)**: Stacked single-column layouts. Link touch targets are optimized to be at least `44px` tall for easy mobile tapping.
- **CSS-Only Hamburger Menu**: Integrates a hidden checkbox trigger (`#menu-toggle`) to slide the navigation links down into view when tapped on mobile, complete with a hamburger-to-"X" rotation animation.

### 4. CSS-Only Theme Toggle (Bonus Challenge)
- Supports Light and Dark modes.
- Utilizes CSS variables defined on `:root` and re-assigned via the checked sibling selector `#theme-toggle:checked ~ .page`.
- Smoothly transitions background colors, text colors, shadows, and borders over a `0.3s` duration.
- Toggled via a custom-styled sliding pill switch in the navigation bar.

---

## 📁 File Structure
```text
week-1-day-4-assignment/
│
├── index.html          # Main page containing semantic tags and content sections
├── style.css           # Styling rules, animations, theme vars, and media queries
├── README.md           # Project documentation
│
└── assets/
    └── images/
        └── profile.jpg # Profile photo used in the bio
```

---

## 💻 Local Setup & Preview
1. Clone this repository or download the files.
2. Open `index.html` directly in any web browser, or use a local development server like VS Code Live Server.

---

## 📱 Screenshots (Placeholder)
Here are the preview layouts across three screen sizes:

### 1. Desktop Layout (1024px+)
![Desktop Mockup](assets/images/screenshot-desktop.png)

### 2. Tablet Layout (768px - 1023px)
![Tablet Mockup](assets/images/screenshot-tablet.png)

### 3. Mobile Layout (Below 768px)
![Mobile Mockup](assets/images/screenshot-mobile.png)

---

## 🤖 AI Usage Statement
All code in this repository includes custom comments above major layouts and functional logic. These comments explain the engineering rationale (e.g. checkbox state selectors, flex alignments, and CSS variables) in my own words.
