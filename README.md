# PearlCrest Dental Studio

A highly optimized, premium front-end landing page for a cosmetic and family dentistry clinic. This project showcases advanced frontend development techniques, focusing on zero-dependency core architecture, fluid responsiveness, and high-performance interactive elements.

## 🚀 Technical Highlights

This project was built from the ground up prioritizing speed, maintainability, and a modern aesthetic without relying on heavy frameworks like React or Bootstrap.

### Architecture & Core
* **Vanilla Stack:** Built with semantic HTML5, modern CSS3, and ES6 JavaScript.
* **Separation of Concerns:** Clean architectural split between markup (`index.html`), presentation (`style.css`), and behavior (`script.js`).
* **CSS Design System:** Implemented a robust token system using CSS Custom Properties (`:root` variables) for colors, spacing (`--sp-*`), typography, and easing functions, ensuring consistency and easy theme scaling.

### Layout & Responsiveness
* **Fluid Typography:** Utilized CSS `clamp()` functions for highly responsive, viewport-scaling typography across all devices.
* **Modern CSS Layouts:** Extensive use of CSS Grid and Flexbox for complex, multi-dimensional layouts (e.g., masonry-style galleries, multi-column feature grids).
* **Viewport Optimization:** Thoroughly audited and optimized for strict viewports down to 360x740, dynamically switching from complex grids to refined mobile columns and hamburger navigation logic.

### Interactions & Animations
* **Hardware-Accelerated CSS:** Complex animations (hero floaters, continuous shimmers, hover states) leverage properties like `transform` and `opacity` to ensure 60fps performance without triggering layout repaints.
* **Intersection Observer API:** Custom vanilla JS implementation for scroll-triggered "reveal" animations, staggering the entry of elements smoothly as they enter the viewport.
* **State Management:** Custom DOM state management for handling the mobile navigation menu, custom image lightboxes, and dynamic sticky headers.

### Third-Party Integrations
* **Lenis Smooth Scroll:** Integrated for a premium, buttery-smooth scrolling experience synchronized with native browser APIs.
* **Swiper.js:** Implemented a touch-capable, responsive carousel specifically configured for mobile patient testimonial slideshows.

### Performance Optimizations
* **Asset Optimization:** Comprehensive use of next-gen `WebP` image formats.
* **Resource Hinting:** Directives like `preconnect` and `dns-prefetch` utilized in the `<head>` for critical Google Fonts.
* **DOM Ready Execution:** Scripts are deferred to ensure the HTML parser is never blocked, yielding extremely fast First Contentful Paint (FCP) times.

## 🛠 Local Development

Ensure you have [Node.js](https://nodejs.org/) installed, then serve the directory locally:

```bash
# Execute using npx (no installation required)
npx serve .
```
Navigate to `http://localhost:3000` (or the port specified in your terminal) to view the project.
