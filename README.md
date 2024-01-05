# U_JUMP_I_JUMP_JACK
Predicting Titanic passengers survival rate through machine learning models. 

Table of Contents
General Info
Setup
Usage
Project Results
Future Data Exploration Ideas
Acknowledgements
Contact

General Information
I’m uploading my code of the Titanic machine learning model I trained to predict passengers' survival rate!💻🚢 The goal was to explore the data available on Kaggle and see if I could find the most relevant features to predict passenger's survival rate💀. With this initiative I also want to support other coders who are just starting training machine learning models like me and are willing to get more familiar with the basics!🗺️🔎👣

I used the data from the publicly available Kaggle competition [here](https://www.kaggle.com/competitions/titanic/overview). I helped myself with this article because it easily explains how the competition works. I then got the data, cleansed it🛁, and started exploring it.

Setup
First off, make sure you have conda🐍👀:

conda create -n <replace-with-name-you-want> python=3.11

conda activate <replace-with-name-you-want>

pip install -r requirements.txt

Usage
Check out the ipynb file in my repo to see how I've processed the data, built and trained the models!

Project Results
I discovered that the combination of features with which I trained the best performing model are: `'Pclass', 'Sex', 'SibSp', 'Parch', 'Age'`. The model is a Random Forest Classifier and it scored with an accuracy of 0.7. Moreover, when I then tried to code a sequential feature selector to select the best features, I discovered that these were the following: `'Sex', 'Fare', 'Pclass', 'FamilySize'`. However, the model I then trained on this new set of features actually scored slightly lower than the previous one (i.e., 0.76). 

Future Data Exploration Ideas
For future use, we could try to use the sequential feature selector on a different machine learning model (e.g., Decision Tree), to see if we get better results. We could also explore alternative feature engineering techniques to use to train the machine learning model.

Acknowledgements
A massive thank you to Rachael Tatman and Alexis Cook for the awesome Kaggle tutorial on the Titanic Machine Learning Kaggle competition. Your insights have been a game-changer for me!

Big kudos to Manav Sehgal from the Kaggle community for the fantastic forum post feature engineering – your article gave me the right inspiration to get started with feature engineering!

Finally, a special thank you goes to Ward Haddadin, who has always been motivating me to review my code, be curious, and be ambitious!

Contact
For any question, drop me a line at giorgiadt14@gmail.com and I'll be happy to help you out! Feel free to message me on LinkedIn too! Happy coding!