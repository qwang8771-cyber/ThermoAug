# PairUAV-150

Official homepage for the dataset used in our paper.

## Overview

PairUAV-150 is a paired infrared dataset for UAV small target analysis.

The dataset consists of **150 paired sample groups**, and each group contains:

- one target-present infrared image containing a UAV small target
- one corresponding target-absent infrared image
- one mask annotation
- one XML bounding-box annotation

The dataset was acquired using a long-wave cooled infrared imaging system and is intended for research on infrared UAV small targets.

## Highlights

- Paired sample design: each group contains both target-present and target-absent images for controlled comparison
- Dual annotation formats: both pixel-level mask annotations and XML bounding-box annotations are provided
- Focused on infrared UAV small targets: suitable for detection, segmentation, and related evaluation tasks
- Useful for fusion/synthesis evaluation: applicable to target extraction, target insertion, target-background fusion, and realism assessment of synthetic results

## Dataset Information

- **Dataset name**: PairUAV-150
- **Number of paired groups**: 150
- **Imaging device**: long-wave cooled infrared imaging system
- **Target category**: UAV small targets
- **Annotation types**:
  - binary mask annotation
  - XML bounding-box annotation

## Download

The dataset can be accessed via the following link:

- **Baidu Netdisk**: [Insert your Baidu Netdisk link here](YOUR_BAIDU_LINK_HERE)
- **Extraction code**: `YOUR_CODE_HERE`

> Note: This GitHub repository serves as the public homepage and documentation page of the dataset, while the full dataset is distributed via the external link above.

## Annotation Format

### 1. Mask Annotation

The mask is a binary image with:

- **target region = 255**
- **background = 0**

### 2. XML Annotation

Each target-present image is accompanied by an XML file that provides the rectangular bounding-box annotation of the UAV target.
