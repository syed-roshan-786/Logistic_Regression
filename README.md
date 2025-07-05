 Student Performance Prediction using Logistic Regression

 -> Objective  
To build a simple machine learning model that predicts whether a student will pass or fail based on study hours and attendance percentage.

 -> Dataset  
The dataset includes 500 records with the following columns:  
- Hours_Studied – Number of hours the student studied  
- Attendance (%) – Attendance percentage of the student  
- Pass/Fail – 1 = Pass, 0 = Fail  

-> Tools Used  
- Python  
- Jupyter Notebook  
- Libraries: pandas, matplotlib, seaborn, sklearn  

-> Steps Done  
1. Loaded and displayed the dataset using pandas  
2. Visualized the data using a scatter plot  
3. Split the dataset into training and test sets  
4. Trained a Logistic Regression model  
5. Evaluated the model using confusion matrix and accuracy  
6. Predicted outcome for new input data  
7. Visualized the confusion matrix with a heatmap  

-> How to Run  
- Open the notebook in Jupyter  
- Make sure `student_data.csv` is in the same folder  
- Run all cells step by step  

-> Expected Output  
- Accuracy between 90% to 95%  
- Example: Predicting for a student with 6 study hours and 80% attendance → **Pass**
