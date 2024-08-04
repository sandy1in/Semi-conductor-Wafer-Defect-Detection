# Semi-conductor-Wafer-Defect-Detection

Project focused on using Convolutional Neural Networks (CNNs) to improve defect identification in 
semiconductor wafer surfaces. Traditional methods like manual inspection and feature-based 
algorithms Often fall short in accuracy and reliability for such tasks.

We developed a specialized CNN architecture called CNN-WDI (CNN for Wafer Defect Identification) to 
directly learn and extract meaningful features from raw wafer map images. This approach aimed to 
achieve higher classificaƟon accuracy compared to convenƟonal methods.

We used the WM-811K dataset consists of 800,000 images but in that only 120,000 are labelled also 
there was an imbalance in the dataset. To address this imbalance, we applied data augmentaƟon 
techniques like rotaƟon and flipping, shearing, scaling. Preprocessing involved resizing images to a 
standard format of (224,224,3) and using One-Hot Encoded SemanƟc SegmentaƟon (OHESS). Data was 
divided into three groups: 60% for training, 15% for testing, and 25% for validaƟon.
The results showcased excepƟonal performance: training accuracy reached 99.18%, test accuracy 
stood at 96.8%, and validaƟon accuracy at 96.6%. 
In evaluating our model's performance, we created visual plots of accuracy scores, confusion matrices, 
and precision-recall curves. These insights guided us in refining hyperparameters and validaƟng the 
model's robustness, ulƟmately enhancing defect idenƟficaƟon in semiconductor wafers.
