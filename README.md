# fifa-record-data-cleaning
Data Cleaning of FIFA 21 Dataset

## About Dataset
One of the challenges of web scraping is unclean data, and it natural, really. Different front-end developers write the HTML their own way, and that makes the incoming data unpredictable. This is definitely a chance to learn lot about data cleaning with this dataset. The dataset has been webscrapped from EA Sports' hit series FIFA 21, which is scrapped from sofifa.com

## Understanding the Data
The dataset contains over 18979 rows and 77 columns. Each column has the key metrics of players perfromance. Since each columns contains pivotal value of player's data, it makes hard to remove the unnecessary columns. However columns that might cause a outlier and affects overall analysis is dropped from the dataset.

## Data Cleaning
Performed basic cleaning of data which will be important in descriptive analysis of the data. Dropped duplicated rows, unnecessary columns, converted objects to other formats, splitted datetime to seperate date, month, and year, removed *,\ and other symbols which are not useful for the analysis and converted the money value from € Euros to ₹ INR. Have a look at the notebook for more detailed analysis of the data.

## Acknowledgement
Thanks to sofifa.com for providing the this amazing data. Special thanks to Rachit Toshniwal for uploading the data in Kaggle.com
