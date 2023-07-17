# Prognostication in Agriculture using Neural Networks
## A forecasting study based on BigData methods through the example of pesticide sales. Predictions are based on linear regression and two neural networks frameworks, to obtain statistics and compare results.
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white)

The basic methods of forecasting using Linear Regression and Neural Networks were used. This consists of three stages:
* Download and preliminary analysis of data
* Forecasting
* Artificial Neural Networks

The first stage downloads data and pre-prepares it for the analysis:
* downloading data
* changing the data types of columns
* grouping data
* DataSet transformation

At the stage of forecasting, begins the building and fitting of models, as well as the automation of statistical information calculation, in particular:
* hypothesis creation
* splitting the DataSet into training and test sets
* creating a linear model using sklearn
* calculation of basic statistical indicators
* creating a linear model using statsmodels

At the stage of Artificial Neural Networks, begins the building and fitting of models based on Artificial Intelligence:
* creating a linear model using Scikit-learn
* creating a linear model using keras

______
### Basic Tools

* Python - basic level
* [Pandas](https://pandas.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01)
* [SeaBorn](https://seaborn.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01)
* Statistics - basic level
* [Scikit-learn](https://scikit-learn.org/stable/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01)
* [keras](https://keras.io/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01)

________
### Libraries Used
* Intel Scikit-Learn
* Conda-Forge TensorFlow
* Conda-Forge Pycountry (Deprecated in Python 3.10 onwards)
* Conda-Forge keras
* Pandas
* Numpy

________
### Dataset
The Dataset being used here is `Pesticide sales`, referring to sales of pesticides in Europe between 2011-2012 on the Eurostat website. Eurostat has a policy of encouraging the free re-use of its data, both for non-commercial and commercial purposes. 
[Check out the dataset!](https://pandas.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01](https://ec.europa.eu/eurostat/databrowser/view/AEI_FM_SALPEST09__custom_1145078/default/table?lang=enhttps:%2F%2Fec.europa.eu%2Feurostat%2Fdatabrowser%2Fview%2FAEI_FM_SALPEST09__custom_1145078%2Fdefault%2Ftable%3Flang%3Den)https://ec.europa.eu/eurostat/databrowser/view/AEI_FM_SALPEST09__custom_1145078/default/table?lang=enhttps:%2F%2Fec.europa.eu%2Feurostat%2Fdatabrowser%2Fview%2FAEI_FM_SALPEST09__custom_1145078%2Fdefault%2Ftable%3Flang%3Den)
_________________
## Takeaways

In my project, I observed that the Artificial Neural Network (ANN) produced superior results compared to other models. The ANN demonstrated higher accuracy and better performance in forecasting Fungicides and bactericides sales.

The success of the ANN can be attributed to its ability to capture complex non-linear relationships within the data, which proved beneficial in this scenario where the dependence between variables was non-linear. This allowed the ANN to make more accurate predictions and outperform other models.

By leveraging the power of neural networks, I was able to enhance the forecasting capabilities of my project and achieve more reliable and precise predictions for agricultural sales data. The improved results of the ANN reaffirmed its effectiveness in handling complex data patterns and underlined its value in the field of agricultural prognostication.
_________________
## Final Plots and Graphs

### Loss and Validation loss dynamics

![image](https://github.com/probablyabdullah/Prognostication-in-Agriculture-using-Neural-Networks/assets/79295754/c7c9ab6b-346c-43b2-b5cb-69851d80cba9)

### Predictions of the training set and the test set using the fitted Neural Network. After inverse normalisation of data and linear regrassion, we get the following

![image](https://github.com/probablyabdullah/Prognostication-in-Agriculture-using-Neural-Networks/assets/79295754/0f5fbdab-cf6f-4914-aa70-24891bde88c9)


![image](https://github.com/probablyabdullah/Prognostication-in-Agriculture-using-Neural-Networks/assets/79295754/e2cee966-830b-483f-bfc9-a4b5927c33e0)


![Screenshot (1151)](https://github.com/probablyabdullah/Prognostication-in-Agriculture-using-Neural-Networks/assets/79295754/4439cdaa-0709-42ee-953c-aa763f81e9ec)

__________________________
### Credits
This project was created in a guided project form with the framework created by Dr.Yaroslav Vyklyuk, prof., PhD., DrSc.<br>
Find more such guided projects on [cognitiveclass.ai](https://cognitiveclass.ai/courses/course-v1:IBM+GPXX04P5EN+v1).<br>
Copyright &copy; 2020 IBM Corporation. This notebook and its source code are released under the terms of the `MIT License`
