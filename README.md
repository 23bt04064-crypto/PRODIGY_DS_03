# PRODIGY_DS_03
# Prodigy InfoTech Data Science Internship Task 3:
<br>
<img width="1287" height="668" alt="Screenshot 2025-12-07 at 12 35 56 PM" src="https://github.com/user-attachments/assets/1c21686b-31d4-4fb7-a51c-2ff741882392" />


Welcome to my submission for Task 3 of the Data Science Internship at Prodigy Infotech. In this task, I developed and evaluated a Decision Tree Classifier to predict whether a client will subscribe to a term deposit based on a bank marketing campaign dataset.

## Dataset

The dataset used for this task is 
<a href="https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%03">
Bank Marketing 
</a>.

 

## Tools and Libraries used

- Kaggle notebook
- Pandas
- Numpy
- Matplotlip & Seaborn for visualization


## Methodology

The methodology for Task 3 focused on building an interpretable and robust Decision Tree model for predicting term deposit subscriptions. The process began with critical data preparation, specifically removing the data-leakage-prone duration feature and transforming all 16 categorical columns into numerical binary features using One-Hot Encoding. The imbalanced nature of the target variable was addressed proactively by using stratified sampling during the 80/20 data split. Finally, a Decision Tree Classifier was selected and trained with a fixed maximum depth of 5 to ensure the model was regulated against overfitting and remained simple enough for clear visual analysis and business interpretation .


## Conclusion

Task 3 successfully implemented a constrained Decision Tree Classifier for predicting bank term deposit subscriptions. The model achieved a high Overall Accuracy of 89.27% , largely influenced by the imbalanced nature of the dataset. The key finding, however, lies in the model's poor performance on the minority class ('yes' for subscription), evidenced by a very low Recall of 0.15. This indicates the model struggles significantly to correctly identify potential subscribers, missing out on 85% of positive cases. Therefore, while the accuracy is high, the model is currently not practical for business use as it fails to effectively target new customers. Future work must focus on imbalance techniques (e.g., SMOTE) and exploring alternative models to achieve a better balance between Precision and Recall for the subscriber class.

Thank you for reviewing my submission!

## 📬 Contact

For any inquiries or feedback regarding this project, please contact:
- Email: 23bt04064@gsfcuniversity.ac.in
