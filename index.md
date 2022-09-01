## Publications

## Overview of the QuantImage v2 platform

QuantImage v2 (QI2) is an open-source web-based platform for no-code clinical radiomics research. It has been developed with the aim to empower physicians to play a leading role in clinical radiomics research. We believe that tighter involvement of domain experts is critical to ensuring the clinical relevance of radiomics research and will lead to the development of better interpretable and more generalizable radiomics models.

To implement this vision, and different to most other radiomics softwares, QI2 supports all steps of a typical radiomics study workflow, (a) allowing the user to create patient cohorts, (b) extracting radiomics features from regions of interest (ROIs) of CT/PET/MR images, (c) exploring and selecting features using visualisation and (d) creating and evaluating machine learning models for  classification & survival tasks. 
Furthermore, QI2 was designed to integrate well into the clinical environment; it provides PACS-like functionality for managing imaging studies, is ubiquitously accessible through a web portal and guides the user through the radiomics analysis processs.

QI relies on established components for medical image management, radiomics feature computation and machine learning, including [Kheops](https://github.com/OsiriX-Foundation/kheops), an open-source web-based for managing collections of DICOM images, [pyradiomics](https://pyradiomics.readthedocs.io/en/latest/index.html) for feature extraction and [scikit-learn](https://scikit-learn.org/stable/) / [scikit-survival](https://scikit-survival.readthedocs.io/en/stable/) for machine learning model development and evaluation.

![QuantImage2 schema](/assets/images/qi-overview.png "QuantImage2")

The video below is an introduction to the QuantImage v2 radiomics research platform and its features:

<!-- Video does not appear in the Preview, but is visible on the deployed website -->
<video style='max-width: 832px; max-height: 832px' controls><source src='https://drive.switch.ch/index.php/s/3Tom8ZnIF8wl2r3/download' type='video/mp4'>Video Not Suppported</video>

## Getting Started
You can try out the platform <a href="https://quantimage2.ehealth.hevs.ch" target="_blank">here</a>

 
