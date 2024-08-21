# Shopping
CS50AI Project 4a - AI predicting online customer shopping trends through supervised learning.

## Instructions
1. Download this repository to your device.
2. Open a terminal or command prompt.
3. Navigate to the directory where you downloaded the repository.
4. Install the requirements usign the following command
5. Run the file with Python 3 using the following command, choosing which model you would like to use out of:
k-nearest neighbour (knn), support vector machine (svm) or perceptron (perceptron)
```bash
python shopping_multi_model.py shopping.csv knn
```
6. Watch the AI learn from the data and evaluate its own accuracy

## Background
When users are shopping online most visitors don’t end up going through with a purchase during that web browsing session. Therefore, this AI was created to predict whether a user intends to make a purchase or not: perhaps displaying different content to the user, like showing the user a discount offer if the website believes the user isn’t planning to complete the purchase. 

Using Machine Learning this project aimed to understand human patterns during a shopping session, measuring different variables such as type of page visited, month, browser type and region. Supervised learning was implemented by splitting the dataset of 12,000 users into training and testing groups to spot patterns and evaluate itself afterwards.

The programme reads the csv then trains itself using various models from the scikit-learn library. The first model used was nearest neighbour classifier (KNN), splitting the data into clusters and grouping common variables. The programme then evaluates its own accuracy using the test group to gain an understanding of how accurate its predictions were.

Other training models from the scikit-learn library can also be evaluated like Perceptron and Support Vector Machine (SVM), providing an opportunity to see which model works best with the data presented. In the case of spotting data trends in shopping sessions, the nearest neighbour algorithm seemed to operate best.
