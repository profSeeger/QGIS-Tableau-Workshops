---
title: "QGIS Workshop - February 2026"
excerpt: "Hands-on introduction to QGIS for geospatial analysis and mapping"
date: 2026-02-28
workshop_date: "February 28, 2026"
software: "QGIS"
status: "upcoming"
level: "Beginner to Intermediate"
duration: "Full day (9:00 AM - 4:00 PM)"
header:
  teaser: /assets/images/qgis-thumbnail.jpg
  overlay_image: /assets/images/qgis-header.jpg
  overlay_filter: 0.5
toc: true
toc_label: "Workshop Contents"
toc_icon: "map"
---

## Overview

This comprehensive, hands-on workshop introduces participants to QGIS, the leading open-source Geographic Information System. You'll learn essential GIS concepts and techniques through practical exercises using real-world datasets.

**Workshop Date:** {{ page.workshop_date }}  
**Time:** {{ page.duration }}  
**Level:** {{ page.level }}  
**Instructor:** Your Name

### What You'll Learn

- Navigate the QGIS interface and manage projects
- Import and work with vector and raster data
- Perform spatial analysis and geoprocessing
- Create professional-quality maps with proper cartographic design
- Export maps for print and digital use

### Who Should Attend

This workshop is ideal for:
- Researchers working with spatial data
- Urban planners and environmental scientists
- Students interested in GIS
- Anyone wanting to learn open-source mapping tools

## Software Setup

### System Requirements

- **Operating System:** Windows 10/11, macOS 10.14+, or Linux
- **RAM:** Minimum 4GB (8GB recommended)
- **Disk Space:** 2GB free space
- **Display:** 1280x800 minimum resolution

### Installation Instructions

#### Download QGIS

1. Visit the official QGIS download page: [https://qgis.org/download/](https://qgis.org/download/)
2. Download **QGIS 3.34 LTR** (Long Term Release) for your operating system
3. Choose the standalone installer for simplest installation

#### Windows Installation

1. Run the downloaded `.msi` installer
2. Follow the installation wizard (default settings are recommended)
3. Launch QGIS from the Start menu to verify installation

#### macOS Installation

1. Open the downloaded `.dmg` file
2. Drag QGIS to your Applications folder
3. First launch: Right-click QGIS and select "Open" to bypass security restrictions

#### Linux Installation

For Ubuntu/Debian:
```bash
sudo apt update
sudo apt install qgis qgis-plugin-grass
```

### Verify Installation

Open QGIS and verify you see the welcome screen. The version should be **3.34.x** or higher.

**Having installation issues?** Email us at [your.email@example.com](mailto:your.email@example.com) before the workshop.

## Agenda

### Morning Session (9:00 AM - 12:00 PM)

**9:00 - 9:30: Introduction & Setup**
- Welcome and introductions
- Verify software installation
- Download workshop data
- QGIS interface overview

**9:30 - 10:45: Working with Vector Data**
- Understanding shapefiles and GeoPackages
- Loading and styling vector layers
- Attribute tables and data queries
- Basic symbology and labeling

**10:45 - 11:00: Break**

**11:00 - 12:00: Coordinate Systems & Projections**
- Understanding CRS (Coordinate Reference Systems)
- Reprojecting data
- Working with GPS coordinates
- Exercise: Combining data from different projections

**12:00 - 1:00: Lunch Break**

### Afternoon Session (1:00 PM - 4:00 PM)

**1:00 - 2:15: Spatial Analysis**
- Buffer analysis
- Spatial joins
- Selecting features by location
- Geoprocessing tools
- Exercise: Site suitability analysis

**2:15 - 2:30: Break**

**2:30 - 3:30: Map Design & Cartography**
- Print layout composer
- Adding map elements (legend, scale bar, north arrow)
- Multi-page atlas generation
- Exporting maps (PDF, PNG, SVG)

**3:30 - 4:00: Q&A and Wrap-up**
- Review key concepts
- Resources for continued learning
- Certificate distribution

## Workshop Data

All datasets needed for the workshop are available on GitHub.

### Download Instructions

**Option 1: Direct Download (Recommended for beginners)**

[Download Workshop Data ZIP](https://github.com/yourusername/workshop-data/archive/refs/heads/main.zip){: .btn .btn--success .btn--large}

1. Click the button above to download the data
2. Extract the ZIP file to your Desktop or Documents folder
3. Remember the location - you'll need it during the workshop!

**Option 2: Git Clone (For experienced users)**

```bash
git clone https://github.com/yourusername/workshop-data.git
```

### Data Contents

The workshop data package includes:

- **Vector Data:**
  - City boundaries (polygon shapefile)
  - Street network (line shapefile)
  - Points of interest (point shapefile)
  - Census data (GeoPackage with attributes)

- **Raster Data:**
  - Digital elevation model (GeoTIFF)
  - Land use classification (GeoTIFF)
  - Satellite imagery sample

- **Exercise Files:**
  - Pre-made QGIS projects for each module
  - Sample styles and symbology
  - Reference maps

**Data License:** All workshop data is provided for educational use. See the included README for specific attribution requirements.

## Prerequisites

### Required Knowledge

- Basic computer skills (file management, installing software)
- No prior GIS experience necessary!

### What to Bring

- Laptop computer (tablets/Chromebooks won't work)
- Power adapter/charger
- Mouse (recommended - GIS work is easier with a mouse)
- Notebook for taking notes

### Pre-Workshop Checklist

- [ ] QGIS installed and tested
- [ ] Workshop data downloaded and extracted
- [ ] Laptop fully charged
- [ ] Completed pre-workshop survey (link sent via email)

## Additional Resources

### Reference Materials

These materials will be available during and after the workshop:

- Workshop slides (PDF)
- Exercise solutions
- Quick reference guide
- Keyboard shortcuts cheatsheet

### Recommended Follow-up Tutorials

After the workshop, continue learning with these resources (see our [Resources page](/resources/) for more):

- QGIS Training Manual: [https://docs.qgis.org/training_manual/](https://docs.qgis.org/training_manual/)
- QGIS Tutorials and Tips: [https://www.qgistutorials.com/](https://www.qgistutorials.com/)

## Questions?

**Before the workshop:** Email [your.email@example.com](mailto:your.email@example.com)

**Day of workshop:** Arrive 15 minutes early for technical assistance

---

[Back to All Workshops](/workshops/){: .btn .btn--info}
