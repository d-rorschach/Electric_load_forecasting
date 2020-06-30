# Electric_load_forecasting
#load prediction using LSTM network.
This Electric Load Forecast project is done using LSTM network in keras tensorflow framework.
.csv data file for this project is given in data folder selected_data_ISONE.csv.
It is recommended to use Jupyter Notebook or Google Colab(I've train this model in google colab TPU runtime) to run this project.
Pretrained weight ('weight.h5') and model('LSTM_model.json') is also given in data folder.
You should run load_predict_step_by_step.ipynb to get clear idea about the code. Otherwise, you can just run test.ipynb to get the output graph for test data.


References:
1. https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/ (To know more about handling time series data using LSTM)
2. https://www.youtube.com/watch?v=rdkIOM78ZPk&list=PLZoTAELRMXVPGU70ZGsckrMdr0FteeRUi&index=35&t=0s (basic tutorial video on LSTM)
