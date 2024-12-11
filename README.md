# Breast-Cancer-Imaging-Datasets
This repository serves as a centralized resource listing various breast imaging and pathology datasets commonly used in academic research, clinical training, and machine learning applications. The goal is to provide detailed summaries of key characteristics, usage instructions, and guidance on how to obtain these datasets, all in one place.
If you know any more datasets, and want to contribute, please submit a pull request and I'll happily approve it.

## Introduction

This repository provides a curated list of breast imaging and histopathology datasets, aiming to streamline access for researchers, clinicians, and students. Here, the datasets are separated by each modality for easier understanding. This repository is composed of 47 publicly available datasets.

Below is a histogram showing the number of datasets in each modality, and pie chart representations that visualize the distribution of datasets by modality.

**Histogram of Datasets by Modality:**

![Histogram of Datasets by Modality](images/histogram.png "Histogram")

**Pie Chart of Datasets Distribution by Modality:**

![Pie Chart of Datasets Distribution](images/piechart.png "Pie Chart")

## Table of Contents
- [Datasets](#datasets)
  - [Ultrasound](#ultrasound)
  - [Digital Breast Tomosynthesis (DBT)](#digital-breast-tomosynthesis-dbt)
  - [Mammography](#mammography)
  - [MRI](#mri)
  - [Histopathology](#histopathology)
- [Contributing & Contact](#contributing--contact)

## Datasets

### Ultrasound

| Dataset                                 | Subjects | Nº Samples |  Format | Size   | Year | Cite | Access data |
|------------------------------------------|----------|-----------|--------|--------|------|------|----------|
| Breast Ultrasound Images (BUSI)  | 600      | 780    |    PNG      |  204MB      |   2020   | [Dataset of breast ultrasound images](https://www.sciencedirect.com/science/article/pii/S2352340919312181 "Link to paper")  |   [Download here](https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset_"Download_link")       |
| Breast Lesions USG                       |  256        |   522        |   PNG     |  66.67MB      |   2024   |  [Curated benchmark dataset for ultrasound based breast lesion analysis](https://doi.org/10.1038/s41597-024-02984-z_"Link_to_paper")    |   [Download here](https://www.cancerimagingarchive.net/collection/breast-lesions-usg/#citations_"Download_link")       |
| UDIAT Breast Ultrasound Dataset B                           |   163       |   163        |    N/A   |  N/A    |    2017    |  [Automated Breast Ultrasound Lesions Detection Using Convolutional Neural Networks](https://ieeexplore.ieee.org/document/8003418_"Link_to_paper")     |  [Resquest Permission](https://helward.mmu.ac.uk/STAFF/m.yap/dataset.php)        |
| OASBUD                           |     78     |    200       |  Matlab      |    296.8MB    |  2017    |  [Open access database of raw ultrasonic signals acquired from malignant and benign breast lesions](https://doi.org/10.1002/mp.12538_"Link_to_paper")    |   [Downnload here](https://zenodo.org/records/545928_"Download_link")       |
| BUS Synthetic Dataset                    |    0      |   500        |  PNG      |   9.7MB     |   2023   |  [PDF-UNet: A semi-supervised method for segmentation of breast tumor images using a U-shaped pyramid-dilated network](https://doi.org/10.1016/j.eswa.2023.119718_"Link_to_paper")    |    [Download here](https://data.mendeley.com/datasets/r4phtn49r7/1_"Download_link")      |

### Digital Breast Tomosynthesis (DBT)

| Dataset                        | Subjects | Nº Samples | Format | Size | Year | Cite | Download |
|--------------------------------|----------|-----------|--------|------|------|------|----------|
| Breast Cancer Screening DBT    |  5060        |   22 032        |  DICOM      |  1.63TB    |  2024    | [A Data Set and Deep Learning Algorithm for the Detection of Masses and Architectural Distortions in Digital Breast Tomosynthesis Images](https://doi.org/10.1001/jamanetworkopen.2021.19100_"Link_to_paper")     |  [Download here](https://doi.org/10.7937/e4wt-cd02_"Download_link")        |
| EA1141       |   1444       |   500        |  DICOM      |   2.82TB   |  2023    | [Abbreviated Breast MRI and Digital Tomosynthesis Mammography in Screening Women With Dense Breasts (EA1141) (Version 1) (dataset)](https://doi.org/10.7937/2BAS-HR33)     |  [Download here](https://doi.org/10.7937/2BAS-HR33_"Download_link")        |
| VICTRE      |   2994       |    2994       |   DICOM     | 1.03TB     |  2019    | [The VICTRE Trial: Open-Source, In-Silico Clinical Trial for Evaluating Digital Breast Tomosynthesis](http://doi.org/10.7937/TCIA.2019.ho23nxaw)     |   [Download here](http://doi.org/10.7937/TCIA.2019.ho23nxaw_"Download_link")       |

### Mammography

| Dataset                           | Subjects | Nº Samples | Format | Size | Year | Cite | Download |
|-----------------------------------|----------|-----------|--------|------|------|------|----------|
| CBIS-DDSM                         | 1566         |  6 671          |   DICOM     |  161.51GB    |  2017    | [A curated mammography data set for use in computer-aided detection and diagnosis research](https://www.nature.com/articles/sdata2017177)     |   [Download here](https://www.cancerimagingarchive.net/collection/cbis-ddsm/)       |
| CMMD                              |  1775        |    3 728       |  DICOM      |  2021    |  22.86GB    |  [The Chinese Mammography Database (CMMD): An online mammography database with biopsy confirmed types for machine diagnosis of breast](https://doi.org/10.7937/tcia.eqde-4b16)    |  [Download here](https://doi.org/10.7937/tcia.eqde-4b16)        |
| CDD-CESM                          |  326        |    2 006       |   JPEG     |   1.5GB   |  2021    |  [Categorized Digital Database for Low energy and Subtracted Contrast Enhanced Spectral Mammography images (Dataset)](https://doi.org/10.7937/29kw-ae92), [Categorized contrast enhanced mammography dataset for diagnostic and artificial intelligence research](https://www.nature.com/articles/s41597-022-01238-0), [The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository](https://link.springer.com/article/10.1007/s10278-013-9622-7)    |   [Download here](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=109379611#109379611bcab02c187174a288dbcbf95d26179e8)       |
| VinDr-Mammo                       |   5000       | 20 0000          |   DICOM     |  N/A    |  2022    |  [A large-scale benchmark dataset for computer-aided diagnosis in full-field digital mammography”](https://www.medrxiv.org/content/10.1101/2022.03.07.22272009v1)    |  [Download here](https://www.physionet.org/content/vindr-mammo/1.0.0/)         |
| INBreast                          |    115       |    410       | N/a        |  N/A    |  2012    |  [INbreast: toward a full-field digital mammographic database
](https://pubmed.ncbi.nlm.nih.gov/22078258/)    | [Contact the authors](https://pubmed.ncbi.nlm.nih.gov/22078258/)         |
| MIAS                              |    N/A      |     322      |   PGM     |   1.5GB   | 2015     |  [Mammographic Image Analysis Society (MIAS) database v1.21](https://www.repository.cam.ac.uk/items/b6a97f0c-3b9b-40ad-8f18-3d121eef1459)    |  [Download here](https://www.repository.cam.ac.uk/items/b6a97f0c-3b9b-40ad-8f18-3d121eef1459)        |
| Breast Tumor Mammography Dataset for Computer Vision                           |   N/A      |  3 383         |   JPG     |  103.49MB    |  2024    |  N/A    |    [Download here](https://www.kaggle.com/datasets/hayder17/breast-cancer-detection)      |


### MRI

| Dataset                      | Subjects | Nº Images | Format | Size | Year | Cite | Download |
|------------------------------|----------|-----------|--------|------|------|------|----------|
| RIDER Breast MRI             |          |           |        |      |      |      |          |
| fastMRI                      |          |           |        |      |      |      |          |
| ACRIN - 667                  |          |           |        |      |      |      |          |
| ACRIN-6698                   |          |           |        |      |      |      |          |
| ISPY1                        |          |           |        |      |      |      |          |
| ISPY2                        |          |           |        |      |      |      |          |
| Duke-Breast-Cancer-MRI       |          |           |        |      |      |      |          |
| Breast Cancer Patients MRI's |          |           |        |      |      |      |          |
| TCGA-Breast-Radiogenomics    |          |           |        |      |      |      |          |
| DICOM-SR-Breast-Clinical     |          |           |        |      |      |      |          |
| Breast-MRI-NACT-Pilot        |          |           |        |      |      |      |          |
| QIN Breast DCE-MRI           |          |           |        |      |      |      |          |
| QIN-BREAST                   |          |           |        |      |      |      |          |
| QIN-BREAST-02                |          |           |        |      |      |      |          |
| Advanced-MRI-Breast-Lesions  |          |           |        |      |      |      |          |
| RIDER PHANTOM MRI            |          |           |        |      |      |      |          |
| BREAST-DIAGNOSIS             |          |           |        |      |      |      |          |




 
