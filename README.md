# Hormuz Watch

A real-time maritime vessel tracking dashboard for the Strait of Hormuz. Built with React and Leaflet, it provides live vessel positions, traffic analytics, port intelligence, and detailed ship profiles — all in a dark-first, responsive UI.

---

## Features

- **Interactive Map** — Live vessel positions rendered on a Leaflet map with animated movement for underway ships
- **Vessel Filtering** — Filter by vessel type (tanker, cargo, LNG, etc.) or flag state
- **Traffic Analytics** — Charts for vessel type distribution, flag breakdown, speed profiles, and hourly transit data
- **Vessel Details Panel** — Full ship profile with status, speed, heading, and vessel photo
- **Ports Panel** — Port activity and status overview
- **News Panel** — Maritime news feed
- **Side Navigation** — Quick access to Compliance, Pricing, Data Services, Solutions, Notifications, Support, and Profile panels
- **Dark / Light Mode** — Toggle between themes

---

## Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 19 |
| Build Tool | Vite 7 |
| Map | Leaflet + react-leaflet |
| Charts | Chart.js + react-chartjs-2 |
| Linting | ESLint 9 |

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Installation

```bash
# Clone the repository
git clone https://github.com/ferzxdigitals-gif/Hormuz-Watch_files.git
cd Hormuz-Watch_files

# Install dependencies
npm install

# Start the development server
npm run dev
```

The app will be available at `http://localhost:5173`.

### Build for Production

```bash
npm run build
```

The output will be in the `dist/` folder.

### Preview Production Build

```bash
npm run preview
```

---

## Project Structure

```
├── public/
│   ├── ships/          # Vessel photos by type
│   └── header-bg.png
├── src/
│   ├── components/
│   │   ├── panels/     # VesselDetails, Ports, News, Profile panels
│   │   ├── Charts.jsx
│   │   ├── FilterBar.jsx
│   │   ├── Header.jsx
│   │   ├── ShipMap.jsx
│   │   ├── ShipSilhouette.jsx
│   │   ├── SideNav.jsx
│   │   ├── TrafficAnalytics.jsx
│   │   └── VesselTable.jsx
│   ├── data/
│   │   ├── vessels.js      # Vessel data generator
│   │   ├── shipPhotos.js
│   │   └── shipSvgs.js
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start development server with HMR |
| `npm run build` | Build for production |
| `npm run preview` | Preview production build locally |
| `npm run lint` | Run ESLint |

---

## License

Private project — all rights reserved.
