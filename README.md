# Crop-Type-Classification

Classification of crop types using multitemporal multispectral satellite images.

1. `crop_classification.ipynb` - Obtained Landsat 8 images over Fresno, California along with indices. CDL was used for labelled dataset and filtered to only include highly accurate labels. Random Forest classifier was used to identify the major crops in the region.

2. `classification_sklearn.ipynb` - Since overfitting was observed, larger sample size was exported to train using sklearn due to the limitation of GEE. Accuracy of 85% was obtained.
