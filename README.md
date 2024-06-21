![image](https://github.com/tejaswini-meshram/Unsupervised-ML---Online-Retail-Customer-Segmentation/assets/159335164/1f350559-29fa-4efa-9280-91c86608e41a)# Unsupervised-ML---Online-Retail-Customer-Segmentation

# Problem Statement
In this project, your task is to identify major customer segments on a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

# File 

[Sample_Unsupervised-ML---Online-Retail-Customer-Segmentation.ipynb]([https://github.com/tejaswini-meshram/EDA-Project-Hotel-Booking-/blob/main/Sample_EDA_Submission_Template.ipynb](https://github.com/tejaswini-meshram/Unsupervised-ML---Online-Retail-Customer-Segmentation/blob/main/Unsupervised_ML_Online_Retail_Customer_Segmentation.ipynb)) : Google Colab containing the project code and analysis.

[README.md]([https://github.com/tejaswini-meshram/EDA-Project-Hotel-Booking-/blob/main/README.md](https://github.com/tejaswini-meshram/Unsupervised-ML---Online-Retail-Customer-Segmentation/edit/main/README.md)) :  This file, providing an overview of the project and instructions for running the colab.

# Data Set
 [link_to_dataset]([https://drive.google.com/file/d/1dvYR4YDgoQD4xvOyJ8HWh99wXSFhw2c0/view](https://drive.google.com/file/d/1alxySo8mV_NHvCK3NpXSARKoXFD1_HcX/view?usp=sharing))


# Data Exploration
Removed Null Values
Removed duplicated Values
Maximum transactions are from UK

# RFM Analysis
RFM is Recency, Frequency, Monetary. It looks at what was the last time a customer transacted, how frequent they transacted and what monetary value they bring to the business as factors to assign score to customers. These scores can further be used to group customers.

# Summary
+--------+-------------------------------+------+---------------------------+
| Sr No. |           Model_Name          | Data | Optimal_Number_of_cluster |
+--------+-------------------------------+------+---------------------------+
|   1    | K-Means with silhouette_score |  RM  |             2             |
|   2    |   K-Means with Elbow methos   |  RM  |             2             |
|   3    |             DBSCAN            |  RM  |             2             |
|   4    | K-Means with silhouette_score |  FM  |             2             |
|   5    |   K-Means with Elbow methos   |  FM  |             2             |
|   6    |             DBSCAN            |  FM  |             2             |
|   7    | K-Means with silhouette_score | RFM  |             2             |
|   8    |   K-Means with Elbow methos   | RFM  |             2             |
+--------+-------------------------------+------+---------------------------+

Contact
For any inquiries or feedback regarding this project, feel free to contact:

Tejaswini Meshram: tejaswinimeshram0253@gmail.com
