# standardized-multichannel-dataset-glaucoma
Standardized Multi-Channel Dataset for Glaucoma (SMDG-18) is a collection and standardization of 18 public full-fundus glaucoma images and associated metadata.

## File Descriptions
- Metadata.csv : Links dataset instance metadata to image file paths.
- full-fundus/ : Folder containing all full fundus images.
- optic-cup/ : Folder containing the optic cup segmentation map based on the full fundus image.
- optic-disc/ : Folder containing the optic disc segmentation map based on the full fundus image.
- blood-vessel/ : Folder containing the blood vessel segmentation map based on the full fundus image.
- artery/ :Folder containing the artery segmentation map based on the full fundus image.
- vein/ : Folder containing the vein segmentation map based on the full fundus image.

## The images in this dataset are standardized from the following open-access datasets.
- OIA-ODIR-TRAIN
- OIA-ODIR-TEST-ONLINE
- OIA-ODIR-TEST-OFFLINE
- HRF (High Resolution Fundus)
- LES-AV
- sjchoi86-HRF
- BEH (Bangladesh Eye Hospital)
- REFUGE1-TRAIN (Retinal Fundus Glaucoma Challenge 1 Train)
- REFUGE1-VAL (Retinal Fundus Glaucoma Challenge 1 Validation)
- DR-HAGIS (Diabetic Retinopathy, Hypertension, Age-related macular degeneration and Glacuoma ImageS)
- CRFO-v4
- JSEIC-1000 (Joint Shantou International Eye Center)
- DRISHTI-GS1-train
- DRISHTI-GS1-test
- G1020
- EyePACS-AIROGS (Referable Glaucoma Images Only)
- PAPILA

## Excluded Images
- OIA-ODIR-TEST-OFFLINE-21 : 1322_right.jpg : Not a fundus image.
