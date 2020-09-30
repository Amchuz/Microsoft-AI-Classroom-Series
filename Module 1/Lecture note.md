# Artificial Intelligence
<br/>
&nbsp;&nbsp;&nbsp;&nbsp; AI can be defined as the theory and development of computer to be able to perform tasks normally requiring human intelligence such as :
  
  
- Visual perception 
- Speech Recognition
- Decision-Making
- Translation between languages etc.
<br/>
<details>
  <summary><b>Want to go through some history ?</b></summary>
  <img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/History1.png">
  <img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/History2.png">
 
</details>
<br/><br/>

# Data Science Life Cycle
<br/>
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/ds%20lifecycle.png" height=500 width=620>
<br/>

### Business Understanding
  
- **Goals :**
  
  - Specify the key variables that are to serve as the model targets and whose related metrics are used determine the success of the project.
  - Identify the relevant data sources that the business has access to or needs to obtain.

- **There are two main tasks addressed in this stage :**
  - **Define objectives :** Work with your customer and other stakeholders to understand and identify the business problems. Formulate questions that define the business goals that the data science techniques can target.
  - **Identify data sources :** Find the relevant data that helps you answer the questions that define the objectives of the project.
  
### Data acquisition and understanding
  
- **Goals :**
  
  - Produce a clean, high-quality data set whose relationship to the target variables is understood. Locate the data set in the appropriate analytics environment so you are ready to model.
  - Develop a solution architecture of the data pipeline that refreshes and scores the data regularly.
  
- **There are three main tasks addressed in this stage :**
  - **Ingest the data** into the target analytic environment.
  - **Explore the data** to determine if the data quality is adequate to answer the question.
  - **Set up a data pipeline** to score new or regularly refreshed data.
  
### Modelling
  
- **Goals :**
  
  - Determine the optimal data features for the machine-learning model.
  - Create an informative machine-learning model that predicts the target most accurately.
  - Create a machine-learning model that's suitable for production.
  
- **There are three main tasks addressed in this stage :**
  
  - **Feature engineering :** Create data features from the raw data to facilitate model training.
  - **Model training :** Find the model that answers the question most accurately by comparing their success metrics.
  - Determine if your model is **suitable for production.**
  
### Deployment
  
- **Goal :**
  
  - Deploy models with a data pipeline to a production or production-like environment for final user acceptance.

- **The main task addressed in this stage :**
  
  - **Operationalize the model :** Deploy the model and pipeline to a production or production-like environment for application consumption.
  
### Customer acceptance
  
- **Goal :**
  
  - **Finalize project deliverables :** Confirm that the pipeline, the model, and their deployment in a production environment satisfy the customer's objectives.
  
- **There are two main tasks addressed in this stage :**
  
  - **System validation :** Confirm that the deployed model and pipeline meet the customer's needs.
  - **Project hand-off :** Hand the project off to the entity that's going to run the system in production.
<br/>
  
# Data Nomenclature
<br/>
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/microsoft%20data.png">
  
- **Attriutes** : Theses are also known as variables. They define the characteristics of data.
- **Target Attribute** : Also known as Label. It is the value we are trying to predict. The output of the model.
  
### Datasets will be divided into 3:
  
- **Training Set :** 
  - Majority of data
  - Given to algorithm to learn from it.
  - Ususally 70-80% of data.
    
- **Validation Set :**
  - Check whether the model does a good job or not.
  - Usually 10-20% of data
  
- **Test Set :**
  - Sometimes hand-picked.
  - Or 10-20% of data.
  
### Model (Don't mind the ticks :sweat_smile: )
  
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/Model.png">
<br />

# Types of Learning Algorithms
  
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/algorithms.png">
  
## 1. Supervised Learning Algorithms
  
- Used to predict target attribute/label.
- Needs dataset with target attribute values.
- Supervised learning model can be further classified into :
  - Classification Models :
    - Type of problems where the outputs variable is a category such as red, blue or disease or undisease.
  -Regression Models :
    - Type of problems where output variable is a real number.
  
## 2. Unsupervised Learning Algorithms
  
- Dose not have dataset with target attribute values.
- Used to find pattern among the input dataset.
- Unsupervised Learning can be further grouped into :
  - Clustering :
    - A clustering problem is where you want to discover the inherent groupings in the data such as grouping customers by purchasing behaviour.
  - Association : 
    - An association rule learning problem is where you want to discover rules that describe large portions of your data, such as people that buy X also tend to buy Y.
  
## 3. Semi-Supervised  Learning Algorithms
  
- Semi-Supervised models are used in the cases where some of the input data is labelled and some of them are not. 
- Example : Photo archive where only some of the images are labelled.
<br />
  
# Algorithms
  
- Regression (Supervised)
- Clustering (Unsupervised)
  - K-Means
- Classification (Supervised)
  -Decision Trees
- Neural Network
<br />
  
## 1. Regression
  
- Derived from statistics.
- Used in Machine Learning
- Calculate values of dependent variable (Target) based on independent variable(s)
- Example : Sale/growth forecast, financial portfolio prediction, credit standing of policy holders by insurance companies and real estate price prediction.
  
### Linear Regression
  
- Goal : Draw a straight line that best fits all the data points on the scattterplot.
- Best fit line also known as regression line.
- Regression line must have minimum distance from all data points (least amount of error)
  
<img src="https://nextjournal.com/data/QmfPuPp4V74FyvTTojMj6ix9T8Skj1ji4GhX5Pr6zK8w4N?filename=linear-regression.png&content-type=image/png">
  
- First degree curve
- y=mx+c where m and c are constants.
