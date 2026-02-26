# MorphEO Resources

This repository lists key datasets, codebases, and methodological references relevant to:

- Multi-temporal landslide mapping  
- Spatio-temporal modelling of geomorphic features  
- Deep learning for EO time series  




# Study Area

## 🇳🇿 Kaikōura, New Zealand (2016 Earthquake)

### 1. Landslide detection
**Repo:**  https://github.com/kushanavbhuyan/Large-scale-multi-spatiotemporal-landslide-mapping  
**Paper:**  https://www.nature.com/articles/s41598-022-27352-y  

**Notes:**  
- attention, deep Supervision Multi-scale U-Net (ADSMS-UNet)  
- cross-modal transfer learning  
- multi-event inventories (Wenchuan, Gorkha, Kaikōura, PNG)  



### 2. Landslide area modelling

**Repo:**  https://github.com/mmorenoz/GAM_LandslideSize  
**Paper:**  Moreno et al. (2023), Engineering Geology  https://doi.org/10.1016/j.enggeo.2023.107121  

**Notes:**  
- Models landslide area (not just occurrence)  
- Random + spatial cross-validation  
- object-level descriptors (area evolution)

## 🇳🇿 Leader dam landslide and dammed lake, New Zealand

### Datasets
- [NZLDD V1 Dam](https://osf.io/nw6mt/overview) -> Nez Zealand landslide dam database, polygons of dammed lakes (-2023)
- [Landslide inventory](https://www.designsafe-ci.org/data/browser/public/designsafe.storage.published/PRJ-2765/) -> V2.0 Landslide inventory for the Mw7.8 2016 Kaikōura Earthquake, NZ
- [DEM](https://data.linz.govt.nz/layer/110632-canterbury-kaikoura-lidar-1m-dem-2016/) -> Cantenbury - Kaikōura LiDAR 1m DEM (2016)
- 




# Dataset

## Landslide4Sense 2022

**Repo:**  https://github.com/iarai/Landslide4Sense-2022  
**Dataset Paper:**  ... Ghorbanzadeh et al. (2022), IEEE JSTARS  

**Notes:**  
- 14 band input (Sentinel-2 + slope + DEM)  
- pixel-wise labels  
- U-Net baseline (PyTorch)  
- F1 evaluation  
- multi-modal segmentation  





To add:
- NZ files from Geomorphology...

  
*(Living document – updated as wego :) )*
