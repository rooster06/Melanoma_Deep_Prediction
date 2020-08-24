# Deep Melanoma Diagnostics
Prabhat Rayapati

   ![melanoma_image_ex](https://github.com/rooster06/Melanoma_Deep_Prediction/blob/master/banner.png)

Melanoma is the most serious type of skin cancer, develops in the cells (melanocytes) that produce melanin, early daignosis is key for recovery.


## Final_Driver_Notebook.ipynb

- Set up TPU
- Data augmentations in generator - random rotation, random shear, random zoom, random shift
- Callbacks for learning rate scheduler & model checkpoint saving
- Binary cross entropy loss & AUC metric tracking
- Train in full EfficientNets B0 to B7 family use as ensembles
- Graphing tools for loss and auc metric by epoch for all models
- Build a decision tree classifier to ensemble EffNet family and take straight average of all EffNet Family
- Use these two ensembling techniques for inference with test time augmentations

## 1_Explore_Augment_SampleModel.ipynb

- Exploratory analysis 
- Body hair removal augmentation 

## 2_Augment_TransferLearning.ipynb

## 3_1_Preprocess_TransferLearning_init.ipynb

- Directory restructuring 
- image generator with augmentation 
- ResNet50 init_
