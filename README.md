[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhoward-haowen%2Fkh-real-estate&count_bg=%2367E805&title_bg=%23555555&icon=grav.svg&icon_color=%2367E805&title=visitors&edge_flat=false)](https://hits.seeyoufarm.com)

# About
This is a machine learning project for creating models to predict the real estate prices in Kaohsiung, Taiwan. This is an ongoing project, to be described in more detail when I find time to do so. 

# Data
The raw data, named `a_trade_raw.pkl`, is too big to be uploaded to GitHub, so I sotre it on [Google Drive].

The data used for building the two models is a subset of the raw data, saved as `a_trade_filtered_45717entries.pkl` and `kh-house-prices.pkl`. The two files differ only in one aspect:
- Column names in `a_trade_filtered_45717entries.pkl` are in Chinese, as in the raw data whereas those in `kh-house-prices.pkl` are translated into English for easy display in plots.  

# Models
- `kh_house_catboost_model.pkl`: 
  * trained by CatBoost Regressor 

