# Stellar_Classification
Classifying cosmic entities based on their distinct characteristics and properties into appropriate classes.


## Dataset
This project aims to classify cosmic entities into their appropriate classes using the [Stellar Classification Dataset - SDSS17](https://www.kaggle.com/datasets/fedesoriano/stellar-classification-dataset-sdss17) from Kaggle. The dataset contains observations taken by the [Sloan Digital Sky Survey (SDSS)](https://www.sdss.org/) and provides valuable information about stars, galaxies, and quasars. <br>
The data consists of 100,000 observations of space taken by the SDSS (Sloan Digital Sky Survey). Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy, or quasar.


| # | Feature    | Description                                                     |
|---|------------|-----------------------------------------------------------------|
| 1 | obj_ID     | Object Identifier, uniquely identifies the object in the catalog |
| 2 | alpha      | Right Ascension angle (at J2000 epoch)                           |
| 3 | delta      | Declination angle (at J2000 epoch)                               |
| 4 | u          | Ultraviolet filter in the photometric system                    |
| 5 | g          | Green filter in the photometric system                          |
| 6 | r          | Red filter in the photometric system                            |
| 7 | i          | Near Infrared filter in the photometric system                  |
| 8 | z          | Infrared filter in the photometric system                       |
| 9 | run_ID     | Run Number used to identify the specific scan                   |
| 10 | rereun_ID | Rerun Number to specify how the image was processed             |
| 11 | cam_col    | Camera column to identify the scanline within the run           |
| 12 | field_ID   | Field number to identify each field                             |
| 13 | spec_obj_ID | Unique ID used for optical spectroscopic objects                |
| 14 | class      | Object class (galaxy, star, or quasar object)                   |
| 15 | redshift   | Redshift value based on the increase in wavelength              |
| 16 | plate      | Plate ID, identifies each plate in SDSS                         |
| 17 | MJD        | Modified Julian Date, indicates when the SDSS data was taken    |
| 18 | fiber_ID   | Fiber ID that identifies the fiber pointing the light in each observation |

## Classification
By employing machine learning techniques, we will develop a classification model that can accurately predict the class of new cosmic entities based on their features. Through feature engineering, exploratory data analysis, and the implementation of various classification algorithms, we will strive to achieve high-performance predictions. The successful outcome of this project will contribute to our understanding of the universe and aid in astronomical research.

The algorithms which I've used are:-
```
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Gaussian Naive Bayes (GaussianNB)
- Random Forest 
- XGBoost
```
I will compare the performance of these algorithms based on their recall scores to select the best-performing one. For certain algorithms with hyperparameters that can take on different values, such as the n_neighbors in KNN or the n_estimators in Random Forest, I will evaluate multiple combinations of hyperparameter values.

I will calculate the recall scores for each combination of hyperparameters and select the one with the highest recall score. Once the best-performing hyperparameter value is determined for each algorithm, I will compare the algorithms based on their corresponding best recall scores. This way, I can identify the algorithm that provides the highest accuracy on the given dataset.

## Libraries/concepts used
```
- pandas
- numpy
- matplotlib
- seaborn
- sklearn (scikit-learn)
- Label Encoding
- SMOTE (Synthetic Minority Oversampling Technique)
- Classification algorithms
- Naive Bayes classifier
- Extreme Gradient Boosting
```
