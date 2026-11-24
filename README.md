# Regional maize yield prediction with phenology-informed stage representations and historical climate conditioning

This repository contains the PCSR-Net model and the scripts used to train it and predict regional maize yield. PCSR-Net encodes daily weather separately for four maize growth stages and uses historical climate to adjust each stage representation before combining them to predict yield.

## Acknowledgments

- We thank the CY-Bench team and its data contributors for the maize datasets used in our experiments in the United States, Argentina, France, and Germany. [CY-Bench](https://cybench.agml.org/)
- We thank the National Cryosphere Desert Data Center for providing access to the meteorological data used in China. [Dataset record](https://www.ncdc.ac.cn/portal/metadata/21691d03-bef2-4800-924e-5614e7268b87)
- We obtained the phenological stage information through Google Earth Engine. [Google Earth Engine](https://earthengine.google.com/)
