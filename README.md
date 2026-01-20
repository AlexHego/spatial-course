# Spatial Multiplex Analysis – Course Notes

## Spatial biology

Recent advances in spatial proteomics now make it possible to measure dozens to hundreds of proteins directly in intact tissue sections. These technologies generate highly multiplexed images that capture both protein expression and spatial relationships between cells. While biologically powerful, such datasets are complex and their analysis is far from trivial.

A major challenge of spatial multiplex imaging is not data acquisition, but data analysis. Highly multiplexed images must be transformed into structured, interpretable datasets through multiple processing steps, each involving methodological choices that can strongly impact biological conclusions.

The purpose of this course is to introduce the main concepts and workflows used in spatial multiplex analysis, with a strong emphasis on accessibility and interpretability. Whenever possible, the course relies on graphical user interfaces (GUIs) to make analyses more intuitive and reproducible.

In addition to QuPath, graphical tools such as CytoMAP are used as intermediate steps to illustrate clustering and neighborhood analysis concepts before introducing Python-based implementations.

## Prerequisites

Basic familiarity with microscopy concepts is assumed. Additional background resources and references are provided within the relevant chapters when appropriate.
No advanced programming skills are required, and Python is introduced progressively when needed.

## Course overview

This course introduces the main concepts and workflows required to analyze spatial multiplex imaging data, from images to interpretable spatial patterns.

The course is structured around three complementary stages:
image-based analysis in QuPath, graphical spatial exploration with CytoMAP, and programmable spatial analysis in Python.

QuPath is used to transform multiplex images into single-cell data through tissue detection, cell segmentation, object classification, quality control,
and feature extraction. CytoMAP is then introduced as a graphical tool to make clustering and spatial neighborhood concepts explicit and accessible. Finally, Python-based workflows are presented as a flexible and extensible option for advanced spatial analysis.

The focus of the course is on understanding workflows, concepts, and analytical choices rather than providing black-box pipelines. While CytoMAP is used to introduce spatial analysis concepts, advanced users may choose to move directly from QuPath to Python-based workflows.

## Course structure

The course is organized into chapters located in the `docs/` folder:

- [Chapter 1 – QuPath basics and project setup](docs/01_qupath_basics.md)  
- [Chapter 2 – Tissue detection and cell segmentation](docs/02_segmentation.md)  
- [Chapter 3 – Object classification and phenotyping](docs/03_object_classification.md)  
- [Chapter 4 – Quality control and data filtering](docs/04_quality_control.md)  
- [Chapter 5 – First spatial analysis in QuPath](docs/05_spatial_qupath.md)  
- [Chapter 6 – Graphical spatial analysis with CytoMAP](docs/06_cytomap_spatial_analysis.md)  
- [Chapter 7 – Transition CytoMAP to Python](docs/07_cytomap_to_python.md)  
- [Chapter 8 – Advanced spatial analysis in Python](docs/08_python_spatial_analysis.md)  


## License
