# BitcoinStockPrediction

Generate accurate predictions on the future price of bitcoin stocks

python_ver_3.6

frameworks needed: Keras, Tensorflow, Sklearn,NumPy,Pandas

# A recurrent neural network (RNN) is similar to a feedfoward neural-net/MLP with the differences in the algorithm is that it has the capability of backpropagation, where connections are also pointing backwards sending the output back into itself. At each time-step(t) this recurrent neuron receives its input (x(t)) as well as output from previous time step (y(t)-1). When there is only one neuron the outputs are scalar when there are more than one input, outputs will be vectors.

# Since outputs for a recurrent neuron at each time-step is a function of all imputs from previous time-steps, this  will make the model have the abilty to maintain a form of memory in its cell. LONG SHORT TERM MEMORY CELLS(LSTM'S) have the ability to go through time freely while it could be removed or erased while variables could be added to it as well . 

## Predicting stock prices is a difficult proccess given that the "Browning Motion" states that predicting stock prices is practically impossible because future variations of stock prices are independent of the past. While that is true it is possible to capture upward and downward trends of the stock prices with the correctly tuned model that can generate accurate predictions on various high dimensional datasets. 

##Recurrent Neural Network's can help perform a very complex optimization on time-series data for prediction(to a certain extent) for music generation as well as predicting future stock market prices. 

## This is very suitable for an implentation for analysis given that the data expands over an extended period of time thus  it will be easy for the network to recognize patterns along different dates in the data and predict the stock prices over the next month or longer depending on how robust the network has been created.

Bitcoin train dates: 07/16/2010 - 08/8/2018

Ethereum train dates: 08/06/2015 - 08/15/2018

Bitcoin Cash train dates: 07/31/2017 - 08/15/2018

Ripple train dates: 01/21/2015 - 08/15/2018

LiteCoin train dates: 10/23/2013 - 08/15/2018
