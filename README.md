<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250"/> <br>
  
<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/5ce058ca-3906-4d05-baf6-75248cb9356b"/> 

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#download">Download</a> •
  <a href="#example">Example</a> •
  <a href="#license">License</a>
  
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly)
[![downloads](https://app.supervise.ly/img/badges/downloads/supervisely-ecosystem/aerial-power-infrastructure-detection-train-dataset.png)](https://supervise.ly)

# Train dataset - Eschikon Wheat Segmentation (EWS) 

</div>

# Overview

💾 Train and validation data datasets

Within the scope of this work, a new dataset for the segmentation of plants and soil was created. It consists of 190 manually chosen and hand annotated image patches of 350 × 350 pixels. The images were selected from a large unlabeled dataset that consists of approximately 100,000 20 Mpx RGB images of different winter wheat genotypes. These images were collected between 2017 and 2020 with a Canon 5D Mark II (Canon Inc., Japan) - 35 mm. The image set within each year covers the whole growing period from emergence to harvest. As the images are taken in the field, they show situations with widely varying illumination and soil moisture conditions:

<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/18c1a8d3-765f-4661-9864-8058ab74a403"/>

To generate a training set, images of the wheat canopies between emergence and stem elongation were selected.🟥In order to ensure a balanced sampling of the different imaging situations, the subsampling strategy was used. 🟥 Different growth stages with respect to plant pixel ratios with respect to soil can be seen in 🟥.

# Download

Direct download: [tar archive](https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/releases/download/v0.9.0/Train.tar)

# Example

<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/18c1a8d3-765f-4661-9864-8058ab74a403"/>

> Overview of variance in images from the Eschikon wheat segmentation (EWS) dataset of images.

# License

[Data source](https://doi.org/10.3929/ethz-b-000512332)

License: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)

[Original article](https://www.frontiersin.org/articles/10.3389/fpls.2021.774068/full)

Citation:

```
Zenkl R, Timofte R, Kirchgessner N, Roth L, Hund A, Van Gool L, Walter A and Aasen H (2022) Outdoor Plant Segmentation With Deep Learning for High-Throughput Field Phenotyping on a Diverse Wheat Dataset. Front. Plant Sci. 12:774068. doi: 10.3389/fpls.2021.774068
```
