# instruments classification 
The objective of this project is to develop a real-time musical instrument recognition system that will accurately identify the different instruments present in the sound signal. To achieve this, we designed a feature extraction system and built a labeled database containing 0.1 s audio sequences. We then trained and compared two convolutional neural network (CNN) and long-term memory (LSTM) models for audio classification. Finally, we developed a Streamlit application for real-time audio analysis.

## Dataset:
Freesound plus de 370 000 avec plus de 40 labels https://www.kaggle.com/c/freesound-audio-tagging

![class distribution](https://github.com/lachtarnour/deep_learning-classification-des-instruments/blob/0844fbaba73429148db5bc14f8435ddd5ad810d0/class%20distribution.png)

##For use this repository, you need to install this requirements
python3.6
IPython
Numpy
python_speech_features
h5py
Pandas
Librosa
Scikit-learn
scipy.io
os
keras
Matplotlib

##result
### convolutional neural network
![confusion matrix]([images/cnn/confusion matrix.png](https://github.com/lachtarnour/deep_learning-classification-des-instruments/blob/6e74ac8ca5764587108c0d882d187915ddbd9435/images/cnn/confusion%20matrix.png))
![conv epochs]([images/cnn/conv epochs.png](https://github.com/lachtarnour/deep_learning-classification-des-instruments/blob/6e74ac8ca5764587108c0d882d187915ddbd9435/images/cnn/conv%20epochs.png))
![learning curve](https://github.com/lachtarnour/deep_learning-classification-des-instruments/blob/863c6b4842ab70f29d6049ccad81da1e60fac9e5/images/cnn/learning%20curve%20.png)
