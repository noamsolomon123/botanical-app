# בוטניקה-פדיה (Botanica-Pedia) 🌿

A comprehensive, interactive, and highly engaging Botanical Educational Application built as a lightweight single-page React app (no build step required). 

This application is fully responsive, mobile-first, and designed with a modern Glassmorphism UI, Right-to-Left (RTL) Hebrew support, and a pastel color palette. It serves as an encyclopedic wiki, a gamified learning platform, and a plant care companion.

## ✨ Key Features

*   **📚 Massive Plant Catalog**: A deeply researched database of 78 unique botanical species ranging from everyday houseplants and herbs to rare orchids, massive trees (like the Baobab), and carnivorous plants. Includes search and a "Pet-Friendly" filter.
*   **🌱 My Garden Dashboard**: Users can save their favorite plants to their personal garden. Data is persisted directly to the browser's `localStorage`.
*   **🔥 Plantder (Swipe Feature)**: A Tinder-like gamified card swiping UI. Swipe left to pass, swipe right to discover the plant's deep botanical details and save it to your garden.
*   **🩺 Plant Clinic (Symptom Checker)**: An interactive diagnostic tool. Select a symptom (e.g., "Yellow leaves", "Brown tips", "Bugs") and receive immediate diagnoses and care actions.
*   **🧪 Growth Simulator**: A physics-and-logic based simulator. Choose a plant, guess its exact water and sun requirements (0-6 scale), and watch a custom-built, animated organic SVG plant grow sequentially if you get it perfectly right!
*   **🧠 Advanced Gamified Trivia**: A dynamic trivia generator that quizzes you on plant families, Latin names, and toxicity, complete with blurred image hints, visual feedback overlays, and a playful ranking system.
*   **🔊 Read-Aloud Accessibility**: Every plant modal features a text-to-speech button that pronounces the plant's Hebrew name and its Latin scientific name.
*   **📱 Mobile-Flawless UI**: Auto-hiding frosted glass sticky navigation, bottom-sheet style modals for mobile, and touch-friendly UI elements.

## 🛠️ Tech Stack

*   **Core**: React 18 & ReactDOM (Loaded via CDN)
*   **Styling**: Tailwind CSS (Loaded via CDN, custom configured with pastel themes)
*   **Typography & Icons**: 'Varela Round' Google Font, Lucide-React Icons, Native Emojis.
*   **Architecture**: Zero-build architecture. All logic resides in `index.html` via Babel standalone, with data separated cleanly into `data.js`.
*   **Data APIs**: Wikipedia native API for fetching high-resolution, accurate botanical thumbnails dynamically.

## 🚀 How to Run (Local)

Because this app uses a CDN-based architecture, there is zero setup required.

1. Clone or download this repository.
2. Simply double-click `index.html` to open it in any modern web browser.
3. Enjoy!

## 🌍 How to Host (Free)

This application is a pure "Static Site", meaning it can be hosted instantly for free.
*   **GitHub Pages**: Push this repository to GitHub and enable GitHub Pages in the repository settings from the `main` branch.
*   **Netlify Drop**: Simply drag and drop the project folder into [Netlify Drop](https://app.netlify.com/drop) to get an instant live URL.