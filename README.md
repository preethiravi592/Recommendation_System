This project provides product recommendations for a customer in a ecommerce platform based on the customer's past behaviour.
The data was in three different CSV files. i have merged them into single single dataframe.
I performed some EDA and visualized different data insights using Matplotlib plots and graphs.
This includes finding distribution of ratings, which produsts are more popular among customers,top products,etc..
I have used Item based filtering approach by constructing user_interaction_matrix.
cosine similarity metrics is used to calculate item similarity.
Two different functions has been used to predict product ratings by customer and to get recommendations.
For model evaluation, I used Mean Squared Error(MSE).
I futher did fine tuning of the model by calculating item similarity using different metrics( here i used cosine, pearson and adjusted cosine).
Finaly i applied a cross validation technique "kfold" for error evaluation.
