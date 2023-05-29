# LSTM_e-scooters_position_forecasting

[IN PROGRESS]

Here is the work done together with my colleague Remo Marconzini for the Data Science exam on Smart Cities. Using a week's worth of data (Dec. 2, 2019 to Dec. 8, 2019) of e-scooters in the city of Milan, through a simple recurrent neural network with LSTM units, we predicted, given a sequence of e-scooters with the same destination, their drop-off zone. Next, the same task is performed with an even greater level of granularity, considering the drop-off zone of each individual e-scooter. The study was conducted by considering two distinct numbers of e-scooters in each sequence (5 and 10) and two different levels of granularity of the city, performing a classification task by dividing the city of Milan into 12 and 36 discrete zones, respectively.

In this repo you can find the Python code and the related report in pdf. Moreover, we provide several animated choropleth maps, including the one concerning the surplus/deficit of e-scooters in the various Milan NIL.
