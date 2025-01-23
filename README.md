# Practical Machine Learning: Predict user decisions and preferences for purchasing a bike.
Welcome to my project on model building of predicting whether a customer will buy a bike or not, using a **Machine Learning Classification Model**! This project applies supervised learning techniques to predict customer behavior, specifically focusing on factors that influence their likelihood to purchase a bike. 

## Important Note

If you encounter difficulties opening or previewing the files directly from GitHub, please use the following link to access the files through Google Colab:
[Open in Google Colab](https://colab.research.google.com/drive/1-i8Tr9DWQ7pJP-7qM3VOH-sZKaA9jgdS#scrollTo=l3Uk9JCBmH8u)

## Project Overview
In this project, I developed a classification model to predict whether a customer will purchase a bike. The model was built using a variety of machine learning techniques and evaluated to ensure high predictive accuracy. The goal is to gain insights into the customer profile and use these insights for marketing strategies, product development, and customer targeting.

This project is a practical application of **supervised learning**, where a model is trained on labeled data to make predictions on unseen data. In this case, we are trying to predict the binary target variable—whether a customer will buy a bike (yes/no)—based on various customer features.

### Dataset Strategy

To identify the best model, I divided the data into three datasets:
1. **Original dataset**.
2. **Dataset with outliers treated using the Winsorization Approach**.
3. **Dataset with outliers treated using the Interquartile Approach**.

For each dataset, I tested three different models:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**

The model selection was based on the model’s performance, with a focus on both the accuracy score and the consistency of performance during cross-validation.

## Key Takeaways

- **Random Forest Classifier** emerged as the top performer with an **accuracy score of 85%**, demonstrating excellent predictive power.
  
- The model showed balanced performance across multiple evaluation metrics, including **precision**, **recall**, and **F1-score**, making it a reliable model for predictions.

- **Cross-validation** results revealed an average score of **0.8** with a standard deviation of **0.034**, indicating that the model generalizes well to unseen data.

- The inclusion of a **full feature set** significantly contributed to the model’s predictive ability. The features considered included customer demographics (age, income) and contextual factors such as **commute distance**.

- **Top 3 important features**: 
  1. **Age**
  2. **Income**
  3. **Commute Distance**
  
  Among these, **commute distance** emerged as the most important factor influencing the likelihood of purchasing a bike. This insight suggests that the bike company could focus on targeting urban commuters from the **Upper-Middle-Class** segment, as they are more likely to be interested in biking.

These findings provide actionable insights that can inform future marketing strategies, product development, and customer segmentation.


# Thank you for visiting my portfolio!
Come along and join me in this exciting journey of growth and discovery! Together, we'll make progress, one data point at a time🌈💻
