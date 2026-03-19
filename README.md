# MorphEO Resources

This repository lists key datasets, codebases, and methodological references relevant to:

- Multi-temporal landslide mapping  
- Spatio-temporal modelling of geomorphic features  
- Deep learning for EO time series  


---

## Contents

- [Study Areas](#study-areas)
  - [🇳🇿 New Zealand](#-new-zealand)
  - [🇹🇼 Taiwan](#-taiwan)
  - [🇮🇸 Iceland](#-iceland)
- [General Datasets](#general-datasets)
- [Methods & Tools](#methods--tools)
  - [Segmentation — Landslides](#segmentation--landslides)
  - [Change Detection](#change-detection)
  - [Time Series](#time-series)
  - [Foundational Models](#foundational-models)
  - [Data Access & Cubing](#data-access--cubing)

---

## Study Areas

---

### 🇳🇿 New Zealand

#### Kaikōura (2016 Earthquake)

##### Landslide Detection

[Large-scale-multi-spatiotemporal-landslide-mapping](https://github.com/kushanavbhuyan/Large-scale-multi-spatiotemporal-landslide-mapping) -> Attention + deep supervision multi-scale U-Net (ADSMS-UNet) for landslide detection; cross-modal transfer learning across Wenchuan, Gorkha, Kaikōura, and PNG inventories. [Paper](https://www.nature.com/articles/s41598-022-27352-y)

##### Landslide Area Modelling

[GAM_LandslideSize](https://github.com/mmorenoz/GAM_LandslideSize) -> Generalised additive models for landslide area prediction (not just occurrence); uses object-level descriptors and random + spatial cross-validation. Moreno et al. (2023), Engineering Geology. [Paper](https://doi.org/10.1016/j.enggeo.2023.107121)

---

#### Leader Dam Landslide and Dammed Lake

##### Datasets

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

##### References

- [Detecting landslide-dammed lakes on Sentinel-2 imagery and monitoring their spatio-temporal evolution following the Kaikōura earthquake in New Zealand](https://www.sciencedirect.com/science/article/pii/S0048969722004272)
- [Evolution of the Leader River in response to a landslide dam, triggered by the 2016 Mw 7.8 Kaikōura earthquake.](https://ir.canterbury.ac.nz/items/adbdbab8-2678-45a2-87e9-b67bd8e14496)
- [Overview of the Geologic Effects of the November 14, 2016, Mw 7.8 Kaikoura, New Zealand, Earthquake](https://pubs.usgs.gov/sir/2017/5146/sir20175146.pdf)
- [An alternative to landslide volume-area scaling relationships: an ensemble approach adopting a difference model to estimate the total volume of landsliding triggered by the 2016 Kaikōura earthquake, New Zealand](https://link.springer.com/article/10.1007/s10346-025-02479-x)

---

#### Te Horo (Dart River) Landslide and Dammed Lake

##### Datasets

- [NZLDD V1 Dam](https://osf.io/nw6mt/overview) -> New Zealand landslide dam database, polygons of dammed lakes (-2023)
- [Landslides Otago](https://orc-spatial-data-portal-orcnz.hub.arcgis.com/datasets/landslides-otago/explore?location=-45.182407%2C170.281064%2C8) -> Landslide polygons in Otago (2006-2017)
- [Otago aerial 2017-2019](https://data.linz.govt.nz/layer/104460-otago-03m-rural-aerial-photos-2017-2019/) -> Otago 0.3m Rural aerial photos (2017-2019)
- [Otago aerial 2004-2011](https://data.linz.govt.nz/layer/51910-otago-075m-rural-aerial-photos-2004-2011/) -> Otago 0.75m Rural aerial photos (2004-2011)

##### References

- [Measuring landslide-driven ground displacements with high-resolution surface models and optical flow](https://www.sciencedirect.com/science/article/pii/S0098300423000821?via=ihub)

---

### 🇹🇼 Taiwan

#### Butangbunasi Landslide

##### Datasets

- [Butangbunasi landslide and landslide-dammed lake outlines](https://zenodo.org/records/10635102) -> Butangbunasi landslide and landslide-dammed lake outlines based on Landsat time series using OBIA (1984-2018)
- [Taiwan landslides](https://data.gov.tw/en/datasets/166846) -> Annual Taiwan Landslide Map Layer
- [UAV aerial images](https://data.gov.tw/en/datasets/107506) -> UAV aerial orthophoto image tiles (gets updated)

##### References

- [Mapping and Analyzing the Evolution of the Butangbunasi Landslide Using Landsat Time Series with Respect to Heavy Rainfall Events during Typhoons](https://www.mdpi.com/2076-3417/10/2/630)
- [Landscape evolution characteristics of large-scale erosion and landslides at the Putanpunas Stream, Taiwan](https://www.tandfonline.com/doi/full/10.1080/19475705.2017.1414079)

---

#### Matai'an Valley Landslide

##### Datasets

- [Taiwan landslides](https://data.gov.tw/en/datasets/166846) -> Annual Taiwan Landslide Map Layer
- [UAV aerial images](https://data.gov.tw/en/datasets/107506) -> UAV aerial orthophoto image tiles (gets updated)
- [OpenAerialMap](https://map.openaerialmap.org/#/-18.720703125,18.47960905583197,3?_k=fgavux) -> open-source aerial images from OpenAerialMap

---

### 🇮🇸 Iceland

#### Fagradalsfjall Lava Flow

##### Datasets

- [Fagradalsfjall DEMs, ortho, and lava outlines, 2022](https://zenodo.org/records/7871187) -> DEMs, 5 aerial surveys (Aug 2022), 1 satellite survey (Aug 2022), 1 aerial survey of eruption sites (Sep 2022), and lava area outlines for the August 2022 eruption at Fagradalsfjall
- [Fagradalsfjall DEMs, ortho, and lava outlines, 2021](https://zenodo.org/records/7866738) -> Digital Elevation Models (DEMs), orthoimages and lava outlines created as part of the near-real time monitoring of the Fagradalsfjall 2021 eruption (SW-Iceland).
- [Fagradalsfjall DEMs, ortho, GCPs, video, time-lapse](https://arizona.figshare.com/collections/Fagradalsfjall_Iceland_Eruption/6175633/4) -> DEMs and UAV orthophotos, Ground control point locations, UAS nadir video of lava flow, Time-lapse image sequences of the eruption
- [ÍslandsDEM útgáfa 1.0](https://gatt.lmi.is/geonetwork/srv/eng/catalog.search#/metadata/e6712430-a63c-4ae5-9158-c89d16da6361) -> Iceland DEM
- [ArcticDEM](https://fridge.pgc.umn.edu/) -> DEM covering the Arctic, including Iceland
- [Fagradalsfjall eruption photogrammetry](https://sketchfab.com/natturufraedistofnun/collections/fagradalsfjall-volcanic-eruption-3911d686287848f9b2cb4d04d2fbba22) -> 3D models of the eruption
- [Fagradalsfjall UAV 2021](https://arizona.figshare.com/articles/dataset/Fagradalsfjall_Iceland_2021_Eruption_Unoccupied_Aircraft_Systems_UAS_Data_Surveys/21071140?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> UAV orthomosaics and DEMs (2021)
- [VERITAS UAV surveys](https://arizona.figshare.com/articles/dataset/VERITAS_Unoccupied_Aircraft_System_UAS_Surveys/26035837?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> Survey locations include the 2021 Fagradalsfjall lava flow-field
- [Fagradalsfjall UAV 2024](https://arizona.figshare.com/articles/dataset/Photogrammetry_Experiment_at_Fagradalsfjall_Iceland/26741719?backTo=/collections/Fagradalsfjall_Iceland_Eruption/6175633) -> UAV orthomosaic, DEMs, pointcloud, and original UAV images (2024)

##### References

- [Lava Flow Mapping Using Sentinel-1 SAR Data at the Fagradalsfjall Volcano, Iceland](https://www.researchgate.net/publication/376628001_Lava_Flow_Mapping_Using_Sentinel-1_SAR_Data_at_the_Fagradalsfjall_Volcano_Iceland)

---

#### Jökulsárlón Glacial Lake

##### Datasets

- [Jökulsárlón lake outlines over time](https://islenskirjoklar.is/#/page/map) -> Glacier web portal visualizes lake outlines (1890-2025)
- [HMA glacial lake inventory](https://nsidc.org/data/hma_gli/versions/1) -> High Mountain Asia Near-Global Multi-Decadal Glacial Lake Inventory, V1 (1990-2018)
- [ÍslandsDEM útgáfa 1.0](https://gatt.lmi.is/geonetwork/srv/eng/catalog.search#/metadata/e6712430-a63c-4ae5-9158-c89d16da6361) -> Iceland DEM
- [ArcticDEM](https://fridge.pgc.umn.edu/) -> DEM covering the Arctic, including Iceland
- [Historical aerial archive](https://loftmyndasja.gis.is/mapview/?application=loftmyndasja) -> Historical aerial survey archive. Includes images of the lake from 1980-1994

##### References

- [Proglacial lake development and outburst flood hazard at Fjallsjökull glacier, southeast Iceland](https://nhess.copernicus.org/articles/25/1913/2025/)

---

## General Datasets

### Sen12Landslides

- [Sen12Landslides](https://huggingface.co/datasets/paulhoehn/Sen12Landslides) -> Large-scale multi-sensor benchmark for spatio-temporal landslide detection. 39,556 NetCDF patches (128×128 px, 10m resolution) across 15 time steps; Sentinel-1 (VV, VH, ascending/descending) and Sentinel-2 (B02–B12) with paired binary landslide masks, DEM, and rich metadata. Over 75,000 annotated landslide polygons. Includes task splits for supervised detection (S12LS-LD) and anomaly detection (S12LS-AD). [Paper](https://www.nature.com/articles/s41597-025-06167-2)

### Landslide4Sense 2022

- [Landslide4Sense-2022](https://github.com/iarai/Landslide4Sense-2022) -> Multi-modal landslide segmentation benchmark; 14-band input (Sentinel-2 + slope + DEM), pixel-wise labels, U-Net baseline (PyTorch), F1 evaluation. Ghorbanzadeh et al. (2022), IEEE JSTARS.

### The Earth Observation Database (Training datasets for DL)

[IEEE GRSS Earth Observation Database (EOD)](https://eod-grss-ieee.com/dataset-search) -> An interactive online platform for cataloguing different types of datasets leveraging remote sensing imagery. [Schmitt et al 2022](https://ieeexplore.ieee.org/abstract/document/9884725)

---

## Methods & Tools

### Segmentation — Landslides

- [landslide-sar-unet](https://github.com/ESA-PhiLab/landslide-sar-unet) -> Deep learning for rapid landslide detection using SAR datacubes

- [landslide-mapping-with-cnn](https://github.com/npuchenbowen/landslide-mapping-with-cnn) -> Generalised CNN strategy for landslide mapping across regions

- [Landslide-mapping-on-SAR-data-by-Attention-U-Net](https://github.com/iprapas/landslide-sar-unet) -> Rapid mapping of landslides on SAR data using Attention U-Net

- [SAR-landslide-detection-pretraining](https://github.com/links-ads/sar-multi-temporal-landslide-detection) -> SAR-based landslide classification pretraining improves segmentation performance

- [Erosion-detection](https://github.com/sentinel-hub/eo-learn) -> Using Sentinel-2 to detect erosion patterns over time

### Change Detection

- [STANet](https://github.com/justchenhao/STANet) -> Spatio-temporal attention network for remote sensing image change detection

- [ChangeFormer](https://github.com/wgcban/ChangeFormer) -> Transformer-based Siamese network for change detection; captures fine-grained multi-scale details. [Paper](https://arxiv.org/abs/2201.01293)

- [Landslide mapping from Sentinel-2 imagery through change detection](https://github.com/links-ads/sar-multi-temporal-landslide-detection) -> Bitemporal change detection approach for landslide mapping

- [forest_change_detection](https://github.com/QuantuMobileSoftware/forest_change_detection) -> Forest change segmentation with time-dependent models including Siamese, UNet-LSTM, UNet-diff, UNet3D

### Time Series

- [utae-paps](https://github.com/VSainteuf/utae-paps) -> U-TAE and PaPs for satellite image time series panoptic segmentation; directly relevant to object-level tracking in SITS

- [pytorch-psetae](https://github.com/VSainteuf/pytorch-psetae) -> Pixel-Set Encoders and Temporal Self-Attention for satellite image time series classification

- [SITS-Former](https://github.com/linlei1214/SITS-Former) -> Pre-trained spatio-spectral-temporal representation model for Sentinel-2 time series classification

- [temporal-cluster-matching](https://github.com/microsoft/temporal-cluster-matching) -> Detecting change in structure footprints from time series of remotely sensed imagery

### Foundational Models

- [TerraTorch](https://github.com/IBM/terratorch) -> Python toolkit for fine-tuning geospatial foundation models (incl. Prithvi-EO-2.0) based on PyTorch Lightning and TorchGeo

- [Prithvi-EO-2.0](https://huggingface.co/ibm-nasa-geospatial/Prithvi-EO-2.0-300M) -> IBM–NASA Earth observation foundation model pre-trained on HLS (Harmonized Landsat Sentinel-2) time series; 300M parameter version available for fine-tuning

- [Prithvi-CAFE](https://github.com/ClarkCGA/multi-temporal-crop-classification-baseline) -> Transformer-based global reasoning (Prithvi-EO-2.0) with CNN-based local spatial sensitivity for multi-sensor inputs; applied to flood inundation mapping

- [TorchGeo](https://github.com/microsoft/torchgeo) -> PyTorch library for geospatial data with pre-trained models and remote sensing datasets; supports Sentinel-1/2, Landsat, and DEM inputs

- [geo-bench](https://github.com/ServiceNow/geo-bench) -> General Earth Observation benchmark for evaluating large pre-trained models on geospatial data

### Data Access & Cubing

- [terragon](https://github.com/drnhhl/terragon) -> Streamlined EO data downloading from multiple APIs (Planetary Computer, GEE, CDSE, ASF) using a single polygon-based interface; used to build Sen12Landslides. `pip install terragon-downloader`

- [odc-stac](https://github.com/opendatacube/odc-stac) -> Load STAC items into xarray datasets with efficient tiling; core tool for MorphEO data cube workflows

- [stackstac](https://github.com/gjoseph92/stackstac) -> Turn STAC metadata + rasters into an xarray DataArray with lazy Dask loading; Sentinel-2 ready

---

*(Living document — updated as we go 🌋)*
