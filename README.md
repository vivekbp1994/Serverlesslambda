# Serverless lambda

This is part of a project for cloud computing for Data Analysis wherein we are creating a serverless AI Data engineering pipeline

![image](https://user-images.githubusercontent.com/47410643/79695123-e9315c00-8242-11ea-9c6c-1be8d333514f.png)
<br>
The following steps were followed:
<li>Cretaed a cloud9 environment
<li>A lambda function was created with a python environment. Admin role was chosen for full access.
<li>In the cloud9 environment lambda fuction was created and existing role was chosen
<li>A python file by name "lambda_function" was created
<li>A table by name "fang" was created in DynaboDB with few rows of data
<li>A trigger was set up using cloud watch
  
![image](https://user-images.githubusercontent.com/47410643/79695551-7bd2fa80-8245-11ea-850d-c11c0b212f00.png)

<li>Lambda function was deployed
<li>Messages are populated in SQS 

![image](https://user-images.githubusercontent.com/47410643/79695499-31ea1480-8245-11ea-8141-2add70585524.png)
  
  
