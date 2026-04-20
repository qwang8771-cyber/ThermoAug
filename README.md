# ThermoAug
Official homepage for the dataset used in our paper.
Overview

PairUAV-150 is a paired infrared dataset for UAV small target analysis.
The dataset consists of 150 paired sample groups, and each group contains:

one target-present infrared image containing a UAV small target,
one corresponding target-absent infrared image,
one mask annotation,
one XML bounding-box annotation.

The dataset was acquired using a long-wave cooled infrared imaging system and is intended for research on infrared UAV small targets.

Highlights
Paired sample design: each group contains both target-present and target-absent images for controlled comparison;
Dual annotation formats: both pixel-level mask annotations and XML bounding-box annotations are provided;
Focused on infrared UAV small targets: suitable for detection, segmentation, and related evaluation tasks;
Useful for fusion/synthesis evaluation: applicable to target extraction, target insertion, target-background fusion, and realism assessment of synthetic results.
Dataset Information
Dataset name: PairUAV-150
Number of paired groups: 150
Imaging device: long-wave cooled infrared imaging system
Target category: UAV small targets
Annotation types:
binary mask annotation
XML bounding-box annotation
Download

The dataset can be accessed via the following link:

Baidu Netdisk: Insert your Baidu Netdisk link here
Extraction code: YOUR_CODE_HERE

Note: This GitHub repository serves as the public homepage and documentation page of the dataset, while the full dataset is distributed via the external link above.
Annotation Format
1. Mask Annotation

The mask is a binary image with:

target region = 255
background = 0
2. XML Annotation

Each target-present image is accompanied by an XML file that provides the rectangular bounding-box annotation of the UAV target.

Potential Research Uses

PairUAV-150 can be used for, but is not limited to:

infrared UAV small target detection
infrared small target segmentation
evaluation of target extraction methods
evaluation of target insertion and synthesis methods
evaluation of target-background fusion methods
paired analysis of target presence under controlled conditions

In particular, because the dataset provides paired target-present and target-absent samples, it is suitable for assessing whether a method can preserve background consistency while introducing realistic target responses.

Visual Examples

Several representative paired samples can be displayed below.

Example 1
<p align="center"> <img src="assets/examples/example_pair_01.png" width="85%"> </p>
Example 2
<p align="center"> <img src="assets/examples/example_pair_02.png" width="85%"> </p>
Example 3
<p align="center"> <img src="assets/examples/example_pair_03.png" width="85%"> </p>

It is recommended that each example figure includes a target-present image, a target-absent image, the mask annotation, and the bounding-box visualization.

License

This dataset is released for academic research only.

Commercial use, redistribution, or any other use beyond academic research is not allowed without prior permission from the authors.

A formal license file may be added later if needed.

Citation

If you use this dataset in your research, please cite the related paper or the dataset homepage.

Citation of the dataset homepage
@misc{pairuav150,
  title={PairUAV-150: A Paired Infrared UAV Small Target Dataset},
  author={Author One and Author Two and Author Three},
  year={2026},
  note={Dataset homepage. Link will be updated after publication.},
  howpublished={GitHub repository}
}
Citation of the paper
@article{yourpaper2026,
  title={Your Paper Title},
  author={Author One and Author Two and Author Three},
  journal={TBD},
  year={2026},
  note={To be updated after publication}
}
Contact

For questions about the dataset, please contact:

Name: YOUR_NAME
Email: YOUR_EMAIL
