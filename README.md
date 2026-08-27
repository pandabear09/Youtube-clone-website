# Youtube-clone-website
# 🎬 (Frontend UI)

A pixel-perfect, fully responsive static clone of YouTube's desktop interface built entirely from scratch using pure **HTML5** and **CSS3**.

---

## 📌 Project Overview

This project was built to master core frontend styling, modern layout systems, and responsive web design without the aid of external UI frameworks, JavaScript libraries, or CSS preprocessors. The focus was on replicating YouTube's recognizable interface—capturing precise spacing, typography, component hierarchies, and interactive states.

---

##✨ Key Features

- **Top Navigation Bar:**
  - Fixed header layout with search input bar and search action button.
  - Quick action icons (Create, Notifications, Apps) and user profile badge.
  
- **Sidebar Navigation:**
  - Main categories (Home, Shorts, Subscriptions).
  - Library sections (History, Your Videos, Watch Later, Liked Videos).
  - Explore sections (Trending, Music, Gaming, News, Sports).

- **Filter / Topic Chips Bar:**
  - Horizontal category chips for filtering video genres (e.g., *All, JavaScript, Music, Web Development, Podcasts*).

- **Video Content Grid:**
  - Multi-column card layout displaying video thumbnails with duration overlay badges.
  - Channel avatar with `object-fit` circular cropping.
  - Video title, verified badges, channel name, views count, and relative upload timestamps.

- **Micro-Interactions & CSS States:**
  - Smooth hover transitions on video cards and thumbnail scale effects.
  - Interactive states on buttons, search bars, and navigation links.

- **Responsive Design:**
  - Adaptive CSS Grid that adjusts column counts seamlessly across various screen resolutions.

---

## 🛠️ Built With

- **HTML5:** Semantic document structure using `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<aside>`.
- **CSS3:**
  - **CSS Grid:** Multi-column dynamic video feed layout.
  - **CSS Flexbox:** Alignment for navigation bars, sidebar items, and card metadata.
  - **CSS Positioning:** Absolute positioning for video duration timestamps and badge overlays.
  - **Custom Properties (CSS Variables):** Maintainable color schemes and spacing variables.
  - **Media Queries:** Fluid viewport responsiveness.

---

## 📂 Project Structure

```text
Youtube-project/
│
├── youtube.html          # Main HTML markup
├── style/
│   └── general.css # Main stylesheet
|   └── header.css
|   └── sidebar.css
|   └── video.css   
├── icons/         # icon images
├── channel/         # images of channels
├── thumbnail/       # thumbnail images
└── README.md           # Project documentation
