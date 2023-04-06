# Quora_Insincere_Questions_Classification


### Description
[Quora](https://www.quora.com/) is a platform that empowers people to learn from each other. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions those founded upon false premises, or that intend to make a statement rather than look for helpful answers.

[Kaggle: Quora Insincere Questions Classification](https://www.kaggle.com/c/quora-insincere-questions-classification) **Build a model to classify whether a question asked on Quora is sincere or not.**

#### Data:

- Quora provided a good amount of training and test data to identify the insincere questions. 
- **Train data** consists of **1.3 million rows and 3 features** in it. And the **Test data** consists of **300K rows and 2 features.** 

#### Evaluation Metrics :

- Metric is F1 Score between the predicted and the observed targets. There are just two classes, but the positive class makes just over 6% of the total. So the target is highly imbalanced, which is why a metric such as F1 seems appropriate for this kind of problem as it considers both precision and recall of the test to compute the score.

In summary,  the Quora Insincere Questions Classification challenge dataset represents a challenging task for text classification due to the high level of Insincere in the questions and the imbalanced class ratio. In this notebook, We have explored three models for this task: **Logistic Regression model, a Naive Bayes model, and a CNN model.**
The study highlights the effectiveness of **CNN** in Binary text classification, especially in Imbalanced datasets.

![quora5](https://user-images.githubusercontent.com/128596977/230318109-9e5e7547-2cb0-4665-9e05-5894e0bd5844.png)
