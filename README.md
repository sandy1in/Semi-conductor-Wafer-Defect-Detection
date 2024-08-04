#Semiconductor-Wafer-Defect-Detection
##Overview
Welcome to the "Wafer Defect Identification" repository! This project focuses on identifying defects in wafer images using deep learning techniques. The dataset comprises images with nine distinct classes of defects. To address challenges such as class imbalance & image quality , we have employed the techniques ,Data Augmentation, One-Hot Encoded Semantic Segmentation (OHESS) preprocessing technique.

##Dataset

Link : http://mirlab.org/dataset/public/
Raw_images

Our dataset includes images of wafers with defects classified into nine different classes. To enhance the dataset and mitigate the class imbalance issue, we have implemented data augmentation techniques.

##Preprocessing
One-Hot Encoded Semantic Segmentation (OHESS) To prepare the data for training, we have utilized the One-Hot Encoded Semantic Segmentation (OHESS) technique. This involves resizing and augmenting the images, enhancing the model's ability to generalize and recognize defects effectively.



##Handling Class Imbalance
Class imbalance is a common challenge in multi-class classification problems. In our dataset, we observed a significant imbalance between classes. To address this, we have employed data augmentation strategies to increase the representation of minority classes. This ensures that the model learns effectively from all classes, improving overall performance.

##Requirements
pip install -r requirements.txt
Follow the instructions in the notebooks and scripts within each directory to explore and run the project components. Contributing
