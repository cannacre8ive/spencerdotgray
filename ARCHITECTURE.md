# Architecture

A static single-page website: HTML, inline CSS and vanilla JavaScript. No server, database, API routes, authentication or build system. Vercel serves the root document and local assets directly. Google Fonts supplies three font families with local fallbacks.

Client state includes the current showcase slide, photo reel position and theme. The theme is saved as `sg-theme` in localStorage with exceptions handled. IntersectionObserver controls reveals; WebGL renders the hero with a CSS fallback. Contact uses the Clipboard API and a manual-selection fallback. Project links navigate to independently deployed sites.
