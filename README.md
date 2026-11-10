##### Dataset: Customer Personality Test ########

- This dataset was taken from Kaggle and this is a Customer Personality Analysis Dataset which gives a detailed output of a companies ideal customers.


##### Model Steps ########

- A) Data Inputs: This uploads the dataset into Jupyter notebook. This part of the step gives a full list of the fields and what we think the business explanation is for each field.
- B) Exploratory Phase: This explores the data itself and tries to perform data checks to ensure the dataset is fit for use. We also look at things like Histograms, Box Plots & correlation matrixes to understand the relationship between each of the fields while understanding the distribution of the data.
- C) Feature Engineering: We look to add more features to the dataset like length of time the customer is with the business, age of customers, combining spend products all into one field and total number of kids each customer has. By adding more variables it may help us distinguish clusters more separately
- D) K Means Cluster Model: For this project I decided to go with a K Means Cluster Model which is an unsupervised machine learning model. We applied techniques like X Scaled & PCA to the data before building the model. We also applied checks like the Elbow Method, Silhouette Score & Davies Bouldin Index to decide how many clusters to use and what was the best fit for this dataset.
- E) Train + Assign + Profile: Once we have built the model and we then move into the stage of deciding a segment name of each cluster. Using PCA1 & PCA2 variance graph can be very helpful when deciding your segment name.
- F) Presentation & Insights: This is the final step of the model process where we try understand the landscape view and use the Cluster Model information to translate this into Business Value Ex: Recommendations & Insights
