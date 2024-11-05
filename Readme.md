# Assignment 50
### MLP using TensorFlow (Multilayer Perceptron)


##  1-Weather  🌦️  (Using Neural Network)

+ It's the same problem we "solved" in exercise 47 with single layer perceptron but this time we're gonna solve it with multi layer perceptron. So we're going to use 
Keras framework from TensorFlow. 


## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run Weather.ipynb file in jupyter notebook
```

## **Results**

### Temperature Of Days
<img src="Weather\Output\Temperature_Of_Days.png">


### Model Loss
<img src="Weather\Output\Model_Loss.png">


## Compare Results Of NN And Perceptron
<img src="Weather\Output\Temperature_Of_Days(MLP).png">



### **Temperature Of Days : MLP**
||MLP|Perceptron|
|---|---|---|
|Loss|14.301847457885742|79.14943050104955|


##  2-House Prices 🏡 

+ This dataset has some data about houses specifications.
At first I do a preprocessing on data. Then I select some feature that more useful for Regression model and make our result less loss.
After I select the best features I fit my model that I made it by tensorflow.
I use my model on Test data of house price from kaggle site and I submit my results for test data on kaggle site.



## **Results**


* **Evaluate your trained model on validation data (You should achieve an loss < $50000)**
```
Loss : 41898.01953125 $ (< $5000)
```

### Model Losses With 140 Epochs With *41898.01953125* loss.
<img src="House_Prices\Output\Loss.png">


### I Submited My Model Into Kaggle Competition:
<img src="House_Prices\Output\Submissions.png">



* **Save your trained model as a `*.h5` extension file**

    Saved File : [model.h5](House_Prices\Output\model.h5)



## How to Install
Run following commend :
```
pip install -r requirments.txt
```

## How to Run
```
Run House_Prices.ipynb file in jupyter notebook
```











