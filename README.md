# BankNote_Authentication


Dataset Overview
This dataset is about distinguishing genuine and forged banknotes. Data were extracted from images that were taken from genuine and forged banknote-like specimens. For digitization, an industrial camera usually used for print inspection was used. The final images have 400x 400 pixels. Due to the object lens and distance to the investigated object gray-scale pictures with a resolution of about 660 dpi were gained. A Wavelet Transform tool was used to extract features from these images.

Attribute Information
V1. variance of Wavelet Transformed image (continuous)
V2. skewness of Wavelet Transformed image (continuous)
V3. curtosis of Wavelet Transformed image (continuous)
V4. entropy of image (continuous)
Data source: https://www.openml.org/d/1462


The purpose of this project is to build a K-Means clusterng model to detect if the banknote is genuine or forged so that people don't need to conduct inspection
