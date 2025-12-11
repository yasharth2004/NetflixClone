# Netflix India Landing Page Clone

A front-end replica of the Netflix India homepage. This project focuses on recreating the visual layout, typography, and styling of the original site using pure HTML and CSS.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup & Installation](#setup--installation)
- [Future Improvements](#future-improvements)

## 🔭 Overview
This project is a static landing page that mimics the design of Netflix. It covers the hero section, feature showcases (TV, Mobile, Device compatibility), a Frequently Asked Questions (FAQ) list, and the site footer. It demonstrates proficiency in Flexbox, CSS Grid, and positioning.

## ✨ Features
- **Hero Section:** Full-width background image with overlay, logo positioning, and "Get Started" email input field.
- **Feature Sections:** Alternating layouts (Text-Image / Image-Text) using Flexbox to display Netflix features (Watch on TV, Download offline, etc.).
- **Visual Accuracy:** Uses Netflix's specific red color scheme (`#e50914`) and closely matched typography (Poppins/Martel Sans).
- **FAQ Section:** A styled list of frequently asked questions with SVG icons.
- **Footer:** A multi-column footer layout using CSS Grid.

## 🛠 Technologies Used
- **HTML5:** Semantic structure (`<nav>`, `<section>`, `<footer>`).
- **CSS3:** Custom styling without frameworks.
    - **Flexbox:** Used for navigation and row alignment.
    - **CSS Grid:** Used for the footer link columns.
    - **Google Fonts:** Integration of 'Poppins' and 'Martel Sans'.

## 📂 Project Structure
To run this project correctly, ensure your folder structure looks like this:

```text
/netflix-clone
  ├── index.html        # Main HTML file
  ├── style.css         # Main stylesheet
  ├── /images           # Folder for image assets
  │     ├── bg.jpg
  │     ├── logo.svg
  │     ├── tv.png
  │     ├── mobile.jpg
  │     ├── arrow.svg
  │     └── ... (other icons/images)
  └── /videos           # Folder for video assets
        ├── video1.m4v
        └── video2.m4v
```

> **Note:** The HTML and CSS reference specific assets (e.g., `images/bg.jpg`). Ensure these files exist in their respective directories, or the images will appear broken.

## 🚀 Setup & Installation
1.  **Clone the repository** (or download the files):
    ```bash
    git clone [https://github.com/your-username/netflix-clone.git](https://github.com/your-username/netflix-clone.git)
    ```
2.  **Navigate to the project folder**:
    ```bash
    cd netflix-clone
    ```
3.  **Run the project**:
    * Simply double-click `index.html` to open it in your default web browser.
    * Alternatively, use a VS Code extension like **Live Server** to launch it.

## 🔮 Future Improvements
* **Responsiveness:** Add CSS Media Queries (`@media`) to make the site mobile-friendly (currently optimized for desktop).
* **Interactivity:** Add JavaScript to make the FAQ accordions expandable and collapsible.
* **Form Validation:** Add basic validation to the email input fields.

## 🤝 Contributing
Feel free to fork this project and submit pull requests for improvements!

---
*This project is for educational purposes only.*
