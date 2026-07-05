# ZenGIS: GIS Developer Learning Resources

Welcome to **ZenGIS**, a curated, tiered training resource portal designed to help junior CS/IT developers transition into GIS-related developer roles (Frontend, Backend, Database, DevOps, and GIS Analyst).

Rather than writing custom content, this website compiles high-quality external resources (videos, official guides, books, exercises) and structures them into separate modular concept maps.

---

## Getting Started

This site is powered by **Zensical** (`zensical.org`). Follow the steps below to run it locally or compile the static pages.

### 📋 Prerequisites

Ensure you have Python 3 and `pip` installed on your machine.

### 🛠️ Installation

Install the required dependencies inside a Python virtual environment:

```bash
# Create virtual environment (if not already done)
python3 -m venv .venv

# Activate it
source .venv/bin/activate

# Install Zensical
pip install zensical
```

### 🚀 Running the Local Server

Start the live-reloading Zensical preview server:

```bash
zensical serve
```

Once running, open your browser and navigate to:
👉 **[http://127.0.0.1:8000/](http://127.0.0.1:8000/)**

### 📦 Building the Production Site

To generate the static HTML files:

```bash
zensical build
```

This compiles the entire site.

---

## Repository Structure

- `zensical.toml`: The main configuration file defining the sidebar navigation, layout, theme palettes, and features.
- `docs/`: The source directory containing all Markdown documentation files.
  - `index.md`: The home/introductory page listing all categories.
  - `gis/`: General GIS concepts.
  - `rs/`: Remote Sensing concepts.
  - `frontend/`: UI mapping (Leaflet, OpenLayers, MapLibre, Cesium, Deck.gl) and basic UI/UX, HTML, and CSS concepts.
  - `database/`: Spatial Databases (PostgreSQL, PostGIS).
  - `backend/`: Map servers, APIs, and tiling protocols.
  - `devops/`: Containerization, caching, and JVM/Postgres performance tuning.
  - `analyst/`: QGIS interface, vector analysis, and Python automation scripts.
