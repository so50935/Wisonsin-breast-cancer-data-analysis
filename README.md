![IS777_PROJECT_WRRP_PRESENTATION](https://user-images.githubusercontent.com/57547960/92500044-9abd3380-f1ca-11ea-8cb5-1fabda4df064.png)

# Wisonsin-breast-cancer-data-analysis
Breast cancer being one of the major cause of death among women, if tumor is not detected in early stages sometimes it is difficult to detect the tumor therefore, I am trying to implement machine learning algorithm to detect breast cancer for the well being of mankind.

# INTRODUCTION
Machine learning is a method of data analysis that provide machines i.e. computers the ability to build analytical model.
So basically it is a branch of AI which is based on idea that systems can learn from he available data, identify patterns and also make decision with very less human help.
Machine learning incorporates a large set of statistical techniques.
With the help of these techniques we can create models with old data and detect patterns from noisy and massive data set.
We have used various statistical learning methods for cancer prediction and prognosis.
The objective is to present a report on breast cancer where we took advantage of those available technological advancements to develop prediction models for breast cancer survivability.

Breast cancer is the most common malignancy in women, accounting for almost 1 in 3 cancers diagnosed among women in the United States, and is the second leading cause of death for women from cancer. Breast cancer occurs as a result of irregular breast tissue cell growth, commonly known as a tumor. A tumor does not mean cancer-tumors can be either benign (not cancerous), pre-malignant (pre-cancerous), or cancerous. Tests including MRI, mammogram, ultrasound, and biopsy are widely used to detect performed breast cancer. We can create a classifier that can help diagnose patients and predict the likelihood of a breast cancer.

# Dataset 1
The Breast Cancer Wisconsin (Original) dataset from UCI machine learning repository is a classification dataset, which records the measurements for breast cancer cases.
There are two classes, benign and malignant. The dimensionality of data is 9. Each variable except for the first was converted into 11 primitive numerical attributes with values ranging from 0 through 10. There are 16 missing attribute values. This data frame has 699 observations on 11 variables, one being a character variable, 9 being ordered or nominal, and 1 target class.
The objective is to identify each of a number of benign or malignant classes. Samples arrive periodically as Dr. Wolberg reports his clinical cases. The database therefore reflects this chronological grouping of the data.
 This grouping information appears immediately below, having been removed from the data itself.
 Id Sample code number
 Cl.thickness Clump Thickness
 Cell.size Uniformity of Cell Size
 Cell.shape Uniformity of Cell Shape
 Marg.adhesion Marginal Adhesion
 Epith.c.size Single Epithelial Cell Size
 Bare.nuclei Bare Nuclei
 Bl.cromatin Bland Chromatin
 Normal.nucleoli Normal Nucleoli
 Mitoses Mitoses
 Class Class

# Dataset 2
The Breast Cancer Wisconsin (Diagnostic) dataset from UCI machine learning repository is a classification dataset, which records the measurements for breast cancer cases.
As data set 1 in this data set as well there are two classes, benign and malignant. A data frame with 569 observations on 11 variables. In this dataset there are no missing values.
The features from the data set describe characteristics of the cell nuclei and are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. As described in UCI Machine Learning Repository, the attribute information are:
1. ID number
2. Diagnosis (M = malignant, B = benign)
3. 32 Ten real-valued features are computed for each cell nucleus
 Radius (mean of distances from centre to points on the perimeter)
 Texture (standard deviation of grey-scale values)
 Perimeter
 Area
 Smoothness (local variation in radius lengths)
 Compactness (perimeter^2 / area - 1.0)
 Concavity (severity of concave portions of the contour)
 Concave points (number of concave portions of the contour)
 Symmetry
 Fractal dimension ("coastline approximation" - 1)
