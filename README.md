# Customer_Behavior_Prediction
Repository space for my second springboard capstone project

**Exploratory Data Analysis**
After exploring and investigating each column of the dataset independently I find some valuable insights about 1 or two of those columns. Namely discovering the unexpected behavior regarding the 'Amount' and 'Sales Price' columns and their effect on one another. I found that these two important columns have non-normally distributed data and seem to have an unclear relationship. After investigating that relationship I surmise that the 'Sales Price' column is probably the total transaction price as opposed to the price per unit. Using this assumption would explain the relationship between 'Amount' and 'Sales Price'. After further exploring the data by performing some statistical tests on the data I provide some valuable business metrics based on cohort analysis.

**Cohort Analysis**
I first separate the cohorts into weekly intervals by the first week that the customers purchased an item. After which I provide tables based on cohort counts, such as customer retention rate, average number of items purchase per cohort, the average transaction cost per cohort, and the average unit price (*see below*) per cohort. After doing some basic cohort analysis I then start to classify customer ids based on their Recency, Freqency, and Monetary values. In doing so, I make it easier to identify and classify customers whom are most important to target with special promotions and offers. 

**Customer Segmentation**
The first form of customer segmentation I employ is based on percentiles (*quartiles*) of RFM purchasing behavior.
I further make these RFM findings easier to understand by providing an 'RFM Score' which shows the relative customer value of each customer id. This is further simplified by classifying customer ids into groups such as gold, silver, and bronze level shoppers. Finally, I finish off my customer segmentation by using K-means to automatically classify similar behavior customers which is a convenient method for simplicity and unique ability to work with especially large datasets.
https://nbviewer.jupyter.org/github/pmleffers/Customer_Behavior_Prediction/blob/master/Customer_Behavior_Prediction_EDA_Metrics.ipynb



https://nbviewer.jupyter.org/github/pmleffers/Customer_Behavior_Prediction/blob/44c3b5ff64faa0a6bc96ee7c33924fc77c41ab11/Customer_Behavior_Prediction_Model.ipynb
