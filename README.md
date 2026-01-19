# BajooAramSe 🎧

**BajooAramSe** is a responsive front-end clone of the Spotify web player interface. This project replicates the core layout and visual aesthetics of the popular music streaming service, featuring a dark-themed UI, a navigation sidebar, a main content area with music cards, and a sticky music player bar.

## 🚀 Features

* **Responsive Layout:** Built using CSS Flexbox to manage the sidebar, main content, and player controls.
* **Sidebar Navigation:** Includes standard navigation links (Home, Search) and a library section with "Create Playlist" and "Browse Podcasts" prompts.
* **Music Card Grid:** Displays playlists and albums in a grid format using specific sections like "Recently Played," "Trending Now," and "Featured Charts."
* **Sticky Music Player:** A fixed bottom player bar containing:
    * Album art and song details.
    * Playback controls (Shuffle, Previous, Play/Pause, Next, Loop).
    * Progress bar simulation.
    * **Interactive Volume Control:** A volume slider that reveals itself on hover (styled using CSS transforms).
* **Sticky Header:** The top navigation bar inside the main content area sticks to the top while scrolling.
* **Hover Effects:** Interactive opacity changes on buttons, icons, and navigation links for a polished user experience.

## 🛠️ Tech Stack

* **HTML5:** Semantic structure for the web page.
* **CSS3:** Custom styling, including:
    * Flexbox for layout management.
    * Media Queries for responsiveness (adapts layout for screens smaller than 1000px).
    * CSS Transitions for hover effects.
* **Font Awesome:** Used for icons (Home, Search, Play, Heart, etc.).
* **Google Fonts:** Uses the "Montserrat" font family for typography.

## 📂 Project Structure

```text
BajooAramSe/
├── assets/                  # Contains images (icons, album covers, cards)
│   ├── logo.png
│   ├── screenshot.png       # <--- Your website screenshot goes here
│   └── ...
├── index.html               # Main HTML structure
├── index.css                # Main Stylesheet
└── README.md                # Project Documentation
