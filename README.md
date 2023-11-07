# Measuring Pelican Horn Sizes using Image Detection: Insights into Seasonal Dynamics of Pelican Horn Growth

This repository contains the ibynb file and link to the data for a research project on measuring pelican horn sizes using image detection. The project aims to shed light on the dynamic patterns of pelican horn growth during their critical breeding season using deep learning techniques.

## Dataset

The dataset used in this project consists of more than 4000 pictures of individual pelicans, focusing on their beaks and horns. We labeled around 150 individual pelicans and used YOLO to iteratively train a model for precise detection of first the pelican , followed by the beak and finally the horn. We then extracted all the necessary data from the detected pelicans and calculated the area ratio between beaks and horns for every picture. For the data from March to November, we calculated the average of these ratios for each day.

## Results

The resulting dataset was used to construct a graphical representation, featuring dates on the x-axis and the average weighted beak-to-horn area ratio on the y-axis. Through this research, we aim to shed light on the dynamic patterns of pelican horn growth during their critical breeding season.

## Code

The code used in this project was written in Python and utilized several libraries and tools, including:

- Pytesseract
- OpenCV
- Albumentations
- Matplotlib
- NumPy
- Ultralytics YOLO
- Torch

We used YOLO and Roboflow for image detection and processing, and Python libraries such as Pytesseract, OpenCV, Albumentations, Matplotlib, NumPy, Ultralytics YOLO, and Torch for data extraction, analysis, and visualization.

The code used to train the neural network and analyze the data is available in this repository.

## Authors

- Chhimi
- Yuhao
