# Project: Using PCA to Predict the Price of Common Grocery Items
Motivation: Recently, we have been hearing a lot about recalls for grocery items, while also constantly hearing about rising prices due to inflation. It is known that recalls can cost millions every year. My thinking is that if an item is carrying salmonella or some other pathogen, there will be less items on shelves as they get pulled, and the price may go up. On the other hand, the presense of an outbreak might decrease demand if everyone is informed of the outbreak, which would decrease the price. Either way, I want to see if this, along with inflation and gas prices can be used to predict the price of basic groceries.

Data source 1: Average cost of grocery items in the US from the Bureau of Labor Statistics
Data source 2: CDC foodborne illnesses dataset (Salmonella, for example)
Data source 3: Inflation rate dataset from the Bureau of Labor Statistics 

I wanted to see if the frequency of foodborne illnesses could be used to predict the price of these items, while also accounting for inflation
I also decided to include gas prices, which was already included in the groceries price dataset
Doing PCA with gas price, inflation rate, and foodborne illnesses as the predictors 
Attempting to predict the prices of bananas, oranges, bread, tomatoes, chicken, eggs, beef, milk.
