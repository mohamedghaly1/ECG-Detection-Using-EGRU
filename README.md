# ECG-Detection-Using-EGRU

## EGRU: Event-based Gated Recurrent Unit
According to the paper by [Subramoney et al.](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/files/15474074/EFFICIENT.RECURRENT.ARCHITECTURES.THROUGH.ACTIVITY.SPARSITY.AND.SPARSE.BACK.PROPAGATION.THROUGH.TIME.pdf), they have created a new method called Event Gated Recurrent Unit (EGRU) it is an extension of the normal Gated reccurent unit with a gating mechanism that takes care of the efficiency aspect without sacrificing on accuracy.EGRU is a variant of the GRU architecture including a biologically inspired neuron dynamics driven event generation mechanism as shown below from the [Subramoney et al.](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/files/15474074/EFFICIENT.RECURRENT.ARCHITECTURES.THROUGH.ACTIVITY.SPARSITY.AND.SPARSE.BACK.PROPAGATION.THROUGH.TIME.pdf) paper , that enables an RNN unit to communicate sparsely and discretely with others.


![egru-overview](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/assets/102426735/c2818957-656c-43c8-90f2-957e863d00e3)

![EvNNPlot_ManimCE_v0 17 2](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/assets/102426735/78141783-2e76-4da6-adb5-e47f72607f53)





## Arrhythmia Detection in ECG Using Event Gated Recurrent Unit (EGRU)

I have created a model which can detect Arrhythmia in ECG signals using The Event Gated Recurrent Unit (EGRU).
Using the Dataset MIT-BIH was taken from a research paper where all the samples are cropped, downsampled and padded with zeroes if necessary to the fixed dimension of 188 and divided in to training and testing dataset.
I went through Experiments using the EGRU model until I got the best one and compared it with other models like LSTM and GRU with the same parameters and layers. Comparing the power Consumption, Co2 emmision, time, accuracy and sparsity was the main metrics used for comparison.
EGRU model has shown significant and better results compared to LSTM and GRU in every aspect.

Final form of the EGRU model block digram:


![resultsBD2white](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/assets/102426735/964e972b-fddd-4615-9316-dbff74e2e178)

The Thesis paper of the project [click here](https://github.com/mohamedghaly1/ECG-Detection-Using-EGRU/files/15391603/ECG-Detection-Using-EGRU.pdf)
