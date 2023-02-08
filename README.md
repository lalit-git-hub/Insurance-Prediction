# Insurance-Prediction

Following are the steps to create a complete end to end ML project:   

A. Complete the eda, data preprocessing, algorithm development in either Jupyter Notebook or any IDE.    
B. Save the pickle file for normalization and model.    
C. Create a github repository. (Make sure to add the readme file and the gitignore file)    
D. Clone the repository in the local machine from the command prompt. (command: git clone repository_name)    
E. Open the folder in the suitable IDE.   
F. Create a new environment:   
    1. Conda environment: conda create -p venv python==3.11 -y (venv= environment_name; -y: yes to all the questions)   
    2. Activating the environment: conda activate venv/   
    3. Deactivating the environment: conda deactivate   
G. Create a requirements.txt file. (for libraries to be used)   
H. To install those libraries: pip install -r requirements.txt    
I. Configure git (git config --global user.name "Lalit") then configure email (git config --global user.email "lalitwale100@gmail.com")       
J. Commiting the file to the github account:    
    1. To add just one file: git add file_name.extension
    2. To add all the files: git add .
    3. To check the status: git status    
    4. To commit: git commit -m "message"   
    5. Push: git push <remote> <branch>  (git push origin main)   
K. Create app.py file and create the application in that.    
L. Create a templates folder and add home.html to it.   
M. Add all the new files to the github. (using process in point 'J')     
N. To deploy the app in Heroku:
    1. Create a Procfile
    2. Using Git-CLI in the Heroku app, deploy the application.
O. To deploy using Dockers and Github actions:
    1. Create a Dockerfile.
    2. Create '.github' folder. In that folder, create 'workflows' folder. In that folder create 'main.yaml' file. 
    3. Copy secret keys from the Heroku app (it will be available in the account settings) to the Github secrets.   
    4. Add everything to the github   






