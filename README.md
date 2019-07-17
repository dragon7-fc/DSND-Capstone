# Create a Customer Segmentation Report for Arvato Financial Solutions

[//]: # (Image References)

[image1]: ./imgs/missing_value.png "missing_value"
[image2]: ./imgs/formatit_missing_value.png "formatit_missing_value"
[image3]: ./imgs/categorical.png "categorical"
[image4]: ./imgs/quantitative.png "quantitative"
[image5]: ./imgs/cap_outlier.png "cap_outlier"
[image6]: ./imgs/drop.png "drop"
[image7]: ./imgs/pca.png "pca"
[image8]: ./imgs/kmeans.png "kmeans"
[image9]: ./imgs/cluster.png "cluster"
[image10]: ./imgs/diff_feature.png "diff_feature"
[image11]: ./imgs/train.png "train"
[image12]: ./imgs/model.png "model"
[image13]: ./imgs/xgboost.png "xgboost"




### Table of Contents

1. [Introduction](#introduction)
1. [Installation](#installation)
1. [File Descriptions](#files)
1. [Results](#results)
1. [Terms & Conditions](#terms)


### Introduction <a name="introduction"></a>:
The project has three major steps: the customer segmentation report, the supervised learning model, and the Kaggle Competition.

1. Customer Segmentation Report
This section will be similar to the corresponding project in Term 1 of the program, but the datasets now include more features that you can potentially use. You'll begin the project by using unsupervised learning methods to analyze attributes of established customers and the general population in order to create customer segments.

2. Supervised Learning Model
You'll have access to a third dataset with attributes from targets of a mail order campaign. You'll use the previous analysis to build a machine learning model that predicts whether or not each individual will respond to the campaign.

3. Kaggle Competition
Once you've chosen a model, you'll use it to make predictions on the campaign data as part of a Kaggle Competition. You'll rank the individuals by how likely they are to convert to being a customer, and see how your modeling skills measure up against your fellow students.


### Installation <a name="installation"></a>:
Below are some libraries we used.
* Python 3.6.8
* numpy 1.16.4
* pandas 0.24.2
* matplotlib 3.0.2
* seaborn 0.9.0
* scikit-learn 0.21.2
* xgboost 0.90
* ipython 6.1.0
* ipython-genutils 0.2.0
* jupyter-client 5.1.0
* jupyter-console 5.2.0
* jupyter-core 4.3.0
* jupyterlab 0.35.6
* jupyterlab-launcher 0.4.0
* jupyterlab-server 0.2.0

Or you can run below command to setup the environment.
```
    conda create --name arvato-project python=3.6
	source activate arvato-project
	pip install -r requirements/requirements.txt
```


### File Descriptions <a name="files"></a>:
```
- terms_and_conditions
|- terms_completed.md
|- terms.md
|- terms.pdf
- Arvato Project Workbook.ipynb
- Arvato Project Workbook.html
- Project Rubric.pdf
- requirements.txt
- README.md
```


### Results <a name="results"></a>:

* Data Preprocessing
    * missing value distribution 

    ![alt text][image1]

    * missing value distribution after change unknown value to NA

    ![alt text][image2]

    * categorical feature

    ![alt text][image3]

    * quantitative feature

    ![alt text][image4]

    * quantitative feature after log transform and outlier caping

    ![alt text][image5]

    * drop

    ![alt text][image6]

* Customer Segmentation Report
    * PCA

    ![alt text][image7]

    * KMeans

    ![alt text][image8]

    * cluster

    ![alt text][image9]

    * feature difference

    ![alt text][image10]

* Supervised Learning Model

    * data distribution

    ![alt text][image11]

    * model selection

    ![alt text][image12]

    * XGBoost

    ![alt text][image13]


The main findings of the code can be found at the post available [here]().

### Terms & Conditions <a name="terms"></a>:
In addition to Udacity's Terms of Use and other policies, your downloading and use of the AZ Direct GmbH data solely for use in the Unsupervised Learning and Bertelsmann Capstone projects are governed by the following additional terms and conditions. The big takeaways:

1. You agree to AZ Direct GmbH's General Terms provided below and that you only have the right to download and use the AZ Direct GmbH data solely to complete the data mining task which is part of the Unsupervised Learning and Bertelsmann Capstone projects for the Udacity Data Science Nanodegree program.

1. You are prohibited from using the AZ Direct GmbH data in any other context.

1. You are also required and hereby represent and warrant that you will delete any and all data you downloaded within 2 weeks after your completion of the Unsupervised Learning and Bertelsmann Capstone projects and the program.

1. If you do not agree to these additional terms, you will not be allowed to access the data for this project.
The full terms are provided in the workspace below. You will then be asked in the next workspace to agree to these terms before gaining access to the project, which you may also choose to download if you would like to read in full the terms.
