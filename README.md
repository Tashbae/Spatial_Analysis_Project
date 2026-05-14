# Monitoring Land Cover Changes using GIS & Remote Sensing from 2019 - 2024
## Spatial Analysis of Kiambu, Murang'a, Nyeri & Kirinyaga Counties in Kenya
**Project Overview**

This project applies **Spatial Analysis, Geographic Information Systems (GIS) and Remote Sensing** techniques to monitor **land cover and vegetation changes** across four counties in Kenya's central highlands: Kiambu, Murang'a, Nyeri and Kirinyaga.

Using **Sentinel-2 satellite imagery, Google Earth Engine (GEE), NDVI (Normalized Difference Vegetation Index)** and county boundary datasets, the study evaluates vegetation dynamics between **2019 and 2024** to identify patterns of environmental degradation, urban expansion and vegetation recovery.

### **🎯 Objectives**
**General Objective** - To assess land cover and vegetation changes in selected counties using GIS and remote sensing tools.

**Specific Objectives:**
* Understand the theoretical foundations of spatial analysis and GIS
* Acquire and preprocess spatial datasets from satellite and administrative sources.
* Perform Exploratory Spatial Data Analysis (ESDA)
* Calculate annual and comparative NDVI changes.
* Visualize vegetation trends using thematic maps and statistical charts.
* Compare vegetation dynamics across counties.
* Support environmental planning and sustainable land-use decision making.

### **🗺️ Study Area**

The project focuses on four counties in Kenya's Central Highlands: Kiambu, Murang'a, Nyeri and Kirinyaga.

These regions were selected due to their varying levels of:
* Urbanization
* Agricultural expansion
* Forest cover
* Climate variability

### **🧰 Tools & Technologies Used**
**GIS & Remote Sensing Platforms**
* Google Earth Engine (GEE)
* QGIS / ArcGIS
* Geemap
* Python

**Data Sources**
* Sentinel-2 Surface Reflectance Imagery
* FAO GAUL Administrative Boundaries
* Google Earth Engine Data Catalog

### **📂 Spatial Data Models**
**Vector Data:**
* County boundaries
* Administrative regions
* Infrastructure layers

**Raster Data:**
* Sentinel-2 imagery
* NDVI composites
* Vegetation change rasters

### **🔍 Methodology**
**Week 1: GIS Foundations**
* Spatial analysis concepts
* GIS components (Hardware, Software, Data, People, Methods)
* Vector vs Raster data models
* Spatial properties and metadata

**Week 2: Data Sourcing & Preparation**
* Satellite imagery filtering
* Cloud masking
* Coordinate system harmonization
* Raster clipping to county boundaries
* Data cleaning

**Week 3: Exploratory Spatial Data Analysis (ESDA)**
* Spatial queries
* Attribute queries
* Thematic mapping
* Buffer analysis
* Preliminary visualization

**Applied Analysis (2019-2024)**
1. General annual median NDVI composites
2. Computation of NDVI using: NDVI = (NIR - Red / NIR + Red)
3. Calculation of NDVI change: NDVI Change = NDVI (2024) - NDVI (2019)
4. Aggregation of mean NDVI per county
5. Visualization of outputs with:
* NDVI change maps
* Chloropleth maps
* County comparison bar charts

### **📊 Key Findings** 
**Kiambu County**
* It has the largest vegetation decline.
* Some of the major causes include but not limited to:
    * Urban sprawl
    * Infrastructure development
    * Land-use conversion

**Murang'a County**
* It has a moderate vegetation decline.
* It is likely influenced by:
    * Agricultural expansion
    * Deforestation

**Nyeri County**
* There is a noticeable vegetable loss.
* The contributing factors may be:
    * Land conversion
    * Climate variability
 
**Kirinyaga County**
* It is the county with the least decline.
* There is some localized vegetation gains.
* Possible drivers of this growth may be:
    * Irrigation
    * Favorable rainfall
 
### **📈 Outputs**
* NDVI maps (2019 & 2024)
* NDVI change raster
* County-level vegetation comparison
* Chloropleth thematic maps
* Statistical summaries
* Environmental interpretation

### **🌍 Significance of the Project**

This project demonstrates how GIS and spatial analysis can:
* Monitor environmental change
* Detect vegetation degradation
* Support sustainable land management
* Inform county planning
* Guide conservation policy

**🚀 Future Improvements**
* Integrate Land Surface Temperature (LST)
* Add machine learning for land cover classification
* Expand to all Kenyan counties
* Include rainfall and population growth datasets
* Develop an interactive dashboard.

### **📚 Academic Concepts Applied**
*  Spatial Analysis
*  GIS components
*  ESDA
*  Spatial Queries
*  Raster Processing
*  Buffering
*  Zonal Statistics
*  Thematic Mapping
*  NDVI Change Detection

**Conclusion**

The project successfully integrates theoretical GIS principles with practical remote sensing applications to evaluate land cover changes in Kenya's Central Highlands.

Results indicate widespread vegetation decline, especially in rapidly urbanizing regions like Kiambu, reinforcing the importance of geospatial technologies in environmental monitoring and policy planning.
