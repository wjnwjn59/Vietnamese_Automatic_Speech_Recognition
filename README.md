# Vietnamese Automatic Speech Recognition
![](https://img.shields.io/badge/python-3.7-blue)
## Description
This repo is about learning the basic process in speech's field by practicing creating an Automatic Speech Recognition (ASR) system. The process contains data preprocessing, model training and evaluation.

## Dataset
The dataset used in training ASR model is the __VIVOS Corpus__. You can download the dataset from [here](https://ailab.hcmus.edu.vn/vivos).

## Model
Here is a DeepSpeech2 model trained on VIVOS with the batch size of 8 and epochs of 200, which reached 0.4390 WER on VIVOS test set. You can download the model in here: [link](https://drive.google.com/file/d/1Ywa70m728XKSSkfs7Lbcg10-6i92k1yp/view?usp=sharing)


## Instruction
- Insight on audio processing: [audio_processing](https://github.com/thangdduong/Vietnamese_Automatic_Speech_Recognition/blob/main/audio_processing.ipynb)
- Train a ASR model with DeepSpeech2 and CTC Loss: [training](https://github.com/thangdduong/Vietnamese_Automatic_Speech_Recognition/blob/main/training.ipynb)
- Examine edit distance for word_error_rate: [word error rate](https://github.com/thangdduong/Vietnamese_Automatic_Speech_Recognition/blob/main/word_error_rate.ipynb)
- Use the trained model to apply ASR part of Virtual Assistant:  [virutal assistant demi](https://github.com/thangdduong/Vietnamese_Automatic_Speech_Recognition/blob/main/virtual_assistant_demo.ipynb)