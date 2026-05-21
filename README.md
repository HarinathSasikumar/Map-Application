# Map-Application
# Paranoid GPS Navigation

<p align="center">
  <b>"The optimal route is never the safest route."</b>
</p>

<p align="center">
AI-powered cinematic navigation with real-time routing, hazard detection, voice guidance, and psychological survival mechanics.
</p>

---

## Overview

Paranoid GPS Navigation is a futuristic AI-themed web application that transforms traditional navigation into an immersive psychological thriller experience.

Unlike conventional GPS systems that simply provide directions, Paranoid GPS treats every route like a survival mission. The system analyzes your environment, evaluates your stability, detects potential threats, and guides you through a world where the safest path is not always the shortest one.

Built entirely with pure HTML, CSS, and JavaScript, the project combines real-world mapping technologies with cinematic storytelling and interactive user experiences.

---

## Live Demo

Add your deployment link here:

```bash
https://HarinathSasikumar.github.io/paranoid-gps/
```

---

## Features

### Real-Time GPS Navigation
- Live route generation using OSRM
- Accurate road-based directions
- Dynamic route rendering

### Smart Geolocation
- Detects current user location automatically
- Converts coordinates into readable addresses

### AI Psychological Stability Check
- Interactive breathing rhythm test
- Verifies user calmness before navigation
- Trust-based navigation system

### Hazard Detection System
- AI-generated hazard zones
- Automatic safe-route calculations
- Emergency evasion path generation

### Voice Navigation
- Turn-by-turn voice instructions
- AI-style navigation alerts
- Browser-native speech synthesis

### Multiple Travel Modes
- Car mode
- Bike mode
- Bus mode

### Satellite Terrain Scan
- Simulated terrain analysis
- Radar scan effects
- Animated threat detection

### Dark Cinematic Interface
- Futuristic UI
- Neon effects
- Glitch animations
- Responsive design

---

## Tech Stack

| Technology | Purpose |
|------------|----------|
| HTML5 | Application structure |
| CSS3 | Styling and animations |
| JavaScript | Application logic |
| Leaflet.js | Interactive maps |
| OpenStreetMap | Map tiles |
| Nominatim API | Geocoding |
| OSRM API | Route calculation |
| Web Speech API | Voice navigation |
| Google Fonts | Typography |

---

## Project Structure

```bash
Paranoid-GPS/
│
├── index.html
├── style.css
├── app.js
├── README.md
│
└── assets/
```

---

## How It Works

### Step 1: Location Detection
The application automatically detects the user's current location through the browser Geolocation API.

### Step 2: Destination Search
Users can search destinations using OpenStreetMap's Nominatim API.

### Step 3: Stability Verification
Low-trust users must complete a psychological breathing test.

### Step 4: Satellite Scan
The AI scans the route and checks for possible hazards.

### Step 5: Route Generation
The application generates:

- Safe route
- Optimal route
- Emergency detour route

### Step 6: Voice Guidance
The system announces route instructions using speech synthesis.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/paranoid-gps.git
```

Move into the project folder:

```bash
cd paranoid-gps
```

Run using Python:

```bash
python -m http.server
```

Open:

```bash
http://localhost:8000
```

---

## Deployment

### GitHub Pages

```bash
git init

git add .

git commit -m "Initial Commit"

git branch -M main

git remote add origin https://github.com/YOUR_USERNAME/paranoid-gps.git

git push -u origin main
```

Go to:

```bash
Repository → Settings → Pages
```

Select:

```bash
Branch → main
Folder → /(root)
```

---

## Browser Compatibility

| Feature | Chrome | Firefox | Edge | Safari |
|-----------|---------|----------|-------|---------|
| Geolocation | Yes | Yes | Yes | Yes |
| Voice API | Yes | Partial | Yes | Yes |
| Leaflet Maps | Yes | Yes | Yes | Yes |

---

## Future Enhancements

- Real AI threat prediction
- Weather-based navigation
- Multi-user navigation
- Real-time traffic analysis
- Offline map support
- Machine learning route personalization

---

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## License

Distributed under the MIT License.

---

## Acknowledgements

- Leaflet.js
- OpenStreetMap Contributors
- OSRM Routing Engine
- Nominatim API
- Web Speech API

---

<p align="center">
Built with passion, imagination, and a healthy dose of paranoia.
</p>
