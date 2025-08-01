# Dynamic Portfolio Web App

## Objective
This is a performant, responsive, and cross-browser compatible portfolio web application that demonstrates core web development skills using **HTML**, **CSS**, and **JavaScript**. It integrates dynamic features and progressive enhancements with a focus on speed and compatibility.

## Features
- **Dynamic content loading:** Projects are injected via JavaScript with a "Load More" mechanism.
- **Lazy loading images:** Uses native `loading="lazy"` attribute to defer offscreen image loading.
- **Theme toggle:** Light/dark mode with preference persisted in `localStorage` and system-preference fallback.
- **Responsive design:** Fully mobile-friendly layout with a collapsible navigation menu.
- **Cross-browser compatibility:** Uses modern but broadly supported APIs and fallback-friendly CSS.
- **Performance optimizations:**
  - Minimal external dependencies (vanilla JS).
  - Preloading critical stylesheet.
  - Efficient DOM updates.
- **Offline support:** Service Worker caches key assets for improved repeat load performance and basic offline fallback.
- **Accessible markup:** Semantic HTML, `aria` labels where appropriate, and polite live region for form feedback.

## File Structure

