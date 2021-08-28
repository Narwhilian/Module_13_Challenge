# Prophet_Forecasting

This notebook uses Tensorflow to create a series of Neural Networks to predict the success rate of startups based on the data given by the Alphabet Soup business team.

---

## Technologies

This project uses the Python Programming language in a Jupyter Notebook as well as the following libraries
    
    - pandas
    - pathlib
    - tensorflow
      - keras
        - Dense
        - Sequential
    - sklearn
      - train test split
      - standard scaler
      - one hot encoder


---

## Installation Guide

To install you will want to pull the entire Alphabet_Soup_NN folder from github including its subfolder
    
    * Subfolder
        * Resources (the folder containing the csv data of the startups as well has the .h5 files containing the saved neural networks)
        * venture_funding_with_deep_learning.ipynb (the jupyter notebook itself)
    * ReadMe (This file)


---

## How it works

1) First the user will open the venture_funding_with_deep_learning.ipynb notebook in the Alphabet_Soup_NN folder (using jupyter labs)
2) Then the user will simply run each cell in the notebook in order to get its output

    i) The app will read the startup data into a dataframe and then clean the data and finally identify and encode categorical variables
    
    
    ii) Then it will break up the data into features and targets and split the data into training and testing data. Finally scaling the features to eliminate bias

    
    iii) Then it will create, test, and save its first (and most simple) neural network for predicting startup success
    
    
    iv) It will then go on to create 3 more neural nets all with different numbers of epochs, nodes, and layers to find the most accurate network
    
    
    v) Finally it will analyse the output of the 4 neural networks and save them all as .h5 files.
    





---

## Usage

Overall it should be a very simple application to use, all you need to do is open the venture_funding_with_deep_learning.ipynb notebook in the Alphabet_Soup_NN folder and run each cell in order using the jupyter labs interface.


---

## Contributors

Colin Benjamin

Linkedin: [Colin Benjamin](https://www.linkedin.com/in/colinbenjamin/)
    
email: cbenjamin33@gmail.com

---

## License

MIT
