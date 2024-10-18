FOREX Trading Prediction CAPSTONE PROJECT
Overview

This repo consists of Jupyter notebooks which cover a literature survey along with the development and application of a model to predict the forex market. The intended purpose of this project is to create a model that predicts fluctuation in the foreign exchange market and aligns trader decisions with profitable outcomes. The last model employs a Long Short-Term Memory (LSTM) neural network, which turned out to be the most efficient for predicting variations, occurring in the short term on foreign exchange markets.
Repository Structure

    Capstone_Project_1.ipynb:
        This notebook is mostly concerned with the first steps of data analysis as well as feature creation. Other data sets were considered, and specific preprocessing methods were used.

    Capstone_Project_2.ipynb:
        A different dataset was explored and additional tests of different models. Regarding this notebook, it is aimed at the further application of classical methods of machine learning.

    LSTM.ipynb:
        This is the last notebook where the implementation of the LSTM neural network will be demonstrated. Comparing the results, LSTM gave better accuracy of prediction than all other models, including RMSE, and was chosen for implementation. The notebook includes the architectural design of the LSTM model, methodology, and the assessment of the LSTM model.

    Predictive_Trading_ipynb.ipynb:
        A notebook with initial machine learning trading models was found in a relatively early stage of their development. Different models were developed and experimented using the preprocessed datasets to determine the effectiveness of LSTM over others.

Final Model

The final model was an LSTM neural network for its capability also in training time-dependent patterns in the forex data. Important observations with regards to the model: The model was trained and tested using historical forex data, and was market-ready; it was capable of providing forecasts, within short horizons, on currency prices for trading purposes.


All the CSV files are the data used throughout the project.


