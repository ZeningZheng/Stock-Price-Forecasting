# Stock-Price-Forecasting
This is a project I worked on with two other students during my masters in Deep learning course.

#### Aim of this project:
Predict stock prices.

#### Model:
CNN-BiLSTM-ECA model. 

CNN is convolutional neural network which can extracts features, then it passes features to Bidirectional LSTM, which performs two LSTM function, backward and forward, which can use the information from both the past and future. Then comes ECA, Effective channel attention model, this model can further reduce model complexity and focus on the most useful information. And finally, dense layer to perform prediction. 

#### Process: 
1 Replication of other’s work. 
2 Application and improvement of the existing model to other stocks. (PetrolChina, Dogecoin, Bitcoin, Bitcoin cash)
