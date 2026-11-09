# 🛰️ PS8 — Lunar South Pole Exploration & AI Mission Command Center

<p align="center">
  <strong>AI-Powered Lunar GIS • Ice Detection • Safe Landing Analysis • Autonomous Rover Path Planning</strong>
</p>

<p align="center">
  An interactive lunar exploration command center inspired by India's Chandrayaan missions and NASA's Artemis program.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Space%20Tech-00D9FF?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Frontend-React%20%2B%20Tailwind%20v4-38BDF8?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Backend-FastAPI-009688?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Mapping-Leaflet-7CB342?style=for-the-badge" />
</p>

---

## 🌕 Project Overview

**PS8** is an interactive AI-assisted lunar exploration dashboard designed to visualize, analyze, and process lunar South Pole exploration data.

The platform combines Geographic Information System (GIS) visualization, lunar ice detection concepts, permanently shadowed region (PSR) analysis, landing-site assessment, and autonomous rover path planning into a unified mission command interface.

The system features an interactive lunar surface map with multiple analytical layers, CSV-based data processing workflows, mission telemetry visualization, and a five-stage exploration pipeline.

The project aims to demonstrate how AI, geospatial analysis, and intelligent planning can support future lunar exploration missions.

> **Project Type:** Hackathon / Research Prototype  
> **Focus:** Lunar GIS, AI-assisted exploration, geospatial analytics and autonomous navigation.

## 🖥️ Dashboard Preview

<p align="center">
  <img src="assets/mission-dashboard.png" width="100%" alt="PS8 Lunar South Pole Mission Dashboard" />
</p>

<p align="center">
  <em>Interactive Lunar South Pole GIS and Mission Command Center</em>
</p>

> Replace the image path above with your actual screenshot uploaded to the repository.

## 🚀 Live Demo

**Explore the Dashboard:**

https://ps8-three.vercel.app/

## ✨ Key Features

### 1. Interactive Lunar GIS Map

- Lunar South Pole surface visualization.
- NASA LROC / OpenPlanetary Moon basemap attribution.
- Interactive zoom and map navigation.
- Telemetry point visualization.
- Coordinate and elevation cursor display.
- Multiple geospatial visualization layers.

### 2. Five-Stage AI Exploration Pipeline

| Stage | Module | Function |
|---|---|---|
| 01 | Ice Detection | Visualizes subsurface ice probability |
| 02 | Ice Volume & PSRs | Estimates ice volume and identifies nested PSRs |
| 03 | Safe Landing Analysis | Evaluates candidate landing locations |
| 04 | Rover Path Planning | Demonstrates A* route-planning workflows |
| 05 | AI Confidence | Presents model confidence and validation metrics |

### 3. Ice Detection Layer

- Subsurface radar probability visualization.
- Ice probability threshold filtering.
- CSV input and output support.
- Interactive lunar map overlays.

### 4. Ice Volume & Doubly PSR Analysis

- Permanently Shadowed Region visualization.
- Nested PSR identification.
- Ice volume estimation workflow.
- CSV-based density analysis.

### 5. Safe Landing Site Assessment

- Terrain slope analysis.
- Landing candidate visualization.
- Low-hazard touchdown zone identification.
- DEM CSV processing workflow.

### 6. Autonomous Rover Path Planning

- A* path-planning algorithm integration.
- Exploration route visualization.
- Safer route selection concepts.
- Emergency rerouting interface.

### 7. AI Confidence & Validation

- AI confidence score visualization.
- Model validation metrics.
- Stage-wise analytical output.
- Mission status monitoring.

### 8. Mission Command Interface

- Mission telemetry dashboard.
- Spacecraft and exploration status panels.
- Fullscreen console interface.
- Mission report export.
- Interactive map controls.

---

## 📊 Dashboard Demonstration Metrics

The current dashboard displays the following sample metrics:

| Metric | Displayed Value |
|---|---:|
| Telemetry Points | 5,000 |
| High Ice Probability Zones | 526 |
| Safe Landing Candidates | 1,501 |
| Estimated Ice Volume | 4.82 × 10⁶ m³ |
| Doubly Nested PSRs | 14 |
| Average Surface Temperature | 167.6 K |
| AI Confidence | 87.4% |

**Important:** These are demonstration dashboard values, not independently verified measurements or confirmed real-time spacecraft telemetry. Actual scientific results require validated source datasets and documented processing methods.

