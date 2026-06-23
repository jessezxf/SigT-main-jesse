
# SigT
This is the code for paper "SigT: An Efficient End-to-End MIMO-OFDM Receiver Framework Based on Transformer"

# Tips on using our code
The following structure is as follows:

1.Prepare the data
2.Train the model
3.Use saved model to evaluate
Generate Data
Train the Model
Signal Transformer
using Stochastic Gradient Descent (SGD)
python TRAIN.py -GI * -LP * -SP * -LR 0.5
using Adam
python TRAIN.py -GI * -LP * -SP * -OPTIM adam -LR 0.0001
