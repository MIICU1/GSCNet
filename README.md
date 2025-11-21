# GSCNet
Global Structural Consistency Interaction Teaching Framework for Semi-Supervised Medical Image Segmentation
# Data
Public data 'ACDC' can be downloaded at: [https://humanheart-project.creatis.insa-lyon.fr/database/#collections](https://humanheart-project.creatis.insa-lyon.fr/database/#collections).

Public data 'LA' can be downloaded at: [https://www.cardiacatlas.org/atriaseg2018-challenge/atria-seg-data/](https://www.cardiacatlas.org/atriaseg2018-challenge/atria-seg-data/).

Public data 'Pancreas-CT' can be downloaded at: [https://www.cancerimagingarchive.net/collection/pancreas-ct/](https://www.cancerimagingarchive.net/collection/pancreas-ct/).
# Train
on the ACDC dataset：python train_ACDC.py --root_path /data/ACDC --res_path /results/ACDC

on the LA dataset：python train_LA.py --root_path /data/LA --res_path /results/LA

on the Pancreas-CT：python train_Pancreas.py --root_path /data/Pancreas --res_path /results/Pancreas
# Test
on the ACDC dataset: python test_performance_2d.py

on the LA and Pancreas-CT datasets: python test_performance_3d.py
