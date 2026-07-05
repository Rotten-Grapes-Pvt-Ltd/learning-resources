# ZenGIS: GIS Developer Learning Resources 🧘‍♂️

Welcome to **ZenGIS**, a comprehensive, granular learning resource portal for junior CS/IT developers transitioning into geospatial development.

This site contains individual concept pages for all core technologies, libraries, and workflows. You can drill down into any topic below to find notes, references, and practice challenges.

---

## 📚 Table of Contents

### 🌍 General GIS
*   [Vector Data](gis/vector.md)
*   [Raster Data](gis/raster.md)
*   [Map Projections](gis/projections.md)
*   [Coordinate Reference Systems (CRS)](gis/coordinate-systems.md)
*   [Spatial Relationships & Queries](gis/spatial-relationships.md)
*   [Web GIS Architecture](gis/web-gis-architecture.md)
*   [Spatial Data Formats](gis/data-formats.md)
*   [Geospatial Metadata](gis/metadata.md)

### 🛰️ Remote Sensing
*   [Fundamentals of Remote Sensing](rs/basics.md)
*   [Active vs. Passive Sensors](rs/active-vs-passive.md)
*   [Spectral Signatures](rs/spectral-signature.md)
*   [Spectral Bands & Imagery](rs/bands.md)
*   [NDVI & Spectral Indices](rs/ndvi.md)
*   [Elevation Models (DEM/DTM/DSM)](rs/dem.md)
*   [Sentinel-2 Satellites](rs/sentinel2.md)
*   [Landsat Satellites](rs/landsat.md)
*   [LiDAR Data](rs/lidar.md)
*   [Synthetic Aperture Radar (SAR)](rs/sar.md)

### 🌐 Frontend Web Mapping & Web Basics
*   **UI/UX Principles**:
    [Basic Principles](frontend/ui-ux/principles.md) | 
    [Typography](frontend/ui-ux/typography.md) | 
    [Colors & Contrasts](frontend/ui-ux/colors.md)
*   **HTML Basics**:
    [HTML Syntax](frontend/html/basics.md) | 
    [Semantic HTML5](frontend/html/semantic.md) | 
    [The DOM](frontend/html/dom.md)
*   **CSS Basics**:
    [CSS Syntax](frontend/css/basics.md) | 
    [Layouts (Flex & Grid)](frontend/css/layout.md) | 
    [Variables & Properties](frontend/css/variables.md)
*   **JavaScript**:
    [Syntax & Types](frontend/js/basics.md) | 
    [Async & Fetch](frontend/js/async.md) | 
    [DOM & Events](frontend/js/dom-events.md)
*   **React Basics**:
    [Core Concepts](frontend/react/basics.md) | 
    [Hooks](frontend/react/hooks.md) | 
    [State Management](frontend/react/state.md)
*   **Next.js**:
    [Fundamentals](frontend/nextjs/basics.md) | 
    [Routing](frontend/nextjs/routing.md) | 
    [Data Fetching](frontend/nextjs/data-fetching.md)
*   **Leaflet.js**:
    [Initialization](frontend/leaflet/setup.md) | 
    [Markers & Popups](frontend/leaflet/markers.md) | 
    [Vector Layers](frontend/leaflet/vector-layers.md) | 
    [Layer Switcher](frontend/leaflet/layerswitcher.md) | 
    [Event Handling](frontend/leaflet/events.md) | 
    [Plugins](frontend/leaflet/plugins.md)
*   **OpenLayers**:
    [Setup](frontend/openlayers/setup.md) | 
    [Views & Projections](frontend/openlayers/views.md) | 
    [WMS Layers](frontend/openlayers/wms.md) | 
    [WFS Layers](frontend/openlayers/wfs.md) | 
    [Drawing](frontend/openlayers/draw.md) | 
    [Modifying](frontend/openlayers/modify.md) | 
    [Styling](frontend/openlayers/styling.md) | 
    [Vector Tiles (MVT)](frontend/openlayers/vector-tiles.md)
*   **MapLibre GL JS**:
    [Setup](frontend/maplibre/setup.md) | 
    [Vector Styles](frontend/maplibre/basemaps.md) | 
    [GeoJSON Sources](frontend/maplibre/geojson-source.md) | 
    [3D Terrain](frontend/maplibre/3d-terrain.md) | 
    [Building Extrusions](frontend/maplibre/extrusion.md) | 
    [Data-Driven Expressions](frontend/maplibre/expressions.md)
