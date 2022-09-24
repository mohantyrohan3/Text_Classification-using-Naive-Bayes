# Text_Classification

### This model is a usecase of Naive Bayes Algorithm
###### This is a build using a pipeline where all the training data is vectorized using Tfidfvectorizer which is a preprocessing step and then Naive Bayes algo is applied

### The Predictions of model are as below:
<img src="https://user-images.githubusercontent.com/100196185/192103099-784c5747-32fa-44e3-a5ad-cf7ba9bc2b29.png" alt="Girl in a jacket" width="500" height="600">


## Steps to use the model:

#### 1. First Clone the model into your Project Directory :
      open your command promt and write :  git clone https://github.com/mohantyrohan3/Text_Classification-using-Naive-Bayes 
#### 2. Then in your .py app import pickle library and write the following code:
      with open('Text_Classification_model','wb') as f:
                  model1=pickle.load(f)
#### 3. Now you are ready to go just start Predicting:
      ans=model.predict(['Absence of Doctors'])
      print(categories[ans[0]])
