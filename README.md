# Hi, I'm Edmond Akello 👋

**Civil engineer · Hydrology, drainage and roads · Open-source engineering software**

I'm a civil engineer in Nairobi working on hydrology, hydraulics, drainage and road design. I build open-source QGIS tools that bring that work out of closed desktop packages and into reproducible, checkable workflows, validated against the industry tools engineers already trust (ArcHydro, Civil 3D) and against the design manuals they work to.

## Featured projects

### 🛣️ [Road Furniture Designer](https://github.com/EdmondAkello/Road-Furniture-Designer)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24162212.svg)](https://doi.org/10.5281/zenodo.24162212)

A QGIS plugin for road furniture along a Civil 3D LandXML alignment, to the Kenya Road Design Manual (2025):
- Traffic signs, markings, road studs, safety barriers, traffic calming and speed limit zones, proposed from the road geometry or placed by hand.
- Junctions, roundabouts, bus and truck bays, climbing and descending lanes, brake check areas and truck escape ramps.
- A live inventory for the QTO, an A3 report with checks against the geometry, a georeferenced DXF and 3D feature lines back to Civil 3D.

Comes with a full user guide and technical manual.

### 🌧️ [QEHT — QGIS Engineering Hydrology Toolkit](https://github.com/EdmondAkello/qeht)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23393476.svg)](https://doi.org/10.5281/zenodo.23393476)

An in-process QGIS Processing toolkit that replicates the ArcHydro workflow, from a DEM to catchments and their characteristics:
- Depression filling, D8 flow direction, flow accumulation, stream networks with Strahler order, catchments from pour points, longest flow paths and catchment characteristics.
- Pure NumPy and GDAL, so it runs where SAGA, GRASS and subprocesses are blocked.
- Validated against ArcHydro outputs.

Available in the official QGIS plugin repository.

### 🗺️ [LandXML Road & Terrain GIS Tools](https://github.com/EdmondAkello/LandXML-Road-and-Terrain-GIS-Tools)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23402501.svg)](https://doi.org/10.5281/zenodo.23402501)

A native QGIS Processing provider that turns Civil 3D and OpenRoads LandXML into GIS-ready data and design checks:
- TIN surfaces to GeoTIFF, plus alignments, profiles and corridor sections.
- A profile and cross-section viewer.
- Earthworks and site-grading quantities that reproduce Civil 3D's volumes.
- A geometric design review to the Kenya RDM or the AASHTO Green Book.

Co-developed with Cole Winstead; runs on QGIS 3.44 and 4. Available in the official QGIS plugin repository.

### 🌊 [FloodDepth](https://github.com/EdmondAkello/Flood-Depth)

Flood extent, depth and uncertainty from Sentinel-2 or Sentinel-1 imagery and a DEM:
- Automatic water classification, with flood-trace mapping for receded flash floods.
- Depth from the flood boundary.
- Monte Carlo uncertainty and a report.

Benchmarked on Sen1Floods11.

## What I work on

- **Hydrology and hydraulics:** catchments, design floods, culvert and drainage design, flood mapping, erosion and scour.
- **Roads:** geometric design, drainage, road furniture and safety to the Kenya Road Design Manual, with LandXML and Civil 3D workflows.
- **Engineering software:** Python and QGIS plugins that run in-process (no installs, no pip), with tests, CI, Zenodo releases and user manuals.

## Research

Erosion and sediment risk in road drainage structures: *AJERI*, Vol. 3 No. 4, Dec 2025 (presented at AJERI's 1st Scientific Conference, Kenyatta University). More papers on flat-terrain flow routing and flood mapping are in progress.

## Approach

- Engineering methods first: every tool cites the manual, standard or paper it implements.
- Validated against real project data and the reference software.
- Open source, versioned and citable, so a design can be checked and reproduced.

📫 akelloedmond@gmail.com
