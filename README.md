# Future-Sales-Prediction--Time-Series-Analysis-in-R
Exploratory data analysis with detailed visualizations in a top-down manner, exploring every attribute with respect to sales and revenue and performed a time-series predictive analysis model and plot using Auto Regressive Integrated Moving Average (ARIMA) modelling.
The dataset contains records from Jan 2013 to October 2015. I have predicted the approximate sales line for November 2015 using historical data.

# Dataset Source
Predict Future Sales - Kaggle
https://www.kaggle.com/c/competitive-data-science-predict-future-sales

# Description of Dataset
## File descriptions
sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.<br>
test.csv - the test set. You need to forecast the sales for these shops and products for November 2015.<br>
sample_submission.csv - a sample submission file in the correct format.<br>
items.csv - supplemental information about the items/products.<br>
item_categories.csv  - supplemental information about the items categories.<br>
shops.csv- supplemental information about the shops.<br>

## Data fields
ID - an Id that represents a (Shop, Item) tuple within the test set<br>
shop_id - unique identifier of a shop<br>
item_id - unique identifier of a product<br>
item_category_id - unique identifier of item category<br>
item_cnt_day - number of products sold. You are predicting a monthly amount of this measure<br>
item_price - current price of an item<br>
date - date in format dd/mm/yyyy<br>
date_block_num - a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33<br>
item_name - name of item<br>
shop_name - name of shop<br>
item_category_name - name of item category<br>
