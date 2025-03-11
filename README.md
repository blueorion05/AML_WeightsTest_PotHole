# Advanced Machine Learning - Pothole WebApp  ![Badge](https://img.shields.io/badge/BSCS%203IS2-AML-red)

#  Introduction
  - This Web Application is based from AHG Superconductor's project https://github.com/AHG-BSCS/semaphore-machine-learning
  - This Web Application is made standalone to be used for any weights, or for this instance, Potholes.
    
***NOTE: This guide will assume that Python is already installed, pip is installed, and all environment variables are taken care of.***

# Instructions
1) Clone this repository by opening your terminal and typing

   `git clone https://github.com/Valdezin/AML_WeightsTest_PotHole`

2) Navigate to the downloaded repository

    `cd AML_WeightsTest_PotHole`
   
3) To install the required dependencies
   
   `pip install -r requirements.txt`

4) Go to Roboflow, navigate to your group project, click on versions and download your weights
   ![image](https://github.com/user-attachments/assets/4d7f5d86-96ce-44bb-9875-58daf3cade20)
   ![image](https://github.com/user-attachments/assets/9efceedf-390c-4a98-b024-532ed216679d)

Sidenote: **Obtain an API Key from ngrok by signing up for a free account**

6) Save your weights.pt to the `model` folder of the repository.
7) Start the Flask server by using the command

   `python app.py`

You may now start uploading/drag and drop images in the webapp.
![image](https://github.com/user-attachments/assets/a734b51e-7ecf-4a6d-ba53-5266404345df)