*   **CesiumJS (3D)**:
    [Setup](frontend/cesium/setup.md) | 
    [3D Tiles](frontend/cesium/3d-tiles.md) | 
    [Terrain Settings](frontend/cesium/terrain.md) | 
    [Entities API](frontend/cesium/entities.md) | 
    [Camera Controls](frontend/cesium/camera.md)
*   **Deck.gl**:
    [Setup](frontend/deckgl/setup.md) | 
    [Scatterplot Layer](frontend/deckgl/scatterplot-layer.md) | 
    [Arc Layer](frontend/deckgl/arc-layer.md) | 
    [Hexagon Layer](frontend/deckgl/hexagon-layer.md)

### 🗄️ Spatial Databases
*   **PostgreSQL**:
    [SQL Basics](database/postgresql/basics.md) | 
    [Indexes & Performance](database/postgresql/indexing.md) | 
    [Triggers & Stored Procedures](database/postgresql/triggers.md)
*   **PostGIS**:
    [Extension Setup](database/postgis/extension-setup.md) | 
    [Geometries vs Geographies](database/postgis/geometries.md) | 
    [Spatial Relationships](database/postgis/queries-relationship.md) | 
    [Spatial Calculations](database/postgis/queries-measurement.md) | 
    [Spatial Indexing (GIST)](database/postgis/spatial-indexing.md) | 
    [Spatial Joins](database/postgis/spatial-joins.md) | 
    [pgRouting Network](database/postgis/pgrouting.md)

### 💻 Backend Development
*   **Python for GIS**:
    [OOP Basics](backend/python/oops.md) | 
    [Django Basics](backend/python/django.md) | 
    [Django REST Framework](backend/python/django-rest-framework.md) | 
    [FastAPI](backend/python/fastapi.md) | 
    [GeoDjango](backend/python/geodjango.md) | 
    [GeoPandas](backend/python/geopandas.md) | 
    [Shapely](backend/python/shapely.md) | 
    [Fiona & Rasterio](backend/python/fiona-rasterio.md)
*   **Node.js**:
    [Express & APIs](backend/nodejs/setup.md) | 
    [Turf.js Math](backend/nodejs/turfjs.md) | 
    [Proj4 Translation](backend/nodejs/proj4.md) | 
    [GeoJSON Parsing](backend/nodejs/geojson.md)
*   **GeoServer**:
    [Workspaces](backend/geoserver/workspaces.md) | 
    [Data Stores](backend/geoserver/stores.md) | 
    [Publishing Layers](backend/geoserver/publishing-layers.md) | 
    [SLD Styling XML](backend/geoserver/sld-styling.md) | 
    [WMS & WFS Services](backend/geoserver/wms-wfs.md) | 
    [GeoServer REST API](backend/geoserver/rest-api.md)
*   **Map Tiling**:
    [XYZ Tiles](backend/tiles/xyz-tiles.md) | 
    [MVT Vector Tiles](backend/tiles/vector-tiles-mvt.md) | 
    [Martin Tile Server](backend/tiles/martin-tileserver.md)

### ⚙️ DevOps & Infrastructure
*   **Docker Containerization**:
    [Docker Basics](devops/docker/docker-basics.md) | 
    [PostGIS Container](devops/docker/postgis-image.md) | 
    [GeoServer Container](devops/docker/geoserver-image.md) | 
    [Docker Compose Stack](devops/docker/docker-compose-stack.md)
*   **Tile Cache Proxies**:
    [GeoWebCache](devops/caching/geowebcache.md) | 
    [MapProxy](devops/caching/mapproxy.md)
*   **Performance Tuning**:
    [JVM Heap Tuning](devops/tuning/geoserver-jvm.md) | 
    [PostgreSQL Tuning](devops/tuning/postgresql-tuning.md)

### 📊 GIS Desktop & Analysis
*   **QGIS**:
    [Interface & Panels](analyst/qgis/interface.md) | 
    [Loading Layers](analyst/qgis/loading-data.md) | 
    [Layer Symbology](analyst/qgis/styling-layers.md) | 
    [Print Layouts](analyst/qgis/print-layouts.md) | 
    [Vector Geoprocessing](analyst/qgis/vector-tools.md) | 
    [Raster Calculations](analyst/qgis/raster-tools.md) | 
    [Graphical Modeler](analyst/qgis/graphical-modeler.md)
