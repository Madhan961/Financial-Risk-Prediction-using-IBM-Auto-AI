# Financial-Risk-Prediction-using-IBM-Auto-AI
## Project Objectives
In this workshop you will learnyou will learn how to  
    ⇾ Work with Watson Studio  
    ⇾ Create a project in Watson Studio  
    ⇾ Use Auto Ai experiment to create a model  
    ⇾ Deploy the ML model as a webserver  
    ⇾ Integrating Model and Node-RED Service  
    ⇾ Build an Application using Node-RED which takes inputs from the user and showcases the prediction on UI  
## Prerequisites  
To complete this project you must have an IBM account   
• Click [here](https://cloud.ibm.com/login) to register for IBM   
• lick [here](https://cloud.ibm.com/login) to log in to IBM Account  
## Create IBM Services
In this activity, you will be creating the Necessary IBM services. The following are the services that you have to create.  
 ⇾ Watson studio  
 ⇾ Node-RED  
 ⇾ Cloud Object Storage service (COS)  
 ⇾ Machine Learning service (ML)  
COS and ML services will e created while creating a Watson Studio Project  
### Create Watson Studio Project  
To create the service click [here](https://www.youtube.com/watch?v=aAT3qALIQXM) to watch the video and follow the steps.  
### Create Node-RED Service  
To create the service click [here](https://www.youtube.com/watch?v=beCCPIH0-8c) to watch the video and follow the steps.  
## Build Machine Learning Model
In this activity, you will learn how you can save a pipeline as a Watson Machine Learning model, deploy the model, and score it to view a prediction.  
This Activity  contains the Following Tasks  
⇾Collect the data set  
⇾Create Watson Studio project  
⇾Add Auto AI experiment  
⇾Run AI Experiment  
⇾Save the model  
⇾Deploy the model  
### Collect The Data Set
Please click [here](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/DATA/fraud_dataset.csv) to download the dataset. 
In this Activity, We gonna build a machine learning model that predicts  fraudulent transactions based on the following parameters 
• Gender,  
• Marital Status,  
• Dependents,  
• Education,  
• Self-employed,  
• Applicant income,  
• Co-applicant income,  
• Loan amount,  
• Loan term,  
• Credit history,  
• Housing,  
• Locality.  
### Create Watson Studio Project
A project is how you organize your resources to achieve a particular goal.  

To Know more about the Watson studio project please click [here](https://dataplatform.cloud.ibm.com/docs/content/wsj/getting-started/projects.html?audience=wdp&context=wdp)  

• Launch the Watson Studio dashboard
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/WSdashboard.png)  
• Create a new project by clicking on Get Started and New Project, or Create Project
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/projects.png.png)
##### Give your Project a name.  
• Select an Object Storage from the drop-down menu or create a new one for free. This is used to store the notebooks and data. Do not forget to click refresh when returning to   the Project page.  
• click Create.  
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/createproject.png)    
##### Once you are in the Project Dashboard, click on "Add to Project" on the top right and select AutoAI Experiment
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/addtoproject.png)  
##### Associate a Machine Learning service
• Give your Auto AI experiment a unique name    
• Associate a Watson Machine Learning service, if you have already created one this will apear in the dropdown or you can create a new one.  
• Once this is done, click the "Reload" button for your Machine Learning service to appear  
• Your machine learning service will appear under "Associated services"  
• Click Create
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/MLservice.png)

