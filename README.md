# Artificial Neural Networks and Deep Learning Challenges (2025/2026)

This repository contains the Jupyter Notebooks and solutions developed by the **Harry Plotter** team for the challenges of the **Artificial Neural Networks and Deep Learning** course, Academic Year **2025/2026**.

The team is composed by
**Leonardo Bertolani**,
**Samuele Tondelli**, 
**Giulio Mantovi**, 
**Riccardo Masetti**.


## Challenge 1: Pirate Pain Challenge

### **Description**

The first challenge focused on the classification of multivariate time series. Each participant received a collection of multivariate time series, where every single data sequence was composed of 161 time steps. The objective was to correctly classify the pain level associated to each pirate.

### **Notebooks & Files**

* `Report.pdf`: Contains the description of our work, specifically our data processing and architectural choiches.
* `notebooks/`: This folder contains all the notebooks related to the 1st challenge. 


### **Results**

**Achieved Metric:** 0.96044 F1-Score.


## Challenge 2: The Grumpy Doctogres Challenge

### **Description**

The second challenge involves the classification of diseased human tissue samples. The dataset consists of 1,272 images of microscopic tissue morphology, each paired with a binary mask. The objective is to correctly predict the molecular subtype of the tissue: Luminal A, Luminal B, HER2(+), or Triple Negative.
A significant part of the work involved data preprocessing, as the creators included many outliers and duplicate images (with different labels) within the training dataset.

### **Notebooks & Files**

* `Report.pdf`: Contains the description of our work for the second challenge.
* `notebooks/`: This folder contains all the notebooks related to the second challenge.

### **Results**

**Achieved Metric:** 0.40009 F1-Score. While the score was not high, this was because the image resolution was insufficient to capture the details necessary to distinguish between the different types of pathologies. This is also why no participant in the competition succeeded in exceeding an F1-score of 0.47.