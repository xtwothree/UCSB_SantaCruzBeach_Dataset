# UCSB Santa Cruz Beach Image Dataset

## Overview
This dataset consists of sequential images of **Santa Cruz Beach**, located on the **University of California, Santa Barbara (UCSB)** campus near Goleta Point. 

All images are captured from a fixed shoreline-facing camera angle overlooking the beach and ocean.

The frames were collected using **VLC Media Player** from the publicly available **CoastSnap citizen-science timelapse** featured in the UCSB article: [UC Santa Barbara Researchers Launch CoastSnap Citizen Science Initiative to Monitor Coastal Change](https://news.ucsb.edu/2024/021425/uc-santa-barbara-researchers-launch-coastsnap-citizen-science-initiative-monitor).

---

## Data Collection
- **Source:** CoastSnap UCSB webcam timelapse  
- **Location:** Santa Cruz Beach, UCSB East Campus, near Goleta Point (approx. *34.406° N, -119.843° W*)  
- **Capture Method:** VLC Scene Filter extraction  
  - Preferences → All → Video → Filters → Scene filter  
  - Directory path prefix set for automatic frame saving  
  - Recording ratio adjusted for ~5 fps capture  
  - Image format: JPEG  
- **Content:** Consecutive images showing varying tidal and lighting conditions  
- **Resolution:** 720p

---

## Purpose
This dataset supports an educational **semantic segmentation** project exploring:
- Water region identification  
- Shoreline motion tracking  
- Temporal visualization of coastal evolution  

It provides a foundation for experimenting with segmentation models on dynamic natural scenes and supports environmental monitoring of coastal change at UCSB.

---

## Model Context
The segmentation model architecture referenced is detailed in  
**“Encoder-Decoder with Atrous Separable Convolution for Semantic Image Segmentation”**  
([Chen et al., 2018, arXiv:1802.02611](https://arxiv.org/pdf/1802.02611)).

## License
CC BY 4.0 — You may share or adapt the dataset with attribution to Alejandro Franco and the CoastSnap UCSB source.
