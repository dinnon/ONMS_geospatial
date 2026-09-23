# Geoportal ONMS

A web-based geospatial platform for the NOAA Office of National Marine Sanctuaries (ONMS). It brings curated data together in one place so sanctuary managers can explore conditions and generate reports for any sanctuary in the system.

## Purpose

- View curated third-party data layers for each sanctuary
- Clip and summarize data by polygon, with simple metrics calculated on the fly
- Show where data is sparse or has little overlap
- Generate reports, similar in spirit to OceanReports, but for sanctuaries

## Users

Sanctuary managers and other non-technical staff. The tool should be simple to use and require no GIS background.

## Approach

- **Platform:** Esri, built on the NOAA geoportal, with custom visuals layered on top (Experience Builder-style)
- **Landing page:** Sanctuary dropdown plus an interactive map that zooms to the selected sanctuary
- **Spatial framework:** 
- **Boundaries:** Actual sanctuary boundaries and shapefiles

## Key Data Inputs

- Benthic data
- Marine-related data
- Offshore climate data

## Open Decisions

- Data ingestion: how layers are sourced, updated, and maintained
- Data themes: how layers are grouped and presented
- Outputs: what the reports and summaries look like

## Status

Scoping phase.
