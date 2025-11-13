---
title: TerraSense
date: 2025-01-18
tags:
  - project
  - hackathon
  - ai
  - geospatial
description: Geospatial platform analyzing NASA satellite data for vegetation health monitoring
---

# TerraSense

*Built at AI ATL 2025 Hackathon*

Geospatial intelligence platform that processes NASA satellite data to analyze vegetation health. Users draw custom regions on an interactive 3D globe to access 25 years of NDVI metrics and AI-powered predictions.

## Architecture

**Frontend:** React.js + CesiumJS for 3D globe visualization and region selection

**Backend:** FastAPI handling satellite data processing and API orchestration

**Data:** Google Earth Engine API for NASA satellite data, MongoDB Atlas for storage

**AI:** Google Gemini API for trend analysis and vegetation predictions

## Technical Approach

Implemented intelligent batching and interpolation to handle thousands of satellite data points per region while managing Google Earth Engine API rate limits. Designed prompt engineering pipeline for Gemini to generate evidence-based predictions from historical NDVI patterns.

## Team

Built with Kevin Kou and edwinthedev at AI ATL 2025.

**Links:** [Devpost](https://devpost.com/software/ecolens-ugyq6j)

---

[[projects/index|← Back to Projects]]
