# Chest_Xray_Classification_Utilizing_CNN_with_Optimized_Hyperparameters

This study presents a deep learning algorithm developed from the ground up to categorize as well as confirm the existence of COVID in a set of X-ray imaging data. We designed a CNN architecture from the ground up to retrieve elements from provided X-ray data to categorize them and identify the individual contaminated with COVID. Our strategy may aid in mitigating the consistency issues while working with medical data. In contrast to some other classifying activities with a large enough image database, obtaining large Xray datasets for this classification job is challenging. So, we applied multiple data enhancement techniques to maximize the accurateness, achieving a significant accuracy of 97.50 percent.

### Table of Contents

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

![Proposed](https://user-images.githubusercontent.com/72793142/209836307-cf9c1581-9348-4603-96aa-b638a08e43a7.png)
                                             
                                        Figure: Process Flow-graph of the Proposed System
   
![Schematic](https://user-images.githubusercontent.com/72793142/209837008-bf1c2931-101d-4918-89f4-93131ee7b4f1.png)

                              Figure: Schematic Block-diagram of the Convolutional Neural Architecture

## Tech/Stacks

- **Python**

- **Keras/TensorFlow**

## Result

