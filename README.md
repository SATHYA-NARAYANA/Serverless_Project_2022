# Serverless_Project_2022
First Serverless Project

# Setting up environment for serverless Project
# STAGE 1  
 # Download Node and Install from below URL
``` 
https://nodejs.org/en/download/
```
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/Images/Serverless/1.png">
</p>
   
# STAGE 2 
 # Download and Install Serverless using below Command 
``` 
 npm install -g serverless
```
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/Images/Serverless/2.png">
</p>

# STAGE 3
 We need Access key and Secrete key of AWS to configure serverless in our local system. So that we no need to go every time ,manually to configure each and every steps.You can Create IAM users as Given Steps below  

# Creating IAM User with access control:
An AWS Identity and Access Management (IAM) user is an entity that you create in AWS to represent the person or application that uses it to interact with AWS. A user in AWS consists of a name and credentials.

An IAM user with administrator permissions is not the same thing as the AWS account root user.
# Step 1: Go to AWS management console and Search IAM 
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/1.png">
</p>

# Step 2: Next Click on Users 
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/2-click%20user.png">
</p>

# Step 3: Next Click on Add User 
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/3.png">
</p>

# Step 4: Next give any name to user " here i gave Jerry" and also assign Access key - programmatic access
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/4.png">
</p>

# Step 5: Next click on existing access role to user 
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/5-attach%20permission%20.png">
</p>

# Step 6: Next Give user an access " Here i am assigning user Administrative access "
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/6-next%20next.png">
</p>

# Step 7: Next Click on Create User
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/7-create%20user.png">
</p>

# Step 8: Finally you have finished creating User
```diff
- Do not share access key and Secrete key with any one
```
<p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/IAM/8-%20download%20keys.png">
</p>
# STAGE 4
   One access key is obtained we can configure serverless in our local system using command mentioned below.
   ```
   
   ```
 <p align="center">
     <img width="900" height="400" src="https://github.com/SATHYA-NARAYANA/Serverless_Project_2022/blob/main/Images/Serverless/3.png">
</p>

