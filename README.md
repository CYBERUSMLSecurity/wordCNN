# WordCNN Reproduction Project
## This is a reproduction using the pre-trained model distilbert-base-uncased-rotten-tomatoes and over the dataset rotten_tomatoes over the training set sizes and comparing over the Baseline methods, Embedding and EasyDataAugmentation dataaugmentation methods.


This project is a reproduction of the WordCNN model for text classification tasks, focusing on using pre-trained models such as `distilbert-base-uncased-rotten-tomatoes` over the Rotten Tomatoes dataset. We compare different augmentation methods and evaluate their performance.

## Project Files

### 1. **WordCNN Colab.ipynb**
   - **Purpose:** This notebook serves as the initial prototype for reproducing the WordCNN model.  
   - **Details:** 
     - It installs necessary libraries like `textattack` and sets up the environment in Google Colab. 
     - The notebook experiments with smaller training set sizes and tests augmentation methods like **Embedding** and **EasyDataAugmentation**.  
     - **Why Important:** This is our first step in setting up the workflow for the project.

### 2. **final_wordCNN_1_.ipynb**
   - **Purpose:** This notebook refines the initial experiments from the prototype and includes a more robust training setup.  
   - **Details:** 
     - It trains the WordCNN model on the Rotten Tomatoes dataset using different augmentation methods. 
     - The notebook explores improved configurations for embedding-based and Easy Data Augmentation techniques.  
     - **Why Important:** It builds upon the prototype and works towards achieving reliable reproduction results.

### 3. **Final Word CNN.ipynb**
   - **Purpose:** This is the final notebook where we aimed to complete the reproduction experiments with the pre-trained model.
   - **Details:** 
     - It attempts to train the `distilbert-base-uncased-rotten-tomatoes` model with varying training set sizes and augmentation methods.  
     - During the process, we encountered **memory failure**, highlighting limitations in our hardware setup for this notebook.  
     - **Why Important:** This notebook represents our final attempt to complete the reproduction process, identifying issues and room for improvement.

## Methodology Overview

- We utilize the **Rotten Tomatoes dataset** to benchmark our models.
- Training configurations involve:
  - Baseline methods (no augmentation).
  - **Embedding Augmentation**: Adds synonyms to sentences to increase variability.
  - **Easy Data Augmentation**: Combines techniques like synonym replacement, random insertion, and more.

## Summary

This project explores the use of **pre-trained models** with **data augmentation techniques** to enhance text classification performance. Despite challenges like memory constraints, we successfully implemented and compared various augmentation strategies.
