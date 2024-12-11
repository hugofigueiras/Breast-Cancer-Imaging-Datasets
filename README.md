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
| CDD-CESM                          |  326        |    2 006       |   JPEG     |   1.5GB   |  2021    |  [Categorized Digital Database for Low energy and Subtracted Contrast Enhanced Spectral Mammography images (Dataset)](https://doi.org/10.7937/29kw-ae92) , [Categorized contrast enhanced mammography dataset for diagnostic and artificial intelligence research](https://www.nature.com/articles/s41597-022-01238-0) , [The Cancer Imaging Archive (TCIA): Maintaining and Operating a Public Information Repository](https://link.springer.com/article/10.1007/s10278-013-9622-7)    |   [Download here](https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=109379611#109379611bcab02c187174a288dbcbf95d26179e8)       |
| VinDr-Mammo                       |   5000       | 20 0000          |   DICOM     |  N/A    |  2022    |  [A large-scale benchmark dataset for computer-aided diagnosis in full-field digital mammography”](https://www.medrxiv.org/content/10.1101/2022.03.07.22272009v1)    |  [Download here](https://www.physionet.org/content/vindr-mammo/1.0.0/)         |
| INBreast                          |    115       |    410       | N/a        |  N/A    |  2012    |  [INbreast: toward a full-field digital mammographic database
](https://pubmed.ncbi.nlm.nih.gov/22078258/)    | [Contact the authors](https://pubmed.ncbi.nlm.nih.gov/22078258/)         |
| MIAS                              |    N/A      |     322      |   PGM     |   1.5GB   | 2015     |  [Mammographic Image Analysis Society (MIAS) database v1.21](https://www.repository.cam.ac.uk/items/b6a97f0c-3b9b-40ad-8f18-3d121eef1459)    |  [Download here](https://www.repository.cam.ac.uk/items/b6a97f0c-3b9b-40ad-8f18-3d121eef1459)        |
| Breast Tumor Mammography Dataset for Computer Vision                           |   N/A      |  3 383         |   JPG     |  103.49MB    |  2024    |  N/A    |    [Download here](https://www.kaggle.com/datasets/hayder17/breast-cancer-detection)      |


### MRI

| Dataset                      | Subjects | Nº Samples | Format | Size | Year | Cite | Download |
|------------------------------|----------|-----------|--------|------|------|------|----------|
| ACRIN-6667                   | 984         |   984        |  DICOM      |  199.59GB    |  2021    |   [ACRIN-Contralateral-Breast-MR (ACRIN 6667) (Data set)](https://doi.org/10.7937/Q1EE-J082)   |  [Download here](https://doi.org/10.7937/Q1EE-J082)        |
| ACRIN-6698                   |   385       |   385        |   DICOM     | 1.94TB     |  2021    | [ ACRIN 6698/I-SPY2 Breast DWI (Data set)](https://doi.org/10.7937/tcia.kk02-6d95)     | [Download here](https://doi.org/10.7937/tcia.kk02-6d95)         |
| ISPY1                        |  222        |   222        |    DICOM    |   78.36GB   | 2016     | [Multi-center breast DCE-MRI data and segmentations from patients in the I-SPY 1/ACRIN 6657 trials](http://doi.org/10.7937/K9/TCIA.2016.HdHpgJLK)     |   [Download here](http://doi.org/10.7937/K9/TCIA.2016.HdHpgJLK)       |
| ISPY2                        |  719        |    719       |    DICOM    |  4.16TB    |   2022   |  [I-SPY 2 Breast Dynamic Contrast Enhanced MRI Trial (ISPY2)  (Version 1) (Data set)](https://doi.org/10.7937/TCIA.D8Z0-9T85) , [ACRIN 6698/I-SPY2 Breast DWI (Data set)](https://doi.org/10.7937/TCIA.KK02-6D95)     |  [Download here](https://www.cancerimagingarchive.net/collection/ispy2/)        |
| Duke Breast Cancer MRI       |  922        |   922        |  DICOM     |  368.89GB    | 2022     |  [A machine learning approach to radiogenomics of breast cancer: a study of 922 subjects and 529 DCE-MRI features](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6134102/)    |  [Download here](https://www.cancerimagingarchive.net/collection/duke-breast-cancer-mri/)        |
| Breast Cancer Patients MRI's |  700        |  700         |    JPG    |  201.4MB    |  2021    |  N/A    |  [Download here](https://www.kaggle.com/datasets/uzairkhan45/breast-cancer-patients-mris)        |
| Breast MRI NACT Pilot        |  64        |   64        |   DICOM     |  19.51GB    |   2023   |  [Single site breast DCE-MRI data and segmentations from patients undergoing neoadjuvant chemotherapy (Version 3) (Data set)](https://doi.org/10.7937/K9/TCIA.2016.QHSYHJKY)    |    [Download here](https://doi.org/10.7937/K9/TCIA.2016.QHSYHJKY)      |
| QIN Breast DCE-MRI           |     10     |    10       |     DICOM   |   15.9GB   | 2019    |   [Variations of dynamic contrast-enhanced magnetic resonance imaging in evaluation of breast cancer therapy response: a multicenter data analysis challenge (QIN Breast DCE-MRI) (Version 2) (Data set)](https://doi.org/10.7937/k9/tcia.2014.a2n1ixox)   |  [Download here](https://doi.org/10.7937/k9/tcia.2014.a2n1ixox)        |
| QIN-BREAST                   | 67          |    67       |  DICOM      | 11.41GB     |  2020    | [ Data From QIN-BREAST (Version 2) (Data set)](https://doi.org/10.7937/K9/TCIA.2016.21JUEBH0)     |  [Download here](https://www.cancerimagingarchive.net/collection/qin-breast/)        |
| QIN-BREAST-02                | 13         |     13      |   DICOM     |  4.19GB    | 2019     |  [Data from QIN-BREAST-02(Dataset)](https://doi.org/10.7937/TCIA.2019.4cfm06rr)    |  [Download here](https://www.cancerimagingarchive.net/collection/qin-breast-02/)        |
| Advanced MRI Breast Lesions  |   632       |    632       |    DICOM    | 646GB     |   2024   |  [Standard and Delayed Contrast-Enhanced MRI of Malignant and Benign Breast Lesions with Histological and Clinical Supporting Data (Advanced-MRI-Breast-Lesions) (Version 2) (dataset)](https://doi.org/10.7937/C7X1-YN57)    |  [Download here](https://www.cancerimagingarchive.net/collection/advanced-mri-breast-lesions/)        |
| BREAST DIAGNOSIS             |     88     |   88        |   DICOM     |  60.87GB    | 2011     |  [ BREAST-DIAGNOSIS (Data set)](http://doi.org/10.7937/K9/TCIA.2015.SDNRQXXR)    |    [Download here](https://www.cancerimagingarchive.net/collection/breast-diagnosis/)      |

### Histopathology

| Dataset                          | Subjects | Nº Samples| Format | Size | Year | Cite | Download |
|----------------------------------|----------|-----------|--------|------|------|------|----------|
| Post NAT BRCA                    |   54     |   54      |   SVS     |  42.3GB    |  2019    | [Assessment of Residual Breast Cancer Cellularity after Neoadjuvant Chemotherapy using Digital Pathology (Data set)](https://doi.org/10.7937/TCIA.2019.4YIBTJNO)     |   [Download here](https://www.cancerimagingarchive.net/collection/post-nat-brca/)       |
| Breast Histopathology Images     |    162      |    162       |    PNG    |  1.6GB    |  2016    | [Deep learning for digital pathology image analysis: A comprehensive tutorial with selected use cases
](https://www.ncbi.nlm.nih.gov/pubmed/27563488)     |    [Download here](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images)      |
| BreakHis                         |    82      |    7,909       |   PNG     | N/A     |   2016   |  [A Dataset for Breast Cancer Histopathological Image Classification](http://www.inf.ufpr.br/lesoliveira/download/TBME-00608-2015-R2-preprint.pdf)    | [Download here](https://web.inf.ufpr.br/vri/databases/breast-cancer-histopathological-database-breakhis/)         |
| Breast Cancer Cell Segmentation  |   N/A       |   58        |   TIFF     | 159.82MB     | 2019    |  [Evaluation and benchmark for biological image segmentation](https://ieeexplore.ieee.org/document/4712130)    |  [Download here](https://www.kaggle.com/datasets/andrewmvd/breast-cancer-cell-segmentation)        |
| BCSS                             | 25         |    151       |   RGB     |  N/A    |   2019   |  [Structured crowdsourcing enables convolutional segmentation of histology images](https://academic.oup.com/bioinformatics/article/35/18/3461/5307750?login=true)    | [Download here](https://github.com/PathologyDataScience/BCSS?tab=readme-ov-file)         |
| TUPAC16                          |   500       |       N/A    |    SVS    |  848GB    |   2016   |  [Predicting breast tumor proliferation from whole-slide images: the TUPAC16 challenge](https://pubmed.ncbi.nlm.nih.gov/30861443/)    |  [Download here](https://tupac.grand-challenge.org/)        |
| CAMELYON                         |   200       |    1 399       | TIFF       |  N/A    |  2018    |  [1399 H&E-stained sentinel lymph node sections of breast cancer patients: the CAMELYON dataset](https://pmc.ncbi.nlm.nih.gov/articles/PMC6007545/)    |  [Download here](https://camelyon17.grand-challenge.org/Data/)        |
| BACH                             |    N/A      |     400      |   SVS & TIFF     |    18.23GB  |  2022    |  [Bach: Grand challenge on breast cancer histology images](https://arxiv.org/abs/1808.04277)    | [Download here](https://www.kaggle.com/datasets/truthisneverlinear/bach-breast-cancer-histology-images)         |

## Contributing & Contact

- **Contributions:**  
  Suggestions for new datasets, updates, or corrections are welcome. Please open an issue or submit a pull request.

- **Contact:**  
  For specific dataset access, follow the provided links or contact dataset maintainers directly. For repository-related questions, use the issue tracker.


 