---

## 🧠 System Architecture

```text
              PS8 MISSION COMMAND CENTER
                         |
              +----------+----------+
              |                     |
          FRONTEND               BACKEND
              |                     |
        React Application       FastAPI
              |                     |
        Tailwind CSS v4         API Endpoints
              |                     |
        Leaflet GIS             Data Processing
              |                     |
        Lunar Map Layers        CSV Analysis
              |                     |
        Telemetry UI            Analytical Results
              |                     |
              +----------+----------+
                         |
                 MISSION DATA LAYERS
                         |
          +--------------+--------------+
          |              |              |
       Ice Zones       Landing       Rover Routes
                       Candidates
```

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React | Frontend application |
| Tailwind CSS v4 | UI styling |
| JavaScript | Application logic |
| FastAPI | Backend API framework |
| Python | Data processing |
| Leaflet.js | Interactive GIS mapping |
| CSV | Dataset input and output |
| A* Algorithm | Rover path planning |

---

## 📂 Project Structure

```text
PS8/
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── ...
│
├── backend/
│   ├── main.py
│   └── requirements.txt
│
├── assets/
│   └── mission-dashboard.png
│
├── README.md
└── ...
```

*The structure above illustrates the intended project organization. Update it if your actual repository differs.*

---

## ⚙️ Installation & Setup

### Prerequisites

- Node.js and npm
- Python 3.10+
- Git

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd PS8
```

### 2. Setup Frontend

```bash
cd frontend
npm install
npm run build:css
npm run dev
```

### 3. Setup Backend

Open another terminal from the project root:

```bash
python -m pip install -r backend/requirements.txt
uvicorn backend.main:app --reload
```

### 4. Access the Application

- Frontend: http://localhost:5173
- Backend API: http://127.0.0.1:8000
- API Documentation: http://127.0.0.1:8000/docs

*Ensure the frontend and backend ports match your actual configuration.*

---

## 🗺️ Data Sources & Scientific Context

The project is inspired by lunar exploration datasets and scientific concepts associated with:

- NASA Lunar Reconnaissance Orbiter (LRO).
- Lunar Reconnaissance Orbiter Camera (LROC).
- Chandrayaan-2 mission instruments.
- Lunar Digital Elevation Models (DEM).
- Permanently Shadowed Regions (PSRs).
- Lunar polar ice exploration research.

**Data transparency:** The use of these mission names and datasets as scientific references does not imply an official partnership, endorsement, or access to live spacecraft telemetry. Dataset provenance and processing details should be documented for each actual input.

## 🎯 Project Objectives

1. Develop an interactive lunar exploration GIS dashboard.
2. Visualize potential lunar ice-rich regions.
3. Demonstrate PSR-based exploration analysis.
4. Evaluate potential landing locations using terrain data.
5. Demonstrate autonomous rover route planning.
6. Integrate geospatial visualization with AI-assisted analytics.
7. Provide an extensible foundation for future lunar research prototypes.

## 🔮 Future Enhancements

- [ ] Integration of verified NASA and ISRO datasets.
- [ ] Real scientific lunar elevation data processing.
- [ ] Advanced ice probability estimation models.
- [ ] Machine learning-based terrain classification.
- [ ] Improved autonomous rover navigation.
- [ ] Real-time data ingestion where supported.
- [ ] Advanced 3D lunar terrain visualization.
- [ ] Downloadable scientific analysis reports.
- [ ] Mission simulation and validation tools.

## 🤝 Contributing

Contributions are welcome!

If you are interested in lunar exploration, GIS, AI, Python, or autonomous navigation, you can contribute by:

1. Forking this repository.
2. Creating a feature branch.
3. Making your improvements.
4. Submitting a Pull Request.

Please include a clear description of your contribution.

## 📜 License

This project is intended for educational, research, and hackathon prototyping purposes.

Add an appropriate open-source license file before permitting reuse and redistribution.

## 👨‍🚀 Acknowledgements

Inspired by the scientific and technological achievements of:

- ISRO — Indian Space Research Organisation
- NASA — National Aeronautics and Space Administration
- OpenStreetMap / Leaflet ecosystem
- Open planetary mapping and lunar research communities

---

<p align="center">
  <strong>Exploring the Lunar South Pole Through AI, GIS & Intelligent Systems.</strong>
</p>

<p align="center">
  Built for the future of lunar exploration. 🌕
</p>
