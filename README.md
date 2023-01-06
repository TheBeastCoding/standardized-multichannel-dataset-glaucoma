# Standardized Multi-Channel Dataset for Glaucoma (SMDG-18), a standardization of 18 public datasets.
Standardized Multi-Channel Dataset for Glaucoma (SMDG-18) is a collection and standardization of 18 public full-fundus glaucoma images and associated metadata.

## Image Standardization
- How are the images standardized? Full fundus images are standardized by cropping the background, centering the fundus image, padding missing information, and resizing to 512x512 pixels.

Original Fundus (sjchoi86-HRF) |   Standardized Fundus Image (sjchoi86-HRF)
--- | ---
![fundus](https://user-images.githubusercontent.com/65875562/204170005-2d4dd051-0032-40c8-ba0b-390b6080bb69.png) | ![fundus_cropped](https://user-images.githubusercontent.com/65875562/204170011-51b7d001-4d43-4f0d-835e-984d45116b18.png)

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

## The following datasets are open-access but do not contain full fundus images. These images are not included in our dataset
- ACRIMA
- KEH (Kim's Eye Hospital)
- RIM-ONE
