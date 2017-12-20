# DSX Local Workshop
In this workshop you will learn how to develop and deploy applications in DSX Local. The workshop has been divided into several stand-alone parts for those who are interested in a certain development tool or a certain deployment task. For example, you can complete just a Jupyter lab, or an SPSS Modeler lab, or a Batch Scoring in DSX lab.  

## About this repository
This repository contains several lab subfolders. Some labs include notebooks and data, while others have additional instructions that are located in the *Lab Instructions* folder. 

## Prerequisites
1. Knowledge of analytics. These labs do not teach you the basics of analytics or how to implement analytics in R, Python and SPSS. The purpose of this workshop is to provide hands-on experience with analytics tools and deployment functions in DSX. 
2. To run this workshop you need an instance of DSX Local. **Please note that while most code is the same between DSX Local and DSX Cloud, the notebooks included in this project will work in DSX Local only**
3. Download and unzip this [this repository](https://codeload.github.com/elenalowery/DSX_Local_Workshop/zip/master). Unzip the repository only, not files in subfolders. 

### Setting up lab projects in DSX Local
1. Rename **DSX_Local_Workshop.zip** located in **DSX_Local_Projects** folder of the unzipped repository to a unique name, for example, add your initials.    *Note: Project names in DSX Local cluster must be unique. When we create a project "from file", the project name is inherited from the file name* 
2. Log in to DSX Local
3. Select "Create New Project" and select "From File"
4. Browse to the .zip file
5. After the project has been imported, follow instructions in the notebooks.
![ProjectFromFile](/img/CreateProjectFromFile.JPG?raw=true)

## Lab 1: Improve customer retention (SparkML models in Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn** *Jupyter* notebook
3. Follow instructions in the notebook
4. **TODO: Add model builder**

## Lab 2: Improve operational efficiency (Scikit-learn and SparkML models in Jupyter/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **CreditCardDefault** notebook
3. Follow instructions in the notebook

## Lab 3: Improve customer retention (SparkML models in Zeppelin/Python)
1. Open the project you just created. 
2. Navigate to **Assets** view and open **TelcoChurn** *Zeppelin* notebook
3. Follow instructions in the notebook

## Lab 4: Data Science for the Automotive Industry (R models in Jupyter and Shiny)
1. Follow instructions in the **R and Shiny Lab.pdf** in the **Lab Instructions** folder of the unzipped repository. 

## Lab 5: Improve customer retention/Fraud Prevention (SPSS Modeler in DSX)
1. Follow instructions in the **SPSS Modeler in DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

## Lab 6: Batch deployment of analytics (Batch Scoring in DSX)
1. Follow instructions in the **Batch Scoring in DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

## Lab 7: DSX - a deployment platform for different types of models (PMML in DSX)
1. Follow instructions in the **PMML in DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

## Lab 8: DSX - a platform that supports analytics application lifecycle (Model Evaluation in DSX)
1. Follow instructions in the **Model Evaluation in DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

## Lab 9: Data Access in DSX (databases and Hadoop)
1. Follow instructions in the **Data Access in DSX.pdf** document in the **Lab Instructions** folder of the unzipped repository. 

## Lab 10: Remote Spark Execution
1. Follow instructions in the **Remote Spark Execution.pdf** document in the **Lab Instructions** folder of the unzipped repository. 
