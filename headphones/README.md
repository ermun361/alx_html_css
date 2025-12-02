# 🎨 Responsive Landing Page - Implementation From Scratch

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Responsiveness](https://img.shields.io/badge/Responsive-Mobile%20First-green?style=for-the-badge)

> A pixel-perfect implementation of a design mockup, built purely with HTML and CSS without any external frameworks or libraries.

## 📑 Table of Contents
- [Overview](#overview)
- [The Challenge](#the-challenge)
- [Screenshots](#screenshots)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [Design System](#design-system)
- [Author](#author)

## 📍 Overview

This project is a culmination of HTML, CSS, Accessibility, and Responsive Design knowledge. The goal was to take a design file and translate it into a fully functional web page that looks identical to the creative vision, ensuring it works seamlessly across desktop and mobile devices.

## 🎯 The Challenge

The specific requirements for this implementation were:

- **No Libraries:** No Bootstrap, Tailwind, or jQuery. Pure Vanilla CSS/HTML.
- **Responsiveness:** The layout must switch to the mobile version when the screen width is `480px` or less.
- **Layout:** The content is centered with a maximum width of `1000px`.
- **Interactions:**
  - Links Hover/Active state: `#FF6565`
  - Buttons Hover/Active state: `opacity: 0.9`

## 📸 Screenshots

### Desktop Version
<img src="./screenshot version/01_headphones_desktop@2x.png" width="300" alt="desktop Screenshot">
*Layout constrained to 1000px width.*

### Mobile Version
<img src="./screenshot version/01_headphones_mobile@2x.png" width="300" height="800" alt="Mobile Screenshot">
*Responsive view at < 480px.*

## 🔗 Links

- **Code Repository:** [github.com/ermun361/alx_html_css](https://github.com/ermun361/alx_html_css/blob/main/headphones)
- **Live Site URL:** [ermun361.github.io/alx_html_css/headphones](https://ermun361.github.io/alx_html_css/headphones/)


## 🛠 My Process

### Built With

- **Semantic HTML5:** For accessible structure and SEO.
- **CSS3:** Custom properties, Flexbox, and Media Queries.
- **Mobile-First Workflow:** Ensuring performance on smaller devices.

### Design System & Implementation Details

I adhered strictly to the following style guide provided in the project brief:

| Category | Element | Value | Note |
| :--- | :--- | :--- | :--- |
| **Layout** | Max Width | `1000px` | Centered on page |
| **Responsive** | Breakpoint | `480px` | Mobile version trigger |
| **Colors** | Links (Hover/Active) | `#FF6565` | Coral / Light Red |
| **Interactions** | Buttons (Hover/Active)| `opacity: 0.9` | Visual feedback |
#### Code Snippet Highlight: Responsiveness
```css
/* Example of the breakpoint logic used */
@media screen and (max-width: 480px) {
    .container {
        width: 100%;
        padding: 0 20px;
    }
    /* Mobile specific adjustments */
}

## 👤 Author

- **Eric Munyi**
- GitHub: [@ermun361](https://github.com/ermun361)
- LinkedIn: [Erivc Munyi](https://www.linkedin.com/in/munyi-eric/)