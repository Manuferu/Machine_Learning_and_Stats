# Machine_Learning_and_Stats
Material under the Machine LEarning and Statistics module for the Higher superior Diploma in Data Analytics - GMIT

In this project, it is contained two jupyer notebooks:

## scikit-learn.ipynb:

The aim of this notebook is to go through the scikit-learn by seeing an overview of the library and trying three different algorithms. The idea is to show how to code those algorithms, our propouse was far to be give an accurate analysis.

within the first section, one of the build in datasets (called wine dataset [1]) has been used for demonstrations. This dataset has the advantage that has been split already in data and target, making the clean up part much more straightforward.

In the second part, it has been picked an external dataset from Forest Observation Systems [2]. The dataset is presented in tabular format (csv). It contains sample information about several variables such wood density, above ground carbon, altitude, forest status and much more. 

**since it was possible to access the dataset from the link directly**, it is not incorporated within the github directory. 

The three algorithms demonstrated are : **LiniarRegression**, **Support Vector Machine**, **MultiLayer Perceptron Classifier**

## scipy.stats.ipynb:

There are two main parts differenciated in this notebook. A first part, following the same structure as the one above, follows a description of some functionalities of the scipy.stats library with some examples and playing a bit with the different attributes in the variables to see how what is the output coming out of those random tests.

The second part of the notebooks makes the ANOVA test using the Wine Quality dataset[3]. Even though the dataset contains 2 tab datasets (one for white and the other one for red wine), I have performed the ANOVA test just using the red wine dataset. All the dataset is within the **WineQualityDataset_ANOVA_** folder in this repository.

## References:

[1] Lichman, M. (2013). UCI Machine Learning Repository [https://archive.ics.uci.edu/ml]. Irvine, CA: University of California, School of Information and Computer Science.

[2] Schepaschenko, D., Chave, J., Phillips, O. L., Lewis, S. L., Davies, S. J., Réjou-Méchain, M., ... & Labrière, N. (2019). The Forest Observation System, building a global reference dataset for remote sensing of forest biomass. Scientific data, 6(1), 1-11

[3] P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.