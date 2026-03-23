# Personal Portfolio

Welcome to the source code for my personal portfolio website. This document outlines the project's file structure so that anyone can easily understand how the files are organized and how the website functions.

## 📂 Project File Structure

The project has a lightweight and straightforward structure. It uses a single HTML file for the content and an `assets` folder to organize all stylesheets, scripts, images, and documents.

```text
portfolio/
│
├── index.html            # The main structural file. Manages all the content and layout.
│
├── README.md             # This documentation file.
│
└── assets/               # Directory holding all static assets (CSS, JS, Images, PDFs).
    │
    ├── styles.css        # Main stylesheet governing the overall look, feel, and responsiveness.
    ├── loader.css        # Styles explicitly for the animated loading screen.
    ├── script.js         # Javascript functionality (menu, animations, modals).
    ├── prem 5pdf.pdf     # Resume document linked in the hero section.
    │
    └── Images            # Certificates, projects, and other graphical assets:
        ├── homepage.jpg
        ├── bookbazaar.png, smartexpense.png, etc. (Project screenshots)
        └── infosys_java_cert.jpg, internship_cert.jpg, etc. (Certificate images)
```

## 📝 Detailed Breakdown

### 1. `index.html`
This is the single-page HTML skeleton of the portfolio. It encompasses all the main sections:
*   **Head**: Imports CSS stylesheets, Google fonts (Outfit, Plus Jakarta Sans), and FontAwesome icons.
*   **Sections**: Nav bar, Home/Hero, Education, Internship Experience, Technical Projects, Technical Expertise (Skills), Professional Certifications, and Contact.

### 2. `assets/` Folder
This is where the magic happens and what makes the website dynamic and visually appealing.

*   **Style Files (`.css`)**: 
    *   `styles.css` handles the primary design: colors, layout elements, typography, and responsive mobile adaptations.
    *   `loader.css` handles the specific styles and logic for the CSS-based initial loading animation when the website is refreshed.
*   **Scripting (`.js`)**: 
    *   `script.js` contains custom vanilla Javascript. It manages interactions like toggling the mobile menu, displaying the full-size certificate modals, and potentially adding scroll animations.
*   **Media Assets**: Contains all images seen on the site, including the background effects, hero profile picture (`homepage.jpg`), thumbnails for various project cards, and images of internship/professional certificates.
*   **Documents**: Contains my resume (`prem 5pdf.pdf`) which users can download from the main landing section.
