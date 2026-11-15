# SUT-Crack - Segmentation

## Overview

This package provides the **Segmentation** variant of SUT-Crack for the Large Road Damage DataLake.

SUT-Crack was introduced in *Data in Brief* as a pavement crack dataset designed to support
classification, object detection, and segmentation workflows under challenging field conditions.

- Dataset ID: sut-crack-segmentation
- Task: segmentation
- Images: 130
- Annotations: 171
- Classes: 1 (crack)
- Format: png_masks
- Source dataset DOI: 10.17632/gsbmknrhkv.6
- Source paper DOI: 10.1016/j.dib.2023.109642

## Source Facts

- Original crack imagery for segmentation/object detection: 130 images (`3024x4032`; 119 of 130 JPEG files carry EXIF orientation tag 6 to match the `3024x4032` portrait masks).
- Images captured from fixed height: 672 mm above pavement.
- Captured with a Samsung Galaxy S20 FE smartphone mounted on the rear bumper of a vehicle on Hashemieh Boulevard, Mashhad, Iran.
- Geotag metadata included (latitude/longitude per image in source dataset).
- Classification set built by 200x200 cropping, producing 25,561 patches in Mendeley Data v6.
- Uses full-size geotagged source images with pixel-level binary crack masks.

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
