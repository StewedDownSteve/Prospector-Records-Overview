# Prospector Records Website

*Currently awaiting domaine problems with Squarespace, redoing the website for updated business photos*

## Live Website 
[demo link](https://prospector-records.netlify.app/)

## About
This is a responsive website built for **Prospector Records**, a local record store that was relocating and needed a new online presence. The site serves as a clean, "brochure-type" website to showcase their services, location, hours, and history while guiding users to their physical store or online Discogs shop. 


## How It's Made
This project was built using:
- **HTML** and **CSS**: For semantic structure and visual design.
- **Vanilla JavaScript**: Used for button animations and a responsive navigation bar.

### Features and Approach:
1. **Component-Based Design**:
   - Each section was designed as a reusable component using just HTML and CSS.
   - A core `styles.css` sheet was implemented to manage reusable colors and themes, utilizing CSS custom properties (e.g., `color: var(--primary)`).

2. **Responsive Design**:
   - The website was developed mobile-first, using media queries to add design variations for tablets and desktops.
   - This approach ensured that sections could be reused across different pages and devices without duplicating code.

3. **Optimized for Performance**:
   - Lazy loading was implemented for non-essential images.
   - All images were compressed and converted to WebP format for faster loading.
   - SVGs were optimized to reduce file sizes.
   - The site achieved a **perfect 100 score on Google PageSpeed Insights**.

## What I Learned
This project reinforced several key concepts:
- **Mobile-First Design**: Building with smaller screens in mind first made it easier to scale up the layout for larger devices.
- **CSS Custom Properties**: Using variables for colors and themes streamlined consistency across pages.
- **Performance Optimization**: Techniques like lazy loading, image compression, and SVG optimization significantly improved load times and user experience.
- **Component-Based Development**: Organizing sections as reusable components simplified the design and development process, making the site more maintainable.

## Optimizations
- **Current Features**:
  - Lazy loading and image compression have minimized load times.
  - Media queries effectively adapt the design to various screen sizes.

- **Future Improvements**:
  - Using a React, Nunjucks, 11ty, SCSS set up so I could use more components without losing performance.
  - Adding Decap CMS integration to allow the client to update content independently.
  - 

## Final Thoughts
This project was a rewarding opportunity to combine best practices in responsive web design with performance optimizations. The end result is a fast, clean, and functional website that serves Prospector Records' needs effectively.



### Hero - Desktop
![Prospector Records Site Hero](https://github.com/StewedDownSteve/prospector-records-site/blob/main/prospector-github-img/prospector-hero-desktop-img.png)

### Hero - Mobile
![Prospector Records Site Hero Mobile](https://github.com/StewedDownSteve/prospector-records-site/blob/main/prospector-github-img/prospector-hero-mobile-img.png)

### Services - Desktop, Tablet, Mobile 
![Prospector Records Site Desktop](https://github.com/StewedDownSteve/prospector-records-site/blob/main/prospector-github-img/prospector-services-desktop-img.png)
![Prospector Records Site Tablet](https://github.com/StewedDownSteve/prospector-records-site/blob/main/prospector-github-img/prospector-services-tablet-img.png)
![Prospector Records Site Mobile](https://github.com/StewedDownSteve/prospector-records-site/blob/main/prospector-github-img/prospector-services-mobile-img.png)

