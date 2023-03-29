![Ciencias_Logo_Azul-01](https://user-images.githubusercontent.com/106987072/228209396-a8737601-f28f-486e-8566-918709663369.png)


# Data Mining
This repository encompasses the projects developed for the Data Mining course, which aimed to familiarize students with Machine Learning and Pattern Recognition in the context of Big Data.


#### Team:
- Alexandre Sobreira
- André Dias
- Tiago Rodrigues

#### Professor: 
- André Falcão


## First Home Assignment - Dimensionality Reduction and Supervised Learning in Data Mining
This home assignment focused on dimensionality reduction through Principal Component Analysis (PCA) and Single Value Decomposition (SVD) and the utilization of basic machine learning models for classification and regression tasks in a Data Mining perspective.

### Models used:
**Regression:** Linear Regression and Decision Tree Regressors

**Classification:** Naïve Bayes and Decision Tree Classifiers

### Data:
The data corresponds to the [Superconductivty Data](https://archive-beta.ics.uci.edu/dataset/464/superconductivty+data), which contains two files: 
- train.csv contains 81 features extracted from 21263 superconductors along with the critical temperature in the 82nd column
- unique_m.csv contains the chemical formula broken up for all the 21263 superconductors from the train.csv file.  The last two columns have the critical temperature and chemical formula.

### Project Objectives:
- Perform dimensionality reduction (PCA or SVD) and analize the data
- Create a Regression and classification model comparing the performance obtained using the full dataset and the projection of the full data in a smaller feature space. For classication categorize the continous data into the following classes: 
  - VeryLow - critical_temp in [0.0, 1.0,[
  - Low - critical_temp in [1.0, 5.0,[
  - Medium - critical_temp in [5.0, 20.0,[
  - High - critical_temp in [20.0, 100.0,[
  - VeryHigh - critical_temp in >= 100.00}
