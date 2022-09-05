## QuantImage v2 platform

QuantImage v2 (QI2) is an open-source web-based platform for no-code clinical radiomics research. It has been developed with the aim to empower physicians to play a leading role in clinical radiomics research. We believe that tighter involvement of domain experts is critical to ensuring the clinical relevance of radiomics research and will lead to the development of better interpretable and more generalizable radiomics models.

<img src="assets/images/qi-overview.png" alt="QuantImage v2" title="QuantImage v2 - Overview" />

### One-stop tool for clinical radiomics research
To implement this vision, and different to most other radiomics softwares, QI2 supports **all steps of a typical radiomics study workflow**:
* allowing the user to create patient cohorts, 
* extracting radiomics features from regions of interest (ROIs) of CT/PET/MR images, 
* exploring and selecting features using visualisation, as well as  
* creating and evaluating machine learning models for  classification and survival tasks. 

Furthermore, QI2 was designed to **integrate well into the clinical environment**:
* providing PACS-like functionality for managing imaging studies, 
* ubiquitous access through a web portal, and 
* guiding the user through the radiomics analysis processs.

### Built upon established Open-Source components
QI relies on established components for medical image management, radiomics feature computation and machine learning, including [Kheops](https://github.com/OsiriX-Foundation/kheops), an open-source web-based for managing collections of DICOM images, [pyradiomics](https://pyradiomics.readthedocs.io/en/latest/index.html) for feature extraction and [scikit-learn](https://scikit-learn.org/stable/) / [scikit-survival](https://scikit-survival.readthedocs.io/en/stable/) for machine learning model development and evaluation.

### Overview
The video below is an introduction to the QuantImage v2 radiomics research platform and its features:

<!-- Video does not appear in the Preview, but is visible on the deployed website -->
<video style='max-width: 832px; max-height: 832px' controls><source src='https://drive.switch.ch/index.php/s/3Tom8ZnIF8wl2r3/download' type='video/mp4'>Video Not Suppported</video>

## Getting Started
You can try out the platform <a href="https://quantimage2.ehealth.hevs.ch" target="_blank">here</a>.
<!-- info about available dataset & sign-up process  -->

### QuantImage v2 as VirtualMachine image 
To make it easy for you to **test QI2 with your data**, we provide QI2 as ([VirtualBox](https://www.virtualbox.org/) virtual image here. 

<!-- add information about minimum specs, startup and update process. We could create a separate page for the technical details  -->

### QuantImage v2 source code
 <!-- github link -->

## Support & Funding

Research and development of QuantImage v2 was supported by

<div class="funding-logos">
    <a href="https://snf.ch" target="_blank" rel="nofollow"><img src="assets/logos/snsf.png" alt="SNSF" /></a>
    <a href="https://sphn.ch" target="_blank" rel="nofollow"><img src="assets/logos/sphn.png" alt="SPHN" /></a>
    <a href="https://haslerstiftung.ch" target="_blank" rel="nofollow"><img src="assets/logos/hasler.png" alt="Hasler" /></a>
</div>

