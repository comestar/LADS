<h2 align="center">LADS</h2>

[English](README.md) | [中文说明](docs/zh/Readme.md)

This Git repository contains the description of the LADS dataset, as well as the implementation code for the four remote sensing models used in the dataset paper—Mask2Former, U-Net, DeepLabV3+, and Mask R-CNN.

## Dataset Details

This dataset contains 1,275 land-cover scenes, each with a ground resolution of 0.1 meters per pixel. For every scene, there is a corresponding “image” and “label.”

The images are PNG files, and the labels are PNG masks. A single image corresponds to multiple labels, distinguished by file suffixes for two categories: cropland and buildings (as described below).

Below is an example of a labeled scene:

<img src="img\18759_yxtdt.png" width="600">

Below is an example of a labeled scene. More examples can be found in [lads](dataset)
