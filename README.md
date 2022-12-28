# Chest_Xray_Classification_Utilizing_CNN_with_Optimized_Hyperparameters

The earlier detection and accurate diagnosis of COVID seem to be a global problem. It is difficult to make a large number of testing equipment, but then again, their reliability is relatively poor. Recent research indicates the usefulness of chest x-ray pictures in identifying COVID. This study presents a deep learning algorithm developed from the ground up to categorize as well as confirm the existence of COVID in a set of X-ray imaging data. We designed a CNN architecture from the ground up to retrieve elements from provided X-ray data to categorize them and identify the individual contaminated with COVID. Our strategy may aid in mitigating the consistency issues while working with medical data. In contrast to some other classifying activities with a large enough image database, obtaining large Xray datasets for this classification job is challenging. So, we applied multiple data enhancement techniques to maximize the accurateness, achieving a significant accuracy of 97.50 percent.

### Table of Contents

(1) Dataset Description

(2) Preprocessing & Augmentation

(3) Proposed Architecture

(4) Tech/Stacks

(5) Result 

(6) Conclusion

### Dataset Description

Any deep neural architecture work needs a vast amount of data as input. An appropriate cluster of data aids in better analyzing a Deep learning challenge. We gathered data for our issue set mostly from three separate and well-known web sources. The following public datasets were used in this study: 

(1) https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database

(2) https://data.mendeley.com/datasets/9xkhgts2s6

(3) https://www.kaggle.com/datasets/nih-chest-xrays/data

The first Database is used to compile chest X-rays of COVID-19 positive pictures and normal images. Images of bacterial pneumonia are sourced from the second Dataset. Furthermore, photos of pneumothorax are obtained from the third Dataset. The subset of X-ray imagery is built using the datasets to identify and assess the efficiency of the suggested CNN model architecture. 

### Preprocessing & Augmentation

(1) I resized all pictures to 224x224 pixels 

(2) Used the min-max normalization method to rescale all pixel values [0, 1]

(3) In addition, I employed photo augmentation for solving the issue of a short dataset and to improve the accuracy rate while limiting model overfitting. Because the data is limited, the data augmentation approach is utilized for training the model in an optimum manner while avoiding overfitting. In the image generator for augmentation,

(a) the sample-wise center is employed first to make the single image’s mean pixel value zero. 

(b) Following that, sample-wise standard deviation normalization is performed to partition pictures based on their associated value. 

(c) Finally, the horizontal flip is used to flip photos horizontally.



