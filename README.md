Name: Swara Patil
RollNo: MM22B045


This project focuses on predicting the hourly bike rental count using the Bike Sharing dataset. The main idea is to compare different ensemble learning methods and understand how they improve model performance.
We first build simple baseline models: Linear Regression and a Decision Tree. These help us understand the basic behavior of the data. Then we apply three ensemble techniques:


Bagging: This reduces variance by averaging the predictions of multiple decision trees.


Boosting: This reduces bias by learning from the mistakes of previous models in a sequence.


Stacking: This combines several different models and uses another model (a meta-learner) to learn the best way to blend their predictions.


After training and evaluating all models, Stacking gives the best performance with the lowest error. This happens because different models capture different patterns in the data, and the meta-learner learns how to balance them effectively. Boosting performs second best. Linear Regression performs reasonably well as a baseline. Bagging improves stability compared to a single decision tree but is not as strong as boosting or stacking.
In short, the main takeaway is that combining models in a smart way (especially Stacking) leads to a more accurate and robust prediction than using any single model alone.
