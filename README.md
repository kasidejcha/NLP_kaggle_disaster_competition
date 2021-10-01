# NLP_kaggle_disaster_competition
Predict which Tweets are about real disasters and which ones are not

`0` = not disaster, `1` = disaster

Model 0: Getting a baseline
Model 1: Feed-forward neural network (dense model)
Model 2: LSTM (Long short term memory)
Model 3: GRU
Model 4: Bidirectional RNN
Model 5: Conv1D
Model 6: TensorFlow Hub Pretrained Sentence Encoder (universal sentence encoder or USE)
Model 7: TF Hub Pretrained USE but with 10% of training data

Result Kaggle Score on Model 6: 0.80753
