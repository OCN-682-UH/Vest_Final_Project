# Vest_Final_Project

# **SGD Nutrient & Isotope Toolbox — Final Project (OCN 682)**

This repository contains the data and code used to explore nutrient dynamics and macroalgal isotope patterns at two Submarine Groundwater Discharge (SGD) sites on Mo‘orea (Cabral and Varari). The project integrates water-column nutrients and *Turbinaria ornata* isotope data to assess how **season**, **tide**, and **space** influence groundwater-driven biogeochemistry.

## **Contents**

* `Script/` – RMarkdown (`.qmd`) file containing full analysis
* `Data/` – Nutrient, isotope, and site coordinate datasets
* `Output/` – Output plots and tables 
* `README.md` – Project overview and metadata

## **Questions Addressed**

1. **How do nutrient concentrations vary by season and tide?**
2. **Do macroalgal isotopes (δ¹⁵N, δ¹³C) track nutrient gradients?**
3. **How can we visualize these spatially?**

## **Data Summary**

* **Nutrients** (µmol L⁻¹): Nitrite, Ammonium, Phosphate, Silicate
* **Isotopes** (‰): δ¹⁵N and δ¹³C from *Turbinaria ornata*
* **Metadata**: Season (March/August), Tide (High/Low/Mid), Site ID (CowTagID), Coordinates

## **Interactive Map**

The dashboard includes interactive Leaflet maps showing nutrient and isotope gradients over Google Satellite imagery.
**Note:** A Google Maps API key is required for the basemap. Set this locally in R console:

```r
Sys.setenv(GOOGLE_MAPS_API_KEY = "YOUR_KEY_HERE")
``'

## **Acknowledgments**

Data collected by the Silbiger Lab and Mo‘orea LTER program. Analysis and visualization completed as part of OCN 682 (UH Mānoa).


