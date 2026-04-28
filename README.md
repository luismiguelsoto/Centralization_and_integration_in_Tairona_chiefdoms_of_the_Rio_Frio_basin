Centralization and integration in Tairona chiefdoms of the Río Frío basin, Sierra Nevada de Santa Marta, Colombia
--------------------------------------------------------------

This repository contains the R code and data used to analyze the processes of political integration and socioeconomic centralization in Tairona chiefdom communities of the Río Frío basin (Sierra Nevada de Santa Marta, Colombia) during the Tairona period (approximately 10th to 16th centuries AD).

Repository Structure:
----------------------------------

1. GIS:
   - Contains the spatial data files (shapefile components and raster files) defining the study area:
     • DEM_POLYGON_52KM.tif
     • SOILS_AGRICULTURE_RASTER_52KM.tif
     • TAIRONA_STRUCTURES.shp
     • TAIRONA_POLYGONS_SITES.shp
     • TAIRONA_CERAMICS.rds
     • LOCAL_COMMUNITIES.shp
     • POLYGON_SURVEY_RIO_FRIO.shp
     • RIVER_POLYGON_52KM.shp
     • regression_data.rds

2. R Code Files:
   - The main R Markdown file (JARE_MARKDOWN_SPRING_2026.Rmd) contains the code to:
     a) Load required packages.
     b) Download the datasets and GIS files directly from GitHub.
     c) Process the data, build similarity matrices, calculate centrality metrics, and perform network analysis.
     d) Generate the figures and tables as presented in the manuscript.

Software and Key Package Versions:
----------------------------------
- R version: [R 4.5.2]
- Key R packages used in this project include (with version numbers):
     • betareg: version 3.2.4
     • car: version 3.1.5
     • dplyr: version 1.2.0
     • dunn.test: version 1.3.7
     • ggplot2: version 4.0.2
     • ggspatial: version 1.1.10
     • gratia: version 0.11.2
     • igraph: version 2.2.2
     • knitr: version 1.51
     • lmtest: version 0.9.40
     • lwgeom: version 0.2.15
     • MASS: version 7.3.65
     • mgcv: version 1.9.3
     • mice: version 3.19.0
     • movecost: version 2.1
     • patchwork: version 1.3.2
     • raster: version 3.6.32
     • RColorBrewer: version 1.1.3
     • readxl: version 1.4.5
     • sandwich: version 3.1.1
     • scales: version 1.4.0
     • sf: version 1.0.24
     • sp: version 2.2.1
     • spatstat.geom: version 3.7.0
     • spatstat.random: version 3.4.4
     • terra: version 1.8.93
     • tibble: version 3.3.1
     • tidyr: version 1.3.2
     • viridis: version 0.6.5

Getting Started:
----------------------------------
1. Clone or download this repository.
2. Open the main R Markdown file (FINAL_JARE_MARKDOWN_SPRING_2026.Rmd) in RStudio.
3. Ensure that you have an active Internet connection; the code downloads the GIS files directly from GitHub.
4. Run the R script from top to bottom to reproduce the analysis and generate all figures and tables as presented in the manuscript.
5. For any issues, consult the comments in the code or contact the corresponding author.

Manuscript Summary:
----------------------------------
During the Tairona period (10th–16th centuries AD), communities in the Sierra Nevada de Santa Marta restructured the regional landscape, constructing thousands of stone terraces, paved roads, and public plazas. This monumentality has been interpreted as evidence of hierarchical organization with dominant administrative centers. A regional settlement pattern study of the Río Frío basin challenges that interpretation. Multiple demographic nuclei coexisted across the landscape, and regional connectivity flowed through topographic corridors where medium-sized settlements acted as key passage nodes. Cooking vessel frequencies remained stable across settlement sizes, indicating autonomous household provisioning, while serving and storage vessels increased with aggregate settlement scale, consistent with periodic collective consumption events hosted at larger sites. Ceramic similarity networks reveal that bridging positions in material interaction were distributed across settlements of different sizes rather than concentrated in large centers. Technical homogeneity in vessel dimensions and residential architecture is consistent with shared design norms sustained through horizontal learning circuits, although alternative mechanisms cannot be excluded. These patterns indicate regional coordination operating through distributed mechanisms rather than through dominant centers, though the institutional arrangements underlying such coordination remain to be specified.

For questions or further information, please contact: lms313@pitt.edu
