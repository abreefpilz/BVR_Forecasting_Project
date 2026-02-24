<p align="left">
<img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg">
<img alt="Python" src="https://img.shields.io/badge/Python-3.9%2B-blueviolet">
<img alt="Models" src="https://img.shields.io/badge/Model-XGBoost-4285F4">
<img alt="Framework" src="https://img.shields.io/badge/Framework-Scikit--learn-orange">
<img alt="Framework" src="https://img.shields.io/badge/Visulisation-Matplotlib-green">
<img alt="RStudio" src="https://img.shields.io/badge/RStudio-4285F4?style=flat&logo=rstudio&logoColor=white">
</p>



# Forecasting Near Term Water Quality using Explanable AI in Beaverdam Reservoir

#### About the Repository
---

This project uses machine learning to forecast Chlorophyll-a at 7 day horizon and identify horizon based as well local drivers using explainable AI (XAI) in the Beaverdam Reservoir (BVR) in Virginia, USA. By analyzing environmental variables collected at the site, we uncover the hidden patterns driving phytoplankton dynamics, offering insights for both water quality management and ecological research. In future we'll update the title with publication name. 

---

## 📁 Instructions to reproduce the figures and analyses

##### Data Access 

The data used in this project are uplaoded as CSV file in this repository. However, to download the data directly from EDI, run the R script below:

**GitHub Repository:** (https://github.com/abreefpilz/Reservoirs/blob/master/Scripts/Daily_avg_RS.R)

The script automatically fetches the required data packages directly from the EDI Repository API portal (given below), processes the variables, and saves the final output as a .csv file. 

> *Note: This script may take several minutes and require substantial memory depending on your system.

#### Citations
Carey, C. C., & Breef-Pilz, A. (2025). Time series of high-frequency meteorological data at Falling Creek Reservoir, Virginia, USA, 2015–2024 (ver. 9). Environmental Data Initiative. https://doi.org/10.6073/pasta/0389840ddcb39ec5526869ac898ddb5d <sub>Accessed 2025-09-17</sub>.

Carey, C. C., & Breef-Pilz, A. (2025). Time series of high-frequency sensor data measuring water temperature, dissolved oxygen, conductivity, specific conductance, total dissolved solids, chlorophyll a, phycocyanin, fluorescent dissolved organic matter, and turbidity at discrete depths, and water level in Beaverdam Reservoir, Virginia, USA, 2009–2024 (ver. 5). Environmental Data Initiative. https://doi.org/10.6073/pasta/8f666b34c120aa5d2242964cf3147f90 <sub>Accessed 2025-09-17</sub>.

---

### The machine learning and explainable AI analyses is performed using the jupyter notebook below.


## Bathymetry Data Processing & Visualization

#### Bathymetry data is downloaded from EDI Repository below (also uploaded here for running the notebook)

Carey, C.C., A.S. Lewis, D.W. Howard, W.M. Woelmer, P.A. Gantzer, K.A. Bierlein, J.C. Little, and WVWA. 2022. Bathymetry and watershed area for Falling Creek Reservoir, Beaverdam Reservoir, and Carvins Cove Reservoir ver 1. Environmental Data Initiative. https://doi.org/10.6073/pasta/352735344150f7e77d2bc18b69a22412 (Accessed 2025-10-01).

##### The bathymetry figures for the reservoir is generated using the notebook below.

-

---
## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/rohitshukla01/BVR_Forecasting_Project.git
cd XAI_Manuscript_Analyses
```

---

## ✅ Citation & Data Access

📑 If you use this code in a publication, please cite this repository/paper. 

🌐 Visit EDI portal for direct data acquisition: https://portal.edirepository.org/nis/home.jsp.









