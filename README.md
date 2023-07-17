# Prognostication in Agriculture using Neural Networks
## A forecasting study based on BigData methods through the example of pesticide sales. Predictions are based on linear regression and two neural networks frameworks, to obtain statistics and compare results.

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
### Libraries Used 
The Dataset being used here is `Pesticide sales`, referring to sales of pesticides in Europe between 2011-2012 on the Eurostat website. Eurostat has a policy of encouraging the free re-use of its data, both for non-commercial and commercial purposes. 
[Check out the dataset!](https://pandas.pydata.org/?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-Channel-SkillsNetworkGuidedProjectsdatascienceinagricultureprognosticationusingbyneuralnetwork466-2022-01-01](https://ec.europa.eu/eurostat/databrowser/view/AEI_FM_SALPEST09__custom_1145078/default/table?lang=enhttps:%2F%2Fec.europa.eu%2Feurostat%2Fdatabrowser%2Fview%2FAEI_FM_SALPEST09__custom_1145078%2Fdefault%2Ftable%3Flang%3Den)https://ec.europa.eu/eurostat/databrowser/view/AEI_FM_SALPEST09__custom_1145078/default/table?lang=enhttps:%2F%2Fec.europa.eu%2Feurostat%2Fdatabrowser%2Fview%2FAEI_FM_SALPEST09__custom_1145078%2Fdefault%2Ftable%3Flang%3Den)
