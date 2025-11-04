# 🧭 SportsVoyager

**SportsVoyager** is a modular, editorial-style travel guide tailored for sports enthusiasts seeking immersive match weekend experiences.
Built with semantic HTML5 and scalable CSS3, the site delivers a visually striking and responsive user experience.

This project was developed as part of **Project Milestone 1 for Code Institute’s Full Stack Software Development Diploma**. 
It demonstrates core front-end development skills while laying the foundation for a possible commercially viable product. The codebase is structured to meet professional standards and is open to future expansion.

---

## 📌 Overview

SportsVoyager blends clean structure, bold design, and practical scalability to showcase iconic sports trips across Europe. Each page is crafted to highlight city-specific match weekends, with a layout optimized for storytelling, experience and future growth.

---

## 🧠 User experience (UX)


SportsVoyager was designed to deliver an emotionally engaging and intuitive experience for football fans planning match weekend escapes. The layout, content, and navigation were shaped for user goals, ensuring the site feels both editorial and practical for the UX and to be as easy as possible to navigate.

👥 User Stories

As a site visitor, I want to:

- 🧭 Understand what the site offers quickly, so I can decide if it’s relevant to me.
- 🏄‍♂️ Explore destinations, so I can find places that match my interests.
- 📱 Use the site easily on mobile, so I can browse on the go.
- 🎯 Access clear navigation and CTAs, so I can move through the site without confusion.
- 🧠 Experience good contrast and keyboard accessibility, so I can use the site regardless of ability.


---

## 🎨 Design


The design of SportsVoyager was crafted to evoke editorial warmth, trust, and fan-first energy. Every visual choice—from typography to imagery—was made to support clarity, emotional impact, and responsive usability.

### 🎨 Colors Variables
This file (variables.css) defines the global design tokens for the SportsVoyagers website. It keeps colors, typography, and component styles consistent across all pages.

✨ What’s Inside

Brand Colors:

--gold-highlight,
--gold-deep,
--charcoal-dark,
--charcoal-panel, 
--gray-muted

Text & Backgrounds:

--text-main,
--text-light,
--bg-panel,
--bg-dark

Accents & CTAs: 

--accent,
--accent-hover

Cards & Shadows:

--card-bg,
--card-shadow,
--gradient-panel

Typography:

--font-main: 'Lato', 
--font-heading: 'Playfair Display'


### 🔠 Typography

Headings: Playfair Display (serif, editorial)

Body: Lato (sans‑serif, clean and legible)

Fonts are loaded with @font-face and font-display: swap for performance.


These colors were chosen to reflect the excitement of matchday travel while maintaining accessibility. The palette evokes clarity, and editorial depth—perfect for fan-first travel story.

---

### 📱 Responsive layout

This website is designed to work well on all screen sizes — from mobile phones to tablets and desktops. I used a mobile-first approach, which means the layout starts simple for small screens and then adds more structure for larger screens.

### How it works

I created a separate CSS file called `responsive.css` that includes media queries to adjust the layout depending on the screen width.

- **Mobile (up to 768px)**  
  - The hero section is centered and resized for readability.  
  - Grid sections stack into a single column for easier scrolling.  
  - Font sizes and padding are adjusted to fit smaller screens.

- **Tablet (up to 1024px)**  
  - Grid sections show two columns instead of one.  
  - Layout spacing is slightly increased for better readability.

- **Desktop (above 1024px)**  
  - Navigation is shown fully across the top with horizontal links.  
  - Grid sections show three or four columns depending on the layout.  
  - The site is centered with a maximum width for better visual balance.

### File used

The responsive layout is handled in `assets/css/responsive.css`.  
All styles are commented to explain what each section does and which screen size it targets.

#### Screenshot

You can find a screenshot showing the layout across devices in the `/assets/screenshots/responsive-layout/` folder.

![Responsive layout](assets/images/screenshots/responsive-layout.png)

---

## 🖼️ Imagery

Imagery plays a central role in creating an immersive, fan-first experience:

- Hero Image
A full-width background photo sets the tone for matchday excitement and editorial depth.

