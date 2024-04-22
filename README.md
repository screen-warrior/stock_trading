Stock trading with machine learnig


Requirements
Python 3.5+
alpha_vantage
pandas
numpy
sklearn
keras
tensorflow
matplotlib




Train your own model
Clone the repo
Pip install the requirements pip install -r requirements.txt
Save the stock price history to a csv file python save_data_to_csv.py --help
Edit one of the model files to accept the symbol you want
Edit model architecture
Edit dataset preprocessing / history_points inside util.py
Train the model python tech_ind_model.py or python basic_model.py
Try the trading algorithm on the newly saved model python trading_algo.py
