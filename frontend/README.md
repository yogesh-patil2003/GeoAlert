# GeoAlert — Frontend 🌐

The web client for **GeoAlert**, built with **React 19**, **Vite 7**, **Tailwind CSS**, **Three.js**, and **Leaflet**.

---

## 🛠️ Tech Stack & Libraries

- **Framework**: React 19 + Vite 7
- **3D Graphics**: Three.js, `@react-three/fiber`, `@react-three/drei` (Interactive 3D Earth Globe)
- **GIS & Mapping**: Leaflet 1.9, `react-leaflet`, `react-leaflet-draw`
- **Charts & Data Viz**: Recharts (NDVI trends and anomaly statistics)
- **Styling & UI**: Tailwind CSS 3.4, Lucide React icons, Framer Motion
- **Notifications**: React Hot Toast

---

## 🚀 Development Setup

1. **Install dependencies:**
   ```bash
   npm install
   ```

2. **Start the development server:**
   ```bash
   npm run dev
   ```
   The application will launch on `http://localhost:5173`.

3. **Build for production:**
   ```bash
   npm run build
   ```
   Build output will be generated in `dist/`.

4. **Lint code:**
   ```bash
   npm run lint
   ```

---

## 🧭 Page Overview

- **Landing (`pages/Landing.jsx`)**: 3D globe hero page with mission overview and authentication.
- **Dashboard (`pages/Dashboard.jsx`)**: Metrics overview, active AOI status, recent alerts, and quick actions.
- **Map Explorer (`pages/MapExplorer.jsx`)**: Full-screen interactive Leaflet map for drawing and exploring custom AOIs.
- **Analysis (`pages/Analysis.jsx`)**: In-depth temporal satellite comparison, NDVI difference maps, and threshold calibration.
- **Alerts (`pages/Alerts.jsx`)**: Incident management, severity breakdown, and email notification logs.
- **Settings (`pages/Settings.jsx`)**: User preferences, API configurations, and threshold settings.
