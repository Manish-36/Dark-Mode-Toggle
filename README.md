# Dark Mode Toggle

A sleek, animated Dark Mode Toggle switch built with vanilla HTML, CSS, and JavaScript that transitions between light and dark themes and saves the user's preference in `localStorage`[cite: 12, 13].

## Preview

### Light Mode
<img width="1912" height="866" alt="Screenshot 2026-11-22 124009" src="https://github.com/user-attachments/assets/7b7cb89f-644f-426a-ab95-9ddf75cea85e" />

### Dark Mode
<img width="1917" height="862" alt="Screenshot 2026-11-22 123958" src="https://github.com/user-attachments/assets/105f6000-92e4-4c98-aad0-4190fb7b0872" />

## Features

* **Smooth Toggle Animation:** Uses CSS `@keyframes` (`toggleOn` and `toggleOff`) to slide the circular knob smoothly across the pill switch[cite: 12, 13].
* **Theme Switching:** Toggles the page background between `white` (light mode) and `black` (dark mode) with a `0.4s` transition[cite: 12, 13].
* **Persistent State (`localStorage`):** Saves the toggle state under `"mode"` and restores it automatically when the page is reloaded.
* **Accessible Label Switch:** Hides the native checkbox visually while binding it to a clickable `<label>` and `.circle` switch element.

---

## Project Structure

```text
├── index.html      # Hidden checkbox input, toggle label, and circular knob markup
├── style.css       # Switch styling, checked pseudo-class rules, and keyframe animations
├── index.js        # Theme toggle logic, change listener, and localStorage persistence
├── light-mode.png  # Light mode screenshot for the README
└── dark-mode.png   # Dark mode screenshot for the README
