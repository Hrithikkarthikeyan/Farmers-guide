#Farmers Guide

5th semester project on machine learning for the welfare of the farmers of India to predict the production of a crop for a particular land and suggest the best crop for that land so that the farmers are profitted.


##Software requirements: 
This project requires node modules file in order to run. This can be created by `npm install` and then `npm start` inside the project folder. 
then come out of project folder and run 'docker-compose build' and 'docker-compose up'...to run the entire project. 
Requires python3 to run the database. 
Requires pickle, pandas, sklearn, numpy to be installed to run the project without any errors.	


##Steps to compile the files:
These steps require a virtual environment. This can be created by entering the following commands inside the project folder.          
1. pipenv shell          
2. export FLASK_APP=api          
3. export FLASK_DEBUG=1  
4. flask run     
These steps will start the database required for the project to run properly.	

##To generate pkl file which will not be available in the zip file.	 	
###STEPS:		
1. Go to cd project/src/components		
2. Type python crop_prediction.py		
3. Then type crop_crop_prediction.py		

=======

>>>>>>> b8e54664ec91b1b4e25b9ab3b9691b151e180582
