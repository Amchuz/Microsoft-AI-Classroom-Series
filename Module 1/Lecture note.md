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
  
#### Advantages of Linear Regression :
  
- Simple to understand and implement.
- Based on mathematics.
- Usually much lower training time.
- Continuous value prediction.
  
#### Challenges with Regression :
  
- Cannot handle complicated shapes.
- Too simple for a lot of real world problems.
  
#### Some modern uses of Regression :
  
- Predicting demand.
- Stock price prediction.
- Credit assessment.
  
## 2. Classification 
  
- Classification is used for categorical response values, where the data can be separated into specific "classes".
- Classification is used to predict discreet value output (ie. 0/1, yes/no)
  
### Two-class classification
  
- Predicts between two categories.
- Simple answer
  - Two choice questions
  - Yes/No
  - True/False
  
### Multi-class classification
  
- Predicts between several categories.
- Coamplex answers
  - Questons with multiple possible answers.
  
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/classification%20eg.png">
  
#### Decision Tree
  
- From the given example, the most relevant attribute becomes the root node and using information gain and entropy calculation the rest of the attributes are arranged in an order.
  
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/final%20DT.png">
  
**Advantages of Decision Tree :**
  
- White box, easy to interpret and easy to explain.
- Useful to find the most important attribute.
- They are not affected by outliers,less data cleaning required.
- Once created, can provide fast classification.
  
**Challenges with Decision Tree :**
  
- Works better with discrete valued attributes compaired to continuous valued attributes.
- Requires a lot of prior data.
- Limited to one output without probability.
- Not great at regression.
  
**Some modern uses of decision tree :**
  
- Astronomy : Filtering noise from Hubble Space Telescope.
- Financial analysis : Asserting the attractiveness of stocks.
- Power Systems : Power usage prediction.
- Molecular biology : Analyzing amino acid sequences.
  
## 3. Clustering
  
### K-Means
  
- Select K random points in the n-dimensional space and find points closest to it.
- Data points in the same cluster will be similar to each other.
- Do it many times until least amount of average within cluster distance.
  
<img src="https://static.javatpoint.com/tutorial/machine-learning/images/k-means-clustering-algorithm-in-machine-learning.png">
  
#### Advantages of Clustering :
  
- No need for classified input data.
- No need to have information about attributes.
  
#### Disadvantages of Clustering :
  
- Result can be different for two successive runs.
- Hard to find good means.
- Need to specify number of clusters.
  
#### Some modern uses of K-Means :
  
- E-commerce : Segmenting users based on purchases.
- Credit : Segmenting loan applicants.
- Supermarkets : Finding the right discounts to send to customers.
- Document classification.
  
## 4. Neural Network
  
<img src="https://miro.medium.com/max/610/1*SJPacPhP4KDEB1AdhOFy_Q.png" width=400 height=350>

- A simple neuron :
  
  - Takes the inputs.
  - Calculate the summation of the inputs.
  - Compare it with the threshold being set during the learning stage.
  
<img src="https://www.researchgate.net/profile/Luyen_Bui/publication/279757450/figure/fig4/AS:284614334664740@1444868753578/A-sample-neural-network-in-which-a-rectangle-is-an-input-node-and-a-circle-is-a-neuron.png">
  
- Neurons consist of 3 basic components :
  - Weights
  - Thresholds
  - Activation functions
- Weighting Factors
  - The values w1,w2,..wn are weightsto determine the strenght of the input vector x=[x1,x2..xn]T
- Thresholds
  - The node's internal threshold is the magnitude offset.
- Activation function
  - Performs a mathematical operation on the signal output.
  - Most common are : linear,threshold,S shaped,tangent etc
  - Choice of the function depends on the problem solved by the neural network.

### Advantages of Neural Networks :
  
- Great with even continuous valued attributes.
- Can have thousands of attributes.
- No need to understand the domain/problem.
- Usually higher accuracy compared to other classification techniques.
- Lots of libraries or implementations available.
  
### Challenges with Neural Networks :
  
- Black-box results. Not possible to check or understand results.
- Training takes a long time.
- Sometimes lack of domain knowledge exposed later.
  
### Some modern applications :
  
- Any kind of cognitive skills.
- Predictive analysis
  - Predict an individual's credit risk based on the information they gave on a credit application.
  - Predicting late payments.
- Click stream analysis
  - Inferring users demographic informations, interests, browsing history, purchasing habbits and predicitng likely future actions.
- Fraud detection
  - Detecting frauduent online transactions.
  
# Responsible AI
  
<img src="https://github.com/Amchuz/Microsoft-AI-Classroom-Series/blob/master/Module%201/AI%20Challenges.png">
  
## Principles of Responsible AI :
  
- **Fairness**
  - AI systems should treat all people fairly.
- **Reliability & Safety**
  - AI systems should perform reliably and safely.
- **Privacy & Security**
  - AI systems should be secure and respect privacy.
- **Inclusiveness**
  - AI systems should empower everyone and engage people.
- **Transparency**
  - AI systems should be understandable.
- **Accountability**
  - People should be accountable for AI systems.
  
# Sample Questions for AI-900
  
1. A cement manufacturing company wants to predict how much cement should they manufacture on a given day. Which kind of data science problem is that ?
  
[] Clustering
[.] Regression
[] Classification
