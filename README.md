# ECG-Detection-Using-EGRU

I have created a model which can detect Arrhythmia in ECG signals using The Event Gated Recurrent Unit (EGRU).
Using the Dataset MIT-BIH was taken from a research paper where all the samples are cropped, downsampled and padded with zeroes if necessary to the fixed dimension of 188 and divided in to training and testing dataset.
I went through Experiments using the EGRU model until I got the best one and compared it with other models like LSTM and GRU with the same parameters and layers. Comparing the power Consumption, Co2 emmision, time, accuracy and sparsity was the main metrics used for comparison.
EGRU model has shown significant and better results compared to LSTM and GRU in every aspect. [test link](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/files/15287108/02_GP24_Mohamed_ECG_ERGU_Detection_10_May.pdf)
