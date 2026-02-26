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
- [NZLDD V1 Dam](https://osf.io/nw6mt/overview) -> New Zealand landslide dam database, polygons of dammed lakes (-2023)
- [Landslide inventory](https://www.designsafe-ci.org/data/browser/public/designsafe.storage.published/PRJ-2765/) -> V2.0 Landslide inventory for the Mw7.8 2016 Kaikōura Earthquake (2016)
- [DEM](https://data.linz.govt.nz/layer/110632-canterbury-kaikoura-lidar-1m-dem-2016/) -> Cantenbury - Kaikōura LiDAR 1m DEM (2016)
- [Cantenbury LiDAR](https://portal.opentopography.org/lidarDataset?opentopoID=OTLAS.122022.2193.1) -> LiDAR aerial survey of Cantenbury (2020-2025)
- [Kaikōura LiDAR](https://portal.opentopography.org/datasetMetadata?otCollectionID=OT.102022.2193.1) -> LiDAR aerial survey Kaikōura Cantenbury (2016)
- [Cantenbury aerial 2025](https://data.linz.govt.nz/layer/122717-canterbury-025m-rural-aerial-photos-2025/) -> Cantebury 0.25m Rural aerial photos (2025)
- [Cantenbury aerial 2022](https://data.linz.govt.nz/layer/111968-canterbury-03m-rural-aerial-photos-2022/) -> Cantebury 0.3m Rural aerial photos (2022)
- [Cantenbury aerial 2014-2015](https://data.linz.govt.nz/layer/52602-canterbury-03m-rural-aerial-photos-2014-2015/) -> Cantebury 0.3m Rural aerial photos (2014-2015)
- [Cantenbury aerial 2004-2010](https://data.linz.govt.nz/layer/51933-canterbury-075m-rural-aerial-photos-2004-2010/) -> Cantebury 0.75m Rural aerial photos (2004-2010)
- [Kaikōura aerial](https://data.linz.govt.nz/layer/95549-kaikoura-03m-rural-aerial-photos-2016-2017/) -> Kaikōura 0.3m Rural aerial photos (2016-2017)
- [NZ Ortho](https://data.linz.govt.nz/layer/51049-nz-orthophotos-2000-2001/) -> NZ Orthophotos (2000-2001)

### References
- [Detecting landslide-dammed lakes on Sentinel-2 imagery and monitoring their spatio-temporal evolution following the Kaikōura earthquake in New Zealand](https://www.sciencedirect.com/science/article/pii/S0048969722004272)
- [Evolution of the Leader River in response to a landslide dam, triggered by the 2016 Mw 7.8 Kaikōura earthquake.](https://ir.canterbury.ac.nz/items/adbdbab8-2678-45a2-87e9-b67bd8e14496)
- [Overview of the Geologic Effects of the November 14, 2016, Mw 7.8 Kaikoura, New Zealand, Earthquake](https://pubs.usgs.gov/sir/2017/5146/sir20175146.pdf)
- [An alternative to landslide volume-area scaling relationships: an ensemble approach adopting a difference model to estimate the total volume of landsliding triggered by the 2016 Kaikōura earthquake, New Zealand](https://link.springer.com/article/10.1007/s10346-025-02479-x)



## 🇳🇿 Te Horo (Dart river) landslide and dammed lake, New Zealand

### Datasets
- [NZLDD V1 Dam](https://osf.io/nw6mt/overview) -> New Zealand landslide dam database, polygons of dammed lakes (-2023)
- [Landslides Otago](https://orc-spatial-data-portal-orcnz.hub.arcgis.com/datasets/landslides-otago/explore?location=-45.182407%2C170.281064%2C8) -> Landslide polygons in Otago (2006-2017)
- [Otago aerial 2017-2019](https://data.linz.govt.nz/layer/104460-otago-03m-rural-aerial-photos-2017-2019/) -> Otago 0.3m Rural aerial photos (2017-2019)
- [Otago aerial 2004-2011](https://data.linz.govt.nz/layer/51910-otago-075m-rural-aerial-photos-2004-2011/) -> Otago 0.75m Rural aerial photos (2004-2011)

### References
- [Measuring landslide-driven ground displacements with high-resolution surface models and optical flow](https://www.sciencedirect.com/science/article/pii/S0098300423000821?via=ihub)

 

## 🇹🇼 Butangbunasi landslide, Taiwan

### Datasets
- [Butangbunasi landslide and landslide-dammed lake outlines](https://zenodo.org/records/10635102) -> Butangbunasi landslide and landslide-dammed lake outlines based on Landsat time series using OBIA (1984-2018)
- [Taiwan landslides](https://data.gov.tw/en/datasets/166846) -> Annual Taiwan Landslide Map Layer
- [UAV aerial images](https://data.gov.tw/en/datasets/107506) -> UAV aerial orthophoto image tiles (gets updated)

### References
- [Mapping and Analyzing the Evolution of the Butangbunasi Landslide Using Landsat Time Series with Respect to Heavy Rainfall Events during Typhoons](https://www.mdpi.com/2076-3417/10/2/630)
- [Landscape evolution characteristics of large-scale erosion and landslides at the Putanpunas Stream, Taiwan](https://www.tandfonline.com/doi/full/10.1080/19475705.2017.1414079)


## 🇹🇼 Matai'an valley landslide, Taiwan

### Datasets
- [Taiwan landslides](https://data.gov.tw/en/datasets/166846) -> Annual Taiwan Landslide Map Layer
- [UAV aerial images](https://data.gov.tw/en/datasets/107506) -> UAV aerial orthophoto image tiles (gets updated)
- [OpenAerialMap](https://map.openaerialmap.org/#/-18.720703125,18.47960905583197,3?_k=fgavux) -> open-source aerial images from OpenAerialMap



## 🇮🇸 Fagradalsfjall lava flow, Iceland

### Datasets
- [Fagradalsfjall DEMs, ortho, and lava outlines](https://zenodo.org/records/7871187) -> DEMs, 5 aerial surveys (Aug 2022), 1 satellite survey (Aug 2022), 1 aerial survey of eruption sites (Sep 2022), and lava area outlines for the August 2022 eruption at Fagradalsfjall
- [Fagradalsfjall DEMs, ortho, GCPs, video, time-lapse](https://arizona.figshare.com/collections/Fagradalsfjall_Iceland_Eruption/6175633/4) -> DEMs and UAV orthophotos, Ground control point locations, UAS nadir video of lava flow, Time-lapse image sequences of the eruption
- [ÍslandsDEM útgáfa 1.0](https://gatt.lmi.is/geonetwork/srv/eng/catalog.search#/metadata/e6712430-a63c-4ae5-9158-c89d16da6361) -> Iceland DEM
- [ArcticDEM](https://fridge.pgc.umn.edu/) -> DEM covering the Arctic, including Iceland
- [Fagradalsfjall eruption photogrammetry](https://sketchfab.com/natturufraedistofnun/collections/fagradalsfjall-volcanic-eruption-3911d686287848f9b2cb4d04d2fbba22) -> 3D models of the eruption
- [Fagradalsfjall UAV 2021](https://arizona.figshare.com/articles/dataset/Fagradalsfjall_Iceland_2021_Eruption_Unoccupied_Aircraft_Systems_UAS_Data_Surveys/21071140?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> UAV orthomosaics and DEMs (2021)
- [VERITAS UAV surveys](https://arizona.figshare.com/articles/dataset/VERITAS_Unoccupied_Aircraft_System_UAS_Surveys/26035837?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> Survey locations include the 2021 Fagradalsfjall lava flow-field
- [Fagradalsfjall UAV 2024](https://arizona.figshare.com/articles/dataset/Photogrammetry_Experiment_at_Fagradalsfjall_Iceland/26741719?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> UAV orthomosaic, DEMs, pointcloud, and original UAV images (2024)

### References
- [Lava Flow Mapping Using Sentinel-1 SAR Data at the Fagradalsfjall Volcano, Iceland](https://www.researchgate.net/publication/376628001_Lava_Flow_Mapping_Using_Sentinel-1_SAR_Data_at_the_Fagradalsfjall_Volcano_Iceland)



## 🇮🇸 Jökulsárlón glacial lake, Iceland

### Datasets
- [Jökulsárlón lake outlines over time](https://islenskirjoklar.is/#/page/map) -> Glacier web portal visualizes lake outlines (1890-2025)
- [HMA glacial lake inventory](https://nsidc.org/data/hma_gli/versions/1) -> High Mountain Asia Near-Global Multi-Decadal Glacial Lake Inventory, V1 (1990-2018)
- [ÍslandsDEM útgáfa 1.0](https://gatt.lmi.is/geonetwork/srv/eng/catalog.search#/metadata/e6712430-a63c-4ae5-9158-c89d16da6361) -> Iceland DEM
- [ArcticDEM](https://fridge.pgc.umn.edu/) -> DEM covering the Arctic, including Iceland
- [Historical aerial archive](https://loftmyndasja.gis.is/mapview/?application=loftmyndasja) -> Historical aerial survey archive. Includes images of the lake from 1980-1994

### References
- [Proglacial lake development and outburst flood hazard at Fjallsjökull glacier, southeast Iceland](https://nhess.copernicus.org/articles/25/1913/2025/)

  

# General datasets

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
