# nicfi_planet_cloud_filtering_repo
Reproducible cloud and haze filtering for Planet-NICFI basemaps on Google Earth Engine. Implements two simple, training-free algorithms — a conservative Blue–NIR threshold and a Sentinel-2–derived adaptive statistical filter — for large-scale tropical monitoring and operational use.

GEE Codebooks and assets:
Algorithm A: Threshold based cloud filtering raw GEE codebook: https://code.earthengine.google.com/a2e63af30378ed620f4e54f22e616f56

Algorithm B: Stat-thresholding based cloud filtering raw GEE codebook:
https://code.earthengine.google.com/02e71ce9205920d9936b662bea784219

ML Model Development Raw:
https://code.earthengine.google.com/1f0884f760b076e30a1e70a8b6a701e7 

GEE ASSET IDs:
Less cloudy NICFI-Planet Scene: 
projects/ee-islamkm/assets/NonCloudy_NICFI_Blue_900_NIR_3500_2021-01 

Cloudy NICFI-Planet Scene: 
projects/ee-islamkm/assets/Cloudy_NICFI_Blue_900_NIR_3500_2020-09
