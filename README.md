# Land Cover Classification System

Following are the directions and requirements to run the each experiment. For each experiment a jupyter notebook is provided.

Kaggle Notebook: Experiments that require Kaggle resource to execute are mentioned below. GPU hardware used is A40.
    
1. DeepLabV3:\
    File: `DeepLabV3.ipynb` \
    Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module. \
    Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells) 
2. U-net: \
    File: `Unet.ipynb` \
    Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module. \
    Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells) 
3. SegNet:\
    File: `SegNet.ipynb` \
    Libraries: torch, pandas, matplotlib, numpy, PIL, OpenCV, pytorch lightning, pytorch's segmentation module. \
    Directions: On kaggle add dataset, and follow and run the each cell sequentially to run the experiment. Before implementation of the model make sure to install library mentioned in fist cell and import all necessary libraries (present in next cells). In this notebook there two different implementation of Segnet, one in which Segnet fails and generate a random color mask. And the other implementation is provided below this failed attempt.
