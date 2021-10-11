# Flight-Fare-Prediction-Web-App  
  
Link for the Web-App:-  https://mlflightfare-prediction.herokuapp.com/  

### Project Structure
This project has four major parts :
1. model.py - This contains code fot our Machine Learning model to predict flight fare absed on trainign data in 'Data_Train.xlsx' file.
2. app.py - This contains Flask APIs that receives flight details through GUI or API calls, computes the precited value based on our model and returns it.
3. templates - This folder contains the HTML template to allow user to enter flight detail and displays the predicted flight fare.
4. static - This folder contains the .css file for the html file index.html to use and render a good looking web-app.

### Guide to run the project locally
1. Ensure that you are in the project home directory. Create the machine learning model by running below command -
```
python model.py
```
This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

3. Navigate to URL http://127.0.0.1:8000/ (This local server will be assigned after you run the unicorn command)

### FlowChart Diagram  
  
  ![proj2_flowchart](https://user-images.githubusercontent.com/54064843/136836342-6b4bb5a5-7b97-40af-aa34-f646b1800a37.jpg)

  
Homepage View:-   
   
![Screenshot (1947)](https://user-images.githubusercontent.com/54064843/136835220-86a8f698-6ce1-4fd7-a4ed-2b5d0601d29a.png)
![Screenshot (1945)](https://user-images.githubusercontent.com/54064843/136835236-bed14ecc-0227-425d-9036-6d46846e1f5c.png)


By clicking on the Source and Destination cities available ,you will land on the wiki page of that city and by clicking on the airline names(e.g Vistara) under the Airline Available tag these links will direct you to their respective official site  where you can further book tickets. The Github link under Connect tag brings you here:)  
  
Enter valid values in all 6 input boxes and hit Predict.
![Screenshot (1944)](https://user-images.githubusercontent.com/54064843/136835261-15ac2a8f-b32d-4f17-a836-269cfa911cfc.png)


If everything goes well, you should  be able to see the predcited flight fare vaule like this:- 
  
![Screenshot (1946)](https://user-images.githubusercontent.com/54064843/136835304-d655b4c0-38e0-444f-b7c4-8e8f70c7bf17.png)



