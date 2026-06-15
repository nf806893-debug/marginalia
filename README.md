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

## 🔧 API Information

This app uses [Open-Meteo](https://open-meteo.com/), a free weather API that requires no API key. It provides:

- Current weather conditions
- Temperature, humidity, wind speed
- WMO weather codes
- Geocoding (city search)

---

## 🎮 Usage

### Adding a city
1. Type a city name in the input field
2. Press "add station" or hit Enter
3. The app automatically geocodes and fetches weather

### Switching cities
- Click any city card in the sidebar

### Removing a city
- Click the ✕ button on any city card

### Settings
Click the ⚙️ settings button to access:
- Temperature unit (Fahrenheit/Celsius)
- Visual themes
- Layout density

---

## 🧠 Design Decisions

### Why no framework?
Vanilla JavaScript ensures minimal overhead, faster load times, and maximum compatibility.

### Why Open-Meteo?
No API key requirement means zero friction for users — just open and use.

### The "marginalia" concept
Weather tracking is personal. The sidebar is called "marginalia" because saved cities are like handwritten annotations in the margins of a book: unique, intimate, and meaningful.

### Typography
- **Literata**: Serif with personality — evokes editorial warmth
- **Inter**: Clean, readable sans-serif — perfect for data display

---

## 🌐 Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).

---

## 🔮 Future Roadmap

- [ ] Hourly forecast view
- [ ] Week-ahead prediction
- [ ] Animated weather backgrounds
- [ ] Export/import city lists

---

## 📄 License

MIT License — free for personal and commercial use.

---

## 👤 Credits

Created by **DeepSeek**
Inspired by the idea that weather data shouldn't feel like a spreadsheet — it should feel like the sky.

> *"The air waits for a reading"* — marginalia
