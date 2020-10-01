# Introduction to the Azure AI/ML platform
  
<!-- ![microsoft-ai-platform](https://user-images.githubusercontent.com/26376075/94688538-606b3000-034b-11eb-98cd-4251d89439c1.png) -->
<img src="https://user-images.githubusercontent.com/26376075/94688538-606b3000-034b-11eb-98cd-4251d89439c1.png" width="1500">
  
## 1. What is a Workspace?      
  
Top level resource of Azure Machine Learning Sevice, it serves as a hub for building and deploying models. It stores the experiment objects that are required for each model we create.     
  
## 2. What is a Datastore?     
  
It is an abstraction over an Azure Storage account. Each workspace has a registered default datastore, still we can register another Azure blob or File storage contianers as a datastore.      

## 3. What is a Pipeline?   
  
It is a tool to create and manage workflows during a datascience process (data manipulation, model trainig & testing, development). Each step of the process can run unattended in different compute targets, which makes it easier to allocate resources.      
![pipeline](https://user-images.githubusercontent.com/26376075/94691557-13895880-034f-11eb-9d87-c46e5ee1120d.png)       

-  Introduction to Azure Machine Learning Service       
  
    -  Model Management
    -  Model Training
    -  Model Selection
    -  Hyper-paramete Tuning
    -  Feature Selection
    -  Model Evaluation
<!--
![what-is-azure-ml-service](https://user-images.githubusercontent.com/26376075/94708485-4b4dcb80-0362-11eb-8890-1dee9bb824a0.png)

![ml-serice](https://user-images.githubusercontent.com/26376075/94708572-61f42280-0362-11eb-9531-9d8f943a23f3.png)

![development-environment](https://user-images.githubusercontent.com/26376075/94709555-6ff67300-0363-11eb-8dba-96140c25e812.png)

1. ![jupyter-notebook](https://user-images.githubusercontent.com/26376075/94712172-b8636000-0366-11eb-8bd2-6fe95bf89a26.png)
  
2. ![azure-notebook](https://user-images.githubusercontent.com/26376075/94712472-2871e600-0367-11eb-8893-263306d9b59a.png)
![azure-notebook1](https://user-images.githubusercontent.com/26376075/94712699-75ee5300-0367-11eb-8150-275cd6e3881a.png)
  
3. ![ml-studio-classic1](https://user-images.githubusercontent.com/26376075/94713551-923ebf80-0368-11eb-91af-9502871e9e46.png) 
![ml-studio-classic](https://user-images.githubusercontent.com/26376075/94713019-e09f8e80-0367-11eb-935a-ca1f890fa549.png)
  
**workflow**
  
![import data](https://user-images.githubusercontent.com/26376075/94716087-fadb6b80-036b-11eb-8072-022cbd3ba358.png)
![explore](https://user-images.githubusercontent.com/26376075/94716105-02027980-036c-11eb-94b0-60061d6fe6df.png)
![create](https://user-images.githubusercontent.com/26376075/94716115-04fd6a00-036c-11eb-95b2-3b96c481024c.png)
![clean-missing-data](https://user-images.githubusercontent.com/26376075/94716127-0890f100-036c-11eb-8096-cd8123b8cead.png)

**automl**
  
![automl](https://user-images.githubusercontent.com/26376075/94717861-82c27500-036e-11eb-961e-24ed9f5b2650.png)
![automl-steps](https://user-images.githubusercontent.com/26376075/94717892-8f46cd80-036e-11eb-8d86-637d6d7242ab.png)
![algorithms](https://user-images.githubusercontent.com/26376075/94717873-85bd6580-036e-11eb-9e86-4de7a216f2e7.png)
![automl-demo](https://user-images.githubusercontent.com/26376075/94717879-881fbf80-036e-11eb-8045-94298ade8cf7.png)

-->
<img src="https://user-images.githubusercontent.com/26376075/94708485-4b4dcb80-0362-11eb-8890-1dee9bb824a0.png" width="1500" height="350">
<img src="https://user-images.githubusercontent.com/26376075/94708572-61f42280-0362-11eb-9531-9d8f943a23f3.png" width="1500" height="350">
<img src="https://user-images.githubusercontent.com/26376075/94709555-6ff67300-0363-11eb-8dba-96140c25e812.png" width="1500" height="350">

### 1. Jupyter Notebook
  
    -  On local machine
    -  Consumes resources
    -  Computation power depends on the machine
      
<img src="https://user-images.githubusercontent.com/26376075/94712172-b8636000-0366-11eb-8bd2-6fe95bf89a26.png" width="1500" >

### 2. Azure Notebook
  
    -  similiar to jupyter notebook (as per interface)
    -  we can create n' run the notebook using free resources provided by azure (FREE COMPUTE)
      
<img src="https://user-images.githubusercontent.com/26376075/94712472-2871e600-0367-11eb-8893-263306d9b59a.png" width="1500" >
<img src="https://user-images.githubusercontent.com/26376075/94712699-75ee5300-0367-11eb-8150-275cd6e3881a.png" width="1500" >

### 3. Azure Machine Learning Studio Classic
  
    -  Visual Drag and Drop ML Training and Development
    -  Complete Machine Learning Environment
    -  Ideal for learning and beginner data scientists
      
<img src="https://user-images.githubusercontent.com/26376075/94713551-923ebf80-0368-11eb-91af-9502871e9e46.png" width="1500" height="350">
<img src="https://user-images.githubusercontent.com/26376075/94713019-e09f8e80-0367-11eb-935a-ca1f890fa549.png" width="1500" height="350">

#### Workflow     
  
**import data** &#8594;**explore and create summaries** &#8594;**pre-process and clean the data** &#8594;**algorithm selection** &#8594;**model training and tuning** &#8594;**deploy and consume**
    
<img src="https://user-images.githubusercontent.com/26376075/94716087-fadb6b80-036b-11eb-8072-022cbd3ba358.png" width="1500" height="350" >
<img src="https://user-images.githubusercontent.com/26376075/94716105-02027980-036c-11eb-94b0-60061d6fe6df.png" width="1500" height="350">
<img src="https://user-images.githubusercontent.com/26376075/94716115-04fd6a00-036c-11eb-95b2-3b96c481024c.png" width="1500" height="350">
<img src="https://user-images.githubusercontent.com/26376075/94716127-0890f100-036c-11eb-8096-cd8123b8cead.png" width="1500" height="350"> 

### 4. Automated Machine Learning
  
<img src="https://user-images.githubusercontent.com/26376075/94717861-82c27500-036e-11eb-961e-24ed9f5b2650.png" width="1500" height="350"> 
<img src="https://user-images.githubusercontent.com/26376075/94717892-8f46cd80-036e-11eb-8d86-637d6d7242ab.png" width="1500" height="350"> 
<img src="https://user-images.githubusercontent.com/26376075/94717873-85bd6580-036e-11eb-9e86-4de7a216f2e7.png" width="1500" height="350"> 
<img src="https://user-images.githubusercontent.com/26376075/94717879-881fbf80-036e-11eb-8045-94298ade8cf7.png" width="1500" height="350"> 
