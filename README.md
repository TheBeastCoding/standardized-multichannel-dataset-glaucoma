# standardized-multichannel-dataset-glaucoma
Standardized Multi-Channel Dataset for Glaucoma (SMDG-18) is a collection and standardization of 18 public full-fundus glaucoma images and associated metadata.

## File Descriptions
- Metadata.csv : Links dataset instance metadata to image file paths.
- full-fundus/ : Folder containing all full fundus images.
- optic-cup/ : Folder containing the optic cup segmentation map based on the full fundus image.
- optic-disc/ : Folder containing the optic disc segmentation map based on the full fundus image.
- blood-vessel/ : Folder containing the blood vessel segmentation map based on the full fundus image.
- artery/ : Folder containing the artery segmentation map based on the full fundus image.
- vein/ : Folder containing the vein segmentation map based on the full fundus image.

## The images in this dataset are standardized from the following open-access datasets.
- OIA-ODIR-TRAIN
- OIA-ODIR-TEST-ONLINE
- OIA-ODIR-TEST-OFFLINE
- sjchoi86-HRF
- BEH (Bangladesh Eye Hospital)
- JSEIC-1000 (Joint Shantou International Eye Center)
- EyePACS-AIROGS (Referable Glaucoma Images Only)

## The following databases will be added at a later date
- HRF (High Resolution Fundus)
- LES-AV
- REFUGE1-TRAIN (Retinal Fundus Glaucoma Challenge 1 Train)
- REFUGE1-VAL (Retinal Fundus Glaucoma Challenge 1 Validation)
- DR-HAGIS (Diabetic Retinopathy, Hypertension, Age-related macular degeneration and Glacuoma ImageS)
- CRFO-v4
- DRISHTI-GS1-train
- DRISHTI-GS1-test
- G1020
- PAPILA

## Excluded Images
- OIA-ODIR-TEST-OFFLINE-21 : 1322_right.jpg : Not a fundus image.
- OIA-ODIR-TRAIN-3149 : 4290_right.jpg : No ONH present
- OIA-ODIR-TRAIN-3148 : 4290_left.jpg : No ONH present
- OIA-ODIR-TRAIN-3213 : 4500_left.jpg : No ONH present
- OIA-ODIR-TRAIN-3162 : 4330_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-3034 : 3442_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-3022 : 3436_right.jpg : No ONH present
- OIA-ODIR-TRAIN-3010 : 3430_right.jpg : No ONH present
- OIA-ODIR-TRAIN-3009 : 3430_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2990 : 3420_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2981 : 3416_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2982 : 3416_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2951 : 3401_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2839 : 3345_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2840 : 3345_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2831 : 3341_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2782 : 3316_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2700 : 3375_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2681 : 3266_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2566 : 3208_right.jpg : No ONH present
- OIA-ODIR-TRAIN-3561 : 3206_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-3562 : 3206_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2556 : 3203_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2532 : 3191_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2497 : 3174_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2443 : 3147_left.jpg : ONH obscured
- OIA-ODIR-TRAIN-2433 : 3142_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2419 : 3135_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2420 : 3135_right.jpg : Partial ONH present
