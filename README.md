# ASTROLITH: ZERO G FORCE
### *Abandoned but not Forgotten · NASA Space Apps Challenge*

[![Next.js 16](https://img.shields.io/badge/Next.js-16.4.3-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![React 19](https://img.shields.io/badge/React-19.0.0-blue?style=for-the-badge&logo=react)](https://react.dev/)
[![Three.js](https://img.shields.io/badge/Three.js-r187-black?style=for-the-badge&logo=three.js)](https://threejs.org/)
[![React Three Fiber](https://img.shields.io/badge/R3F-v9-red?style=for-the-badge)](https://r3f.docs.pmnd.rs/)
[![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS-v4-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Web Audio API](https://img.shields.io/badge/Web_Audio_API-Procedural-green?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.7-3178C6?style=for-the-badge&logo=typescript)](https://www.typescriptlang.org/)
[![Static Export](https://img.shields.io/badge/Build-Static_Export_(out/)-success?style=for-the-badge)](https://nextjs.org/docs/app/building-your-application/deploying/static-exports)

---

## 🌌 Overview

**Astrolith: Zero G Force** is an interactive, educational, and scientifically grounded 3D web experience that preserves and celebrates the enduring legacy of **13 historic NASA spacecraft** resting silently across the Moon, Mars, the Asteroid Belt, and interstellar deep space.

Crafted around a strict **Modern Aerospace** design language inspired by NASA JPL and Mission Control interfaces, the application eliminates oversaturated neon clichés in favor of deep space obsidian (`#050810`, `#080B10`), matte titanium finishes, hairline glass borders, and floating VisionOS frosted-glass panels.

Every probe, lander, rover, and telescope is brought to life using official 3D hardware geometry, real NASA archival photography, real-time Deep Space Network (DSN) ephemeris calculations, and heartfelt first-person stories designed to inspire the next generation of explorers (ages 8–15).

---

## ✨ Key Features

### 1. 🪐 Real-Time 3D Solar System (0.1 AU – 30 AU)
* **Seamless Scaled Planetary Exploration:**
  * **Sun to Neptune:** Accurate relative orbital distances, self-rotations, and axial tilts.
  * **Earth & Moon:** High-resolution procedural and photographic crater maps with real-world Apollo coordinates.
  * **Mars:** Detailed topography highlighting Olympus Mons, Valles Marineris, and polar ice caps.
  * **Asteroid Belt (Ceres & 433 Eros):** Realistic irregular asteroid geometry based on NEAR Shoemaker telemetry and cryovolcanic Ahuna Mons on dwarf planet Ceres.
  * **Saturn (8K):** Multi-banded atmospheric shaders and double-sided shadow-casting ring disk featuring the Cassini Division.
  * **Uranus & Neptune:** Accurate retrograded axial tilts (97.8°), vertical ring systems, and deep azure methane scattering.

### 2. 🛰️ Official 3D Hardware Roster (13 Historic NASA Missions)
All spacecraft are rendered using official `.glb` models with dynamic physically based rendering (PBR) materials, seated seamlessly on terrain surfaces without clipping:
* **The Moon:**
  * `Apollo 11 Eagle Lunar Module` – Descent stage with gold Kapton thermal foil and the historic plaque.
  * `Lunar Roving Vehicles (LRV)` – Open chassis with woven titanium wire mesh tires.
  * `ALSEP Science Packages` – Nuclear RTG-powered surface experiments with active laser retroreflectors.
  * `Surveyor 3 Robotic Lander` – Shock-absorbing tripod struts, planar solar mast, and surface sampling scoop.
* **Mars:**
  * `Sojourner Mars Rover` – Microwave-sized pioneer with rocker-bogie suspension.
  * `Spirit & Opportunity (MER)` – Solar-winged twin geologists with panoramic cameras.
  * `Viking 1 & 2 Landers` – Three-legged stationary science stations that sent the first color Mars panoramas.
  * `Phoenix & InSight` – Robotic doctors with circular solar arrays and the SEIS seismic dome.
  * `Ingenuity Mars Helicopter` – Ultra-lightweight coaxial carbon fiber rotorcraft.
* **Orbits & Asteroids:**
  * `Kepler Space Telescope` – Earth-trailing 95-megapixel exoplanet hunter.
  * `Dawn Spacecraft` – Dual-target explorer with 20-meter tennis-court-sized solar arrays and blue xenon ion thrusters.
  * `NEAR Shoemaker` – First spacecraft to soft-land on a tumbling potato-shaped asteroid (433 Eros).
* **Deep Space:**
  * `Pioneer 10 & 11` – Interstellar probes equipped with 2.74-meter dish antennas and Carl Sagan's Golden Plaques.

### 3. 📡 Real-Time Deep Space Network (DSN) & Ephemeris Telemetry
* **Live Distance & Light Delay:** Dynamically calculates the exact real-time distance from Earth in both kilometers and Astronomical Units (AU), as well as **One-Way Light Time (OWLT)** and **Round-Trip Light Time (RTLT)** based on relativistic photon speeds ($c = 299,792\text{ km/s}$).
* **Active DSN Ground Stations:** Assigns the active Deep Space Network antenna complex (Goldstone DSS-14, Madrid DSS-63, Canberra DSS-43) and carrier frequency bands (X-band, S-band, UHF relay).
* **Interactive Light-Speed Transmission Simulator:** Sends a simulated radio carrier wave to each spacecraft, displaying the real propagation delay and retrieving historical mission telemetry logs.
* **Heritage Protection Status:** Highlights international space heritage classifications (NASA Artemis Accords, COSPAR Planetary Protection, and Interstellar Archival status).

### 4. 📖 First-Person Storytelling & Typewriter Terminal
* **Youth-Focused Narrative (Ages 8–15):** Written from the first-person perspective of each spacecraft (*"I am...", "I drove..."*), balancing heroism, pride, and poetic nostalgia.
* **Relatable Analogies:** Everyday comparisons kids can visualize (*"size of a golf cart"*, *"camping cooler"*, *"microwave oven"*, *"grand piano"*, *"tennis court"*, *"African elephant"*).
* **VisionOS Mission Panel:** Features live telemetry cards, NSSDCA catalog numbers, landing coordinates, NASA archival photos, why the mission went to sleep, and key scientific breakthroughs.

### 5. 🧊 "ZERO G FORCE" Decoupled Intro Animation
* **Interactive Ice Shatter:** First two clicks propagate realistic frost fracture networks and particle chips.
* **1.5-Second Decoupled Sequence:**
  1. On the 3rd click, the ice violently shatters into flying shards.
  2. The giant brand text **"ZERO G FORCE"** remains **completely stationary and visible for exactly 1.5 seconds (1500 ms)**.
  3. Only after the 1.5s delay do miniature rocket boosters ignite beneath the letters to thrust them away into deep space.
* **Acoustic Decoupling:** Glass explosion audio fires immediately; rocket thruster roar engages precisely after 1500 ms.

### 6. 🔊 100% Procedural Web Audio API Sound Engine
* Native browser audio synthesis without external MP3/WAV dependencies:
  * Deep cosmic ambient drone (`startCosmicAmbientDrone`)
  * Telemetry typewriter blips (`playTelemetryBlip`)
  * Deep space radar ping (`playSignalPing`)
  * Explosive ice fracture and rocket booster burn synthesis

---

## 📂 Directory Structure

```text
astrolith-main/
├── app/
│   ├── globals.css          # Tailwind CSS v4 design tokens and aerospace theme
│   ├── layout.tsx           # Root HTML layout, SEO metadata, and viewport configuration
│   └── page.tsx             # Main application entry point
├── components/
│   ├── experience.tsx       # Core orchestrator: camera tweening, active mission state
│   ├── IceIntroOverlay.tsx  # "ZERO G FORCE" 3-stage interactive ice break & rocket launch
│   ├── overlay/
│   │   ├── site-header.tsx  # Floating pill Navbar ("zero" logo, audio mute, explore button)
│   │   ├── story-modal.tsx  # VisionOS side panel with live DSN telemetry & stories
│   │   ├── hero.tsx         # Aerospace hero title and quick navigation guide
│   │   └── loading-screen.tsx
│   └── space/
│       ├── solar-system-scene.tsx # 3D Three.js solar system, orbits, and lighting
│       ├── spacecraft-models.tsx  # useGLTF loaders, procedural textures, and PBR materials
│       ├── lunar-rover.tsx        # LRV 3D model component
│       ├── alsep.tsx              # ALSEP 3D model component
│       ├── surveyor.tsx           # Surveyor 3 3D model component
│       └── mars-rover.tsx         # Sojourner 3D model component
├── lib/
│   ├── telemetry.ts         # Real-time Earth distance, OWLT, and DSN ephemeris engine
│   ├── stories.ts           # First-person narrative scripts for all 13 spacecraft
│   ├── equipment.ts         # Hardware specifications, NSSDCA IDs, coordinates
│   ├── i18n.ts              # English and Turkish localization dictionaries
│   ├── audio.ts             # Web Audio API procedural sound synthesizer
│   └── geo.ts               # Spherical latitude/longitude to 3D Cartesian vector math
├── public/
│   ├── models/              # Official NASA 3D .glb assets (lrv, alsep, surveyor3, sojourner...)
│   ├── textures/            # 8K/4K planetary maps, Kapton foil normals, solar arrays
│   └── spacecraft/          # NASA JPL archival mission photography
├── out/                     # 🚀 PRODUCTION-READY STATIC EXPORT DIRECTORY
├── dist/                    # Next.js build output
├── next.config.mjs          # Static export configuration (output: 'export')
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites
* **Node.js:** version 18.0.0 or higher (recommended: Node.js 20 LTS or 22 LTS)
* **Package Manager:** `npm`, `pnpm`, or `yarn`

### 1. Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/astrolith-zero-g-force.git
cd astrolith-zero-g-force
npm install
```

### 2. Run the Development Server
```bash
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser to view the application with Hot Module Replacement (HMR).

---

## 📦 Static Export & Production Build (`out/`)

This project is configured with **Next.js Static Export (`output: 'export'`)**, generating pure, serverless static HTML, JavaScript, CSS, and 3D assets that require no Node.js runtime in production.

### Building for Production
```bash
npm run build
```
When executed:
1. Turbopack compiles all pages, Three.js shaders, and Tailwind utility classes into static assets.
2. The complete production-ready site is output to the **`out/`** directory.
3. All 3D `.glb` models, 8K textures, and audio synthesis scripts are automatically packaged and bundled.

### Testing the `out/` Directory Locally
You can preview the built static site using any local HTTP server:
```bash
# Using npx serve:
npx serve out -l 5000

# Or using Python 3:
cd out && python -m http.server 5000
```
Then navigate to [http://localhost:5000](http://localhost:5000).

---

## 🌐 Deployment

Because the application builds to a pure static folder (`out/`), it can be hosted anywhere:

### 1. GitHub Pages
1. Push the code to your GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **GitHub Actions**.
4. The workflow in `.github/workflows/deploy.yml` will automatically build and publish the `out/` folder on every commit to `main`.

### 2. Vercel
Connect your GitHub repository to Vercel. Next.js static export settings are detected automatically:
* **Framework Preset:** Next.js
* **Output Directory:** `out` (or default `.next`)

### 3. Netlify / Cloudflare Pages / AWS S3
* **Build Command:** `npm run build`
* **Publish Directory:** `out`

---

## 🛠️ Tech Stack

* **Framework:** [Next.js 16](https://nextjs.org/) (App Router, Turbopack, Static Export)
* **UI Library:** [React 19](https://react.dev/)
* **3D Graphics Engine:** [Three.js r187](https://threejs.org/) & [@react-three/fiber](https://github.com/pmndrs/react-three-fiber) & [@react-three/drei](https://github.com/pmndrs/drei)
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/)
* **Motion & Physics:** [Framer Motion](https://www.framer.com/motion/)
* **Iconography:** [Lucide React](https://lucide.dev/)
* **Audio Synthesis:** Native Web Audio API (100% Procedural)
* **Type Safety:** TypeScript 5.7

---

## 📚 NASA Data Sources & References

* **3D Models:** [NASA 3D Resources](https://nasa3d.arc.nasa.gov/)
* **Archival Photography:** [NASA JPL Photojournal](https://photojournal.jpl.nasa.gov/)
* **Mission Telemetry & Catalog:** [NASA Space Science Data Coordinated Archive (NSSDCA)](https://nssdc.gsfc.nasa.gov/)
* **Solar System Ephemerides:** [NASA JPL Horizons System](https://ssd.jpl.nasa.gov/horizons/)
* **Tracking Network:** [NASA Deep Space Network (DSN) Now](https://eyes.nasa.gov/dsn/dsn.html)

---

## 📜 License

This project is licensed under the **MIT License**. Created with passion for the **NASA Space Apps Challenge**. Educational and open-source exploration encouraged!
