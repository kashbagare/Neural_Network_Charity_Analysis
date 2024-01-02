# Neural_Network_Charity_Analysis

The purpose of this project was to use knowledge of Machine Learning, Neural Networks and Python to predict whether applicants will be successful if funded by Alphabet Soup.

## Results 

### Data Preprocessing

<img width="577" alt="Screen Shot 2021-10-31 at 2 14 15 PM" src="https://user-images.githubusercontent.com/48080598/139598116-d7388312-f6e1-4b1a-af7d-d84cf82c0af0.png">

- For this model, the variable that we considered our target array is the "IS_SUCCESSFUL" column while the variable tha we considered our feature array was every column other than the "IS_SUCCESSFUL" column. 

<img width="533" alt="Screen Shot 2021-10-31 at 2 17 17 PM" src="https://user-images.githubusercontent.com/48080598/139598163-7f55c9eb-0eeb-42d0-b17f-6a9ed36f9134.png">

- The variables that are not target or features are the "EIN" and "NAME" columns because they are non-beneficial (which is why we dropped them). 

### Compiling, Training, and Evaluating the Model

<img width="914" alt="Screen Shot 2021-10-31 at 2 21 20 PM" src="https://user-images.githubusercontent.com/48080598/139598297-daa2bbb2-8498-4111-9e11-4adaba2018b3.png">

- I had two hidden layers with the first having 80 neurons and the second having 30 neurons. The activation function for the first layer was "relu" and the activation function for the second layer was "sigmoid"

<img width="628" alt="Screen Shot 2021-10-31 at 2 23 35 PM" src="https://user-images.githubusercontent.com/48080598/139598360-e67eb7d6-1a21-4d4e-b95e-7f25aa036135.png">

- I was not able to reach the 75% optimization level but I was able to get to 64%. In order to raise the accuracy, I played around with the number of epochs until I found that 65 epochs gave me the highest accuracy level. 

## Summary 

After looking at the data and accuracy score, it is a possibility that thisi model is overfitted. In order to get a higher score, we can add more features or change the data in order more accuracy. 
