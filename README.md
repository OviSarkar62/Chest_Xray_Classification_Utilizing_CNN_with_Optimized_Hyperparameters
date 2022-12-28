# Chest_Xray_Classification_Utilizing_CNN_with_Optimized_Hyperparameters

This study presents a deep learning algorithm developed from the ground up to categorize as well as confirm the existence of COVID in a set of X-ray imaging data. We designed a CNN architecture from the ground up to retrieve elements from provided X-ray data to categorize them and identify the individual contaminated with COVID. 

## Table of Contents

(1) **Dataset Description**

(2) **Preprocessing & Augmentation**

(3) **Proposed Architecture**

(4) **Tech/Stacks**

(5) **Result** 

(6) **Conclusion**

### Dataset Description

Any deep neural architecture work needs a vast amount of data as input. An appropriate cluster of data aids in better analyzing a Deep learning challenge. We gathered data for our issue set mostly from three separate and well-known web sources. The following public datasets were used in this study: 

(1) https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

(2) https://data.mendeley.com/datasets/9xkhgts2s6

(3) https://www.kaggle.com/datasets/nih-chest-xrays/data

The first Database is used to compile chest X-rays of COVID-19 positive pictures and normal images. Images of bacterial pneumonia are sourced from the second Dataset. Furthermore, photos of pneumothorax are obtained from the third Dataset. The subset of X-ray imagery is built using the datasets to identify and assess the efficiency of the suggested CNN model architecture. 

### Preprocessing & Augmentation

- I resized all pictures to 224 × 224 pixels,

- Used the min-max normalization method to rescale all pixel values [0, 1],

- In addition, I employed photo augmentation for solving the issue of a short dataset and to improve the accuracy rate while limiting model overfitting. 

### Proposed Architecture

<p align="center">
  <img alt="img-name" src="https://user-images.githubusercontent.com/72793142/209853172-e30766d2-18fd-40ba-8b6c-8f032b95c748.png" width="800">
  <br>
    <em>Fig: Schematic Block-diagram of the Convolutional Neural Architecture</em>
</p>

### Tech/Stacks

- **Python**

- **Keras/TensorFlow**

### Results

- **Learning Curve**
<p align="center">
  <img alt="img-name" src="https://user-images.githubusercontent.com/72793142/209853161-95145f03-fed7-4c79-8c6b-2c5f68d5bbf0.png" width="400">
  <br>
    <em>Fig: Training and Validation Graph</em>
</p>

- **Confusion Matrix**
<p align="center">
  <img alt="img-name" src="https://user-images.githubusercontent.com/72793142/209853100-9736fa73-9073-42b1-aa51-8c9c55ff888f.png" width="300">
  <br>
    <em>Fig: Connfusion Matrix</em>
</p>

- **GradCAM**
<p align="center">
  <img alt="img-name" src="https://user-images.githubusercontent.com/72793142/209853138-f4bc1d6c-1ae1-4d17-8895-77e751eb31c7.png" width="300">
  <br>
    <em>Fig: Heatmap Visualization Using GradCAM</em>
</p>
