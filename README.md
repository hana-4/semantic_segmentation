# Semantic Segmentation in Urban Road Scenes

This repository implements a **semantic segmentation** pipeline for urban road scenes using the **U-Net** architecture. The model is trained and tested on the **Indian Driving Dataset (IDD)**, with a focus on robust real-world performance.  

## Overview
- The pipeline leverages **U-Net** for pixel-wise classification of road scenes.  
- The model is trained to segment urban road scenes into various classes such as road, vehicles, pedestrians, traffic signs, and more.  
- **Data augmentation** techniques were applied to improve robustness against real-world variations such as lighting, occlusions, and weather conditions.

## Technologies used
- **Python**  
- **PyTorch** (for deep learning model)  
- **OpenCV** (for image processing)  
- **Matplotlib** (for visualizations)  
- **Indian Driving Dataset (IDD)** (for training and testing)

## Pipeline
1. **Data Preprocessing**  
   - The IDD dataset is preprocessed for training, including resizing and normalization.
   
2. **Data Augmentation**  
   - To simulate real-world variations, techniques such as random cropping, flipping, rotation, and color adjustments are used.

3. **Model Training**  
   - The U-Net architecture is trained with **Cross-Entropy Loss** and **Adam optimizer**.

4. **Evaluation**  
   - Performance is evaluated using **Mean Intersection over Union (mIoU)** and **pixel accuracy**.

## Sample Outputs

Here are some sample outputs showing the **original image**, **ground truth**, and **predicted mask** for the semantic segmentation task:

![Sample Output](sample.png)

- **Original Image:** The input image from the Indian Driving Dataset (IDD).  
- **Ground Truth:** The manually annotated mask representing the correct segmentation labels.  
- **Predicted Mask:** The segmentation mask predicted by the trained U-Net model.

## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/semantic_segmentation.git
cd semantic_segmentation

