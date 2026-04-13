# SUT-Crack - Segmentation

## Overview

This package provides the **Segmentation** variant of SUT-Crack for the Large Road Damage DataLake.

SUT-Crack was introduced in *Data in Brief* as a pavement crack dataset designed to support
classification, object detection, and segmentation workflows under challenging field conditions.

- Dataset ID: sut-crack-segmentation
- Task: segmentation
- Images: 130
- Annotations: 174
- Classes: 1 (crack)
- Format: png_masks
- Source dataset DOI: 10.17632/gsbmknrhkv.6
- Source paper DOI: 10.1016/j.dib.2023.109642

## Source Facts

- Original crack imagery for segmentation/object detection: 130 images.
- Images captured from fixed height: 672 mm above pavement.
- Geotag metadata included (latitude/longitude per image in source dataset).
- Classification set built by 200x200 cropping, producing over 25,000 patches.
- Uses full-size geotagged source images with crack masks.

## Source Dataset

- Source URL: https://data.mendeley.com/datasets/gsbmknrhkv/6
- Mendeley DOI URL: https://doi.org/10.17632/gsbmknrhkv.6
- Source paper: https://doi.org/10.1016/j.dib.2023.109642
- Package URL: https://github.com/large-road-damage-datalake/sut-crack-segmentation

## Package Contents

- METADATA.json
- stats/
- visualizations/
- ABSTRACT.md
- SUMMARY.md
- CITATION.bib
- CITATION.md
- DOWNLOAD.md
- LICENSE.md
