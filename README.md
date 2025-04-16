# Semantic Segmentation for Urban Road Scenes

This repository implements a **semantic segmentation** pipeline for urban road scenes using the **U-Net** architecture. The model is trained and tested on the **Indian Driving Dataset (IDD)**, with a focus on robust real-world performance.  

## Overview
- The pipeline leverages **U-Net** for pixel-wise classification of road scenes.  
- The model is trained to segment urban road scenes into various classes such as road, vehicles, pedestrians, traffic signs, and more.  
- **Data augmentation** techniques were applied to improve robustness against real-world variations such as lighting, occlusions, and weather conditions.

## Dataset
- The **Indian Driving Dataset (IDD)** captures the uniqueness of the Indian driving scene. It includes various types of road conditions, traffic situations, and typical elements found on Indian roads such as animals, auto-rickshaws, etc.  
- The dataset consists of images obtained from a front-facing camera mounted on a car, along with corresponding annotations. The car was driven in and around **Hyderabad** and **Bangalore**, including their outskirts.  
- This implementation makes use of **21 unique classes** available in the dataset annotations.  


## Sample Output

Here is a sample output showing the **original image**, **ground truth**, and **predicted mask** for the semantic segmentation task:

![Sample Output](sample.png)
