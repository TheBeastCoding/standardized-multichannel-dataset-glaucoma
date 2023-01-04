# Standardized Multi-Channel Dataset for Glaucoma (SMDG-18)
Standardized Multi-Channel Dataset for Glaucoma (SMDG-18) is a collection and standardization of 18 public full-fundus glaucoma images and associated metadata.

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

## Public Glaucoma Image Datasets
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
| OIA-ODIR-TRAIN | 2933 | 197 | 18 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| OIA-ODIR-TEST-ONLINE | 802 | 58 | 25 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| OIA-ODIR-TEST-OFFLINE | 417 | 36 | 9 | https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k |
| ORIGA-light | 482 | 168 | 0 | https://www.kaggle.com/datasets/sshikamaru/glaucoma-detection |
| PAPILA | 333 | 87 | 68 | https://doi.org/10.6084/m9.figshare.14798004.v1 |
| REFUGE1-TRAIN (Retinal Fundus Glaucoma Challenge 1 Train) | 360 | 40 | 0 | https://refuge.grand-challenge.org/REFUGE2Download/  |
| REFUGE1-VALIDATION (Retinal Fundus Glaucoma Challenge 1 Validation) | 360 | 40 | 0 | https://refuge.grand-challenge.org/REFUGE2Download/  |
| sjchoi86-HRF | 300 | 101 | 0 | https://github.com/yiweichen04/retina_dataset |
| Total | 7300 | 4617 | 133 | |

## The following datasets are open-access but do not contain full fundus images
- ACRIMA
- KEH (Kim's Eye Hospital)
- RIM-ONE

## The following images are excluded from the OIA-ODIR dataset:
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
- OIA-ODIR-TRAIN-2405 : 3128_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2382 : 3116_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2379 : 3115_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2380 : 3115_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2326 : 3088_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2228 : 3039_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2155 : 3003_left.jpg : No ONH present
- OIA-ODIR-TRAIN-2156 : 3003_right.jpg : No ONH present
- OIA-ODIR-TRAIN-2120 : 2985_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2063 : 2956_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2064 : 2956_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2057 : 2953_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-2058 : 2953_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1971 : 2910_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1972 : 2910_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1943 : 2896_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1920 : 2884_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1913 : 2881_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1889 : 2869_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1890 : 2870_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1845 : 2847_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1846 : 2847_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1739 : 2794_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1725 : 2787_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1703 : 2776_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1699 : 2774_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1665 : 2757_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1598 : 2723_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1592 : 2720_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1571 : 2710_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1572 : 2710_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1561 : 2705_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1562 : 2705_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1550 : 2699_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1543 : 2696_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1536 : 2692_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1501 : 2675_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1502 : 2675_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1473 : 2661_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1469 : 2659_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1465 : 2657_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1466 : 2657_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1461 : 2655_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1441 : 2645_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1428 : 2638_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1402 : 2625_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1348 : 2598_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1343 : 2596_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1327 : 2588_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1328 : 2588_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1276 : 2562_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1277 : 2563_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1219 : 2534_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1220 : 2534_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1183 : 2516_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1184 : 2516_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1098 : 2473_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1057 : 2453_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1058 : 2453_right.jpg : No ONH present
- OIA-ODIR-TRAIN-1036 : 2442_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1025 : 2437_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1009 : 2429_left.jpg : No ONH present
- OIA-ODIR-TRAIN-1010 : 2429_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-1001 : 2425_left.jpg : No ONH present
- OIA-ODIR-TRAIN-920 : 2384_right.jpg : No ONH present
- OIA-ODIR-TRAIN-917 : 2383_left.jpg : Partial ONH present
- OIA-ODIR-TRAIN-895 : 2372_left.jpg : No ONH present
- OIA-ODIR-TRAIN-822 : 2335_right.jpg : No ONH present
- OIA-ODIR-TRAIN-653 : 1417_left.jpg : No ONH present
- OIA-ODIR-TRAIN-645 : 1406_right.jpg : No ONH present
- OIA-ODIR-TRAIN-624 : 1369_left.jpg : No ONH present
- OIA-ODIR-TRAIN-601 : 1319_right.jpg : No ONH present
- OIA-ODIR-TRAIN-543 : 1254_right.jpg : No ONH present
- OIA-ODIR-TRAIN-473 : 1145_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-441 : 1066_right.jpg : No ONH present
- OIA-ODIR-TRAIN-369 : 884_right.jpg : Partial ONH present
- OIA-ODIR-TRAIN-280 : 643_left.jpg : No ONH present
- OIA-ODIR-TRAIN-165 : 351_right.jpg : No ONH present
- OIA-ODIR-TRAIN-120 : 252_left.jpg : No ONH present
- OIA-ODIR-TRAIN-71 : 141_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-903 : 4930_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-818 : 3927_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-804 : 3920_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-796 : 3916_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-797 : 3916_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-783 : 3909_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-769 : 3902_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-761 : 3898_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-722 : 3879_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-723 : 3879_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-717 : 3876_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-715 : 3875_right.jpg : Blurry Fundus
- OIA-ODIR-TEST-ONLINE-713 : 3874_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-710 : 3873_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-643 : 3839_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-514 : 3775_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-515 : 3775_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-504 : 3770_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-505 : 3770_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-498 : 3767_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-486 : 3761_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-487 : 3761_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-482 : 3759_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-483 : 3759_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-466 : 3751_left.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-467 : 3751_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-441 : 3738_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-400 : 3718_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-397 : 3716_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-356 : 3696_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-357 : 3696_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-338 : 3687_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-241 : 3638_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-227 : 3631_right.jpg : Partial ONH present
- OIA-ODIR-TEST-ONLINE-202 : 3612_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-186 : 3599_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-116 : 2039_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-112 : 2036_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-39 : 1748_right.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-34 : 1715_left.jpg : No ONH present
- OIA-ODIR-TEST-ONLINE-3 : 1204_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-445 : 3623_right.jpg : Partial ONH present/Blurry
- OIA-ODIR-TEST-OFFLINE-373 : 3572_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-365 : 3568_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-356 : 3564_left.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-339 : 3555_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-313 : 3542_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-310 : 3541_left.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-301 : 3536_right.jpg : Partial ONH present
- OIA-ODIR-TEST-OFFLINE-293 : 3532_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-280 : 3526_left.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-252 : 3512_left.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-253 : 3512_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-155 : 3462_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-136 : 3453_left.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-129 : 3447_right.jpg : Partial ONH present
- OIA-ODIR-TEST-OFFLINE-49 : 1390_right.jpg : No ONH present
- OIA-ODIR-TEST-OFFLINE-3 : 1107_left.jpg : No ONH present
