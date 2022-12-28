# Chest_Xray_Classification_Utilizing_CNN_with_Optimized_Hyperparameters

The earlier detection and accurate diagnosis of COVID seem to be a global problem. It is difficult to make a large number of testing equipment, but then again, their reliability is relatively poor. Recent research indicates the usefulness of chest x-ray pictures in identifying COVID. This study presents a deep learning algorithm developed from the ground up to categorize as well as confirm the existence of COVID in a set of X-ray imaging data. We designed a CNN architecture from the ground up to retrieve elements from provided X-ray data to categorize them and identify the individual contaminated with COVID. Our strategy may aid in mitigating the consistency issues while working with medical data. In contrast to some other classifying activities with a large enough image database, obtaining large Xray datasets for this classification job is challenging. So, we applied multiple data enhancement techniques to maximize the accurateness, achieving a significant accuracy of 97.75 percent.

### Table of Contents

(1) Dataset Description

(2) Preprocessing & Augmentation

(3) Proposed Architecture

(4) Tech/Stacks

(5) Result 

(6) Conclusion

### Dataset Description

Any deep neural architecture work needs a vast amount of data as input. An appropriate cluster of data aids in better analyzing a Deep learning challenge. We gathered data for our issue set mostly from three separate and well-known web sources. The following public datasets were used in this study: 

(1) COVID-19 Radiography Database [9], 
(2) Curated Dataset for COVID-19 [10], and 
(3) NIH Chest X-ray Multiclassification Dataset [11].

The Database [9] is used to compile chest X-rays of COVID-19 positive pictures and normal images. Images of bacterial pneumonia are sourced from the Dataset [10]. Furthermore, photos of pneumothorax are obtained from the Dataset [11]. The subset of X-ray imagery is built using the datasets to identify and assess the efficiency of the suggested CNN model architecture. 

