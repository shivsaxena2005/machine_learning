
#Use Cases
Customer churn prediction helps businesses identify customers likely to stop using their services. This project uses "Machine Learning models" to analyze customer behavior and predict churn

#DATASET
 Filename: `Churn_Modelling.csv`
 Contains RowNumber, CustomerId,	Surname,	CreditScore,	Geography, Gender,	Age,	Tenure,	Balance,	NumOfProducts,	HasCrCard,	IsActiveMember,	EstimatedSalary,	Exited history.
 
#DataPreprocessing
  Feature selection: ROWNumber, CustomerId, Surname are not valid feature for prediction user exit or not(Drop)
  Normalizing: Geography and Age normailze using label encoding
  Standarize : This dataset feature like Skewness: -0.07159586676212397, Kurtosis: -0.42611279176518124 So use (standarscaling instead of min-max scaling) 
  Splitting: 80% train and 20% test using train_test_split


#Models:
  1. Logistic regression
      Accuracy: 0.815
  2. Random Forest
      Accuracy: 0.8675
  3. Artificial Neural Network
      Accuracy: 0.8560000061988831
