
# Oil-Spill-Detection-Using-U-Net

This project implements an oil spill detection system using a **U-Net** for image segmentation. The model was designed and trained to automatically identify and segment oil spills from satellite or aerial imagery. The implementation pipeline includes data preprocessing, such as image resizing, normalization, and augmentation to improve model robustness. The U-Net architecture was built with an **encoder–decoder structure**, leveraging convolutional, pooling, and upsampling layers to capture spatial and contextual features effectively. The model was trained using **TensorFlow/Keras**, with binary cross-entropy loss and an **Adam optimizer** to accelerate convergence. The training process incorporated dropout and batch normalization to prevent overfitting and enhance generalization. After training, the model generates **pixel-wise predictions**, producing segmentation masks that clearly highlight oil spill regions, making it a valuable tool for automated environmental monitoring and maritime surveillance.

# Dataset

Oil Spill Detection Dataset: Download both the train and test directories from this https://www.kaggle.com/datasets/nabilsherif/oil-spill Kaggle dataset. This dataset contains Sentinel-1 SAR imagery annotated for oil spills. 

# Plotting the train images

<img width="964" height="496" alt="image" src="https://github.com/user-attachments/assets/868ee625-9be5-429f-81da-1de7ce82e041" />

# Train masks pixel count

<img width="846" height="545" alt="image" src="https://github.com/user-attachments/assets/b26520b2-b003-4759-810a-9ca81f47dea3" />

# Accuracy and Loss Graph

<img width="1001" height="391" alt="image" src="https://github.com/user-attachments/assets/c4ef8ec7-bcd6-4254-9917-fb2b260b9766" />

# Results

<img width="987" height="496" alt="image" src="https://github.com/user-attachments/assets/8c728ada-3897-4eb0-88ab-dc49ccf6d689" />
<img width="521" height="453" alt="image" src="https://github.com/user-attachments/assets/2c2851a9-18b2-40d4-b39a-1ef1379070e6" />

# Evaluation Metrics

```bash
Precision: 0.9490
Recall: 0.9522
F1 Score: 0.9503
```
```bash
Training loss (avg) = 0.143845

Training accuracy (avg) = 0.951965

Validation loss (avg) = 0.152781

Validation accuracy (avg) = 0.955155
```


