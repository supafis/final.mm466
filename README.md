# final.mm466
Bearing health classification machine learning algorithm

This read me file explasin the final adjustments made to our MM466 final project.

1. Since its last update, we have completed the feature extraction and have chosen to forego the 'combination fault' class.
2. We have added our exploratory data analysis which entailed histograms and scatter plots
3. We split the data into three sets, 80% training, 10% validation and 10% test.
4. Principle Component Analysis (PCA) was done as our dimensionality reduction technique. This resulted in our intrinsic dimensionality been 4 PCs.
5. Gscatter and 3D Scatter plots were done to show the interaction between Principal Components (PCs) and their classes.
6. After analysing the reduced dimension data, the classification learner app was opened.
7. We had trained every available model and found that Quadratic SVM had the highest training accuracy (95.4%).
8. This was validated and it turned out that the Boosted Trees Ensemble Model performed better (96%).
9. The top 5 models were exported into the MATLAB workspace and each one was recalled for testing using the Test Data.
10. Again the Boosted Trees Ensemble model showed the highest accuracy. This became our final model.
11. We determined various KPIs for our model such as Recall and F1 Score.
12. All the data was saved and exported to excel and our final report
