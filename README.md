# P5: Air Quality Analysis — Hosur (2022)

## Project Overview
Analysis of Aerosol Optical Depth (AOD) and NO₂ concentration over Hosur, Tamil Nadu
using Google Earth Engine (GEE) and QGIS.

## Study Area
- **Location**: Hosur, Tamil Nadu, India
- **Coordinates**: [77.77, 12.68, 77.87, 12.76]
- **Area**: ~96 sq km

## Data Sources
| Dataset | Platform | Resolution | Period |
|---------|----------|------------|--------|
| MODIS MCD19A2 | GEE | 1 km | 2022 |
| Sentinel-5P NO₂ | GEE | 5.5 km | 2022 |

## Key Findings
- **Annual Mean AOD**: High across entire study area (>0.5)
- **Peak Month**: November (1.0571)
- **Cleanest Month**: December (0.3591)
- **Post-Monsoon** has highest AOD; **Winter** has lowest
- **NO₂**: Annual mean computed and visualized
- **Pollution Classification**: 100% of study area classified as High Pollution (AOD > 0.5)

## Seasonal Analysis
| Season | Images | Mean AOD |
|--------|--------|----------|
| Summer (Mar–May) | 273 | 0.7972 |
| Monsoon (Jun–Sep) | 383 | 0.7833 |
| Post-Monsoon (Oct–Nov) | 176 | 0.8001 |
| Winter (Dec–Feb) | 288 | 0.4777 |

## Tools Used
- Google Earth Engine (Python API)
- Google Colab
- QGIS (Print Layout)

## Files
| File | Description |
|------|-------------|
| P5_01_GEE_Setup.ipynb | Main analysis code |
| hosur_aod_annual_2022.tif | Annual AOD GeoTIFF |
| hosur_aod_qgis_map.png | Final QGIS map |
| monthly_aod_hosur_2022.csv | Monthly AOD values |

## Author
**Muthuraj Vikas V**

**Date**: 2026-06-27
