## Remote Sensing–Based Drought Monitoring | Jeneponto, Indonesia (2015–2024)
This repository implements a remote sensing-based drought monitoring system for Jeneponto, Indonesia, covering the 10-year period from 2015 to 2024. The methodology is primarily inspired by the research of Jesudhas et al. (2024), specifically adapting their approach of using Principal Component Analysis (PCA) to objectively integrate the Precipitation Condition Index (PCI), Vegetation Condition Index (VCI), and Temperature Condition Index (TCI) into a single Synthetic Drought Index (SDI). By applying this framework to the tropical climate of Jeneponto, this project aims to provide a comprehensive assessment of drought hazard through multi-source data from Landsat 8 and CHIRPS.

📡 Methodology:
 • Landsat 8 (30 m) for vegetation condition and land surface temperature
 
 • CHIRPS monthly precipitation, upscaled to 30 m
 
 • Dry-season compositing (August–September) to minimize cloud effects while capturing peak drought stress
 
 • PCA-based integration: VCI, TCI, PCI → SDI

📊 Results indicate that 2023 was the driest year, followed by 2019 and 2015, a pattern consistent with the combined influence of El Niño conditions and Indian Ocean climate variability, which tend to suppress rainfall and prolong dry seasons across southern Indonesia.

💡 Why these matters:
The PCA-based approach objectively integrates vegetation stress, temperature-related stress, and precipitation deficits into a single drought indicator, enabling more effective early detection, agricultural planning, water resource management, and disaster preparedness in climate-vulnerable regions.


Synthetic Drought Index (SDI) Jeneponto in 2015-2024
![image alt](https://github.com/diniyrti/Remote_Sensing_Based_Drought_Monitoring/blob/main/image/sdi_2015-2024.jpg)

Reference Journal Links: Remote sensing-based drought hazard monitoring and assessment in a coastal plain: A principal component approach
https://www.sciencedirect.com/science/article/pii/S0013935123025616
