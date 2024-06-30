# League-of-Legends-Prediction-Model

## Overview
This model predicts winning teams in League of Legends using machine learning techniques applied to a ranked game dataset obtained from Kaggle.com. The goal was to identify key factors influencing game outcomes and build an accurate prediction model based on these insights.

## Methodology
1. **Dataset Exploration**: Utilized a dataset from Kaggle.com containing game statistics and outcomes for ranked matches in League of Legends.
   
2. **Feature Analysis**: Conducted a correlation analysis using a heatmap to identify significant factors influencing game outcomes. This helped in understanding which variables contribute most strongly to predicting the winning team.

3. **Model Training**:
   - Used Decision Tree Classifier to build the prediction model.
   - Employed GridSearchCV to optimize model parameters (`max_depth`, `splitter`, `criterion`) for improved accuracy.

4. **Model Explanation**:
   - Decision trees start from the root node and split data based on features that minimize uncertainty (e.g., Gini impurity or entropy).
   - Traversal through nodes continues until a prediction is made based on the final leaf nodes.

## Results
The model achieved [insert accuracy or performance metric] accuracy on the test set, demonstrating its effectiveness in predicting game outcomes in League of Legends based on selected features.

## Dependencies
- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- seaborn
