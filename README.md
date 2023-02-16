# khantigul-store-sales-forecasting


The problem for this project is a time series prediction, presented as a Kaggle competition.

In fact, the goal is to use machine learning algorithms to forecast store sales on data from Corporación Favorita, a large grocery retailer based in Ecuador. 

- prediction must be for each product family and store combinations.
- forecast for the next 15 days, starting from the last day of the training data provided. This period is called forecast horizon.
- get the lowest score from submissions.

To reach the goal described above, it is necessary to model both time dependence and serial dependence features, into one hybrid model, called BoostedHybrid, composed of two complementary learning algorithms.

----------
The dataset provided by Kaggle is in the subfolder 

[khantigul-store-sales-forecasting/Data/Input/](https://github.com/pasitkhantigul/khantigul-store-sales-forecasting/tree/main/Data/Input)




and it consists of 7 datasets namely:

1. **training.csv** : the training dataset
2. **transaction.csv** : log of the amount of daily 1transaction across all the stores
3. **stores.csv** : every store informations such as area etc.
4. **holiday_events.csv** : list of holiday held in Equador
5. **oil.csv** : Historical price of crude oil (Equador main economic drive is the oil production)
6. **test.csv** : dataset for testing the model
7. **sample_submission.csv** : example of submission csv format

All the data will be further explored in the data exploration part.

-----------
To running the notebook: khantigul-store-sales-forecasting.ipynb

- [Kaggle Notebook](https://www.kaggle.com/code/pasitkhantigul/data-mining-project-work-time-series-forecasting)
It is mandatory to sign in/log in, then click on “Copy & Edit” button to run the notebook.
The dataset is already pre-loaded since it is provided by Kaggle.

- Google Colab Notebook: Anyone with the link can run the notebook. The dataset must be uploaded with path ../input/store-sales-time-series-forecasting/’
