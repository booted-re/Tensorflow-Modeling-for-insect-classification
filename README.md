# Tensorflow Modeling for insect classification
Insect Classification CNN focused on visual similiarities

[Project Video Link](https://youtu.be/qgNHhiA4_YY)

Source: https://www.kaggle.com/datasets/jerzydziewierz/bee-vs-wasp

## Project Goal
1. Modeling to classify similar-looking insects
2. Further tuning to distinguish natural mimicry
(e.g. Bartesian, and Mullerian mimicries)
3. Model development to identify resembling objects other than insects 

## Dataset
Hand-curated, close-up photos of Bee/Wasp/Other_Insect/Other_Object

## Data Preprocessing and Modeling
1.Image Resized to 250px and normalized.
2. Modeling
ResNet50 with Early Stopping and Learning Rate Decay
