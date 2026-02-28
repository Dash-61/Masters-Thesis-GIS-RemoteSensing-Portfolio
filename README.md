# Masters Thesis: GIS & Remote Sensing Portfolio

## 1. Project Title & Description

Main thesis focus on carbon storage and LULC dynamics in Kamalganj, Bangladesh

This repository contains comprehensive geospatial analysis of carbon storage and Land Use/Land Cover (LULC) dynamics in Kamalganj, Bangladesh, utilizing InVEST modeling and Landsat 9 Remote Sensing for REDD+ readiness assessment.

## 2. Study Area

**Geographic Location:** Kamalganj, Bangladesh
- **Coordinates:** 91°42'0"E to 91°58'30"E, 24°7'30"N to 24°29'30"N
- **Characteristics:** Diverse forest ecosystems, agricultural landscapes, and wetlands

**Relevance to REDD+ Readiness Assessment:**
The study area was selected due to its ecological significance, presence of valuable forest ecosystems, and importance for regional climate change mitigation and REDD+ (Reducing Emissions from Deforestation and Forest Degradation) initiatives.

## 3. Methodology

### Data & Tools:
- **Remote Sensing Data:** Landsat 9 satellite imagery with multiple temporal acquisitions
- **Modeling Framework:** InVEST (Integrated Valuation of Ecosystem Services and Tradeoffs)
- **Analysis Techniques:** 
  - Atmospheric correction and radiometric normalization
  - Supervised and unsupervised LULC classification
  - Spatial change detection analysis

### Key Steps:
1. **Data Acquisition:** Collection and preprocessing of Landsat 9 imagery
2. **LULC Classification:** Identification of seven distinct land cover classes
3. **Carbon Storage Modeling:** InVEST model parameterization and valuation
4. **Spatial Analysis:** Mapping carbon hotspots and LULC dynamics
5. **Validation:** Ground truthing and accuracy assessment

## 4. Key Results

### Carbon Storage Findings:
- **Highest Carbon Storage:** Forests with 195.8 tons/ha above-ground carbon
- **Carbon Hotspots:** Concentrated in southwestern and northeastern portions of study area
- **Lowest Storage:** Built-up areas contribute negligibly to carbon stocks

### LULC Classification Insights:
- Complex mosaic of forest patches interspersed with agricultural lands
- Significant urban development in central regions
- Distribution reveals critical areas for conservation and forest management
- Strong spatial relationship between forest coverage and carbon storage capacity

## 5. Biophysical Table ⭐

The table below displays the biophysical carbon parameters for each identified LULC class used in the InVEST carbon storage model:

| LULC Class | Above-ground Carbon (tons/ha) | Below-ground Carbon (tons/ha) | Soil Carbon (tons/ha) | Dead Organic Matter (tons/ha) |
|---|---|---|---|---|
| Forests | 195.8 | 37 | 38.59 | 12.4 |
| Built-up Area | 0 | 0 | 50 | 0 |
| Waterbodies | 10 | 5 | 20 | 0 |
| Row Crop Land | 3 | 2 | 10 | 0 |
| Fallow Land | 1 | 1 | 10 | 0 |
| Trees | 45 | 65 | 60 | 17 |
| Rangeland | 6 | 6 | 20 | 2 |

## 6. Repository Files

### Map Files:
- **LULC_Map_2024.jpg** 
  - Comprehensive raster map showing carbon storage distribution (tons/ha) across the study area
  - Continuous green color gradient indicating carbon storage intensity
  - High resolution visualization at 1cm = 2km scale

- **Carbon_Hotspots.jpg**
  - Thematic LULC classification map with distinct colors for each land cover type
  - Reveals spatial patterns and relationships between land use and carbon storage
  - Detailed view of central study area at enhanced resolution

### Data File:
- **Biophysical_Table.xlsx**
  - Detailed Excel spreadsheet with biophysical parameters for all LULC classes
  - Complete carbon accounting data (above-ground, below-ground, soil, and dead organic matter)
  - Ready for InVEST model parameterization and updates

---

*Last Updated: February 28, 2026*