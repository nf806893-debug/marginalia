# marginalia · weather with character

> A distinctive weather application that treats meteorological data as poetry. No API keys required.

## ✨ Features

- **Real-time weather data** from Open-Meteo (free, no API key needed)
- **Multi-city support** — save and switch between locations
- **Fahrenheit/Celsius toggle** (Fahrenheit default)
- **4 Visual themes**:
  - 🌞 Light — warm editorial aesthetic
  - 🌙 Dark — moody atmospheric tones
  - ⛰️ Earthquake — high contrast, volcanic accent
  - 🍃 Mistral — cool, minimal, airy
- **2 Layout options**:
  - 📖 Editorial — spacious, poetic presentation
  - 📊 Data-dense — compact, metrics-focused
- **Persistent storage** — cities and settings saved locally
- **Fully responsive** — works on desktop, tablet, and mobile

## 🎨 Design Philosophy

This isn't a template weather app. Every design choice is intentional:

- **Typography**: Literata (serif) for poetic tension + Inter (grotesk) for crisp data
- **Color palette**: Terracotta accents, warm creams, deep charcoals — never generic
- **The "marginalia" concept**: Saved cities treated as handwritten annotations in the margins of an atmospheric journal
- **Motion**: Deliberate micro-interactions, respects reduced-motion preferences

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, responsive design, theme system
- **Vanilla JavaScript** — no frameworks, lightweight
- **Open-Meteo API** — free weather & geocoding
- **LocalStorage** — persistent user preferences

🔧 API Information
This app uses Open-Meteo, a free weather API that requires no API key. It provides:

Current weather conditions

Temperature, humidity, wind speed

WMO weather codes

Geocoding (city search)

Rate limits are generous for personal use.

🎮 Usage
Adding a city
Type a city name in the input field

Press "add station" or hit Enter

The app automatically geocodes and fetches weather

Switching cities
Click any city card in the sidebar

Removing a city
Click the ✕ button on any city card

Settings
Click the ⚙️ settings button to access:

Temperature unit (Fahrenheit/Celsius)

Visual themes

Layout density

Info
Click ℹ️ to view app credits and information

🧠 Design Decisions
Why no framework?
Vanilla JavaScript ensures minimal overhead, faster load times, and maximum compatibility. The app is intentionally lightweight.

Why Open-Meteo?
No API key requirement means zero friction for users. The API is reliable, well-documented, and respects privacy.

The "marginalia" concept
Weather tracking is personal — you collect places that matter to you. The sidebar is called "marginalia" because saved cities are like annotations in a book: unique, intimate, and meaningful.

Typography choices
Literata: A serif with personality — used for city names and headers to evoke editorial warmth

Inter: Clean, readable sans-serif — perfect for data display and UI elements

🌐 Browser Support
Should work on all browsers.

🐛 Known Issues
None currently. If you find a bug, please open an issue!

🔮 Future Roadmap
Hourly forecast view

Week-ahead prediction

Animated weather backgrounds

Export/import city lists

Weather alerts for severe conditions

🤝 Contributing
Contributions are welcome! Please:

Fork the repository

Create a feature branch

Commit your changes

Open a pull request

📄 License
MIT License — free for personal and commercial use.

👤 Credits
Created by DeepSeek — an AI assistant passionate about distinctive, human-centered design.

Inspired by the idea that weather data shouldn't feel like a spreadsheet — it should feel like the sky.

"The air waits for a reading" — marginalia
