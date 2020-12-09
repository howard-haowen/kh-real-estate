# kh-real-estate
This is a machine learning project for predicting the real estate prices in Kaohsiung, Taiwan.

# Data
The raw data is too big to be uploaded to GitHub, so I sotre it on [Google Drive](https://drive.google.com/file/d/1d5rYXEZyqvlsx12DfGhWXJhwa-RjGR33/view?usp=sharing). The data used for building the model is a subset of the raw data, saved as `a_trade_filtered_45717entries.pkl` and `filtered-data.pkl`. The two files differ only two aspects:
- Column names in `a_trade_filtered_45717entries.pkl` are in Chinese, identical to the raw data whereas those in `filtered-data.pkl` are translated into English for easy display in plots.  
- The one with Engish columns has one more column (i.e. `property_age` at the time of trading), which is derived by applying a function to two columns in the raw data. 
