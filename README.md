I used a London housing dataset from Kaggle and an API for forex exchange rates to convert prices between pounds and dollars. 
I created additional features like the ratio of square footage to the number of bedrooms, and standardized and 
normalized numerical features to enhance comparability. For exploratory data analysis (EDA), I visualized the data using Folium to map property locations, 
a correlation matrix to analyze relationships between variables, and boxplots to show the distribution of housing prices by neighborhood. 
Scatter plots revealed a strong correlation between housing size (square meters) and price, which was confirmed by the correlation matrix. 
I also analyzed price distribution by heating type and property type.

For predictive modeling, I ran several machine learning algorithms, including linear regression, Random Forest, Decision Tree, and 
Support Vector Regression, and evaluated them using MSE and R² values. The Random Forest model showed the best predictive performance. 
I used one-hot encoding to convert categorical variables like neighborhood, heating type, and property type into binary variables, which 
revealed that being in certain neighborhoods - such as Chelsea - significantly impacts housing prices. I also plotted feature importance 
across models, highlighting square meters as the most influential factor. Based on the Random Forest model, I generated predicted 
prices and introduced a “deal score” variable to quantify the difference between actual and predicted prices. Finally, I plotted 
these prices and deal scores to identify the best and worst property deals, effectively using machine learning to uncover actionable 
insights in the dataset.
