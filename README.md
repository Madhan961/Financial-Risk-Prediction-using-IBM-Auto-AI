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
• Click Create.  

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

### Upload your Data Sets
• In this workshop we will be analysing two Datasets  
• One to create a Classification model and the other to create a Regression Model  
• Browse and add your Data source

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/browsedata.png)  

### We will now work through the different aspects of configuring our AutoAI experiment and discuss the Classification Models that are created.

### Deploying your Model
• Once you select your final model pipeline. You can choose to Save it as a notebook or an ML model.
• Choose your option and Click Save.

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/pipeline.png)  

• Once your model is saved you will see a popup to View in Project or you can access the saved model from the Assets tab.
• Click on the saved model and Promote to a deployment space.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/depolyspa.jpg)  

• Select the target deployment space you want to use for this deployment. If you do not have one yet, you can create a new space.  
 
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/promotespace.jpg)  
 
• Access the deployment space from the left navigation pane. 
• In your Deployment Space, Choose the model you want to deploy from the Assets tab and click the deploy icon as shown.

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/modeldeploy.png)  

• Choose your Deployment type and create your Deployment.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/createdeploy.png)  

Once your model is successuly deployed, you can access the API reference to make API calls or Test your model by providing input using a form or in a JSON format.  


###### For Reference   

I'm providing some youtube videos for reference as well as you can clear all doubts with these videos.  

• Create a project  
        to watch video click [here](https://www.youtube.com/watch?v=Tr82IMw7BZw)  
• Create the AUTO AI Experiment  
        to watch video click [here](https://www.youtube.com/watch?v=QhLNCXj5PY4)  
• Run Auto Ai Experiment 
         to watch video click [here](https://www.youtube.com/watch?v=0nKGHGJcvls)  
• Save The Model  
         to watch video click [here](https://www.youtube.com/watch?v=xkH7fWIteV0)  
• Deploy The Model 
         to watch video click [here](https://www.youtube.com/watch?v=mqeH8-zl24I)  

## Build Node-RED Application  

Let's build a User interface which takes inputs from the user. The Model Analyses the Inputs and returns the Prediction that is showcased on the User interface.  

### Integrate Node-RED With Auto Ai Model  
In this task, you will be creating a Node-RED flow that integrated with the model built.  

Note: Create a form node which has the Input values according to the dataset that you have taken.  

## IBM Cloud API key
• Generate an IBM Cloud apikey by clicking the Manage --> Access (IAM) option on your top right.
 
![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/accessapi.png)  

• Click on API keys from the left navigation pane, and select Create an IBM Cloud API key  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/apikeys.png)  

• Once your key is created Copy or Download your key.  

### Node-RED

• Go to IBM Dashboard and click on the Cloud Foundry apps.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/dashboard.png)  

• Select the created Node.RED app  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/selectnodered.png)  

• Click on the  Visit App URL

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/appurl.png)  

• You will be redirected a new page then click on the "go to your Node-RED flow editor.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/NRfloweditor.png)

• Create a new flow.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/NRfloweditor.png)  

• Search for form node in filter nodes block and drag that form node into flow.  

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/dragform.png)

• Double click on the form node and add new ui_group then enter the required fields as shown in image.

![](https://github.com/Madhan961/Financial-Risk-Prediction-using-IBM-Auto-AI/blob/main/Images/enterfields.png)  










 