- Trip Cards
Destination-specific images highlight iconic stadiums, fan culture, and local atmosphere.


All images were curated to support editorial storytelling and visual rhythm. Each asset was selected for its emotional clarity, cultural relevance, and commercial safety with b.

## 📦 Image Sources & Attribution

| Use Case     | Description / Title                                | Photographer         | Source        |
|--------------|----------------------------------------------------|----------------------|---------------|
| Hero Image   | “A stadium full of people watching a football game”   | Alessio Patron       | [Unsplash](https://unsplash.com) |
| Trip Card    | “Soccer field at Camp Nou, Barcelona”     | Michael Lee    | [Unsplash](https://unsplash.com/@guoshiwushuang) |
| Trip Card    | “Street scene in Dortmund, NRW, Germany”  | Radwan Menzer    | [Pexels](https://pexels.com/@radwanmenzer) |
| Trip Card    | “Aerial view of Camp Nou stadium, Barcelona” | Iakov Filimonov     | [Dreamstime](https://www.dreamstime.com)|
| Trip Card    | “Stadium in Amsterdam” | Toni Cuenca    | [Unsplash](https://unsplash.com/@toni_cuenca)|
| Trip Card    | “Aerial view of Camp Nou stadium, Barcelona” | Iakov Filimonov     | [Dreamstime](https://www.dreamstime.com/jackf_info)|
| Trip Card    | “Panoramic view of Allianz Arena, Munich”     | Mehmet Efe Gencer    | [Pexels](https://www.pexels.com)|
| Trip Card    | “Fan watching a soccer game in Dortmund”   | Bernhard Oberle    | [Pexels](https://www.pexels.com) |
| Trip Card    | “A crowd of people standing around each other” | Alessio Patron   | [Unsplash](https://unsplash.com)|
| Trip Card    | “Football stadium with crowd view”    | Andreas Brox     | [Pexels](https://www.pexels.com)|
| Trip Card    | “View of Anfield Stadium with Ray Clemence mural”         | Alamy Contributor           | [Alamy](https://www.alamy.com)|
| Trip Card    | “An empty Etihad Stadium, Manchester” | Simon Gough      | [Pexels](https://www.pexels.com)|
| Trip Card    | “Street scene with Maradona mural in Naples” | Luca Musella     | [Pexels](https://www.pexels.com)|
| Trip Card    | “Gardener maintains Parc des Princes field in Paris” | TBD Traveller    | [Pexels](https://www.pexels.com)|
| Trip Card    | “Football stadium with lighting” | Pixabay user     | [Pixabay](https://pixabay.com)|
| Trip Card    | “City landmark architecture in Rome”        | Kelly            | [Pexels](https://www.pexels.com)|

All images were sourced ethically, copyright free and optimized for grading-safe and commercial deployment. Attribution details are listed where required.

---

## 🧮 Wireframes


Wireframes were created to guide layout decisions and ensure responsive clarity. Each follows a consistent modular pattern:

🏠 Home Page Wireframe
Features: Hero section, featured trips, navigation bar
Screenshot: 1[Homepage Wireframe](/assets/images/screenshots/screenshot-index.png)
Notes: Establishes visual rhythm and trip hierarchy


🌍 Destinations Wireframe
Features: Grid of featured trips, destination filters
Screenshot: ![Destinations wireframe](/assets/images/screenshots/screenshot-trip-card.png)
Notes: Supports modular expansion and editorial grouping

ℹ️ Info Page Wireframe
Features: How it works, What’s included, FAQs, Fan Experience Video, Testimonials
Screenshot: ![Info page wireframe](/assets/images/screenshots/screenshot-info.png)
Notes: Editorial clarity through sectioning and visual anchors

📬 Contact Page Wireframe
Features: Form structure, social icons, footer layout
Screenshot: ![contact page wireframe](/assets/images/screenshots/screenshot-contact.png)
Notes: Balanced layout with clear CTA and accessibility cues

These wireframes informed the modular structure and helped maintain hierarchy across devices. Each screenshot reflects layout intent and editorial clarity.

---

## 🧱  Project Structure

sports-voyager/
├── index.html               # Homepage with hero section and highlight featured trips|
├── trips.html               # Modular layout for destination listings|
├── info.html                # All info and Q&A |
├── contact.html             # Dedicated contact form page|
├── README.md                # Project documentation|

├── assets/
│   ├── css/
│   │   ├── base.css         # Base and global styles
│   │   ├── buttons.css      # CTA and link button styling
│   │   ├── components.css   # Modular blocks and reusable UI elements
│   │   ├── featured.css     # Styling for featured trip cards
│   │   ├── info-card.css    # Layout for About/Contact info blocks
│   │   ├── layout.css       # Grid and responsive structure
│   │   ├── navigation.css   # Header and nav bar styling
│   │   ├── responsive.css   # Responsive layout tuning for mobile and desktop
│   │   ├── typography.css   # Font styles and text hierarchy
│   │   └── variables.css    # CSS custom properties for color and spacing

│   ├── icons/
│   │   ├── facebook.svg     # Footer social icon
│   │   ├── instagram.svg    # Footer social icon
│   │   └── twitter.svg      # Footer social icon

│   └── images/
│       ├── Barcelona-1.jpg  # Destination imagery
│       ├── barcelona-2.jpg  # Destination imagery
│       ├── dortmund-1.jpg   # Destination imagery
│       ├── dortmund-fan.jpg # Editorial testimonial image
│       ├── hero-bg.jpg      # Homepage hero background
│       └── logo-card.jpg    # Branding asset






Each HTML file uses semantic tags (`<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`) to ensure accessibility, SEO optimization, and clean content hierarchy.

---

## ✨  Features

- ✅ Semantic HTML5 for accessibility and SEO
- ✅ Modular CSS with responsive layout
- ✅ Editorial hero section and trip cards
- ✅ Social media icons with hover transitions
- ✅ Testimonials and Video
- ✅ Contact Form
  

---



## ✅ Testing and Validation

  ✅ The site was tested with the WAVE WebAIM Accessibility Evaluation Tool, which reported 0 errors and 0 contrast errors, confirming that the design meets accessibility standards (with only minor alerts for redundant alt text).
  ![Wave validation Screenshot](assets/images/screenshots/wave-result.png)
  
  All pages passed W3C HTML and CSS validation

  ✅ The site’s CSS was tested using the W3C Jigsaw CSS Validator.
  All custom stylesheets passed without critical errors.
  Minor warnings related to CSS variables and third-party libraries (e.g. Font Awesome) are expected and do not affect browser rendering.
  ![CSS Validation Screenshot](assets/images/screenshots/css-validation.png)

  ✅ The site’s HTML was tested using the W3C Markup Validation Service.
  All pages passed without critical errors.
  Minor warnings (e.g. redundant attributes or empty alt tags) were reviewed and do not affect accessibility or rendering.
  ![HTML Validation Screenshot](assets/images/screenshots/html-validation.png)

### ✅ Browser Testing

| Device        | Chrome | Safari | Firefox | Edge |
|---------------|--------|--------|---------|------|
| Windows Laptop| ✅     | N/A    | ✅      | ✅   |
| MacBook       | ✅     | ✅     | ✅      | ✅   |
| iPhone        | ✅     | ✅     | ✅      | ✅   |
| Android Phone | ✅     | N/A    | ✅      | ✅   |
| iPad          | ✅     | ✅     | ✅      | ✅   |

> Note: Safari is not available on Android devices.

### ✅ Audit Scores (Chrome DevTools)
- Performance: 88
- Accessibility: 91
- Best Practices: 94

---

### ✅ Testing – User Stories

The following section demonstrates how the website meets the expectations outlined in the original user stories. Each story is followed by a brief explanation and a supporting screenshot.

👤 As a first-time visitor, I want to understand what the site offers quickly.

✅ Solution: The homepage features a bold hero banner with a clear tagline and CTA button, supported by a short intro paragraph and visual cues.

📸 Screenshot: Homepage hero section with tagline and CTA
![Homepage Hero](assets/images/screenshots/homepage-hero.png)

---

🧭 As a sports and travel enthusiast, I want to browse destinations.

✅ Solution: The “Destinations” section uses interactive cards with images, a descriptions and hover effects for clicking a destinations accordingly.

📸 Screenshot: Destination card section
![Sport Filter Cards](assets/images/screenshots/destinations.png)

---

📱 As a mobile user, I want the site to be easy to use on my phone or my tablet.

✅ Solution: The layout is fully responsive, navigation, stacked content, and touch-friendly buttons.

📸 Screenshot: Mobile layout home page
![Mobile Layout](assets/images/screenshots/mobile-layout.png)

---

🧠 As a visually impaired user, I want good contrast and keyboard accessibility.

✅ Solution: The site uses high-contrast gold-on-charcoal tones, visible focus states, and semantic HTML. Tested with WAVE accessibility tool.

📸 Screenshot: WAVE results showing 0 errors
![Wave validation Screenshot](assets/images/screenshots/wave-result.png)

---

🎯 As a site visitor, I want clear navigation and CTAs, so I can move through the site without confusion.  

✅ Solution: The navigation bar is consistent across all pages, with clear links to Home, Destinations, Info, and Contact. CTA buttons are styled in gold for 
visibility.  

📸 Screenshot: Navigation bar with highlighted CTA  
![Navigation Screenshot](assets/images/screenshots/navigation.png)

---

## 🐞 Known Bugs


- Hero image scaling on very small screens.
On ultra‑narrow devices, the hero background can extend slightly beyond the viewport, which may introduce horizontal scrolling. This is a visual quirk only and does not affect site functionality.

- Footer alignment inconsistencies.
Depending on the browser, footer text may shift position. This is a minor presentation issue and does not interfere with links or navigation.

- Default form validation styling.
Browser‑generated validation messages (e.g. for required fields) appear with default styles rather than the site’s custom design. The validation works correctly, but the look could be refined.

- Validator warnings from external libraries.
HTML and CSS validators raise expected warnings related to third‑party code (such as Font Awesome) and the use of CSS variables. These are non‑critical and do not impact accessibility or performance.

---

## 🚀 Deployment

This site is designed to be deployed as a static project using GitHub Pages.



## 🌍 How to View the Website

 - Visit the Website
👉 [https://Pierre-Louis789.github.io/sports-voyager1/]
- Browse the Pages
- 🏠 Home: Overview of featured football weekends
- 🧳 Destinations: Explore matchday trips across Europe
- 📍 Info: Learn how SportsVoyager works
- ✉️ Contact: Get in touch or ask questions
- Use Desktop or Mobile


The site is fully responsive—optimized for both desktop and mobile viewing.

🧠 Notes for First-Time Visitors

- No installation needed—just open the link in your browser.
- Best viewed in Edge, Chrome, Firefox, or Safari.
- All images and styles are ethically sourced and performance-optimized.


---

## 🧭 Roadmap

Planned future enhancements include:

- ➕ Additional trip detail pages for other European cities  
- 🔗 Integration of affiliate links for ticketing and accommodation  
- 📝 Fan review sections with moderated submissions  
- 📸 Image galleries and dynamic content zones  
- 🌍 Multi-language support for international audiences

---

## 📜 Credits

### Content

- All written by developer  

## 💬 Testimonials

Fictional quotes were crafted to evoke real fan voices and emotional resonance. These are editorial placeholders used to demonstrate layout rhythm and storytelling tone. No real individuals are represented.

### Acknowledgements

- Thanks to Code Institute and Level 5 Web Application Development cohort

---

## 📬 Contact

For collaboration, feedback, or commercial inquiries:  

📧 sicot.pierrelouis@gmail.com  

Or open an issue via [GitHub]👉 [https://Pierre-Louis789.github.io/sports-voyager1/](https://Pierre-Louis789.github.io/sports-voyager1/)

---

## 🧠 Author

Created by [Pierre-Louis789](https://github.com/Pierre-Louis789)  
Focused on modular architecture, editorial UX, and scalable front-end development.
