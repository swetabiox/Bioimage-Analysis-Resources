# Bioimage-Analysis-Resources
A collection of resources on bioimage analysis and related tools and techniques.

## Contents:
- [Datasets](#sources-of-bioimage-datasets)
- [Courses/Learning resources](#courses-and-learning-resources-for-bioimage-analysis)
- [Researchers/Labs](#researchers-and-labs-working-on-bioimage-analysis)
- [Papers](#landmark-papers)
- [Blogs](#blogs)
- [Softwares and Toolkits](#softwares-and-toolkits)
- [Python libraries](#python-libraries-and-plugins)

## Sources of bioimage datasets

- [Broad Bioimage Benchmark Collection](https://bbbc.broadinstitute.org/image_sets): Annotated biological image sets for testing and validation
- [NUCEXM DATASET](https://ieee-dataport.org/documents/nucexm-dataset-nuclei-segmentation-expansion-microscopy): 3D Instance Segmentation of zebrafish brain nuclei in expansion microscopy
- [FLUORESCENCE MICROSCOPY IMAGE DATASETS FOR DEEP LEARNING SEGMENTATION OF INTRACELLULAR ORGENELLE NETWORKS](https://ieee-dataport.org/documents/fluorescence-microscopy-image-datasets-deep-learning-segmentation-intracellular-orgenelle): Fluorescence microscopy images of the Endoplasmic Reticulum network and mitochondrial network in cultured live cells. The datasets have been used to evaluate and compare performance of the methods proposed in the article “Heuristic Optimization of Deep Learning Models for Segmentation of Intracellular Organelle Networks”.
- [An annotated fluorescence image dataset for training nuclear segmentation methods](https://www.ebi.ac.uk/biostudies/studies/S-BSST265): This dataset contains annotated fluorescent nuclear images of different tissue origins and sample preparation types and can be used to train machine-learning based nuclear image segmentation algorithms.
- [UCSB Bio-Segmentation Benchmark dataset](https://bioimage.ucsb.edu/research/bio-segmentation): Consists of 2D/3D images and time-lapse sequences that can be used for evaluating the performance of novel state of the art computer vision algorithms. Tasks include segmentation, classification, and tracking.
- [PARASITIC EGG DETECTION AND CLASSIFICATION IN MICROSCOPIC IMAGES](https://ieee-dataport.org/competitions/parasitic-egg-detection-and-classification-microscopic-images): The dataset contains 11 parasitic egg types. Each category has 1,000 images, suitable for classification/object recognition.
- [HUMAN SOMATIC LABEL-FREE BRIGHT-FIELD CELL IMAGES](https://ieee-dataport.org/documents/human-somatic-label-free-bright-field-cell-images): Suitable for multi-class cell classification.

(more information will be added soon)

## Courses and Learning resources for bioimage analysis

1. [Bio-image_Analysis_with_Python](https://github.com/BiAPoL/Bio-image_Analysis_with_Python): This repository contains training resources for Python beginners who want to dive into image processing with Python. These are the lecture materials for "Bio-image analysis, biostatistics, programming and machine learning for computational biology" at the Center of Molecular and Cellular Bioengineering (CMCB) / University of Technology, TU Dresden.
2. [Bio-Image analysis with Python and Napari - DIGS-BB Light Microscopy Course 2022](https://biapol.github.io/DIGS-BB_LM_Course_Bio-Image_Analysis_2022/intro.html): This one-day course is focused on processing microscopy images showing cells and nuclei.
3. [Bio-image Analysis Notebooks](https://haesleinhuepf.github.io/BioImageAnalysisNotebooks/intro.html): This collection of Python jupyter notebooks are written for Python beginners who are interested in analyzing three dimensional images of cells and tissues acquired using modern fluorescence microscopes.
4. [DigitalSreeni](https://www.youtube.com/digitalsreeni): This channel walks us through the entire process of learning to code in Python; all the way from basics to advanced machine learning and deep learning. The emphasis is mainly on microscopy and bioimage analysis. The images and code from this channel can be found [here](https://github.com/bnsreenu/python_for_microscopists).
5. [Quantitative Bio-Image Analysis with Python Course from BiA-PoL](https://github.com/BiAPoL/Quantitative_Bio_Image_Analysis_with_Python_2022): This 5-day course introduces us to the basics of image data science using Python, napari and Jupyter, enabling us to develop reproducible image analysis workflows using state-of-the art data science methods.
6. [Introduction to Bio-Image Analysis](https://www.denbi.de/online-training-media-library/919-introduction-to-bioimaging): Robert Haase of CSBD/MPI-CBG Dresden gave lectures as part of a lecture series at Biotec TU Dresden about Bio-Image Analysis using Fiji, ImageJ, and others KNIME, good scientific practice and image analysis basics.
7. [Bioimage analysis talk series](https://www.ibiology.org/techniques/bioimage-analysis/): In this series, Dr. Anne Carpenter and Dr. Kevin Eliceiri provide an overview of bioimage analysis.

(more information will be added soon)

## Researchers and labs working on bioimage analysis

1. [Kreshuk Group](https://www.embl.org/groups/kreshuk/) - Machine learning for bioimage analysis: Led by [Anna Kreshuk](https://www.embl.org/people/person/f6c69f1e5895edd0a5b4577c1c21312c37abad3b950b90f2edba134b1bf45e06/), the Kreshuk group develops machine learning-based methods and tools for automatic segmentation, classification and analysis of biological images.
2. [Biological Image Analysis Unit (BIA)](https://research.pasteur.fr/en/team/bioimage-analysis/): Headed by [Jean-Christophe Olivo-Marin](https://research.pasteur.fr/en/member/jean-christophe-olivo-marin/), this group develops and improves on original and rigorous methodologies for the quantification of 3D multichannel image sequences in biological imaging, at the cellular and molecular level, but also at the level of organizations.
3. [LOÏC ROYER, DR. RER. NAT.](https://www.czbiohub.org/people/cz-biohub-staff/loic-royer-dr-rer-nat/)
4. [Henriques Laboratory](https://henriqueslab.github.io/): Headed by [Ricardo Henriques](https://henriqueslab.github.io/team/2013-09-01-RH/).
5. [Jug Group](https://humantechnopole.it/en/research-groups/jug-group/): Headed by [Florian Jug](https://humantechnopole.it/en/people/florian-jug/).
6. [Myers Lab](http://myerslab.mpi-cbg.de/): Headed by [Gene Myers](https://myerslab.mpi-cbg.de/people/gene/).
7. [Robert Haase](https://haesleinhuepf.github.io/): He leads the [Bio-image Analysis Group](https://physics-of-life.tu-dresden.de/en/research/core-groups/bio-image-analysis)
8. [Weigert group](https://www.epfl.ch/labs/weigert-lab/): Led by [Martin Weigert](https://scholar.google.de/citations?user=ZltxyqoAAAAJ&hl=de), this group focuses on the development of new machine learning based approaches to extract quantitative biological information from microscopy images and the design of novel computational methods to augment and improve optical microscopy.
9. [Kainmueller Lab](https://www.mdc-berlin.de/kainmueller): Led by [Dr. Dagmar Kainmueller](https://www.mdc-berlin.de/person/dr-dagmar-kainmuller), this lab pursues theoretical advances in machine learning and combinatorial optimization to solve challenging image analysis problems in biology.
10. [Uwe Schmidt](http://research.uweschmidt.org/)
11. [Kota Miura](https://www.researchgate.net/profile/Kota-Miura-3): Dr. Kota Miura is a Freelance Bioimage Analyst and works with various research groups and companies in Europe, for teaching, consulting, and collaborations. He also is affiliated with the Nikon Imaging Center at the University of Heidelberg and is the Vice-Chair of NEUBIAS (the Network of European Bioimage Analysts).
12. [Quantitative Microscopy](https://www.it.uu.se/about_us/divisions/vi3/research/quantitativemicroscopy): A research group at Uppsala University that develops automatic image analysis methods for microscopy.
13. [Nataša Sladoje](https://www.cb.uu.se/~natasa/?n=Main.Main)
14. [Uhlmann Group](https://www.ebi.ac.uk/research/uhlmann/): Led by [Virginie Uhlmann](https://www.ebi.ac.uk/people/person/virginie-uhlmann/), the Uhlmann group develops methods to quantify morphology from microscopy images, whether they are 2D, 3D, static, dynamic, and of any imaging modality.

(more information will be added soon)

## Landmark Papers

1. [Bioimage Data Analysis Workflows](https://link.springer.com/book/10.1007/978-3-030-22386-1): This Open Access textbook provides students and researchers in the life sciences with essential practical information on how to quantitatively analyze data images.
2. [Bioimage Data Analysis Workflows ‒ Advanced Components and Methods](https://link.springer.com/book/10.1007/978-3-030-76394-7): This open access textbook aims at providing detailed explanations on how to design and construct image analysis workflows to successfully conduct bioimage analysis. Addressing the main challenges in image data analysis, where acquisition by powerful imaging devices results in very large amounts of collected image data, the book discusses techniques relying on batch and GPU programming, as well as on powerful deep learning-based algorithms. 
3. [A bird’s-eye view of deep learning in bioimage analysis](https://www.sciencedirect.com/science/article/pii/S2001037020303561)
4. [A Practical Guide to Supervised Deep Learning for Bioimage Analysis: Challenges and good practices](https://ieeexplore.ieee.org/document/9721183)

(More coming soon)

## Blogs

- [The BiA-PoL blog](https://biapol.github.io/blog/): The blog of the Bio-image Analysis Technology Development group at the DFG Cluster of Excellence "Physics of Life", TU Dresden.
- [Interpreting bioimages with deep learning](https://www.ebi.ac.uk/about/news/perspectives/deep-learning-bioimaging/)

(More coming soon)

## Softwares and Toolkits

- [BioImage Model Zoo](https://bioimage.io/#/): This is a community-driven, fully open resource where standardized pre-trained models can be shared, explored, tested, and downloaded for further adaptation or direct deployment in multiple end user-facing tools. It has models, applications and datasets for bioimage analysis.
- [QuPath](https://qupath.github.io/): QuPath is an open, powerful, flexible, extensible software platform for bioimage analysis.
- [ilastik](https://www.ilastik.org/): ilastik is a simple, user-friendly tool for interactive image classification, segmentation and analysis, developed by the ilastik team in Anna Kreshuk's lab at the European Molecular Biology Laboratory.
- [ImageJ](https://imagej.nih.gov/ij/)
- [CellProfiler](https://cellprofiler.org/)
- [Fiji](https://fiji.sc/)
- [Icy](https://icy.bioimageanalysis.org/)
- [DeepImageJ](https://deepimagej.github.io/deepimagej/)
- [Microscopy Image Stitching Tool](https://pages.nist.gov/MIST/): Microscopy Image Stitching Tool (MIST), is a stitching tool for 2D grids of images.
 


(More coming soon)

## Python libraries and plugins

1. [Napari](https://napari.org/stable/)

(More Coming soon)
