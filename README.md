# Mobile price range prediction

This project focuses on classifying the price range of mobile phones using their specifications. The primary goal was to develop and evaluate predictive models capable of accurately categorizing devices into four distinct price brackets.

The dataset used in this project is perfectly balanced, with each price category containing an equal number of samples, which is ideal for training and evaluating classification models without the risk of class imbalance bias.

## 🤖 Models and Methodology

Two different classification models were built and evaluated to determine the most effective approach for this dataset:

* **Support Vector Machine (SVM):** A linear kernel SVM was implemented to find the optimal hyperplane that separates the different price range classes.
* **Neural Network:** A Multi-Layer Perceptron (MLP) classifier was also developed to explore a non-linear approach to the classification task.

The data was preprocessed and split into a training set (80%) and a testing set (20%). The models were built using Python with libraries such as Pandas for data manipulation, Matplotlib and Seaborn for data visualization, and Scikit-learn for machine learning.

## 📊 Results

The performance of the two models was compared to determine their practical utility for this dataset.

* The **Support Vector Machine (SVM)** model achieved an impressive **95% accuracy** in classifying mobile phone price ranges. The linear kernel proved to be a suitable choice, indicating a high degree of linear separability in the feature space.
* The **Neural Network** model, on the other hand, exhibited lower precision, especially for two of the price categories. This suggests that for this specific dataset, the SVM was the more suitable and effective model.

The project successfully demonstrated the ability to preprocess data and apply different classification algorithms to achieve high-accuracy predictions. The SVM model, in particular, stands out as a practically useful tool for this classification task.
