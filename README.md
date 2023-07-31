<div align="center" markdown>

<img src="https://i.imgur.com/UdBujFN.png" width="250"/> <br>
  
<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/5ce058ca-3906-4d05-baf6-75248cb9356b"/> 

<p align="center">

  <a href="#overview">Overview</a> •
  <a href="#example">Example</a> •
  <a href="#license">License</a>
  
</p>

[![](https://img.shields.io/badge/slack-chat-green.svg?logo=slack)](https://supervise.ly/slack) 
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/supervisely-ecosystem/EWS-Dataset-training-data)
[![views](https://app.supervise.ly/img/badges/views/supervisely-ecosystem/EWS-Dataset-training-data.png)](https://supervise.ly)
[![downloads](https://app.supervise.ly/img/badges/downloads/supervisely-ecosystem/EWS-Dataset-training-data.png)](https://supervise.ly)

# Train dataset - Eschikon Wheat Segmentation (EWS) 

</div>

# Overview

💾 Train Dataset

Within the scope of [this work](https://www.frontiersin.org/articles/10.3389/fpls.2021.774068/full), a new dataset for the segmentation of plants and soil was created. It consists of 190 manually chosen and hand annotated image patches of 350 × 350 pixels. The images were selected from a large unlabeled dataset that consists of approximately 100,000 20 Mpx RGB images of different winter wheat genotypes. These images were collected between 2017 and 2020 with a Canon 5D Mark II (Canon Inc., Japan) - 35 mm. The image set within each year covers the whole growing period from emergence to harvest. As the images are taken in the field, they show situations with widely varying illumination and soil moisture conditions:

<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/18c1a8d3-765f-4661-9864-8058ab74a403"/>

> *Example: Overview of variance in images from the Eschikon wheat segmentation (EWS) dataset of image*

To generate a training set, images of the wheat canopies between emergence and stem elongation were selected. In order to ensure a balanced sampling of the different imaging situations, the subsampling strategy was used. Different growth stages with respect to plant pixel ratios with respect to soil can be seen in *Example*. The resulting subset of 190 RGB images was cropped into patches of 350 × 350 pixels and then manually annotated in form of binary masks for plants and soil, respectively. The crop size of 350 × 350 pixels was determined so that atleast two wheat rows are visible in the image. 

The presented dataset is the first dataset to cover the same field over multiple years with a number of different lighting conditions scenarios. 

<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/7e06e1d7-4140-42ac-96ed-f6d6395b9b5d"/>

>Eschikon wheat segmentation (EWS) dataset overview of the distribution of direct and diffuse light with respect to the number of different days.

# Example

<img src="https://github.com/supervisely-ecosystem/EWS-Dataset-training-data/assets/119248312/7594a65b-ef17-4b1e-90ea-759dac216ffe"/>

> Example of pre-training wheat images.

# License

[Data source](https://doi.org/10.3929/ethz-b-000512332)

License: Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)

[Original article](https://www.frontiersin.org/articles/10.3389/fpls.2021.774068/full)

Citation:

```
Zenkl R, Timofte R, Kirchgessner N, Roth L, Hund A, Van Gool L, Walter A and Aasen H (2022) Outdoor Plant Segmentation With Deep Learning for High-Throughput Field Phenotyping on a Diverse Wheat Dataset. Front. Plant Sci. 12:774068. doi: 10.3389/fpls.2021.774068
```
