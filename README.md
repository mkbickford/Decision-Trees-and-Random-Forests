This is an analysis of 2007-2010 loan data from Lending Club (https://www.lendingclub.com/). I looked at this data to determine how factors such as the applicant's FICO credit score, revolving account balances, and debt-to-income ratio contributed to their likeliness to get approved for a new loan. Using 11 features to predict the loan decision, I decided that training Decision Tree and Random Forest models would likely be effective in accurately representing these correlations.

Both of my Decision Tree and Random Forest models showed a high correlation between favorable feature values and loan approval and vice versa. I initially predicted the Random Forest model to be noticeably more accurate, due to the random selections of decision trees that help to weigh features more equally. The Decision Tree and Random Forest models performed about equally, with minimal Type 1 and Type 2 errors in the Confusion Matrix and close to 1.00 for both models in precision, recall, and f-1 score. The recall for loan denials was slighly higher in the Decision Tree model and slightly higher for loan aprovals in the Random Forest model.
