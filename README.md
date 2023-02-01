# Convolutional neural network prediction algorithm 

## Work description and analysis:

The new car data set includes 5 columns and 400 rows. The written code predicts whether or not a car manufacturer's customer will buy a new car.
I decided to test the dataset with Neural Network and then compare it with DecisionTreeClassifier in order to see the difference in the results.

## DecisionTreeClassifier

Firstly, I tested the program with DecisionTreeClassifier as I am more familiar with that method. The results were pretty all right:
• The confusion metrix:
![alt text](https://github.com/andevrrr/ANN_DecisionTreeClassifier/blob/main/imagies/plot_1.png?raw=true)

• The accuracy score:0.910
• There call score: 0.906 (Recall measures the proportion of actual positives that were predicted correctly. It takes into account false negatives, which are cases that should have been flagged for inclusion but weren't.)
• The precision score: 0.829 (Precision gives the proportion of positive predictions that are actually correct. It takes into account false positives, which are cases that were incorrectly flagged for inclusion.”)

Neural Network is an algorithm inspired by biological neural networks, which makes it work like a human brain and act accordingly.

DecisionTreeClassifier works differently, It is using a binary tree graph.
To my understanding, Neural Network is supposed to work much better than DecisionTreeClassifier and give more precise results.
What I liked in Neural Network is that you can choose hidden layer sizes, if you put more of them, the running time will be longer, but the results will be more accurate.

## Neural Network

The results from using Neural Network:
• The confusion metrix:
![alt text](https://github.com/andevrrr/ANN_DecisionTreeClassifier/blob/main/imagies/plot_2.png?raw=true)

• The accuracy score: 0.912
• The recall score: 0.905
• The precision score: 0.792
As you can see, the results are slightly different from the first ones, and not for the better.
The accuracy and recall scores are almost the same, but the precision scores are slightly different.

Summarization:
In my opinion, both programs work fine, if there are some confusing numbers for the algorithm to sort, means it probably never will give the perfect results. Nevertheless, I had more positive expectations about using Neural Network, but it turned out not as good as expected.
