# House-Prediction-Model
Hello. It's my first repository. I made a Machine Learning Model in Python Language. This model based on Kaggle Competition. It is a house prediction model which include a GUI which made by Tkinter is Python Library.

# House Prices Advanced Regression Techniques and GUI Design
It is a project made using the Python programming language, capable of estimating house prices, and an interface designed accordingly. Data from the Kaggle site was used. Some of these data were used for training and some for prediction. 
After this data was taken, visualization was made. Efficient data that can be used during this visualization have been selected. Some data has been removed because it causes the accuracy of machine learning's prediction to decrease. Examples of these data are 'GarageCars', 'FullBath'. In some data, the excess of NaN values prevented that data from being usable. After these extracted data, the remaining useful data that can be used were determined.
I used 70 percent of the selected data to train. I used the remaining 30 percent for testing purposes. NaN values prevented me from using many columns in the data or reduced my prediction rate. I had to take these out. After I found the highest percentile accuracy values, I noted down these weights for later self-testing. 

![image](https://user-images.githubusercontent.com/94008001/186026414-174f0f7b-87ac-47de-8ca6-b7fce22acf5d.png)

Some functions that I use to clear the values are shown in the picture above. 

After completing the prediction algorithm, I started the GUI design within the same code block. I used Python's Tkinter library for GUI design. I created an interface that will provide the input of the 5 data I used. I made a message box screen that will confirm the input of 5 data. Thus, data entries are guaranteed. I used the weights I noted earlier in the calculate button of the GUI and compared them. 

Linear regression is a method frequently used in statistical data analysis. Linear regression is a method used for linear and continuous variables. This machine learning function was one of the most suitable machine learning methods for my data.

