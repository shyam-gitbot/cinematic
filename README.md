# Retro Cinema Picker 🎬

Retro Cinema Picker is a lightweight, single-file web application designed to solve the "what should I watch?" dilemma. Wrapped in a nostalgic, 80s-style CRT interface, it randomly selects high-rated movies for you, allowing you to track what you've seen, skip what you dislike, and build a watchlist.

## ✨ Features

- **📺 Retro Aesthetic:** CRT scanlines, neon glows, and digital noise effects for an immersive experience
- **♾️ Hybrid Database:** Comes with a built-in curated list of classics, but seamlessly expands to thousands of movies if a TMDB API key is provided
- **💾 Local Persistence:** Uses browser localStorage to remember your "Watched", "Skipped", and "Watchlist" movies without needing a backend server
- **⚡ Zero-Config Deployment:** The entire app lives in a single index.html file. Perfect for GitHub Pages
- **📱 Responsive Design:** Looks great on desktop and mobile devices
- **🧠 Smart Filtering:** Automatically excludes movies you've already seen or skipped

## 🚀 Live Demo

> Replace this link after you deploy to GitHub Pages

[View Live Demo](#)

## 🛠️ Setup & Installation

### 1. Quick Start (Local)

1. Download the `index.html` file
2. Open it in any modern web browser (Chrome, Firefox, Edge)
3. Enjoy!

### 2. Deploying to GitHub Pages

1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to **Settings** > **Pages**
4. Under **Source**, select `main` branch and `/` (root)
5. Click **Save** — your site will be live in minutes!

## ⚙️ Configuration (Optional)

To unlock the infinite movie database, you need a free API key from [The Movie Database (TMDB)](https://www.themoviedb.org/settings/api).

1. Open `index.html` in a text editor (Notepad, VS Code, etc.)
2. Find the configuration section around line 280:

```javascript
// ==========================================
// CONFIGURATION: API KEY
// ==========================================
const TMDB_API_KEY = "YOUR_API_KEY_HERE";
```

3. Paste your key inside the quotes
4. Save the file — the "LOCAL DB" indicator in the app header will switch to "TMDB CONNECTED"

## 🤝 Contributing

Contributions are welcome! Since this is a single-file project, please ensure any CSS or JS additions are kept within the `index.html` to maintain portability.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under the MIT License. See LICENSE for more information.

## 🙏 Acknowledgments

- [The Movie Database (TMDB)](https://www.themoviedb.org/) for the API
- [Lucide Icons](https://lucide.dev/) for the iconography
- [Tailwind CSS](https://tailwindcss.com/) for the utility classes
- [Google Fonts](https://fonts.google.com/) for the 'Limelight' and 'Share Tech Mono' typefaces