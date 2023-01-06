# Standardized Multi-Channel Dataset for Glaucoma (SMDG-18), a standardization of 18 public datasets for AI applications.
Standardized Multi-Channel Dataset for Glaucoma (SMDG-18) is a collection and standardization of 18 public full-fundus glaucoma images, associated image metadata like,  optic disc segmentation, optic cup segmentation, blood vessel segmentation, and any provided per-instance text metadata like sex and age.

## Dataset Objective
The objective of this dataset that is a machine learning-ready dataset for Glaucoma-related applications. 
 
## Data Standardization
- Full fundus images (and corresponding segmentation maps) are standardized by cropping the background, centering the fundus image, padding missing information, and resizing to 512x512 pixels.
- Each available metadata text attribute is provided as a column in a CSV file

Dataset Instance | Original Fundus  |   Standardized Fundus Image
--- | --- | ---
sjchoi86-HRF | <img src="https://user-images.githubusercontent.com/65875562/204170005-2d4dd051-0032-40c8-ba0b-390b6080bb69.png" width="512"> | <img src="https://user-images.githubusercontent.com/65875562/204170011-51b7d001-4d43-4f0d-835e-984d45116b18.png" width="256">
BEH | <img src="https://user-images.githubusercontent.com/65875562/211052753-93f8a3aa-cc65-4790-8da6-229f512a6afb.PNG" width="512"> | <img src="https://user-images.githubusercontent.com/65875562/211053562-5b269348-a892-469a-acb5-869c622928e1.PNG" width="256">

## Dataset labels
- 0: Non-Glaucoma instance
- 1: Glaucoma instance
- -1: Glaucoma-suspect instance

## SMDG-18 is comrpised of the following Public Glaucoma Image Datasets
| Dataset  | 0 | 1 | -1 | Access Link |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| BEH (Bangladesh Eye Hospital) | 463 | 171 | 0 | https://github.com/mirtanvirislam/Deep-Learning-Based-Glaucoma-Detection-with-Cropped-Optic-Cup-and-Disc-and-Blood-Vessel-Segmentation/tree/master/Dataset |
| CRFO-v4 | 31 | 48 | 0 | https://data.mendeley.com/datasets/trghs22fpg/4 |
| DR-HAGIS (Diabetic Retinopathy, Hypertension, Age-related macular degeneration and Glacuoma ImageS) | 0 | 10 | 0 | https://personalpages.manchester.ac.uk/staff/niall.p.mcloughlin/ |
| DRISHTI-GS1-TRAIN  | 18 | 32 | 0 | https://cvit.iiit.ac.in/projects/mip/drishti-gs/mip-dataset2/Home.php  |
| DRISHTI-GS1-TEST  | 13 | 38 | 0 | https://cvit.iiit.ac.in/projects/mip/drishti-gs/mip-dataset2/Home.php  |
| EyePACS-AIROGS | 0 | 3269 | 0 | https://airogs.grand-challenge.org/data-and-challenge/ |
| G1020 | 724 | 296 | 0 | https://www.kaggle.com/datasets/arnavjain1/glaucoma-datasets |
| HRF (High Resolution Fundus) | 15 | 15 | 0 | https://www5.cs.fau.de/research/data/fundus-images/  |
| JSIEC-1000 (Joint Shantou International Eye Center) | 38 | 0 | 13 | https://www.kaggle.com/datasets/linchundan/fundusimage1000 |
| LES-AV | 11 | 11 | 0 | https://figshare.com/articles/dataset/LES-AV_dataset/11857698/1 |
| OIA-ODIR-TRAIN | 2932 | 197 | 18 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| OIA-ODIR-TEST-ONLINE | 802 | 58 | 25 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| OIA-ODIR-TEST-OFFLINE | 417 | 36 | 9 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| ORIGA-light | 482 | 168 | 0 | https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection |
| PAPILA | 333 | 87 | 68 | https://doi.org/10.6084/m9.figshare.14798004.v1 |
| REFUGE1-TRAIN (Retinal Fundus Glaucoma Challenge 1 Train) | 360 | 40 | 0 | https://refuge.grand-challenge.org/REFUGE2Download/  |
| REFUGE1-VALIDATION (Retinal Fundus Glaucoma Challenge 1 Validation) | 360 | 40 | 0 | https://refuge.grand-challenge.org/REFUGE2Download/  |
| sjchoi86-HRF | 300 | 101 | 0 | https://github.com/yiweichen04/retina_dataset |
| Total | 7299 | 4617 | 133 | |

## Instructions for Popular Use Cases
- Glaucoma classification (12,049 total instances): Split the data by 'types' column in the CSV file. Input = 'fundus' file. Label = 'types' number.
- Optic cup segmentation (2,874 instances): Find all rows in CSV file with a non-empty 'fundus_od_seg' column. Input = 'fundus' file. Label = 'fundus_oc_seg' file.
- Optic disc segmentation (3,103 instances): Find all rows in CSV file with a non-empty 'fundus_oc_seg' column. Note some instances are labeled as 'Not Visible', so you must exclude these as well. Input = 'fundus' file. Label = 'fundus_od_seg' file.

## File Descriptions
- metadata.csv : Links dataset instance metadata to image file paths.
- full-fundus/ : Folder containing all full fundus images.
- optic-cup/ : Folder containing the optic cup segmentation map based on the full fundus image.
- optic-disc/ : Folder containing the optic disc segmentation map based on the full fundus image.
- blood-vessel/ : Folder containing the blood vessel segmentation map based on the full fundus image.
- vessel-artery/ : Folder containing the artery segmentation map based on the full fundus image.
- vessel-vein/ : Folder containing the vein segmentation map based on the full fundus image.
- spectral-oct/ : Folder containing all full spectral oct images.
- spectral-oct-cup/ : Folder containing the optic cup segmentation lines based on the full spectral oct image.
- spectral-oct-disc/ : Folder containing the optic disc segmentation lines based on the full spectral oct image.

## The following datasets are open-access but do not contain full fundus images. These images are not included in our dataset
- ACRIMA
- KEH (Kim's Eye Hospital)
- RIM-ONE
