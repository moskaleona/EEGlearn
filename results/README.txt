Results of training CNN and CONV-LSTM models to classify intentional vs. spontaneous
gaze ﬁxations on EEG data from 19 channels.

All the results were obtained by applying cnn_lstm_optimization.py with
different parameters of learning rate and epoch number.

Name of each folder here is e<numer_of_epochs>lr<learning_rate><data_amount(full - all the data, part - small amount of data)>
E.g. 'e40lr005part' => models were trained for 40 epochs with learning rate 0.005 on partial data (3 subjects instead of 13).