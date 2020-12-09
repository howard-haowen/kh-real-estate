# About
This is a machine learning project for creating models to predict the real estate prices in Kaohsiung, Taiwan.

# Data
The raw data, named `a_trade_raw.pkl`, is too big to be uploaded to GitHub, so I sotre it on [Google Drive](https://drive.google.com/drive/folders/1AL8QH4WFJ9iThYeeU9tO8S_AFRovU05T?usp=sharing), along with two regressor models (see below).

The data used for building the two models is a subset of the raw data, saved as `a_trade_filtered_45717entries.pkl` and `filtered-data.pkl`. The two files differ only in two aspects:
- Column names in `a_trade_filtered_45717entries.pkl` are in Chinese, as in the raw data whereas those in `filtered-data.pkl` are translated into English for easy display in plots.  
- The one with Engish columns has one more column (i.e. `property_age` at the time of trading), which is derived by applying a function to two columns in the raw data. 

# Models
- `kh_house_catboost_model.pkl`: 
  * trained by CatBoost Regressor 
  
- `kh_house_blender_model.pkl`
  * trained by a blend of three regressors, CatBoost Regressor, Extreme Gradient Boosting, and Extra Trees Regressor 
