# Charity Funding Predictor
## Deep Learning Challenge
#
<img align=center src="https://user-images.githubusercontent.com/85762953/143806470-cad1161b-687d-4ab5-b59b-1b17442cd652.jpg" width="600" height="250">

# Background

The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization.

# Tasks

1. Preprocess data
2. Compile, Train, and Evaluate the Model
3. Optimize the Model
4. Write a Report on the Neural Network Model

# Resources 
<details>
<summary>Tools/Libraries/Languages Utilized</summary>
<li>Jupyter Notebook</li></ul>
<li>Tensorflow</li></ul>
<li>Keras</li></ul>
<li>Sklearn</li></ul>
<li>Pandas</li></ul>
</details>

[Resource](https://machinelearningmastery.com/how-to-configure-the-number-of-layers-and-nodes-in-a-neural-network/): used for clearer understanding on how to configure number of layers/nodes.

[Resource](https://machinelearningmastery.com/how-to-stop-training-deep-neural-networks-at-the-right-time-using-early-stopping/): used for understanding number of training epochs.

## Summary/Findings
* Target variable: "IS_SUCCESSFUL" 
* The features to be removed: "EIN", "NAME"

* In the original model, I used two layers, I tried several times to get a better accuracy score using two layers. On the last try, I added a third layer. It may not have been the correct addition or was overfit for this model. In this case it did not make sense to add another layer. The most accurate model I could come up with was from AlphabetSoupCharity_Optimization2.ipynb where the accuracy was 0.73 and loss of 0.56. I tried to improve that with different number of epochs/changing the layers/how the data was preprocessed. 

