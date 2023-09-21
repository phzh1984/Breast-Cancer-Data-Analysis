# Breast Cancer Prediction

Project Overview

Breast Cancer Prediction is a classification task aimed at predicting the diagnosis of a breast mass as either malignant or benign. This project utilizes a dataset comprising features computed from digitized images of fine needle aspirates (FNA) of breast masses. These features describe various characteristics of cell nuclei present in the image, providing quantitative measurements for assessing cell nucleus characteristics and aiding in the early detection and diagnosis of breast cancer.

Dataset Information

The dataset contains the following information for each instance:

ID number: A unique identifier for each sample.

Diagnosis: The target variable indicating the diagnosis, where 'M' represents malignant and 'B' represents benign.

For each cell nucleus, ten real-valued features are computed, which include:

Radius: The mean distance from the center to points on the perimeter of the nucleus.

Texture: The standard deviation of gray-scale values in the nucleus.

Perimeter: The perimeter of the nucleus.

Area: The area of the nucleus.

Smoothness: A measure of local variation in radius lengths.

Compactness: Computed as the square of the perimeter divided by the area minus 1.0.

Concavity: Describes the severity of concave portions of the nucleus contour.

Concave points: Represents the number of concave portions of the nucleus contour.

Symmetry: Measures the symmetry of the nucleus.

Fractal dimension: This feature approximates the "coastline" of the nucleus, using the concept of fractal geometry.

Project Goals

The primary objective of this project is to develop a predictive model using machine learning techniques that can accurately classify breast masses as malignant or benign based on the provided features. Early detection and diagnosis of breast cancer can greatly impact patient outcomes, and this predictive model can play a vital role in assisting medical professionals.


Model Building

In this project, you'll find a machine learning model-building process where various classification algorithms are applied and evaluated to predict breast cancer diagnosis. The evaluation metrics include accuracy, precision, recall, F1-score, and ROC-AUC.

Conclusion

This project aims to contribute to early breast cancer detection by providing a machine-learning model that can assist in classifying breast masses as malignant or benign. The insights gained from this analysis can be valuable for medical professionals and researchers in the field of breast cancer diagnosis.
