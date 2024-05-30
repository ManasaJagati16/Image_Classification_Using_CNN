# COVID-19 AND PNEUMONIA DETECTION USING CNN

![image](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fs41598-022-27266-9/MediaObjects/41598_2022_27266_Fig1_HTML.png) </br>

## Project Overview

In this project, we've created a dynamic and interactive Jupyter notebook application that detects COVID_19, Pneumonia and normal cases
from a massive dataset of chest X-ray images containing examples of COVID-19 cases, Pneumonia cases and  Normal cases.

## Dataset Sources
[Covid Data](https://www.kaggle.com/datasets/andyczhao/covidx-cxr2/code) </br>  
[Pneumonia Data](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) 

## Key Features

- **Data Collecction and Annotation**: We have collected a comprehensive dataset containing chest X-ray images of COVID-19 and Pneumonia patients and normal cases. We labelled the dataset indicating the class of each image like COVID_19, Pneumonia or Normal.

- **Image Processing**: We have classified the images based on their formats. Removed the duplicates based on image paths and filtered out those rows with invalid paths.

- **Machine Learning Models**: Developed and trained deep learning models, such as CNN to automatically extract features from chest X-ray images and classify them into the three target classes.

- **Model Evaluation and Validation**: Evaluated the model performance using metrics like accuracy, precision, recall, F1 score with three different training dataset batch sizes like 2000, 5000 and 20000 and validated the model splitting the remaning data of each batch into test and validation sets.

## Use Cases

- **Early Detection**: Health care professionals can benefit from early identification of COVID-19 and Pneumonia cases using chest X-ray images for patient management and early intervention.

- **Efficient Triage**: Automation of Chest X-rays classification can speed up the triage procedure and helps to prioritize the cases for further medical evaluation.

- **Resource Optimization**: Improved accuracy in detecting cases of pneumonia and COVID-19, can optimize the distribution of resources in medical environments, especially during pandemics or high demand periods.

## Results
- Test Accuracies
  - Training set of 2000 samples 0.8337
  - Training set of 5000 samples 0.8758
  - Training set of 20000 samples 0.9038
 
- Test Loss
  - Training set of 2000 samples 0.4207
  - Training set of 5000 samples 0.3532
  - Training set of 20000 samples 0.2807


## Requirements

- Pyspark 
- Tensor flow for model building
- matplotlib for visualization
- sklearn for model evaluation
- Jupyter Notebook or Jupyter Lab environment

## Conclusion

Through this project we are able to create a functional and reliable system for automated detection and classification of respiratory conditions from Chest X-ray images, which contributes to improved diagnosis and patient care, particularly for COVID-19 and Pneumonia.
