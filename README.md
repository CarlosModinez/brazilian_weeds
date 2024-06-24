# Brazilian weeds

Welcome to the repository dedicated to studies on classification and semantic segmentation of the 8 families and 14 most common weed species in Brazil. This project aims to develop and share machine learning models for accurate identification and segmentation of these weeds, contributing to the advancement of sustainable agriculture.

## Notebooks

The `Notebooks` files contain the primary artifact of this repository:

The Jupyter Notebook details the process of model training, evaluation, and inference. It includes analyses, visualizations, and experimental results. 

## Results

- [x] Classification by families task - `weed_classification.ipynb` (BEST RESULT: resnet50 - weighted CE)
- [x] Classification by species task - `weed_species_classification.ipynb` (BEST RESULT: resnet101 - weighted CE and resnet152 - weighted CE)
- [x] Binary segmentation task (weed x background) - `weed_segmentation.ipynb` (BEST RESULT: UNET++) 
- [x] Semantic segmentation task using original dataset
- [x] Semantic segmentation task using blender dataset
- [x] Semantic segmentation task using mixed dataset
- [x] Result report

## Contributions

Contributions and feedback are welcome!
