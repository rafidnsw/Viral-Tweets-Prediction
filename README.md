# Viral-Tweets-Prediction
This is my first attempt competing in a data science competition. Due to the terms &amp; conditions of the competition, I can not upload the dataset yet. In this projects we tried to do end-to-end process in data science methodology that includes Data Preparation, Exploratory Data Analysis, Data preprocessing, and Machine Learning Modelling.

### Data Preparation
In the data preparation, we imported the datasets to our notebook. There are 3 tables in total which consist of train & test dataset, and users information. In this stage we also checked any null values and finally also in this stage we merge the whole sets into one single set in a purpose of making a dataset that easier to handle later in the preprocessing stage

### Exploratory Data Analysis
In this second stage we tried to do some analysis using descriptive statistics for both numerical & categorical data. Beside doing descriptive analysis, we also visualized our numerical data in order to see how well the distribution of the data was. From our visualization, we found that most of our numerical data aren't normally distributed, and had a positively skewed distribution. Another thing we did in this stage was to point out any outliers in our data, and since the distribution isn't normal it was expected there were some outliers in our data.

### Data Preprocessing
For the third stage, we processed our existing data to become a better-valued dataset in order to later increase our machine learning model performa. Some processing that we did in this stage are such as explode a feature with list-like values, creating new features from existing features, scaling numerical datas to have a better distribution using MinMaxScaler, and encode categorical datas using One-Hot encoding.

### Machine Learning Modelling
In this part we tried to create models with several multi-class supported algorithm. Since the goals of this project is to get highest accuracy score, from our created models, we found that LightGBM boosting algorithm has the highest accuracy score among all other models. In order to further boost the score, we tried to do some hyperparamters tuning for this LightGBM model.
